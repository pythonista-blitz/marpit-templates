---
theme: nista
paginate: true
size: 16:9
marp: true
header: yyyy/mm/dd
headingDivider: 2
created: 2025-05-12T11:14
updated: 2025-05-12T11:38
---
<!-- 
_class: titlepage
_header: 重要 
-->
# スライドのタイトルを # で入力しています

`文責: 黒瀬一平

<style>
@import url('https://fonts.googleapis.com/css2?family=M+PLUS+1&display=swap');
:root {
  font-family: 'M PLUS 1', sans-serif;
}
</style>
<!--
_class: toc
_footer: "." 
-->
## 目次<!-- omit in toc -->
この目次は Markdown All in One (vsCode拡張)の機能で作っています。
- [はじめに](#はじめに)
- [Markdownによる特殊記載](#markdownによる特殊記載)
- [リスト](#リスト)
- [テーブル](#テーブル)
- [画像](#画像)
- [画像(背景)](#画像背景)
- [画像(背景として右半分に貼り付け)](#画像背景として右半分に貼り付け)
- [画像(左側に 20% のサイズ指定)](#画像左側に-20-のサイズ指定)
- [穴埋めページ](#穴埋めページ)

<style>
@import url('https://fonts.googleapis.com/css2?family=M+PLUS+1&display=swap');
:root {
  font-family: 'M PLUS 1', sans-serif;
}
</style>
<!--
class: normal
footer: "."
-->
## はじめに
### この部分はh3です<!-- omit in toc -->
marpitはマークダウン形式からスライドを生成するフレームワークです。
業務上のメモをそのまま報告会や発表に転用できるので便利です。ぜひ使ってください。

必要なことは[マニュアル](https://marpit.marp.app/)を参照したほうが早いと思います。

また、[Marp for VS Code プラグイン](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)で作成することを想定しています。

## Markdownによる特殊記載

_Markdown_ の __記法__ により *斜体* や **太字** ~~打ち消し~~ などが書けます。

> blockquote
> 引用も書くことができます。

## リスト

- 1つめ
- 2つめ
1. 1つめ
2. 2つめ

## テーブル

テーブルも表示できます。

| left | center  |   right |
| :--- | :-----: | ------: |
| odd  | 200,000 | 300,000 |
| even | 123,456 |   2,000 |
| odd  | 999,999 | -50,000 |

## 画像

通常通り指定可能。mdファイルからの相対パス。
!["代替テキスト"](./images/image.jpg)