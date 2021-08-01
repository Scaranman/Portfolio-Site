---
title: マジック:ザギャザリングの自動販売機のUI
summary: マジック:ザギャザリングの自動販売機のUIの原型です。
tags:
# - Deep Learning
date: "2020"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: figma
  icon_pack: fab
  name: プロトタイプへ
  url: https://www.figma.com/proto/sDW38BfMENB7mm0p1anmJu/MTG-Vending-Project?page-id=56466%3A190&node-id=56466%3A190&viewport=771%2C554%2C0.06217627599835396&scaling=contain
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

Vending machines are something we see everywhere. However, it's not very often that you get to see a vending machine that offers something different from the standard snacks or drinks. My partner and I set out to create an interface for a vending machine that breaks the standard design conventions for one.

In trading card games such as Magic The Gathering (MTG), there are many card with common and uncommon rarities that while are very common and not worth much, are absolutely necessary to a deck build. It's because of this that many players often go out of their way to buy these cards despite their rarity and worth. 

At many card and board game shops, customers often build relationships with the staff and might get better prices from the staff, especially for more rare cards. However, these shops often get very crowded and as such, it could seem to be a more tedious process than desirable for both staff and customers when buying or selling such cards. My partner and I sought out to design a vending machine solution that would relieve the burden of local shop staff when it came to these transactions without forcibly taking away from customer-staff relationships.

<h3>解決</h3>

We came up with a vending machine that would streamline the process of buying and selling common and uncommon cards by allowing customers to do it through the machine rather than waiting in line and getting an offer from the staff. When selling cards, the vending machine could scan the cards and compare them to a database where it would then provide and offer price.

Customers would need get their card from the staff that they could then use to build up a balance (either buy selling cards or putting money on at the register) to use when buying cards from the vending machine.

<h3>スケッチ</h3>

<img src="/portfolio/MTG/sketches.png" alt="Early sketches focusing on the layout">

We started out with some rudimentary sketches on how we thought the standard user flow would look like.

<h3>ユーザーフロー</h3>

<img src="/portfolio/MTG/flow.png" alt="A user flow diagram of the Interface">

Before using the vanding machine, customers would first need to get a card from the staff who would activate it. Customers could either take the card as is, or put money on it through the register.

When using the machine, users would be prompted to enter their card and would then be given the opportunity for users to sell any cards they would like to sell to the machine. 

When selling, customers would then insert the cards one by one. Each time they insert a card, the machine would scan the card and compare it to a database where it would then offer a sell price. If the customer accepts, they could either sell more card, shop for cards, or exit and finish.

From there if they decide they would like to buy any card, they could browse through a variety of means such as color, condition, type, or by name. After that, it's a mostly standard checkout process.

<h3>ワイヤフレーム</h3>

<img src="/portfolio/MTG/wireframes.png" alt="A compound view of all the low-fi wireframes">

Picking up where the sketches left off, we then created low-fi wireframes of some of the screens a user might go through in our model user flow.

<h3>スタイルガイド</h3>

<img src="/portfolio/MTG/styleguide.png" alt="A compound view of all the low-fi wireframes">

For our final design, we decided to use the official Magic The Gathering colors along with the Beleren typeface, which is used in the game's logo, as a display font. We also added various art pieces into the background to add a bit more flare to the design.

Our biggest changes were to the card category select screen and the filters. We thought that out initial design of the card category select screen would be too consistent and might confuse users. It also looked strange. Instead, we used the rounded tiles with the color and logos of each card element used in the game. As for the filters, we felt they were too rudimentary and need a bit more put into them. We found that using checkboxes with the Magic The Gathering symbol in the filled in checkboxes really pulled it together. We also added a some more designs for the interaction.

<h3>実施設計</h3>

<h4>しばらくスマホでよく展示しなくてしまいません。</h4>

<div style="position: relative; padding-bottom: 67.5%; height: 0; margin: 10px 0; overflow: hidden;">
  <iframe style="border: 1px solid rgba(0, 0, 0, 0.1); position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FsDW38BfMENB7mm0p1anmJu%2FMTG-Vending-Project%3Fpage-id%3D56466%253A190%26node-id%3D56466%253A714%26viewport%3D-998%252C559%252C0.4117658734321594%26scaling%3Dscale-down" allowfullscreen></iframe>
</div>