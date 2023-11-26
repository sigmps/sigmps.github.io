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

- `about.md`
- `news.md`
- `registration.md`
- `schedule.md`
- `schedule-old.md`
- `tom.md`

データを追加するには， `_config.yml` のコレクションを追加して，
サーバーを立ち上げ直すことで対応可能．コレクションは現状下記で構成中

- `_layouts` 表示ファイルの基本レイアウト
- `_includes` ウェブサイト固有設定
- `_data` MPSメンバーとか，ナビゲーション情報，適応分野表などを突っ込んでいる
- `_mps_docs` これからの CFP 情報などを突っ込んでいる
- `_mps_docs_old` 過去の CFP 情報など
- `_tom_docs` TOM誌の情報源などをを突っ込む予定
