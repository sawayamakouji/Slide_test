---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Bolt.new & StackBlitz 入門
  AI駆動型Web開発ツールについて学ぶ
drawings:
  persist: false
css: unocss
fonts:
  # Noto Sans JPをメインのフォントとして使用
  sans: 'Noto Sans JP'
  # M PLUS Rounded 1cを見出し用フォントとして使用
  serif: 'M PLUS Rounded 1c'
  mono: 'Fira Code'
---

# Bolt.new & StackBlitz
AI駆動型Web開発ツール

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    スペースキーで次のページへ <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://bolt.new" target="_blank" 
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-rocket />
  </a>
</div>

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# Bolt.newとは？

AIパワーのWebアプリケーションビルダーです：

- 🤖 **AI駆動開発** - 自然言語でアプリを構築
- 🌐 **ブラウザベース** - ローカル環境設定不要
- 🚀 **フルスタック対応** - 構築、実行、デプロイまで完結
- ⚡ **即時プレビュー** - リアルタイムで変更を確認
- 🔄 **シームレスな連携** - StackBlitzと直接連携

<br>

StackBlitzチームが開発した、Web開発を革新するツール

---

# Bolt.newを始めよう

<div class="grid grid-cols-2 gap-4">

<div>

### 始め方：
1. Bolt.newにアクセス
2. ログインまたは登録
3. プロンプトを入力
4. アプリが作られる様子を確認！

### プロンプト例：
```
ToDoリストアプリを作成して
```

</div>

<div>
<img
  class="rounded-lg shadow-xl"
  src="https://i.gyazo.com/b8c8a921f5c6288291329f603a386c75.png"
  alt="Bolt.newインターフェース"
/>
</div>

</div>

---

# Bolt.newのインターフェース

<div class="grid grid-cols-2 gap-4">

<div>

### 主な機能：
- ライブプレビューウィンドウ
- コードエディタ
- AIチャットインターフェース
- 即時デプロイオプション

### プレビュー機能：
- インタラクティブなコンポーネント
- リアルタイム更新
- レスポンシブデザインテスト

</div>

<div>
<img
  class="rounded-lg shadow-xl"
  src="https://i.gyazo.com/f1e6afe67feece4fba47f7150b889130.png"
  alt="Bolt.newプレビュー"
/>
</div>

</div>

---

# コードプレビューとエディタ

<div class="grid grid-cols-2 gap-4">

<div>

### エディタ機能：
- シンタックスハイライト
- オートコンプリート
- 複数ファイル対応
- 統合ターミナル

### 表示切替：
- プレビューとコードの切り替え
- 分割画面オプション
- フルスクリーンモード

</div>

<div>
<img
  class="rounded-lg shadow-xl"
  src="https://i.gyazo.com/c4e092666896aa2a3e9e8e9e9bcb2eca.png"
  alt="コードプレビュー"
/>
</div>

</div>

---

# StackBlitzとの連携

<div class="grid grid-cols-2 gap-4">

<div>

### シームレスなワークフロー：
- ワンクリックでStackBlitzを起動
- フル開発環境
- 高度な編集機能
- チーム協業機能

### メリット：
- プロフェッショナルなIDE機能
- バージョン管理
- パッケージ管理
- デプロイオプション

</div>

<div>
<img
  class="rounded-lg shadow-xl"
  src="https://i.gyazo.com/2d815896c07ff01fd392f2a001d87069.png"
  alt="StackBlitzインターフェース"
/>
</div>

</div>

---
layout: center
class: text-center
---

# 今すぐ始めよう！

Bolt.newとStackBlitzで、Web開発の未来を体験

[Bolt.newを開く](https://bolt.new) · [詳細を見る](https://stackblitz.com)

<style>
h1 {
  font-family: 'M PLUS Rounded 1c', sans-serif;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

h2, h3 {
  font-family: 'M PLUS Rounded 1c', sans-serif;
}

.slidev-layout {
  font-family: 'Noto Sans JP', sans-serif;
}
</style>