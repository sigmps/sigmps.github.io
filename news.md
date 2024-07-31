---
layout: default
title: お知らせ
permalink: /news
---
## MPS研究会運営委員会/TOM誌編集委員会メンバー

MPS研究会運営委員会ならびにTOM編集委員会のメンバーは下記をご覧ください．

- [MPS研究会運営委員会メンバー](/committee_members#mps-運営委員会メンバー)
- [TOM編集委員会メンバー](/committee_members#tom-編集委員会メンバー)

## MPS/TOM 編集委員会へのアクセス

MPS研究会ならびにTOM編集委員会へのアクセスは下記をご参照ください．

- [MPS研究会運営への連絡](/contact#mps-研究会関連への連絡先)
- [TOM編集委員会への連絡](/contact#tom-編集委員会関連への連絡先)

## MPS 研究会ベストプレゼンテーション賞

MPS 研究会ベストプレゼンテーション賞は，[こちら](https://www.ipsj.or.jp/award/mps-award1.html) を御覧ください．

## ニュース
<!-- news コレクションの中身を展開 -->

<ul>
{% for item in site.news %}
    <li>{{item.news_date| date: "%Y/%m/%d"}} <a href="{{item.url}}">{{item.news_title}}</a> </li>
{% endfor %}
</ul>
