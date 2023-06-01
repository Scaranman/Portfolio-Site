---
title: Guest Pass
summary: A guest access solution for LenelS2's Elements.
  
tags:
# - Deep Learning
date: "2021"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
# - icon: figma
#   icon_pack: fab
#   name: Link to Figma prototype
#   url: https://www.figma.com/proto/Bm5bpQRGBaoI9DWLHyEodo/Laundy?page-id=1%3A211&node-id=62%3A230&viewport=581%2C569%2C0.28126800060272217&scaling=scale-down
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
### Overview

Guest Pass is a feature I designed for an all-in-one access control security system called Elements during my time at LenelS2. that allows users to send a temporary "guest pass" that visiting guests can access right from their smart phone. Users set an activation and a deletion date/time along with any specific doors they want their guest to have access to. With this feature, users don't need to create credentials and badges normally reserved for employees nor do they have to keep someone on stand by to let guests in.

Since its introduction to Elements, Guest Pass has been a major differentiator to competition and has been included in every demo to potential customers. Additionally, Guest Pass has received numerous requests for additional features and functionality to make it even more useful.

### Who is LenelS2?

LenelS2 is a global leader in advanced physical security solutions, including access control, video surveillance and mobile credentialing. They're famous for products such as OnGuard, Elements, and BlueDiamond.

### What is Elements?

Elements is an SaaS all-in-one cloud-based access control and video management solution that helps companies monitor and secure their facilities with equipment such as cameras and badge readers.

### What Was The Problem?

Before guest pass, whenever a customer wanted give access to a temporary guest in Elements (e.g, job candidate, clients, etc), they had to add them to their elements system and remember to remove them from the system once access needs to be revoked. Customers needed a way to temporarily grant access to temporary guests without adding them as a person in their system which is typically reserved for more long-term "visitors" such as employees.

### My Solution

Create a feature that allows users to create a temporary "guest pass" that will automatically activate, and delete according to user specifications.

### Users

- A person who works at a company and is inviting a guest to their company's facility. This can be anyone from a hiring manager inviting someone for an interview, to management inviting a business client for a meeting.
- A guest who was invited to the company's facility.

### Requirements

#### Issuing a Guest Pass

- Users need to be able to add guest passes and send them themselves as they are responsible for the guest
- Optional start/end date
- Assign door readers to the guest pass
- A method to share the guest pass
- An email template for when a guest pass is shared
- The ability to update a guest pass

#### Using a Guest Pass

- Guest can receive their guest pass via email with link to web UI
- UI shows when the pass is valid for and the customer (who will be issuing the guest pass)
- Buttons available for each reader to unlock

#### Events

- Events in the Elements event feed shows when a guest pass is used and where it was used

<!-- ### Questions and Considerations

Additionally I came up with the following questions:

- What happens when a guest is expires?
- Do we connect a pass to a persons record, or have it be it's own record type?

I also considered simply providing an option for normal credentials to expire, but that would still require someone to create a credential for the guest (which would require them to be in the building already) which would ignores the problem that the guest/user needs a way to get into the building in the first place and that's the problem I was trying to solve. -->

### Wireframes

<img src="/portfolio/GuestPass/invision_screenshot.jpg" width="720" alt="a screenshot of wireframes in InVision FreeHand">

Afterwards, I created a user flow using some low fidelity wireframes I created in InVision Freehand.

#### User Flow:

1. User navigates to the "Guest Passes" area of Elements.
2. User selects the add button to add a guest pass
3. User inputs a name, activation and expiration dates and times, and the recipient email
4. User adds readers
5. User generates the pass

### Hi-Fi Designs

<img src="/portfolio/GuestPass/list.png" width="720" alt="">

<img src="/portfolio/GuestPass/SidePanels.png" width="720" alt="">

After ironing out the designs, I then created high fidelity versions in Figma using the pre-established design system at LenelS2 that I helped manage and expand during my time there.

While in high fidelity, I decided to make a small change of removing the email recipient field in the guest pass creation process because I wanted users to be able to choose when they send the email to the recipient and not have it done automatically.

### Designing the Guest-Facing Guest Pass UI

Once the creation process for guest passes was finished, I moved onto the web UI that guest pass recipients were going to see when using their guest pass.

Since the guest passes are on isolated pages outside of the primary Elements interface, I was apply to apply animation to the buttons that help a user understand that something is happening when they select a button to unlock a door reader.

#### Success

When the user unlocks a door reader successfully using their guest pass.

<video controls>
  <source src="/portfolio/GuestPass/open.mp4" type="video/mp4">
</video>

#### Error

When a user attempts to unlock a door reader using their guest pass and an error occurs.

<video controls>
  <source src="/portfolio/GuestPass/error.mp4" type="video/mp4">
</video>

You can play around with the animation in my ProtoPie prototype <a style="text-decoration: underline;" href="https://cloud.protopie.io/p/9964619755">here</a>. If you want to switch between the success and error animations select the top left corner the prototype where the time is located.

I also made a rough translation of the prototype in code using CodePen. You can see for yourself <a style="text-decoration: underline;" href="https://codepen.io/JEScarani/pen/oNWKmxG">here</a>.

### Conclusion and Results

Guest pass is really interesting because of its dynamic between two types of users: a customer who owns a Elements-based access control security system, and a user who is visiting one of customers locations. As a young designer it was a very enjoyable problem to tackle and I learned a lot about the process of figuring out user flows in such a system. I also learned a lot about animations and how to utilize them to make my designs more responsive.

Guest Pass was successfully put in production in Q4 of 2021. Since it's implementation it has been a become a big success and a major differentiator to competition with users asking for additional features.
