---
title: "Class-bot"
summary: "毎朝8時10分に当日の時間割を通知するBot"
authors: []
tags: ["Flask","Python","LINE","json"]
categories: []

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "/img/linebot.png"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Sw-Saturn/LINE-bot"
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

毎朝8時10分に当日の時間割を通知するBot．

サーバー上に授業日程をjson形式で配置しており，現在はそれを読み出す形で動作している．

将来的には，汎用性を持たせるため，データベースで情報を管理したいと思っている．

##### 構成

- プロセス管理:Systemd
- データベース:MySQL
- サーバー:さくらのVPSサーバー

