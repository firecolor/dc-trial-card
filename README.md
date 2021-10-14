# デザキャン10月体験会 Day3

2021.10.19に使用する教材になります。

----
## ファイル構成
```
card
├── _complete : 参考用に作成したファイルを格納
│
├── assets : アセットフォルダ
│   ├── css
│   ├── images
│
├── index.html
│
├── README.md : このファイル

```
/** ============================================================
 * RESET
 * A modern CSS reset
 * https: //github.com/andy-piccalilli/modern-css-reset
 * ========================================================== */
## 内容
1. HTMLの土台を作る
2. カードを作る
    * 画像の用意
    * 枠を作る
    * 画像とコンテンツの枠を作る
    * 画像を設定
    * コンテンツを作る
    * VSCodeに拡張機能Live Serverを追加
3. CSSを書いてみる
4. リセットを読みこむ
5. 外部ファイルを作る
6. カードを作りこむ
    * Bodyに色を付ける
    * カードの大きさ
    * カードのレイアウト
    * 画像の調整
    * コンテンツの調整
    * カードの位置
    * カードに装飾
----

### Lesson01 HTMLの土台を作る
1. Emmetの!で一気に枠を作る
2. `<meta http-equiv="X-UA-Compatible" content="IE=edge">`を消す
3. titleタグを記入する
4. `<meta name="description" content="">`を追加
5. ついでに`<meta name="robots" content="INDEX,FOLLOW">`と`<meta name="keywords" content="">`も追加

### Lesson02 カードを作る
1. Lesson02-1 「画像の用意」
    * assetsフォルダを作成してその中にimageフォルダをさらに作成。用意した画像を入れる

2. Lesson02-2 「枠を作る」
    * div.cardを作成  
    htmlを書く基本、divタグとクラス名を学習

3. Lesson02-3 「画像とコンテンツの枠を作る」
    * div.cardの中にdiv.card_imageとdiv.card_contentsを作成  
    emmetで書く方法、命名について学習

4. Lesson02-4 「画像を設定」
    * div.card_imageの中にimgタグで画像を設置  
    パス、画像のサイズ記入とaltタグを学習

5. Lesson02-5 「コンテンツを作る」
    * div.card_contentsの中身を作成  
    見出し、span、p、brのタグを学習

6. Lesson02-6 「Visual Studio Codeに拡張追加」
    * live serverを導入  
    VSCodeの拡張追加を学習

## Lesson03 CSSを書いてみる
1. headタグ内にstyleタグを作ってのその中でCSSを書いてみる
cssの書き方の基礎を学習

## Lesson04 リセットを読みこむ
1. assetsフォルダの中にcssフォルダを作成し、用意してあるリセット用のCSSをそこに入れる
2. リセット用のCSSをHTMLに読みこむ

外部CSSの読みこみ方、リセットCSSについて学習

## Lesson05 外部CSSファイルを作る
1. assetsフォルダ＞cssフォルダの中にstyle.cssを作成
2. `@charset "UTF-8";`を記載
3. style.cssをHTMLに読みこむ

独自のcssファイルの作成と文字コードについて学習


### Lesson06 カードを作りこむ
1. Lesson06-1 「Bodyに色を付ける」
    * bodyタグに対してバックグラウンドカラーを設定してカードを見やすくします  
    backgroundについて学習

2. Lesson06-2 「カードの大きさ」
    * .cardに、中身がはみ出たときに隠すようにして、大きさを設定。合わせて背景色も設定  
    overflow、width、heightｍについて学習

3. Lesson06-3 「カードのレイアウト」
    * .cardに`display: grid;`を設定してレイアウトを作る  
    display: gridを使用しながら、displayにとついて学習。flexboxにも軽く触れる


4. Lesson06-4 「画像の調整」
    * .card_imageをグリッドに合わせつつ、余白をつくり、画像の大きさも指定
    display: gridの子要素について、余白について、サイズ指定の最大値を学習

5. Lesson06-5 「コンテンツの調整」
    * .card_contentsをグリッドに合わせ余白調整
    * line-heightを1に
    * .orgに文字色とフォントサイズを指定
    * .memberに`display: block;`を指定して、上の余白とフォントサイズを指定
    * .nameのフォントサイズとウェイト、余白を指定
    * .msgのline-heightを設定し、余白を計算して指定

6. Lesson06-6 「カードの位置」
    * .cardに`margin: auto;`を指定、さらに`position: absolute;`を指定して、カードを中央に持ってくる

7. Lesson06-7 「カードに装飾」
    * .cardにドロップシャドウをつける

----