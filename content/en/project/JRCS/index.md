---
title: JRCS Command Task
summary: Design Challenge for the JRCS Digital Innovation Lab.<br><br>
  
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

One of the JRCS Digital Innovation Lab's flagship products is a command application that provides captains and officers on ships at sea with information regarding the navigation of their vessel, and highlights nearby vessels through AR as well.

The team provided me 2 screens and wanted me to design a method for the application to warn users when they are about to collide with another vessel as well.

<img src="/portfolio/JRCS/start.png" width="720" alt="Two different UI views I was given to work with.">

<h3>Users and Requirements</h3>

I started by recognizing my users and establishing any requirements.

<h4>Users</h4>

- Captains
- Officers on "watch"

<H4>Requirements</h4>

- Must grab users attention
- Must Provide enough information for users to act upon
- Cannot drown out any other important information

<h4>Sketches</h4>

After establishing my users and requirements. I started sketches out my ideas.

<img src="/portfolio/JRCS/sketches.png" width="720" alt="Pictures of my initial sketches.">

My immediate thought went to some kind of dialogue window that pointed to the vessel the user was about to collide with.

I experimented with 3 different shapes, but ultimately settled on a simple rectangular dialogue window that provided users with the needed information.

I also thought about adding lines that indicate the path that each ship was going to take. However, after moving on from my sketches, I decided to scrap that idea as it could be very difficult to implement given the program would have to calculate the angle of the ship, and the surface of the water. Not only would that be a lot to calculate and take into consideration, but rough water at open sea is not exactly computer vision friendly for those kinds of calculations.

Lastly, the application has a view with a sort of compass view. I thought of a way to give users warning while in that view.

<h4>Lo-fi Wireframes</h4>

<img src="/portfolio/JRCS/lofi.png" width="720" alt="Pictures of my initial sketches.">

After my sketches, I decided to focus on the primary view and created some low-fi wireframes for the dialogue.

I tried the dialogue with the information provided vertically, and horizontally. I decided to be consistent with the established UI of the application and went with horizontal.

<h4>Hi-fi Wireframes and Progression</h4>

<img src="/portfolio/JRCS/progression.png" width="720" alt="Pictures of my hi-fi designs for the dialogue with progressive changes.">

After the lo-fi wireframes, I stylized the wireframes using the style of the applications UI.

From there, I progressively start making changes such as adding labels and the boat indicator.

<h4>Designs in Context</h4>

<img src="/portfolio/JRCS/incontext.png" width="720" alt="Pictures of the dialogue in context">

These are my designs when put into context with some notes.

<h4>Pulse</h4>

<img src="/portfolio/JRCS/pulse.png" width="720" alt="Pictures of the dialogue in context with a red bar at the top of the screen">

In addition to the dialogue, I decided I wanted something that draws the users attention to the screen in the case that they are not looking.

Inspired by FPS games such as Halo, and Call of Duty, I decided to add a pulsing red bar at the top of the screen that draws users attention to the screen without being overwhelming.

<h4>Transparency</h4>

<img src="/portfolio/JRCS/transparency.png" width="720" alt="Pictures of the dialogue over night and sunset/sunrise backgrounds with different transparencies">

To explain why I chose to make my dialogues have an opacity of 100%, here's a slide from my presentation that shows the dialogue over sunset/sunrise and nigh time settings with various transparency settings.

As you might be able to tell, while transparency works at night and possibly mid-day, it makes the dialogue information harder to read when it comes to sunset/sunrise settings.

<h4>Color Blind Filters</h4>

<img src="/portfolio/JRCS/colorblind.png" width="720" alt="Pictures of the dialogue through different color blind filters">

Lastly, I ran my dialogue through every colorblind filter to make sure it was accessible.

<h4>Conclusion</h4>

Unfortunately, while the team really liked my designs, they could only hire 1 person and ultimately I did not get the job. However it was really fun to design and I'm proud of the work I did.
