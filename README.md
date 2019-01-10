# hmtrump Package

## What is this?

You will be able to describe playing cards using *hmtrump* package.
**This package needs LuaLaTeX**.

## How to use?

1. Install NKD04 Playing Card's Index font
1. \usepackage{hmtrump} in preamble
1. To describe cards, use \trump{*rank*}{*suit*}

+ *rank*: 1 to 9, T (meaning 10), J, Q, K
+ *suit*: S (Spade), H (Hard), D (Diamond), C (Club), x (no suits)

## Manual

hmtrump.pdf is manual, written in Japanese.

## 日本語でok

hmtrump.pdf がマニュアルです。ご一読ください。

### 使い方

**LuaLaTeX** を必要とします（fontspec パッケージを内部で読み込みます）。

まずはじめに、同梱の NKD04 Playing Card's Index フォントをインストールしてください。

プリアンブルに \usepackage{hmtrump} と書けば使用することができます。

トランプのカードを出力するには \trump{*rank*}{*suit*} とします。
*rank* は 1〜9 の数字または T(10), K, Q, J を指定し、*suit* には S, H, D, C, x
（スペード、ハート、ダイヤ、クラブ、スートなし）を指定します。

その他提供される命令はマニュアルを参照してください。