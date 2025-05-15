このプロジェクトは、都道府県の県庁所在地を当てるクイズゲームです。日本地図上で都道府県を選択し、正解・不正解に応じて得点が加算・減点されます。

## 構成ファイル

- `index.html`  
  メインのHTMLファイル。地図表示・クイズロジック・UIが含まれています。

- `csv/kenchou-shozaichi.csv`  
  都道府県と県庁所在地のデータを格納したCSVファイル。

- `map/dist/jpmap.min.js`  
  日本地図を描画するためのJavaScriptライブラリ。

- `img/`  
  正解・不正解時に表示する画像を格納します。

- `oto/`  
  正解・不正解時に再生する効果音ファイルを格納します。

## 日本地図ライブラリ
jQueryのプラグインであるJapan Map

## 必要環境

- Webブラウザ（Google Chrome推奨）
## サウンド
- 効果音ラボ（https://soundeffect-lab.info）

## 使い方

1. プロジェクトをクローンまたはダウンロードします。
2. `index.html` をブラウザで開きます。
3. 「スタート」ボタンを押してゲームを開始します。
## デモ
https://ken7python.github.io/Todouhuken/

## ディレクトリ構成例

```
project-root/
├── index.html
├── csv/
│   └── kenchou-shozaichi.csv
├── img/
│   └── seikai.png
│   └── zannen.png
├── oto/
│   └── seikai.mp3
│   └── matigai.mp3
├── map/
│   └── dist/
│       └── jpmap.min.js
└── .gitignore
```

## ライセンス

このプロジェクトのライセンスは `LICENSE` ファイルを参照してください。