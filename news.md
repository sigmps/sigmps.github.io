---
layout: default
title: お知らせ
permalink: /news
---
## お知らせ

### MPS研究会運営委員会メンバー

MPS研究会運営委員会メンバーは [こちら](/committee_members#mps-運営委員会メンバー)をご覧ください．

### MPS 研究会ベストプレゼンテーション賞

MPS 研究会ベストプレゼンテーション賞は，[こちら](https://www.ipsj.or.jp/award/mps-award1.html) を御覧ください．

### ニュース

news コレクションの中身を展開
<ul>
{% for item in site.news %}
    <li>{{item.news_date| date: "%Y/%m/%d"}} <a href="{{item.url}}">{{item.news_title}}</a> </li>
{% endfor %}
</ul>