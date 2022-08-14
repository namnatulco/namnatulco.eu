---
layout: page
title: "Gruppenübersicht"
resource: true
categories: [info]
---

Im folgenden eine Liste aller Gruppen (diese Liste wird automatisch generiert, Fehler gerne persönlich oder [via github melden](https://github.com/namnatulco/namnatulco.eu/issues/new)).

{% for item in site.gruppenlabels %}

## {{ item }}

{% for page in site.gruppen %}
{% if page.layout == "gruppe" and page.gruppenlabels contains item %}
### [{{page.gruppenname}}]({{page.url}})
{% endif %}
{% endfor %}
{% endfor %}
