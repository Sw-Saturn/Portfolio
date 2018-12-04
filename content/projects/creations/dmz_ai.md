{
    "title":"dmz_ai",
    "link":"https://github.com/Sw-Saturn/dmz_ai",
    "image":"/img/me.jpg",
    "description":"15分おきに自分の発言をベースにつぶやくBot",
    "featured":true,
    "tags":["Server","SQLite","Python","MeCab"],
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"20",
    "sitemap": {"priority" : "0.2"}
}

自分のTwitterアカウントの発言をベースにして発言させるbot

Twitterの発言を形態素解析したものをSQLiteデータベースにしてサーバーに保存．

そのデータをマルコフ連鎖によって言語化し，TwitterAPIから投稿する．

##### 構成
- プロセス管理:Systemd
- データベース:SQLite
- サーバー:さくらのVPSサーバー

<a class="twitter-timeline" width=60% height="500px" href="https://twitter.com/dmz_ai?ref_src=twsrc%5Etfw">Tweets by dmz_ai</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>