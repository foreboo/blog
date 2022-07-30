---
title: "【総距離10キロ!】海に行ったら帰りのバスを逃して徒歩で帰った話"
date: 2022-07-28T02:55:24+09:00
categories: [釣り]
draft: false
eyecatch: "posts/blog/hello/hello.jpg"
---

ノボログ
ホームプログラミング
【CSS】超簡単！スクロールしても背景画像が固定されたままにする方法【プログラミング】
プログラミング
Twitter
Facebook
はてブ
Pocket
LINE
コピー
 2021.06.11 2020.02.01
おはこんばんにちは！ノボルです。


ポートフォリオサイトを作ってるんだけど、背景画像をスクロールしても固定したままにする方法ってないの？

簡単な方法があるから解説するね！


そこで今回は、スクロールしても背景画像が固定されたままにするCSSテクニックについて解説します！


 
目次
デモサイト
スクロールしても背景画像が固定されたままにする方法
HTML
CSS
最後に
デモサイト
まずは、デモサイトをご覧ください。


出典：coils (https://coliss.com/articles/build-websites/operation/css/css-alternate-fixed-scroll-backgrounds-by-codyhouse.html)
ページをスクロールしても背景画像が固定されているのが分かると思います。

では、さっそく実装する方法を解説していきます！


スクロールしても背景画像が固定されたままにする方法
HTMLとCSSだけで実装できます。

HTML
HTMLのソースコードは以下の通りです。

 

 
「背景画像を固定するセクション」と「スクロールするセクション」を交互に配置するところがポイントです。

固定表示する要素には「.fixed-background」、スクロールする要素には「.scroll-background」というクラス名をつけました。もちろん、自分がわかりやすいように、クラス名を変えてもらっても構いません。


CSS
続いて、CSSを見ていきましょう。

 
 
.fixed-background {
  min-height: 100vh;
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
}
 
.background-1 {
  background-image: url(...);
}
 
.background-2 {
  background-image: url(...);
}
 
CSSでは、「background-attachment: fixed;」を設定することで、背景画像を固定することができます。

なので、上のソースコードでは、背景画像を固定するセクションに「background-attachment: fixed;」を指定しています。

以上です！


思ったより簡単なんだね！



最後に
今回の記事では、スクロールしても背景画像が固定されたままにするCSSテクニックについて解説しました。

背景画像を固定することで、よりデザイン性の高いWEB制作を行うことができます。

この記事読んでくださっているあなたも、WEBサイトを作られる際は、ぜひ「background-attachment: fixed;」を活用してみてください！

最後まで読んで頂き、ありがとうございました(o^^o)


【CSS】letter-spacingで文字間を調整する方法とオススメの値【プログラミング】
おはこんばんにちは！ノボルです。CSSで文字間を調整するのってどうやるんだろ・・・。「letter-spacing」プロパティを使えば、簡単に文字間を調整できるよ！ブログやwebサイトなど、文章の多い媒体において、...

onishi-noboru.com
2020.01.31


【CSS】超簡単！line-heightで行間を調整する方法【オススメの値も】
おはこんばんにちは！ノボルです。CSSで文章の行間を調整する方法ってあるの？「line-height」プロパティを使うことで、簡単に行間を調整できるよ！Webページのデザイン性や可読性は、文章の行間によって大きく変...

onishi-noboru.com
2020.01.27

【初心者向け】超簡単！CSSで円を作る方法と円のど真ん中に文字を配置する方法
おはこんばんにちは！ノボルです。CSSで円を作って真ん中に文字を表示したいんだけど、どうやってするんだろ・・・。そういうことなら任せて！さっそく解説するね。HTMLやCSSの勉強をしていて、円形のパーツってどうやっ...

onishi-noboru.com
2020.01.25
プログラミング CSSプログラミング背景画像
シェアする
Twitter
Facebook
はてブ
Pocket
LINE
コピー
ノボルをフォローする
 ノボル
関連記事
プログラミング
【画像加工不要】超簡単！CSSだけで背景画像のみを暗くする方法【プログラミング】
おはこんばんにちは！ノボルです。 背景画像を暗くしたいんだけど、加工するのがめんどくさい…。 画像加工ソフトを使わなくても、CSSだけでできるよ！ Web制作の際、上の文字などを読みやすくするために背景画像を暗く...

プログラミング
【HTML】見出しタグの使い方を解説｜h1〜h6の使い分けも【プログラミング】
おはこんばんにちは！ノボルです。 HTMLの『見出しタグ』ってどうやって使い分けるんだろう…。 確かにh1〜h6まであって混同するよね。使い方を解説するね！ そこで今回は、HTMLの見出しタグの使い方を解説します！Web...
プログラミング
【無料会員でOK】CodePenで画像を使う方法を分かりやすく解説【プログラミング】
おはこんばんにちは！ノボルです。 最近、CodePenをよく使うんだけど、画像を貼りつける方法ってないの？ もちろんあるよ！さっそく解説するね。 そこで今回は、CodePenの無料会員で画像を使う方法を分かりやすく解説し...
プログラミング
【Mac版】VSCodeで覚えておきたいショートカットまとめ【プログラミング】
おはこんばんにちは！ノボルです。 VSCode(Visual Studio Code)を使ってるんだけど、便利なショートカットとかってある？ そういうことなら任せて！さっそく紹介するね。 そこで今回は、VSCode(Vi...
プログラミング
【CSS】テキストを下線じゃなくてマーカー線(蛍光ペン風)でハイライトする方法
おはこんばんにちは！ノボルです。 下のテキストみたいに、CSSで文字にマーカー線を引きたいんだけど、やり方わかる？ サンプルテキスト CSSでテキストをハイライトするのは簡単だよ。さっそく説明するね！ テキストのハ...
プログラミング
【初心者向け】Web制作で最低限知っておきたい基礎用語25選【プログラミング】
おはこんばんにちは！ノボルです。 Web制作の勉強をしてるんだけど、知っておくべき用語ってある？ 最低限理解しておくべき用語を紹介するね！ Web制作の仕事をする上で、専門用語の理解は欠かせません。SEO、Googleア...

勉強や仕事がラクになる！集中力が続かない原因と今すぐ集中できる5つの方法

【テーマ別】WordPressのアイキャッチ画像とは？オススメのサイズはこれ！【ブログ】
コメント
コメントを書き込む
人気記事

【超簡単】Adobe illustratorで画像を綺麗に書き出す方法【イラストレーター】

【CSS】超簡単！スクロールしても背景画像が固定されたままにする方法【プログラミング】

【1分解説】イラストレーターで回転したアートボードを元に戻す方法【Adobe illustrator】

【悲報】2日連続でチートデイしたら4.5kg太った話【ダイエット】

【CSS】超簡単！テキストを「左揃え」のまま「中央寄せ」にする方法【プログラミング】
新着記事

【便利】iPhoneのデータを簡単転送！ iMobie社の『AnyTrans』を紹介【レビュー】

【超簡単】他のiPhone/iPadでダウンロードしたアプリを同期させない方法【Apple】

【図解】Adobe illustratorの各パーツの名称を解説してみた【イラストレーター】

【1分解説】MacのFinderのサイドバーが消えた時の対処法

【便利】画面録画ソフト 『画面キャプチャー』を使ってみた感想【4videosoft】
プロフィール

ノボル

高校卒業→フィリピン3ヶ月語学留学→マレーシア3年留学→進路選択で迷走中。

 

趣味は、漫画/アニメ/筋トレ/登山/ビジュアルノベルなど。

 

最近は、『魔法使いの夜』をプレイ中。ボイス無いの初めてだけど、むしろ内容に集中できる…!

 

TOEIC945/IELTS Overall 7.0/英検準1級/AOW(ダイビングライセンス)

 

サイト内を検索

アーカイブ
2022年7月2
2022年6月4
2022年5月14
2022年4月11
2022年3月9
2022年2月6
2022年1月4
2021年12月1
2021年11月1
2021年10月1
2021年9月2
2021年8月7
2021年7月7
2021年3月1
2021年2月5
2021年1月6
2020年12月4
2020年11月3
2020年10月20
2020年9月22
2020年8月3
2020年3月2
2020年2月15
2020年1月30
2019年12月43
2019年11月5
2019年10月2
目次
デモサイト
スクロールしても背景画像が固定されたままにする方法
HTML
CSS
最後に
ノボログ
HOME
お問い合わせ
プライバシーポリシー
Copyright © 2019-2022 ノボログ All Rights Reserved.
 HOME
 プログラミング
 ブログ
 PC小技
 読書
 英語
 ライフ
 お問い合わせ
ノボログ
サイト内を検索
