# zenn-content

[Zenn](https://zenn.dev/) に公開する記事と本のリポジトリ。

## 構成

```
articles/   記事（1ファイル1記事）
books/      本
```

## 書き方

記事の frontmatter は次の形。`published: false` の間は下書きとして扱われ、Zenn 上には公開されない。

```yaml
---
title: ""
emoji: "🔧"
type: "tech"   # tech: 技術記事 / idea: アイデア
topics: []
published: false
---
```

## ローカルでプレビューする

```bash
npx zenn-cli preview
```

## 新しい記事を作る

```bash
npx zenn-cli new:article --slug <slug>
```

slug は半角英数字・ハイフン・アンダースコアで 12〜50 文字。
