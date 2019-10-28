{
    "title":"めしめーと",
    "image":"/img/foodmates.jpg",
    "description":"美味しい料理を新発見するために、好みが近い人と繋がることができるサービス",
    "featured":true,
    "tags":["AWS","MySQL","Golang","Gin","GORM"],
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"10",
    "sitemap": {"priority" : "0.8"}
}

・外食に行ってみたいが不安な人

・新しい料理を安心して食べに行きたい人

これらの人をターゲットとし、SNSのような形で料理の名前、写真を投稿できるサービス。

##### 構成
- プロセス管理:Systemd
- データベース:MySQL(サーバーからはGORMでアクセス)
- デプロイ先:AWS(EC2)
- サーバー:Golang(Gin)

#### クライアントサイド
GitHubリポジトリ: https://github.com/jigintern/Foodmates-client

#### サーバーサイド
GitHubリポジトリ: https://github.com/jigintern/Foodmates-server


<script async class="speakerdeck-embed" data-id="1d807680b7bf42bbab3d909f79a7b377" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>


