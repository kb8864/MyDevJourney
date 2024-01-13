# [サービス名]

よさこいネットワーク

## サービス概要

卒業や、上京によって在籍してたよさこいチームを離れた人が新天地で次に在籍するチームを開拓するサービスです。
本サービスはユーザーが特定の条件で検索して、自身の希望に合ったよさこいチームを見つけ出すことができます。

###　想定されるユーザー層
・大学生（社会人）チームを引退して、次のチームが決まっていない学生（社会人）
・メンバー募集をかけているが、知名度がなく中々募集が集まらないチーム
・チーム内で旗を振りたい、踊りに特殊な動きを入れたいがチームが多すぎてどこのチームが当てはまるかわからない人向け
・引越し先でもよさこいをやりたいが、実際に現地に足を運ばないといけなく、腰が重たくなっている人
・新しい趣味を求めている社会人や学生

## サービスコンセプト

作ろうと思った背景・きっかけについて

日本全国各地域で大学生チームや社会人チーム、または混合チームが存在するよさこい。
これらで毎年課題に上がっているのが 2 点あり、1 点目が卒業や上京により所属チームを離れ、好みのよさこいチームを探すのが大変であること
2 点目がチーム側は人が集まらない、または認知がされていないなどの課題があります。

前者の課題の要因は、
・一言によさこいと言っても様々な流派があり自分の好みに合うよさこいチームを探すのが大変。
・特定のポジションを募集しているチームが見つからない。
・気になったチームが入会年にどんなお祭りやダンスイベントに参加するのか入会後じゃないと分からない。
・SNS や動画を確認しても限られた文字数や、実際に踊っている動画しか世の中に出ていないため実際のチームの雰囲気が分からず、結局現地まで行くしか確かめる手段がないなどの多くの要因があります。

後者の課題の要因は、
・よさこいチームの募集は基本的に SNS（X や、インスタグラム、会場）で募集がかけられています。
・そこではどうしても SNS のフォロワー数が多いチームや、受賞歴が輝かしいチームに目が行きがちで多くのよさこいチームでは募集をかけても SNS の波にのまれてしまい、結果チームが発見されず人が集まらない状況となっております。
・また、よさこいチームは様々なポジションによって構成されています。踊り子以外に、作詞作曲する人、踊り子の前後で大きな旗を振る人、演舞の際に掛け声などで盛り上げる人などの
これらの特殊なポジションを募集していますが上記の要因でその情報自体が届いておりません。

これらの状態を改善し、一覧化できるようなサービスが欲しいと思い考案いたしました。

### 実装を予定している機能

## MVP

1 会員登録
2 ログイン
3 チーム紹介ページを編集できる管理者権限機能
4 チーム検索機能
4.1 都道府県検索機能
4.2 タグ検索機能（チーム内の特徴、特殊ポジション、演舞の雰囲気、メンバーの年代など）
5 検索一覧表示機能
6 チーム詳細機能（この中に各種 SNS の TL 表示や、チームの公式 URL へ遷移、チームが出演するイベント告知、特殊ポジション募集などを入れる予定）
7 お気に入りチーム登録機能
8 チーム登録機能

## その後の機能

高度な機能
ステップ入力機能

以下の機能は MVP 後に作りたいと考えている機能です。

1 検索条件上位表示機能
2 カメラマンやお客さんが好きなチームと交流できる機能
2.1 写真投稿機能
2.2 チャット機能
2.3 カメラマンやお客さんからアップロードされた画像を自動的にサイズを統一させる機能

→ 2 の機能を作りたいと思った背景
よさこいには一般の人に演舞中の写真を撮っていただき、それを SNS に流して該当チームがエゴサする文化があります。
現状写真をせっかく撮ってくださり SNS にアップしても SNS の波に飲まれ、チームや、チーム内の踊り子に行き届かない状態が頻発しています。
この問題を解消するためにこのサービスを利用してカメラマンが撮った写真が、正しくチームに行き渡りそのチームからも反応をもらえるような交流の場として使えるような機能を実装したいです。

3 本サービスに登録してくれたチームのみを表示するイベントカレンダー機能
（チーム同士の説明会ブッキング防止や、どのチームがいつ演舞を行うのかチーム側も確認ができるようにする目的）

4 参加するお祭りやイベント名でチーム検索ができる機能

# 画面遷移図の URL

https://www.figma.com/file/K042OjKcFV26TZi1zj0KHT/%E7%84%A1%E9%A1%8C?type=design&node-id=0%3A1&mode=design&t=GTTIWedHPYVVdDSM-1
