# MTML Completions について

MTML Completions は Sublime Text 2 で Movable Type のテンプレートタグ（MTML）の入力補完を提供するパッケージです。  
[DynamicMTML](https://github.com/movabletype/DynamicMTML) のタグも含まれています。

## インストール

### Package Control を使ったインストール

_※あらかじめ Package Control をインストールしておく必要があります。_

Package Controlを起動し「Install Package」を選択し、「MTML Completions」を選択します。

### Git を使ったインストール

_※あらかじめ Git をインストールしておく必要があります。_

Sublime Text 2 の Packages ディレクトリに移動し、git clone します。

```
cd /path/to/your/Sublime Text 2/Packages
git clone https://github.com/bit-part/MTML-ST2
```

### zip ファイルによるインストール

zip ファイルをダウンロードし、Sublime Text 2 の Packages ディレクトリに展開します。

## 動作方法

HTMLとPHPの場合、「<」を入力した時点で自動で補完されます。  
拡張子を .mtml や .tmpl と設定している場合は、シンタックスモードをhtmlにすれば補完されます。

## 表示サンプル

![表示サンプル](http://bit-part.github.com/data/img_mtml-st2.png)

* [B]：Blockタグ
* [F]：Functionタグ
* [C]：Conditionalタグ

![モディファイア表示サンプル](http://bit-part.github.com/data/img_mtml-st2_modifier.png)

Ctrl + Spaceでグローバルモディファイアを補完します

* [M]：モディファイア

## 謝辞

このパッケージの作り方は、 [dreamseeker/ST2MovableType · GitHub](https://github.com/dreamseeker/ST2MovableType) を参考に作りました。[Toru Kokubun](https://github.com/dreamseeker) さんに深く感謝いたします。

---

_Movable Type は Six Apart, Ltd. の登録商標です。_
