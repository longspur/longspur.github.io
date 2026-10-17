---
title: News
layout: base.njk
---
### News
<div style="text-align:center"><b><a href="/">← Return to Homepage</a></b></div>

---

 <ul>
{% for update in news["recent"] %}
        <li style="margin-top:-10px;"><b>{{ update.date }}</b>: {{ update.desc }}</li>
{% endfor %}
{% for update in news["older"] %}
        <li style="margin-top:-10px;"><b>{{ update.date }}</b>: {{ update.desc }}</li>
{% endfor %}
</ul>
