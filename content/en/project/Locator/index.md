---
title: Locator App
summary: An app that helps you find dropped items using computer vision.
  
tags:
# - Deep Learning
date: "2022"

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

Sometimes when you drop something it can be very hard to find them depending on the size and type of item as well as where you dropped it. For example, you ever drop a pill or earing and can't seem to find it?

<h3>The Solution</h3>

Locator is a simple computer vision application for mobile devices that searches surfaces for anomalies that match a given pattern to help you find an item.

<h3>Initial Sketches</h3>

<img src="/portfolio/locator/sketches.jpg" width="720" alt="Initial Sketches of the UI">

With my initial sketches, I tried out a few variations

- One using a lens selector similar to snapchat.
- One using a pull out drawer from the bottom with dropdown menus.
- Another using a pull out drawer from the top.

I was initially going to have 2 selections, one for the item material, and another for the background/context material (i.e. wood, grass, tile, etc.). However, I decided to simplify it so the user isn't selecting the background/context material and is only selected the type of item (i.e., coins, keys, pens, etc.) I figured that this way, not only is it simpler for the user, but you can feed a machine learning algorithm with more specific types of items. If this app was developed and released, more item type filters could be added in the future.

As you can see at the bottom there are 2 icons, one is a flashlight, the other is supposed to be a human head for audio assistance. I initially wanted to incorporate audio assistance that could be turned on and off but instead, I figured the app could automatically use voice assistance if the user had that enabled on their device.

Additionally, given that I want my app to be usable by a wide variety of users, I decided that there should be a help button that gives the users a short walkthrough of the UI.

<h3>Lo-Fi Designs</h3>

<img src="/portfolio/locator/lofi.png" width="720" alt="Low fidelity wireframes">

After my initial sketches, I created some lo-fi wireframes.

Changes I made:

- Moved the help button to the top right.
- Removed the audio assistance button.

<h3>Hi-Fi Designs</h3>

<img src="/portfolio/locator/hifi.png" width="720" alt="High fidelity wireframes">

After the lo-fi wireframes, I created hi-fi ones.

Changes I made:

- added a label to the "lenses"
- added images to the "lenses"
- added a flashlight icon with on/off text

As you can see, items that match the lens are circled. I chose this particular color because it's opposite from the background color on the color wheel. My thoughts are the app would be able to detect the background/context color and use a color opposite on the color wheel so that the circle always has good contrast with the background.

<h3>Prototype</h3>

<div style="position: relative; padding-bottom: 67.5%; height: 0; margin: 10px 0; overflow: hidden;">
  <iframe style="border: 1px solid rgba(0, 0, 0, 0.1); position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2Fv7LOr4K2L2lrzAhbGjFl6M%2FLocator-App%3Fpage-id%3D3%253A211%26node-id%3D3%253A212%26viewport%3D241%252C48%252C0.98%26scaling%3Dcontain%26starting-point-node-id%3D3%253A212" allowfullscreen></iframe>
</div>

Please feel free to look through the designs using the prototype I made.