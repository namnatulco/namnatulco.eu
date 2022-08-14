---
layout: gruppe
gruppenname: "Nürnberg For Future"
twitter: ""
instagram: ""
web: "https://nuernbergforfuture.de/"
gruppenlabels: [klima, bündnis]
last-updated: 2022-08-08
---

Ein Bündnis Nürnberger Klimagruppen. Dazu gehören unter anderem:

{% for page in site.pages %}
{% if page.layout == "gruppe" and page.gruppenlabels contains "NFF" %}
 - [{{page.gruppenname}}]({{page.url}})
{% endif %}
{% endfor %}
