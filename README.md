# リイルヘイラの仮ラジオ（試験放送）

リイルヘイラが、ニュースや日報を読み上げるラジオ局の試験用リポジトリです。
局名・番組内容はまだ仮置きで、これから育てていきます。

▶ **ON AIR**: https://workshop7538315-del.github.io/radio-test/

- プレーヤーは `index.html`、局の設定は `station.json`、台本は `episodes/` にあります
- 音声は main にはコミットしません。`tools/publish.sh` が直近30日分だけを `gh-pages` に載せます

## クレジット

- 声：VOICEVOX:暁記ミタマ
- キャスター：リイルヘイラ（電波の姿を仮置き中）
- 仕組み：[myradio](https://github.com/monoradio102/myradio) テンプレート（monoradio）を利用しています。プログラム（`index.html`、`tools/`）は MIT License です
