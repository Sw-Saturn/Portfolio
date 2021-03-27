---
title: "Translator-bot"
summary: "外国語のテキストを送ると日本語に翻訳してくれるChatBot"
authors: []
tags: ["Azure", "node", "LINE", "json"]
categories: []

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Sw-Saturn/translation-line-bot"
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

外国語のテキストを送信すると，日本語に翻訳して返信してくれる LINE Bot

##### 構成

- サーバー: Azure Bot Service(node.js)
- 翻訳 API: Azure Translator Text API
- デプロイ先: Azure App Service
