---
title: "dmz_ai"
summary: "10分おきに自分の発言をベースにつぶやくBot"
authors: []
tags: ["Golang","Twitter","MeCab"]
categories: []

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Sw-Saturn/dmz_ai.go"
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

自分のTwitterアカウントの発言をベースにして発言させるbot

Twitterの発言を形態素解析し，マルコフ連鎖によって言語化し，TwitterAPIから投稿する．

##### 構成
- プロセス管理:Systemd
- サーバー: Golang
- サーバー:さくらのVPSサーバー

{{<dmz_ai>}}
