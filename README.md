# データモデリング入門

## 課題1

オンラインレッスンサービスを設計するにあたって、以下の要件にもとづいてデータモデル設計をしたい。

- 講師はレッスンを登録することができる
- レッスンにはレッスン日時を設定することができる
- 生徒はレッスンを予約することができる
- レッスン後、講師は生徒にレッスンコメントを返すことができる
- 生徒はレッスン予約をキャンセルすることができる

## 課題2

ミニSNSサービスを設計するにあたって、以下の要件にもとづいてデータモデル設計をしたい。

- ユーザーは他のユーザーをフォローすることができる
- ユーザーはフォローしているユーザーの一覧を見ることができる
- ユーザーはフォローしてくれているユーザーの一覧を見ることができる

## 課題3

グローバル物販サービスを設計するにあたって、以下の要件にもとづいてデータモデル設計をしたい。

- A社は世界各国に部品を供給しているインダストリーである
- 国によって法律が異なるため、卸せる国と卸せない国とがある
- 法律に関わるリスクを最小限におさえるために適切なデータモデルを設計したい

## 課題4

ある施設内で利用する業務システムを設計するにあたって、以下の要件にもとづいてデータモデル設計をしたい。

- 患者の体温、脈拍、血圧（上下）を定期的に記録したい（記録は朝晩行うこともあるし、日次で行うこともある）
- 体温と脈拍だけ記録することもある
- 誰が計測したかは記録として残したい
- このとき各計測項目に対して、最新の値と計測者を取得できるようなモデル設計したい

## 課題5

レギュラー出演している芸能人を局内で管理するシステムを設計するにあたって、以下の要件にもとづいてデータモデル設計をしたい。

- ある番組でレギュラー出演している芸能人のデータを管理したい
- 芸能人の名前は期間によって変わる
- 芸能人の所属事務所も期間によって変わる
- 番組名も期間によって変わる
- 期間によって変わる番組名、芸能人自体は同じものとみなし、ある時点でレギュラー出演している芸能人を、そのときの名前、そのときの所属事務所で把握したい
