---
title: 「Mutter・Museum」と言う博物館の「Hertyl・Skull・Collection」のためのユーザーインターフェース
summary: フィラデルフィアの「Mutter・Museum」と言う博物館の「Hertyl・Skull・Collection」のためのユーザーインターフェースの原型。
tags:
# - Deep Learning
date: "2020"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: fa-figma
  icon_pack: fab
  name: プロトタイプへ
  url: https://www.figma.com/proto/SAB5uqUzoRsV0c8Qs7Nor2/Jacob-Scarani-Museum-Interactive-Exhibit?page-id=212%3A990&node-id=270%3A54&viewport=637%2C487%2C0.22918730974197388&scaling=contain
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

<h4>＊翻訳は進行中です＊<h4>

<!-- <h3>背景</h3>

For this project, I set out to design an interactive UI for an existing museum exhibit. Living in the Philadelphia area, I am lucky to have access to a plethora of museums. However, I set my sights on one particular museum; The Mutter Museum of The College of Physicians of Philadelphia. I wanted to work on an exhibit that was unique, and where else to find unique museum exhibits in Philadelphia other than the Mutter Museum? However, due to the graphic nature of the museum, my choices were rather limited. I chose to create an interactive screen for the Hyrtl Skull Collection. The Hyrtl Skull Collection is a collection of 139 skulls acquired from a Viennese anatomist Joseph Hyrtl (1810-1894) in 1874. Hyrtl's goal with the collection was to show how varied cranial autonomy was in Caucasians in Europe and debunk teh claims of phrenologists that cranial feature were an indicator of the level of ones intelligence. -->

<h3>問題</h3>

フィラデルフィアのマター博物館(Mutter Museum)でヒルトルスカル展示(Hyrtl Skull Exhibit)があります。博物館で他の展示のようにヒルトルスカル展示は大きい陳列棚に入っています。頭骨が多いしグラスの反射に頭骨を醜いにならされるので視覚障害者と色々な訪問者に展示が見にくいかもしれません。
<!-- The Hyrtl Skull Collection, among the Museums many other exhibits, is located in a large glass display case. Due to the sheer amount of skulls, and the glass, the exhibit could be hard for those with low-vision or height restrictions in viewing the skulls freely. Furthermore, visitors could easily be overwhelmed by the sheer amount of skulls and either only look at and read about a few or just briefly glance over the collection. When I visited myself, I only looked at a few skulls before moving on. -->

<h3>解決</h3>

訪問者が難なく頭骨をみって情報を読んで展示のインタラクティブ画面をデザインすることにしました。このインタラクティブ画面で頭骨に違おう見方してもっと情報を見る事もできます。画面で頭骨を見る時展示の中で本当の頭骨をライトアップするはずです。

<!-- I sought out to design an interactive display that would allow visitors to rad about each and every skull in a much less overwhelming manner while also giving them the ability to see the skull in angles not possible from the display case. It would also provide more information about the cranial features of the skull and light up the skull in the display case so as not to take away from the physical exhibit. This would make it easier for visitors with limited sight and height restrictions to look at and read about the skulls, while also encouraging more exhibit engagement from all visitors. -->

<h3>ワイヤーフレーム</h3>

<img src="/portfolio/hyrtl/wireframes.png" alt="3 low fidelity wireframes from the project">

画面を三つデザインしました。最小のはぜんぶの展示の頭骨を見える画面。この画面から特定の頭骨を選んでもっと方法を読める画面に行けます。頭骨の情報を読める画面で見つかったところや人の名前や年齢をよめます。最後に頭骨の3Dモデルの画面をでざいんしました。この画面で頭骨の3Dモデルを回したり頭骨の面白い特徴を見たりできます。

<!-- I created 3 main screens. One screen where users could browse the skulls in the exhibit, A screen with information about a selected skull (with the real skull in the display case lit up), and a screen where a 3D model of the skull could be viewed and interacted with that made note of certain features of the skulls. -->

<h3>ユーザーフロー</h3>

<img src="/portfolio/hyrtl/flow.png" alt="A user flow diagram of the project">

<h3>スタイルガイド</h3>

<img src="/portfolio/hyrtl/styleguide.png" alt="The styleguide for the project that shows the typeface usage, the colors, and the inspiration">

レトロのデザインがあるサイトや博物館のブランドデザインに関わらせました。

<h3>実施設計</h3>

<h4>しばらくスマホでよく展示しなくてしまいません。</h4>

<div style="  position: relative; padding-bottom: 67.5%; height: 0; margin: 10px 0; overflow: hidden;">
  <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FSAB5uqUzoRsV0c8Qs7Nor2%2FJacob-Scarani-Museum-Interactive-Exhibit%3Fpage-id%3D212%253A990%26node-id%3D270%253A54%26viewport%3D637%252C487%252C0.22918730974197388%26scaling%3Dcontain" allowfullscreen></iframe>
</div>