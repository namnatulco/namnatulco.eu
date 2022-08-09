---
layout: page
title: "Gruppenübersicht"
resource: true
categories: [info]
---

Im folgenden eine Liste aller Gruppen.

{% for item in site.gruppenlabels %}

## {{ item }}

{% for page in site.pages %}
{% if page.layout == "gruppe" and page.gruppenlabels contains item %}
### [{{page.gruppenname}}]({{page.url}})
{% endif %}
{% endfor %}
{% endfor %}
