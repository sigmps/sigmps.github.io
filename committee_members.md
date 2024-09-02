---
title: MPS 運営委員会/TOM編集委員会メンバー
layout: page
permalink: /committee_members
tagline: IPSJ SIG MPS/TOM committee members
---

## MPS 運営委員会/TOM編集委員会メンバー

### MPS 運営委員会メンバー

<ul>
{% for member in site.data.mps_members %}
  <li>
    {{member.role}}: &nbsp; {{ member.name }} ({{ member.affiliation }})
  </li>
{% endfor %}
</ul>

### TOM 編集委員会メンバー

<ul>
{% for member in site.data.tom_members %}
  <li>
    {{ member.role }}: &nbsp; {{ member.name }} ({{ member.affiliation }})
  </li>
{% endfor %}
</ul>
