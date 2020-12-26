---
layout: default
permalink: /post/:title
---

{{ page.date | date: "%-d %B %Y" }}

<div style="text-align:left; margin-bottom: -18px;">
    <h1 style="display: inline-block;">{{ page.title }}</h1>
    <span style="float:right; position: relative; bottom: -35px;">
        by {{ page.author }}
    </span>
</div>
<hr style="backgtound: red;">

<div style="padding-top: 15px;">
{{content}}
</div>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}

<script src="https://utteranc.es/client.js"
  repo="lsaa/crimson-skies"
  issue-term="pathname"
  theme="photon-dark"
  crossorigin="anonymous"
  async>
</script>
