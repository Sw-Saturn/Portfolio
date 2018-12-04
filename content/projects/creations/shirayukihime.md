{
    "title":"おだて鏡",
    "link":"https://github.com/Sw-Saturn/ShirayukiHime",
    "image":"/img/shirayukihime.jpg",
    "description":"人の顔を美しく見せかけてくれるソフト",
    "featured":true,
    "tags":["Python","OpenCV","Face++","VoiceRecognition"],
    "fact":"Reduce page load time from minutes to instantaneous.",
    "weight":"40",
    "sitemap": {"priority" : "0.2"}
}

HackU2018 TOKYOにて発表した作品．

「鏡よ鏡，この世で一番美しいのは誰..?」と言うと，ディスプレイ上に美しい容姿のあなたが映し出される．

##### 構成
- docomo音声認識APIで声を認識する
- Face++ APIで性別，年齢を画像認識
- OpenCVで顔認識し，リアルタイムに顔画像を合成しディスプレイに出力
- VoiceTextで音声合成しレスポンスを送る