# STM32F1開発ボード
ケチケチのSTM32最小開発ボードです。チップはSTM32F103C8T6です。JLCPCBで発注することを想定しています。
Basic Partのみ使っており、部品代と送料以外何もかかっていないのでそれなりに安く発注できると思います。発注枚数にもよりますが、1枚当たりの単価は3~4ドルくらい。日本円にすると単価が500円を切るので悪くないんじゃないかなぁと（最もAmazonだと単価370円になったりしている商品もありますが、USBの抵抗値が間違えていたりバックアップバッテリーを取り付けにくいなどの欠陥を抱えていることがあるので難しいところ）。

また、Arduino IDEで使いたかったのでSWDではなくUARTで書き込む基板になっています。シリアル変換はこういうものを使うと良いでしょう。

[秋月電子　ＣＨ３４０Ｅ　ＵＳＢシリアル変換モジュール　Ｔｙｐｅ－Ｃ](https://akizukidenshi.com/catalog/g/gK-14745/)

USBで書き込みたい場合は基板を改造してください。USBのコネクタはBasic Partにないので今回は外しています。

productionフォルダにガーバーと部品表、部品配置ファイルが入っています。

![image](https://user-images.githubusercontent.com/48169975/231992126-a5dd5352-0489-4b56-8d52-f504bca738e5.png)
![image](https://user-images.githubusercontent.com/48169975/231992295-7a19fd3a-0acb-45f4-b1fb-e37810be20b6.png)
