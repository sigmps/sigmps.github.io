---
layout: default
title: お知らせ
---

## 運営委員会メンバー

運営委員会メンバーは こちらをご覧ください．

## ニュース

news コレクションの中身を展開
<ul>
{% for item in site.news %}
    <li>{{item.news_date| date: "%Y/%m/%d"}} <a href="{{item.url}}">{{item.news_title}}</a> </li>
{% endfor %}
</ul>
