# service_name

■ サービス概要

ワインに興味はあるが、ワインの種類が分からずワインを楽しめない人に
「推し」のイメージを診断しそのイメージに近いワインを紹介することで
ワインに触れるきっかけになるサービス

■ ユーザーが抱える課題

ワインをなんとなくで飲んでいたりどんなワインがあるのか分からない
ワインは他のお酒より難しいイメージがあり手が出せない
周りに詳しい人もおらず詳しく聞くことが出来ない

■ 課題に対する仮説

- ワインを知る機会が少ない
  1. 何かのきっかけがないとワインを自分から調べようと思わない
  2. 調べてみたが品種が多く違いが分かりにくい

■ 解決方法

- とっつきにくいイメージのあるワインとその人の「推し」を掛け合わせ、ワインを身近なものにする
  - 「推し」のイメージを診断し、そのイメージに近いワインを紹介する
  - ワインチャートを用い品種ごとの違いを分かりやすく伝える
  - 味わいや品種といった情報からワイン選びのアドバイスをする

■ メインのターゲットユーザー

20〜30 代前半の女性、推し活をしている、ワインに興味がある
ワインに興味はあるが具体的な違いが分からない
飲み会などではワインを頼むが、自分でボトルを買って飲むほどではない

■ 実装予定の機能(MVP)

- ゲストユーザー
  - 診断
    - 診断結果の Twitter シェア
- ログインユーザー - 診断 - 診断結果の Twitter シェア
  - 診断結果登録
  - 投稿、コメント機能
  - ワイン豆知識の閲覧
- 管理ユーザー
  - 診断の一覧、作成、詳細、編集
  - ワイン豆知識の一覧、作成、編集、削除
    - ログインユーザーの一覧、詳細、作成、編集、削除
  - 管理ユーザーの一覧、詳細、作成、編集、削除

■ 実装予定の機能(本番リリース)

- ログインユーザー - ワイン検索 - 推し検索 - ワインチャートの閲覧 - ワインアドバイスの閲覧
- 管理ユーザー - 診断結果と似ているワインのレコメンド
  - 診断結果に Amazon のリンクを添付
    - ワインチャートの一覧、作成、詳細、編集
    - ワインアドバイスの一覧、作成、詳細、編集

■ なぜこのサービスを作りたいのか

今現在ワインを飲む人が増えており、飲食店に勤めていた時は若い方からの注文も多かった。その際ワインの特徴を伝え飲んで頂いた後に、ワインの感想を聞くと「今までよく分からなかったけど、教えてもらって良かった。美味しかった。」と言われることが多く、やはり多少の知識があった方が美味しく飲めるお酒なんだなと実感した。
この体験から気軽にワインを学べて、店で飲む・購入するきっかけになるサービスを作りたいと思い、多くの人の身近に存在する「推し」に着目し、推しイメージワインとしてワインを紹介出来るサービスを考えた。

■ スケジュール

企画〜技術調査：5/17 〆切
README〜ER 図作成：5/24 〆切
メイン機能実装：6/15 - 7/16
β 版を RUNTEQ 内リリース（MVP）：7/16 〆切
本番リリース：7 月下旬

■ 技術選定

- Rails7
- postgresql
- JavaScript
- Bootstrap
- heroku
- スクレイピング（ワインデータ）

■ 画面遷移図
https://www.figma.com/file/Y7WVMUuSJFesHjLFJgbqt1/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?type=design&node-id=0%3A1&t=RrAITQgxvpHxREqj-1

■ ER 図
https://drive.google.com/file/d/1lT6RuaZaLMpydylBcTNh16Ai-lQ8D4sx/view?usp=sharing
