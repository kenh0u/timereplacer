# Time Replacer

[https://kenh0u.github.io/timereplacer.html](https://kenh0u.github.io/timereplacer.html)

## Description

Time Replacerは、YouTube配信をリアルタイム視聴する際、その配信終了後のアーカイブへのコメントにタイムスタンプを付けるための補助ツールです。
配信視聴中に配信開始からの時間を知ることができない環境にて役立てられると思います。

## Usage

1. 配信を見ながら面白い部分の時刻(HH:MM:SS)と内容等をメモします。
2. "Time"フォームに、配信開始時刻(HH:MM:SS)を入力します。
3. "Text"フォームに、1で作ったメモを入力します。
4. "Replace Time"ボタンをクリックします。
5. "Result"フォームに、"Text"の各行先頭の時刻から"Time"の時刻を減算したテキストが表示されます。
6. "Copy to Clipboard"ボタンをクリックすると、"Result"フォームの内容がクリップボードにコピーされます。
7. 配信アーカイブにて正しい時間を探り直し、コメントとして投稿します。

## Note

- 単一のHTMLにて動作します。
- 時刻のフォーマットはH:MM:SSやMM:SSやM:SSも使用でき、いずれの場合も出力はHH:MM:SSになります。
  - "Time"フォームに0を指定すれば既存のコメントのタイムスタンプをHH:MM:SSに揃えるという使い方もできます。
- 先頭が時刻ではない行はそのまま出力されます。

## License

Time Replacerは、GPL-3.0で公開されています。詳細は、LICENSEファイルを参照してください。
