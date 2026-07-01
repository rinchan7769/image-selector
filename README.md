# 画像選別ツール PWA

AI生成イラストの選別・連番リネームツール（iPhone最適化）

---

## 📱 使い方

| 操作 | 動作 |
|------|------|
| 「追加」ボタン | 画像を読み込む |
| サムネイルをタップ | 選別に追加 / 除外 |
| 長押し → 右へドラッグ | 選別パネルに追加 |
| 右パネルをタップ | 選別から除外 |
| No. 入力 | 連番の開始番号を変更 |
| ZIPダウンロード | 001.jpg, 002.jpg... で保存 |

---

## 🚀 GitHub Pages へのアップロード手順

### 1. GitHubアカウント作成
https://github.com にアクセス → Sign up（無料）

### 2. リポジトリ作成
- 右上「+」→「New repository」
- Repository name: `image-selector`
- Public を選択
- 「Create repository」をクリック

### 3. ファイルをアップロード
- 「uploading an existing file」をクリック
- 以下のファイルを全て選択してドラッグ：
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icons/` フォルダごと
- 「Commit changes」をクリック

### 4. GitHub Pages を有効化
- リポジトリの「Settings」タブ
- 左メニュー「Pages」
- Branch: `main` / `(root)` を選択 → Save

### 5. URLを確認（5分ほどで有効になります）
```
https://あなたのユーザー名.github.io/image-selector/
```

### 6. iPhoneのホーム画面に追加
1. iPhoneのSafariでURLを開く
2. 画面下の「共有」ボタン（□↑）をタップ
3. 「ホーム画面に追加」をタップ
4. 「追加」をタップ

✅ これでアプリアイコンがホーム画面に表示されます！

---

## 📝 ファイル構成

```
image-selector/
├── index.html      # メインアプリ
├── manifest.json   # PWA設定
├── sw.js           # オフライン対応
└── icons/
    ├── icon-192.png
    └── icon-512.png
```
