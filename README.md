---
created: 2025-05-12T11:14
updated: 2025-05-12T11:38
---
# Marpit Corporate Slide Template

<div align="center">
<img alt="Static Badge" src="https://img.shields.io/badge/-markdown-000000.svg?style=flat&logo=markdown&logoColor=black&labelColor=white">

</div>

## 概要

### プロジェクト背景

このリポジトリは、個人プレゼンテーションのためのMarpit CSSテンプレートを提供します。統一されたフォーマットでプレゼンテーションを作成することで、効率的に情報を伝達することを目指しています。


### ステータス

開発中

## 環境と使用技術

- Marpit + VSCode

## セットアップ方法

1. VS Codeの拡張機能(marp-team.marp-vscode)を手にいれる:

![vscode_ext](./images/vscode_ext.png)

1. リポジトリのクローン:

    ```bash
    git clone https://github/pythonista-blitz/marpit-template.git
    ```

1. VS Codeの拡張機能設定からCSSファイルのパスを指定する:

```bash
marpit-template/css/nista.css
```

## 使用方法（または実行方法）

マークダウンの先頭にmarpの記法を追加する際に、設定で追加したnistaテーマをthemeに指定する。

```markdown
---
# テーマ設定
theme: nista
# ページ番号を表示する
paginate: true
# サイズ指定
size: "16:9"
# marpの使用
marp: true
# ヘッダー
header: yyyy/mm/dd
# スライド区切り:h2(h1をタイトルとして認識させているため)
headingDivider: 2
---
```

## その他

**このテンプレートは個人のプレゼンテーション専用です。
