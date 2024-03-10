# WhatsYourBrew
## サービス概要
今飲んだコーヒーの感想やコーヒーのレシピを記録、シェアできるサービス。

## このサービスへの思い・作りたい理由

スペシャルティコーヒーを楽しむ人が増え、業界が盛り上がる一助となりたいという想いから企画しました。「スペシャルティコーヒー」というのはまだまだ新しい価値観なので伝わりづらい事もたくさんあります。その入り口は実際に飲んで感じてもらうことでしかないと思うので、その部分は全国にある素晴らしいカフェにお任せし、もしスペシャルティコーヒーが気になった人がいれば、気軽にアクセスできる場所としてこのサービス存在となっているのが理想です。

## ユーザー層について

- 20~30代の男女　
スペシャルティーコーヒーという比較的新しい価値観を受け入れやすい世代
- 独身または結婚しているけど子供はいない
- 都会よりは地方に住んでいる
コーヒー屋さんの選択肢がたくさんある都会よりは、お店の選択肢が少なくインターネットで豆を購入するであろう地方に住んでいる層
- 毎日家でコーヒーを淹れている
- 休みの日はカフェ巡り
- コーヒー豆購入の決め手はインフルエンサーや発信力の強いお店のYoutube,X,Instagram

## サービスの利用イメージ

- 投稿することによって、飲んだコーヒーの記録ができます。「あのおいしかったコーヒーはどこの豆だったかな？」とふと思った時（友達におすすめする時や、時間が経って再購入したい時など）に見返すことができます。
- 他のユーザーの投稿から良さそうに思った豆の販売ページ（外部ページ）に飛び、コーヒーを購入できます。お店のコメントだけではなくて、実際に飲んだことがある人の口コミを参考にすることが可能。

## ユーザーの獲得について

- X、Instagramへ1ユーザーとして投稿する
- コーヒーの記録をSNS上にしている方へ直接宣伝

## サービスの差別化ポイント・推しポイント

次に購入したい豆がみつかり、その豆に関する情報（お店や他社のレビュー）がまとまっていること。他のサイトやアプリに飛んで情報を検索する必要がないので、豆を探し購入するまでがスムーズに行える。

## 機能候補

◎MVP時点

- 新規登録
- ログイン
- コーヒー豆の投稿
- いいね
- レコメンド機能
- 図形（フレーバーホイール）へのカラーマッピング
- マイページ

◎本リリース

- お店のページ（ユーザーが投稿、編集できる）
- レシピの記録
- コーヒー器具の登録
- SNS連携
- フォロー
- 投稿（飲んだコーヒー）のフレーバーの色に基づく流体オブジェクト

## 機能の実装方針予定

- コンテンツベースフィルタリング
- オートコンプリート　Stimulus Autocomplete（Rails7 ）
- Turbo
- Canvas Api