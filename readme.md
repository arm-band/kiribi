# ![Kiribi](https://github.com/arm-band/kiribi/blob/master/misc/img/kiribi.png)

自分用の小規模Webサイト制作用テンプレートです。  
主にデモやテストサイト用。

## How to use?

使い方

### Preparement

事前に以下の準備が必要です。

- Sass(ruby)がインストール・設定済

### Download

このテンプレートは以下のライブラリ・フレームワークの使用を前提としています。  
使用前にダウンロード等の準備をしてください。

- Bootstrapテーマ(日本語対応) ※Scss版 … ver3.3.7
- Font Awesome(CDN使用) … ver4.6.3
- scss
    + sns色一覧
    + 游ゴシック対応フォント指定
    + ハンバーガーメニューのアニメーション
- jQuery
    + jQuery(CDN使用) … ver2.2.2 ※Bootstrapが3未満を要求するため
    + jQuery Easy Easing … ver1.3

### Using

srcをプロジェクトディレクトリにセットして、distディレクトリを用意。あとはsrc内を適宜編集してください。

## Function

用意している機能

- now loading
- アイキャッチ(高さ100vh, 背景fixed) ※画像は適宜用意
- ページトップへ戻る

### Extension

node.js, npm, gulpを前提としても良いですが、一先ず最低限Scssのみ。

## Release

- 2018/01/02 Ver 2.0.0
    - 名前を付けました
    - 各種微調整
- 2017/12/22 ver.1.3.3
    - Bootstrapキャンセラーに追記
- 2017/12/05 ver.1.3.2
    - Bootstrapキャンセラーに追記
- 2017/11/16 ver.1.3.1
    - Bootstrapでいつも気になる指定をキャンセルするscssを追加
- 2017/10/18 ver.1.3.0
    - キービジュアルのmobileSafari対策が不十分だったのを修正
- 2017/10/18 ver.1.2.0
    - onw-libの中に丸ゴシックの記述を追加
- 2017/7/19 ver.1.1.2
    - フッタの微修正（scssファイル）
- 2017/7/6  ver1.1.1
    - Font CDNのAwesomeを4.7.0にバージョンアップ
- 2017/2/22 ver1.1.0
    - キービジュアルのmobileSafari対策が不十分だったのを修正
    - CDNのFontAwesomeとjQueryのバージョンを上げた
- 2017/2/22 ver1.0.7 (内部的には7番目なので)