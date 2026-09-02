# KURU77 — 作ったWebアプリ一覧

作ってきたWebアプリのリンクと概要をまとめたポートフォリオです。

**→ https://kuru77.github.io/**

依存ライブラリなし・ビルド不要の HTML 1ファイルです。`index.html` を編集して push すれば、そのまま反映されます。

## 掲載しているアプリ

### おもなアプリ

| アプリ | 概要 | リンク |
| --- | --- | --- |
| 🎓 資格・検定トラッカー | 取りたい資格をリスト化し、目標スコアと受験記録を管理。約1,400件のプリセットから検索して自動入力 | [開く](https://kuru77.github.io/cert-tracker/) |
| 📺 視聴リスト | アニメ・映画・地上波を4つのリストで管理。AniList・Wikidata から作品情報を取り込み | [開く](https://kuru77.github.io/watchlist/) |
| 🧮 所得シミュレーター | 令和元年〜令和8年それぞれの税制で課税額と「あといくら稼げるか」を試算 | [開く](https://kuru77.github.io/income-tax-simulator-jp/) |
| 📚 マイ本棚 | バーコードをカメラで読むだけの蔵書管理。置き場所・ジャンル分類、読書進捗 | [開く](https://kuru77.github.io/bookshelf_app/) |
| ⏱️ 今！やることリスト | 空き時間と気分から「今やるとよさそうなこと」を提案するタスク管理 | [開く](https://kuru77.github.io/now-todo/) |
| 🍚 自炊ごはん記録 | 自炊を写真で記録して栄養バランスをチェック。在庫の賞味期限管理と献立提案つき | [開く](https://kuru77.github.io/meal-log-app/) |
| 🗺️ 行きたい観光地リスト | 観光地・世界遺産を営業時間と地図つきでリスト化。プリセット405件＋OpenStreetMapから自動入力、地図のオフライン保存つき | [開く](https://kuru77.github.io/travel-wishlist/) |
| 📉 体重トレンド | 体重を2タップで記録。水分のブレをならしたトレンド線で増減を読む。体重計アプリのCSV取り込みつき | [開く](https://kuru77.github.io/weight-trend/) |
| 📈 日本株ポートフォリオ | 保有株の取得単価・株数から株価・配当・優待をまとめて確認。口座別（NISA対応）と買い増しシミュレーションつき | [開く](https://kuru77.github.io/jp-stock-portfolio/) |
| 🎒 教育資金贈与マネージャー | 教育資金の一括贈与の原資と使い道を記録。残りの非課税枠と、30歳満期時の贈与税・手元に残る額を計算 | [開く](https://kuru77.github.io/education-fund-gift-jp/) |
| 📄 積読シェルフ | 読む予定の論文を優先度つきの棚に。arXiv/DOI/BibTeX から取り込み、積んでからの日数を表示 | [開く](https://kuru77.github.io/paper-shelf/) |
| 🩺 からだ記録 | からだの異変を日付×部位で記録。人体図から部位を選び、つらさの分布を可視化 | [開く](https://kuru77.github.io/karada-log/) |
| 📖 株用語ノート | JPX用語集の全605語に対応した株式投資の学習アプリ。用語ごとにメモを残し、暗記カードとクイズで定着を確認 | [開く](https://kuru77.github.io/kabu-yougo-note/) |
| 🍶 のみログ | 飲んだ日も飲まなかった日も記録。純アルコール量と休肝日が積み上がり、抜ける時間の目安も表示 | [開く](https://kuru77.github.io/nomi-log/) |

### そのほか

| アプリ | 概要 | リンク |
| --- | --- | --- |
| 📝 QuizGen | 論文・書籍からクイズを自動生成するPWA | [開く](https://kuru77.github.io/Quizzes-based-on-book-thesis/) |
| 💰 予算管理（円・ドル） | 日本円と米ドルの両方で予算・支出を管理 | [開く](https://kuru77.github.io/Neo-Household-Expenses-For-traveling-to-U.S.A/) |
| 🧺 食材管理アプリ | 賞味期限をジャンル別に管理（現在は「自炊ごはん記録」に統合） | [開く](https://kuru77.github.io/foodnoloss/) |
| 📋 日次タスク管理 | 繰り返しタスクの完了率をカレンダーで可視化 | [開く](https://kuru77.github.io/Neo-To-Do-LIST/) |

> Craftvalley ホームページは、いったんポートフォリオへの掲載を見送っています。

## アプリを追加するには

`index.html` の `<section id="apps">` 内にある `<article class="card">` を1つコピーして、
アイコン・タイトル・リポジトリ名・説明・タグ・リンクを書き換えてください。
見出し横の `<span class="count">` の件数も忘れずに更新します。

そのほかの作品として1行で足す場合は、`<ul class="list">` に `<li>` を追加します。

## ライセンス

MIT License
