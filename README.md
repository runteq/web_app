# サービス名：DANSYARI(仮)

## サービス概要
　DANSYARI(仮)は引越しや衣替え、大掃除の時、捨てるか迷う品物の写真、思い出を投稿することで、残すか、捨てるかの判断基準を提供するサービスです。


## 想定されるユーザー層
断捨離が進まず困っている人,家族


## サービスコンセプト
### ユーザー抱えている課題を提供するサービスでどのように解決するのか
　このアプリは断捨離の際、品物を捨てようか、残しておこうか困っているユーザーに対して、その品物の写真と思い出を投稿してもらうことで、「思い出がないので捨てる」、「思い出があるが、古いから捨てる」、「思い出があるから捨てない！」などの選択肢を提供することで断捨離を進めやすくするサービスです。
### なぜこのサービスを作ろうと思ったか
　私自身、思い出の服を捨てようか迷った時がありました。その思い出のある服は古く捨てるべきだとは思っていましたが、思い出があるためどうしても捨てられませんでした。そこで現物はなくてもすぐ見て思い出せるようにと写真を撮り、捨てることにしました。数日経った頃、写真を見て、「あ、この服は、、、。」と思い出し、現物がなくても思い出は忘れないことがわかり、あの時写真を撮って捨てるという選択は正しかったなと思いました。そういった経験から写真を撮って思い出として保存できれば、断捨離がもっと進むと思い、このサービスを考えました。
### どこが売りになるか、差別化ポイントになるか
　既存のサービスは捨てたものを投稿したり、日記で思い出を綴ったり、写真のみ保存できるサービスなどであるのに対して、本サービスは写真と思い出エピソードと共に捨てた理由、残した理由を記載してもらうことで、他のユーザーが断捨離の時の判断の参考になるところが差別化できるポイントだと考えています。また、例えば家族間でフォローすることで思い出の品物を通して思い出を共有できるところが押しポイントです。
### どのようなサービスにしていきたいか
　思い出の品物の保存場所として、また、思い出の品物をどうするかの一つの選択肢を提供し、思い出の品物を共有するサービスにしていきたいです。


## 実装を予定している機能
### MVP
- 未登録ユーザー
* 会員登録(sorcery)
* 品物の写真一覧
* 品物詳細
* マルチ検索(JQuery)
* タグ
* 品物を捨てた理由、品物を残した理由の閲覧

- 登録しているユーザー
* ログイン(google API)
* ログアウト
* 品物(写真、思い出)投稿
  * 品物の公開・非公開
* 画像加工(MiniMagick)
* いいね機能
* コメント
* フォロー機能
* チャット(Action Cable)
* マイページ
  * フォルダで整理、管理


### その後の機能
* パスワードリセット(sorceryのモジュールを利用)
* 管理者画面
  * 全てのユーザーのCRUD
  * 全ての品物のCRUD