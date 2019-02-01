# Comment

## Go言語の経験

良書として勧められた[Goならわかるシステムプログラミング](https://www.lambdanote.com/products/go)を一通り読んで写経した程度．

## 提出時に添えた苦労・工夫した点

苦労した点：os.Walkをtreeの実装に活用できないか試行錯誤したが，結局活用せずに実装したため遠回りして苦労した．Symbolic Linkがos.Stat()ではエラーとなり，os.Lstat()を使えば良いことに気づくまで少し遠回りした．

工夫した点：表示する深さを指定できるようにした，ヘルプを表示するようにした，ツリー表示する順番をアルファベット順にした，ツリー表示するパスが指定されなかった場合"."をパスとするようにした，複数のパスのツリーを表示できるようにした，treeと似たusageやerrorメッセージとした点，.で始まるファイルやフォルダは無視する点．

## 反省点

課題を無事に提出して参加してきた．簡単に提出コードに関するフィードバックがあり，個人的に反省するべき点は，テストを書くことと，出力を一旦バッファに貯めること．