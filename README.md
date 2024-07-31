# MPS 研究会 Web ページのドラフト

## 作り方

```sh
git clone git@github.com:sigmps/sigmps.github.io.dev.git
cd sigmps.github.io.dev.git
bundle install
bundle exec jekyll serve
```

## 修正方法

トップページは下記で構成している（暫定版）

- `committee_members.md`: MPS運営委員会，TOM編集委員会 のメンバー表示
- `contact.md`: 研究会への連絡先
- `news.md`: 新しいお知らせ
- `index.md`: トップページ
- `registration.md`: 研究会への登録方法
- `schedule-old.md`: 過去のMPS研究会の開催履歴
- `schedule.md`: MPS研究会のこれからの予定
- `tom.md`: TOM編集委員会から

データを追加するには， `_config.yml` のコレクションを追加して，
サーバーを立ち上げ直すことで対応可能．コレクションは現状下記で構成中

- `_layouts` 表示ファイルの基本レイアウト
- `_includes` ウェブサイト固有設定
- `_data` MPSメンバーとか，ナビゲーション情報，適応分野表などを突っ込んでいる
- `_mps_docs` これからの CFP 情報などを突っ込んでいる
- `_mps_docs_old` 過去の CFP 情報など
- `_tom_docs` TOM誌の情報源などをを突っ込む

## 更新のしかた

このリポジトリ
[https://github.com/sigmps/sigmps.github.io.dev]
は本サイトを更新する前のコンテンツ検証用です。

内容更新等はWebサイトと直接紐づく本番リポジトリ
[https://github.com/sigmps/sigmps.github.io]
を直接編集するのではなく、この検証用リポジトリ上で行ってください。  
(間違った内容や、更新途中の情報がWebサイトに掲載されてしまうことを防ぐためです。)

このリポジトリのproductionブランチに変更をpushすると、その更新内容が
GitHub ActionのWorkflowによって、本番リポジトリのmasterに反映され、Webサイトが自動で更新されます。

緊急の場合を除き、productionブランチの変更はPull requestによって、
Web担当者やそれに準ずるメンバのチェックを受けてから反映してください。


