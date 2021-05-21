---
title: Magic The Gathering Vending Machine UI
summary: A prototype UI for a hypothetical Vending machine for the popular trading card game Magic The Gathering (MTG).
tags:
# - Deep Learning
date: "2020"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
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

<h3>Problem</h3>


Vending machines are something we see everywhere. However, it's not very often that you get to see a vending machine that differs from the current ones we have. My partner set out to create an interface for a vending machine that breaks the standard design conventions for one.


<h3>Solution</h3>


We came up with a vending machine for Magic The Gathering, an immensely popular trading card game. Currently, most card stores are locally based and include game spaces in the back. These stores often get very crowded, the purpose of our proposed design is not to replace the store clerks at the front, but to alleviate the the work of the store clerks. This vending machine would streamline the process of buying and selling cards by allowing customers to quickly sell and buy cheap common and uncommon cards.

At the moment, frames are only designed with the assumption that the customer already has a card for the vending machine and is selling cards. 

<h3>Sketches</h3>

<img src="/portfolio/MTGV/sketches.png" alt="Early sketches focusing on the layout">

<h3>User Flow Diagram</h3>

<img src="/portfolio/MTGV/flow.png" alt="A user flow diagram of the Interface">

While some parts of this flow diagram changed throughout the life of the project, most of it is accurate to the current design. 

<h3>Wireframes</h3>

<img src="/portfolio/MTGV/wireframes.png" alt="A compound view of all the low-fi wireframes">

<h3>Style Guide</h3>

<img src="/portfolio/MTGV/styleguide.png" alt="A compound view of all the low-fi wireframes">

For our final design, we decided to use the official Magic The Gathering colors along with the Beleren typeface as a display font which is used in the game's logo. We also added various art pieces into the background to add a bit more to the design. Our biggest changes were to the card category select screen and the filters. We thought that out initial design of the card category select screen would be too consistent and might confuse users. It also looked strange. Instead, we used the rounded tiles with the color and logos of each card element used in the game. As fore the filters, we felt they were to rudimentary and need a bit more. We found that using checkboxes with the Magic The Gathering symbol in the filled in checkboxes really pulled it together. We also added a some more designs for the interaction. 

<h3>Final Prototype</h3>

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FsDW38BfMENB7mm0p1anmJu%2FMTG-Vending-Project%3Fpage-id%3D56466%253A190%26node-id%3D56466%253A714%26viewport%3D1062%252C542%252C0.09153234213590622%26scaling%3Dmin-zoom" allowfullscreen></iframe>