# PaintBBS NEO
お絵描きしぃ掲示板 PaintBBS (&copy;2000-2004しぃちゃん) をhtml5化するプロジェクトです。  

作者行方不明のため、許諾は取れていません。

しぃちゃんのホームページ（Vector）  
http://hp.vector.co.jp/authors/VA016309/

**Flashやhtml5のお絵描きサイトはいっぱいあるんだけど、そうじゃないんだ。  
おじさんは昔のjavaアプレットそっくりの環境が欲しいんだ。**


1. 掲示板に投稿できるMac/Win用のアプリを開発します(中身はjavascript)

2. PaintBBSと見た目や操作性がだいたい同じになってきたら、  
管理人さんに連絡取って直接組み込んでもらうことを目指します

**……というわけで、ふたばでNEOが使えるようになりました！**

    105 名前：◆管理人 投稿日：2017/01/19(木) 02:20 del
    落書き板に組み込みました
    http://nov.2chan.net/q/futaba.htm
    調子が良ければ他のお絵かき板にも導入します

----

## 対応ブラウザ
Chrome/FireFox/Safari/<s>Edge/IE</s>（最近のバージョンのみ）  
- **WindowsのEdgeとIEでは投稿できない不具合があるようです**
- 一応モバイルブラウザでも動くみたいですが、サポート対象外にまります

## Mac/Win用アプリの実行方法
このアプリを使えば、javaを使わずに掲示板に投稿できます

1. neo-darwin-x64.zip(Mac)または  
neo-win32-ia32.zip(Win)をダウンロードして、どこかに展開する  

2. 実行ファイル (neo.app または neo.exe) をダブルクリック

## サンプル掲示板
管理者がNEOを掲示板に組み込めば、アプリを使わずにブラウザから直接NEOを利用することができるようになります

サンプルとして[**NEOテスト**](http://neo.websozai.jp)をオープンしました  
動作確認にご利用ください

掲示板へのNEOの組み込み方法については、 [/samplebbs](https://github.com/funige/neo/tree/master/samplebbs) の下のREADME.mdに書きました  
不明な点があればサンプル掲示板で聞いてください

## 履歴

#### ver1.0 (2016/12/22)
- バグ修正

  だいたい終了です  
  加算逆加算は結局できませんでした  
  そのうち誰かが直してくれると期待して撤退……

![ver1.0](http://cdn-ak.f.st-hatena.com/images/fotolife/f/funige/20161221/20161221215643.png?1482325021)  

#### ver0.9 (2016/12/18)
- <s>Edge対応</s>
- <s>IE対応</s>
- バグ修正

#### ver0.8 (2016/12/13)
- ベジェ曲線
- 角取り・ぼかし
- 加算・逆加算テスト
- リロードした時にキャンバスが保存されるように修正
- Chromeでドラッグ中のカーソルがおかしくなる問題を修正

  残り時間でバグをできるだけ取ります  

#### ver0.7 (2016/12/5)
- 覆い焼き・焼き込み
- テキスト入力テスト
- サンプル掲示板設置

#### ver0.6 (2016/11/22)
- 水彩と鉛筆はどうやっても似ないのでひとまずこれで
- トーン
- 直線
- 傾け
- 四角とか楕円とか

  しんどい

#### ver0.5 (2016/11/3)
- スクロールバーをちゃんと表示するように修正
- キーボードショートカットを一部実装
- コピーツールのテスト  
- 保管ペンのテスト
![ver0.5](http://cdn-ak.f.st-hatena.com/images/fotolife/f/funige/20161103/20161103013321.png?1478104440)  
だいぶ飽きてきましたが  
年末までには何とかver1.0にしたいと思います

#### ver0.4.5 (2016/10/23)
- ブラウザ化テスト
- 画像の解像度を選んで描きはじめられるようになりました

  お絵かき本体はあんまり進んでないです
- 消し四角・レイヤー結合・上下反転・左右反転
- マウスポインタが指の形になっていたのを修正
- 消しペンにもマスクがかかるように修正

#### ver0.4 (2016/10/11)
- ウィンドウビュー
- マスク・逆マスク
- ボタンとかスライダとか実装

- カーソルをちゃんとxorで表示するように修正

#### ver0.3 (2016/10/4)
- 鉛筆・消しペン・塗り潰し
- 透明度
- 拡大した画像をスクロールできなかったのを修正
- マスクのテスト
- 外部のブラウザに飛ばずに送信画面を自分で開いてみるテスト  
 ![ver0.1](http://cdn-ak.f.st-hatena.com/images/fotolife/f/funige/20161004/20161004190655.png?1475575647)

#### ver0.2 (2016/9/28)
いろいろ中途半端なのでこのバージョンは見送ったほうがいいです

#### ver0.1 (2016/9/21)
とりあえず画像を既存の掲示板に送信するところだけ作って検証  
 ![ver0.1](http://cdn-ak.f.st-hatena.com/images/fotolife/f/funige/20160922/20160922095441.png?1474505726)

----
**質問・要望等は直接こちらへ**  
https://github.com/funige/neo/issues  

- しぃペインターとかPooとかは作りません  
- アニメーションの記録・再生には対応しません  
