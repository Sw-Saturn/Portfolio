---
title: "おだて鏡"
summary: "人の顔を美しく見せかけてくれるソフト"
authors: []
tags: ["Python","OpenCV","Face++","VoiceRecognition"]
categories: []

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Sw-Saturn/ShirayukiHime"
url_pdf: ""
url_slides: "https://speakerdeck.com/12swsaturn/hacku2018tokyo-odatejing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

{{< speakerdeck b06f41dc977a4b459fa899762e3a2ad2 1.77777777777778 >}}

HackU2018 TOKYOにて発表した作品．

「鏡よ鏡，この世で一番美しいのは誰..?」と言うと，ディスプレイ上に美しい容姿のあなたが映し出される．

##### 構成

- docomo音声認識APIで声を認識する
- Face++ APIで性別，年齢を画像認識
- OpenCVで顔認識し，リアルタイムに顔画像を合成しディスプレイに出力
- VoiceTextで音声合成しレスポンスを送る
