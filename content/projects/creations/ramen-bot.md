{
    "title":"Ramen-Bot",
    "link":"https://github.com/Sw-Saturn/ramenBot",
    "image":"/img/ramen-bot.jpg",
    "description":"らーめんたべたいBot",
    "featured":true,
    "tags":["Azure","Docker","Go","Gurunavi-api","LINE","json"],
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"20",
    "sitemap": {"priority" : "0.2"}
}

LINEで位置情報を送信すると近くのラーメン屋を返してくれるBot。



##### 構成
- サーバー: Go
- コンテナ: [https://hub.docker.com/r/swsaturn/ramen_bot](https://hub.docker.com/r/swsaturn/ramen_bot)
- レストラン取得API: [ぐるなび Web Service - レストラン検索API](https://api.gnavi.co.jp/api/manual/restsearch/)
- デプロイ先: Azure App Service
- CIサービス: Azure DevOps Pipelines

<img src="/img/ramen-bot.gif" width=30%>
