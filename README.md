#  Myうちわアプリ

カメラで写真を撮って、自分だけのオリジナル団扇を作成＆印刷できるWebアプリです！

---

## 🌟 デモページ

👉 [デモを開く](https://chc-chupea.github.io/uchiwamaker/)  
※スマートフォンのブラウザからアクセス可能です。

---

## 📸 主な機能

- カメラで撮影＆プレビュー
- 母の日／父の日などのテンプレート選択
- 高解像度画像で印刷対応（A4サイズ）
- 多言語対応（日・英・中・韓・越）
- シャッター音・撮影アニメーションあり

---

## 🧑‍💻 使用方法

1. ページにアクセス
2. テンプレートを選択
3. カメラを許可する
4. 「📷」ボタンで撮影（シャッター音＆保存）
5. 保存された画像（高解像度）をGoogleフォームで送信

---

## 🗂️ フォルダ構成

.
├── index.html
├── camera-shutter.mp3
├── shutterbotann.png
├── fan1-lowres.png / fan1-highres.png
├── fan2-lowres.png / fan2-highres.png
├── fan3-lowres.png / fan3-highres.png

yaml
コピーする
編集する

---

## 🌍 多言語対応

日本語／英語／中国語／韓国語／ベトナム語 に対応。画面上部の言語ボタンで切り替え可能。

---

## 🛠️ 開発者向けメモ

- 静的サイトのためNode.js不要
- GitHub Pagesで無料ホスティング可能
- カメラは `navigator.mediaDevices.getUserMedia()` を使用
- 印刷は `@media print` を活用

---

## 📄 ライセンス

MIT License
