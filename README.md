# vuejs-jp/012-jp.vuejs.org

このリポジトリは Vue.js v0.12 向けのドキュメントを管理しているレポジトリです。

このサイトは [hexo](http://zespia.tw/hexo) で構築されています。サイトコンテンツは `source` の位置に markdown フォーマットで書かれています。プルリクエスト、歓迎します！

## 貢献ガイド
[Vue.js 公式サイト日本語翻訳ガイド](https://github.com/vuejs-jp/vuejs.org/blob/lang-ja/CONTRIBUTING.md) を一読お願いします！

## 開発

**hexo 3.0 以降** を使っているか確認してください。`localhost:4000` で開発サーバーを開始します。

```
$ npm install -g hexo-cli
$ npm install
$ hexo server
```

## デプロイ

### Node バージョン

v6.3.0

### デプロイ時のビルドに必要なもの

```
$ npm i -g grunt-cli webpack@1.11.0 hexo@3.4.0
```

### Vue レポジトリの用意
```
$ cd ../ # repo `012-jp.vuejs.org` があるディレクトリの親に移動
$ git clone git@github.com:vuejs/vue.git # vue の repo を clone
$ git checkout 0.12 # vue@v0.12 の branch へ checkout
$ npm install # vue@v0.12 上での npm install
```

### make deploy の実行

```
$ make deploy
```

## 翻訳プロジェクト発起人
(アルファベット順)

- [hashrock](https://github.com/hashrock)
- [kazupon](https://github.com/kazupon)
- [kojimakazuto](https://github.com/kojimakazuto)
- [positiveflat](https://github.com/positiveflat)
- [tejitak](https://github.com/tejitak)
- [yasunobuigarashi](https://github.com/yasunobuigarashi)

## 貢献者
(アルファベット順)

- [bouzuya](https://github.com/bouzuya)
- [chi-bd](https://github.com/chi-bd)
- [chrispecoraro](https://github.com/chrispecoraro)
- [hrysd](https://github.com/hrysd)
- [mono0x](https://github.com/mono0x)
- [pocke](https://github.com/pocke)
- [showwin](https://github.com/showwin)
- [sunya9](https://github.com/sunya9)
- [tnir](https://github.com/tnir)
- [y-yagi](https://github.com/y-yagi)
- [zakuro9715](https://github.com/zakuro9715)
