---
permalink: /postes/
---

{% for post in site.categories.post %}
<div>
    {{post.excerpt}}
    </div>
{% endfor %}