# STM32F1開発ボード
ケチケチのSTM32最小開発ボードです。チップはSTM32F103C8T6です。JLCPCBで発注することを想定しています。
Basic Partのみ使っており、部品代と送料以外何もかかっていないのでそれなりに安く発注できると思います。発注枚数にもよりますが、1枚当たりの単価は3~4ドルくらい。日本円にすると単価が500円を切るので悪くないんじゃないかなぁと（最もAmazonだと単価370円になったりしている商品もありますが、USBの抵抗値が間違えていたりバックアップバッテリーを取り付けにくいなどの欠陥を抱えていることがあるので難しいところ）。

USBで書き込みたい場合は基板を改造してください。USBのコネクタはBasic Partにないので今回は外しています。

productionフォルダにガーバーと部品表、部品配置ファイルが入っています。

## 追記
よく考えたら水晶発振子周りのキャパシタや配線適当すぎて全く使い物にならない...
