---
title: "TRY 聴音羽 -聴覚障がい者会話支援システム-"
summary: "聴覚障害者と健聴者の自然に会話を支援するAndroidアプリケーション"
authors: []
tags: ["Android", "Firebase", "Java", "VoiceRecognition"]
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

url_code: "https://github.com/Sw-Saturn/TRY_Ultrasonic"
url_pdf: ""
url_slides: "https://speakerdeck.com/12swsaturn/tryting-yin-yu"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

{{< speakerdeck e33a67d3db07468db72d22867b4d6dad 1.77777777777778 >}}

第 28 回全国高専プロコン自由部門にて発表した作品．

聴覚障害者と健聴者の会話を支援する Android アプリケーション．

聴覚障害者にスマートフォンを持っていただき，チャットベースで会話を行う．

指向性スピーカー、指向性マイクを使ったケースを作成し，より遠くの人に話しかけることが可能．

また返答も問題なく拾うことが可能．

##### 構成

- 音声認識: Google Speech Recognizer
-  音声合成: VoiceText Web API
- チャットサーバー: Firebase

{{< figure src="/img/tryus.png" width="40%" >}}
