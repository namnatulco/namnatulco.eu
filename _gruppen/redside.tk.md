---
layout: gruppe
gruppenname: "redside.tk"
twitter: ""
instagram: ""
web: "https://redside.tk/"
gruppenlabels: [lnke, bündnis]
last-updated: 2022-09-03
shortname: "redside"
---

Die Seite [redside.tk](https://redside.tk) beinhaltet eine Reihe Organisationen:

{% for page in site.pages %}
{% if page.layout == "gruppe" and page.gruppenlabels contains "redsidetk" %}
 - [{{page.gruppenname}}]({{page.url}})
{% endif %}
{% endfor %}

sowie:
 - [AAB](https://www.redside.tk/antifaschistisches-aktionsbundnis/)
 - [GegangenengewerkschaftGG/bundesweite Organisation Soligruppe](https://www.redside.tk/ggbo-nbg/)
 - [Organisierte Autonomie](https://www.redside.tk/organisierte-autonomie/) & [revolutionär organisierte Jugendaktion (ROJA)](https://www.redside.tk/revolutionar-organisierte-jugendaktion/)
 - [Pension Ost](https://www.redside.tk/pension-ost/)
 - radikale Linke (Link geht nicht, vermutlich inaktiv)
