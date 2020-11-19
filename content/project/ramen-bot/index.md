---
title: "Ramen-Bot"
summary: "らーめんたべたいBot"
authors: []
tags: ["Azure","Docker","Go","Gurunavi-api","LINE","json"]
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

url_code: "https://github.com/Sw-Saturn/ramenBot"
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

LINEで位置情報を送信すると近くのラーメン屋を返してくれるBot。

##### 構成

- サーバー: Go
- コンテナ: [https://hub.docker.com/r/swsaturn/ramen_bot](https://hub.docker.com/r/swsaturn/ramen_bot)
- レストラン取得API: [ぐるなび Web Service - レストラン検索API](https://api.gnavi.co.jp/api/manual/restsearch/)
- デプロイ先: Azure App Service
- CIサービス: Azure DevOps Pipelines

{{< figure src="/img/ramen-bot.gif" width="40%" >}}
