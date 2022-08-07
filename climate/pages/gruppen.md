---
layout: page
title: "Gruppenübersicht"
resource: true
categories: [info]
---

{% for page in site.pages %}
{% if page.layout == gruppe %}
### [{{page.gruppenname}}]({{page.url}})

{% endif %}
{% endif %}
{% endfor %}
