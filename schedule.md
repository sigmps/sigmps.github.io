---
layout: default
title: 研究会開催日程
ref: mps_schedule
permalink: /schedule
---

## これからの研究会

<!-- 
研究会の案内はコレクションとして _mps_docs に入れる．
で，そこで mpsXXX.md を編集すると下に反映されるハズ．
-->
研究会に参加するには参加登録が必要となります．
詳しくは，情報処理学会の 「[研究発表会に参加する](https://www.ipsj.or.jp/kenkyukai/sanka.html) 」ページを御覧ください．
年間を通して，複数回参加される方は，[研究会登録](/registration) することをお勧めいたします．

<ul>
{% for item in site.mps_docs %}
    <li><a href="{{item.url}}">{{item.sig_id}} のご案内</a>
        <ul>
            <li>場所: {{item.location}}</li>
            <li>日程: {{item.date_from | date: "%Y/%m/%d"}} ~ {{item.date_to | date: "%Y/%m/%d"}}</li>
        </ul>
    </li>
{% endfor %}
</ul>

## 過去の研究会

過去の研究会については，[こちら](/schedule-old)をご覧ください．
