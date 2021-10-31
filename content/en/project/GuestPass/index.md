---
title: Guest Pass
summary: A guest access solution for LenelS2 Elements.<br><br>
  
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

<h3>The Problem</h3>

Elements is a cloud based unified access control and video management system from LenelS2.

Before guest pass, whenever a customer wanted to add a give access to a temporary guest in Elements (e.g, job candidate, clients, etc), they had to add them to their elements system and remember to remove them from the system once access needs to be revoked. Customers needed a way to temporarily grant access to temporary guests without adding them as a person in their system which is typically reserved for more long-term "visitors" such as employees.

<h3>The Solution</h3>

Guest Pass allows customers to create a temporary guest pass that will automatically activate and delete according to user specifications that they can send to their guests.

<h3>Creating a guest pass</h3>

<img src="/portfolio/GuestPass/create.png" width="400" alt="a screenshot of the guest pass creation process">

Before designing the guest pass itself, I needed to design the method of creating one.

There were 4 essential requirements that we needed for guest passes:
- An activation date/time.
- An expiration date/time.
- a list of readers/doors that a visitor can unlock using their guest pass.
- a method to share the guest pass

<h3>The Guest Pass</h3>

Because the actual guest passes are located on their pages, this allowed me to experiment with animations which are typically not done in Elements. Have a look:

<h4>Success</h4>

<video controls>
  <source src="/portfolio/GuestPass/open.mp4" type="video/mp4">
</video>

<h4>Error</h4>

<video controls>
  <source src="/portfolio/GuestPass/error.mp4" type="video/mp4">
</video>

You can play around with the animation in my ProtoPie prototype <a href="https://cloud.protopie.io/p/9964619755">here</a>. If you want to switch between the success and error animations select the top left corner the prototype where the time is located.

I also made a rough translation of the prototype in code using CodePen. You can see for yourself <a href="https://codepen.io/JEScarani/pen/oNWKmxG">here</a>.

<h3>Conclusion</h3>

Guest Pass was successfully put in production in Q4 of 2021. This was my first time working with animations like this and it helped me learn to think outside the box a little more when it came to how users interact with my designs.