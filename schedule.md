---
layout: default
---
# 研究会のスケジュール

研究会の案内はコレクションとして _mps_docs に入れる．
で，そこで mpsXXX.md を編集すると下に反映されるハズ．

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
