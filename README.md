# CASIOPEA(カシオペア)

### バージョン
[![Ruby](https://img.shields.io/badge/Ruby-2.6.3-red.svg)](https://docs.ruby-lang.org/ja/2.6.0/doc/index.html)
[![Ruby on Rails](https://img.shields.io/badge/Ruby%20on%20Rails-5.2.3-blue.svg)](https://guides.rubyonrails.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-9.5.19-yellow.svg)](https://www.postgresql.org/)

### 概要
- 心に響いた言葉を蓄積、管理、振り返り、他者との共有を支援するアプリケーション。<br><br>

私たちは日々を過ごす中で、多くの機会で多くの言葉と触れ合っています。<br>
時にはその言葉に心動かされて毎日の生活を改めようと考え、気が付くと一つの言葉が人生の方向性を決定づけることもあります。<br>
多様性が広く認められている昨今、自らの生きる道を自ら決めることがますます重要になるでしょう。<br>
<br>

しかしながら、人間の記憶は思った以上に脆弱で消えやすく、言葉もまた、うつろいやすいものです。<br>
特に情報過多で多忙な現代社会を過ごしていると、一つ一つの言葉を忘れ、やがて自らの決心が鈍ってしまうこともあります。<br>
せっかく出会った素晴らしい言葉や、人生の方向を見失ってしまうのはとても惜しい。<br>
<br>

CASIOPEAは、そのような問題に対する一つの解答提示です。<br>

<br>
あなたが日々の生活の中で出会った、『心に響いた言葉』をCASIOPEA上に投稿しましょう。<br>
投稿された言葉は、CASIOPEAによって定期的に自動通知されます。<br>
心に響いた言葉を振り返ることで、あなたは言葉と出会った時の考えを、忘れかけていた感情を思い出すことが出来るのです。<br>
<br>

日々の生活に忙殺されて人生の意義を失いそうになった時、CASIOPEAから届いた言葉を振り返ってみましょう。<br>
CASIOPEAは、あなたが進みたいと思っていた人生の方向を、再確認させてくれる一助になる筈です。<br>

### コンセプト
- May the Word be with you (言葉と共にあらんことを)<br>
言葉をもっと身近に感じよう。<br>
言葉から得られた力で、より良い生活を過ごそう。<br>
- 地球から0光年に位置するカシオペヤ座<br>
方角を探すための目印である北極星。カシオペヤ座は北極星を探す目印となる星座です。<br>
あなたの定めた人生の方角を、CASIOPEAを使って探し出せるようにしよう。<br>
<br>

### 機能
- ユーザー管理機能
  - [x] ユーザー登録、編集、削除
  - [x] ユーザーログイン、ログアウト
  - [x] パスワード再設定
  - [x] パスワード再設定メール自動送信
- 言葉の投稿機能
  - [x] 言葉の投稿、編集、削除
  - [x] 投稿した言葉の検索
  - [x] 一覧表示された言葉の並び替え
  - [x] ページネーション機能
- 通知機能
  - [x] 投稿した言葉の定期的なメール通知
### その他
  - [x] Rspecの実装(テスト)
    - モデルスペック、システムスペック

### カタログ設計

### テーブル定義

### 画面遷移図

### 画面ワイヤーフレーム

#### 使用予定Gem
* active link to
* acts-as-taggable-on
* bcrypt
* better_errors
* binding_of_caller
* bootstrap
* brakeman
* bullet
* carrierwave
* coderay
* database_cleaner
* devise
* dotenv-rails
* factory_bot_rails
* faker
* font-awesome-sass
* high_voltage
* kaminari
* launchy
* letter_opener_web
* mini_magick
* ransack
* rspec-rails
* rubocop
* spring-commands-rspec
* whenever
