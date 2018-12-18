{
    "title":"LINE-bot",
    "link":"https://github.com/Sw-Saturn/LINE-bot",
    "image":"/img/linebot.png",
    "description":"毎朝8時10分に当日の時間割を通知するBot",
    "featured":true,
    "tags":["Server","MySQL","Python","LINE","json"],
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"20",
    "sitemap": {"priority" : "0.2"}
}

毎朝8時10分に当日の時間割を通知するBot．

サーバー上に授業日程をjson形式で配置しており，現在はそれを読み出す形で動作している．

将来的には，汎用性を持たせるため，データベースで情報を管理したいと思っている．

##### 構成
- プロセス管理:Systemd
- データベース:MySQL
- サーバー:さくらのVPSサーバー

<img src="/img/linebot.png" width=30%>