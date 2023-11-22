---
layout: default
---

# 過去の研究会に関して

こちらは過去の研究会です．
研究会の案内（過去版）もコレクションとして保存する _mps_docs_old に移動させることで対応

<ul>
{% for item in site.mps_docs_old %}
    <li><a href="{{item.url}}">{{item.sig_id}} のご案内</a>
        <ul>
            <li>場所: {{item.location}}</li>
            <li>日程: {{item.date_from | date: "%Y/%m/%d"}} ~ {{item.date_to | date: "%Y/%m/%d"}}</li>
        </ul>
    </li>
{% endfor %}
</ul>

なお，今後の研究会については [こちら](/schedule) を御覧ください．
