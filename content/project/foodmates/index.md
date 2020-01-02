---
title: "めしめーと"
summary: "美味しい料理を新発見するために、好みが近い人と繋がることができるサービス"
authors: []
tags: ["AWS","MySQL","Golang","Gin","GORM"]
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

url_code: ""
url_pdf: ""
url_slides: "https://speakerdeck.com/12swsaturn/mesimeto"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
{{< speakerdeck 1d807680b7bf42bbab3d909f79a7b377 1.77777777777778 >}}

jig.jp学生インターンプログラム2019にて，4人1チームで制作したプロダクト。

・外食に行ってみたいが不安な人

・新しい料理を安心して食べに行きたい人

これらの人をターゲットとし、SNSのような形で料理の名前、写真を投稿できるサービス。

##### 構成

- プロセス管理:Systemd
- データベース:MySQL(サーバーからはGORMでアクセス)
- デプロイ先:AWS(EC2)
- サーバー:Golang(Gin)

#### クライアントサイド

GitHubリポジトリ: [https://github.com/jigintern/Foodmates-client](https://github.com/jigintern/Foodmates-client)

#### サーバーサイド

GitHubリポジトリ: [https://github.com/jigintern/Foodmates-server](https://github.com/jigintern/Foodmates-server)


