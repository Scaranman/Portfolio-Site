---
title: ゲストパース（Guest Pass）
summary: LenelS2のElementsのげストアクセス機能です。
  
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

<h4>＊ 翻訳は進行中です。＊<h4>

<h3>問題</h3>

Elements is a cloud based unified access control and video management system from LenelS2.

Before guest pass, whenever a customer wanted give access to a temporary guest in Elements (e.g, job candidate, clients, etc), they had to add them to their elements system and remember to remove them from the system once access needs to be revoked. Customers needed a way to temporarily grant access to temporary guests without adding them as a person in their system which is typically reserved for more long-term "visitors" such as employees.

<h3>解決</h3>

Guest Pass allows customers to create a temporary guest pass that will automatically activate and delete according to user specifications that can then be sent to a guest.

<h3>Requirements</h3>

This project was done during my time as a UX Designer Co-op/intern at LenelS2. For this specific task, I was given a set of requirements. It was my job to not only find a solution to the given requirements, but find out any hidden requirements that I would need to work with. So including those that were given to me, I settled on the following requirements:

<h4>Issuing a Guest Pass</h4>

- Users need to be able to add guest passes and send them themselves as they are responsible for the guest
- Optional start/end date
- Assign door readers to the guest pass
- A method to share the guest pass
- An email template for when a guest pass is shared
- The ability to update a guest pass

<h4>「Guest Pass]を使うこと</h4>

- Guest can receive their guest pass via email with link to web UI
- UI shows when the pass is valid for and the customer (who will be issuing the guest pass)
- Buttons available for each reader to unlock

<h4>Events</h4>

- Events in the Elements event feed shows when a guest pass is used and who used it

<h3>質問</h3>

Some of the questions that I came up were:
- What happens when a guest is expires?
- Do we connect a pass to a persons record, or have it be it's own record type?

I also considered simply providing an option for normal credentials to expire, but that would still require someone to create a credential for the guest (which would require them to be in the building already) which would ignores the problem that the guest/user needs a way to get into the building in the first place and that's the problem I was trying to solve.

<h3>ワヤーフレーム</h3>

<img src="/portfolio/GuestPass/invision_screenshot.jpg" width="720" alt="「InVision　FreeHand」のワヤーフレーム">

I then created some wireframes for the guest pass creation process in InVision.

<h4>Breakdown:</h4>

1. User navigates to the "Guest Passes" area of Elements.
2. User selects the add button to add a guest pass
3. User inputs a name, activation and expiration dates and times, and the recipient email
4. User adds readers
5. User generates the pass

<h3>ハイ―ファイ</h3>

<img src="/portfolio/GuestPass/create.png" width="720" alt="a screenshot of the guest pass creation process">

I then moved my designs to high fidelity in Figma using the pre-established design system at LenelS2 that I helped manage and expand during my time there.

While in high fidelity, I decided to remove the email recipient field in the guest pass creation process as I wanted users to be able to choose when they send the email to the recipient and not have it done automatically.

<h3>お客様が使うUIをデザインすること</h3>

Once the creation process for guest passes was designed, I moved onto the web UI that guest pass recipients were going to see when using their guest pass.

Since the guest passes are on isolated pages outside of the primary Elements interface, I was apply to apply animation to the buttons that help a user understand that something is happening when they select a button to unlock a door reader.

<h4>Success</h4>

When the user unlocks a door reader successfully using their guest pass.

<video controls>
  <source src="/portfolio/GuestPass/open.mp4" type="video/mp4">
</video>

<h4>Error</h4>

When a user attempts to unlock a door reader using their guest pass and an error occurs.

<video controls>
  <source src="/portfolio/GuestPass/error.mp4" type="video/mp4">
</video>

You can play around with the animation in my ProtoPie prototype <a style="text-decoration: underline;" href="https://cloud.protopie.io/p/9964619755">here</a>. If you want to switch between the success and error animations select the top left corner the prototype where the time is located.

I also made a rough translation of the prototype in code using CodePen. You can see for yourself <a style="text-decoration: underline;" href="https://codepen.io/JEScarani/pen/oNWKmxG">here</a>.

<h3>結論</h3>

Guest pass is really interesting because of it's dynamic between two types of users: a customer who owns a Elements-based access control security system, and a user who is visiting one of customers locations. As a young designer it was a very enjoyable problem to tackle and I learned a lot about the process of figuring out user flows in such a system. I also learned a lot about animations and how to utilize them to make my designs more usable.

Guest Pass was successfully put in production in Q4 of 2021.
