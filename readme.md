#mvc2のモデル（表示とロジックを分ける）
##web開発で使用するmvc2のモデル、スタート構成です

[htdocs]が公開ディレクトリでcontrollerの置き場所です

クライアントからのhttp通信はhtdocsの中のcontrolerファイル群がさばくように作ります

[conf]は設定ファイル

[model]はデータやデータベースへのアクセス、ビジネスロジック全般を処理します

[view]表示用のファイルです

[controller]が必要に応じて[model]に処理を渡し、結果を[view]で表示（html）に整形します

<img src="http://www.weblabo.work/sample/data/img/mvc.png">
