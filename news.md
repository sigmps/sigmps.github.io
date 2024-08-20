---
layout: page
title: お知らせ
tagline: IPSJ SIGMPS news
ref: news
permalink: /news
---
## MPS 研究会ベストプレゼンテーション賞

MPS 研究会ベストプレゼンテーション賞は，[こちら](https://www.ipsj.or.jp/award/mps-award1.html) を御覧ください．

## ニュース

<!-- news コレクションの中身を展開 -->

<ul>
{% for item in site.news %}
    <li>{{item.news_date| date: "%Y/%m/%d"}} <a href="{{item.url}}">{{item.news_title}}</a> </li>
{% endfor %}
</ul>
