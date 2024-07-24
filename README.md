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
