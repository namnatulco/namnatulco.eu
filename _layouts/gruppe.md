---
layout: grupp
---
 ## {{ post.gruppenname }}
 {{ post.gruppenname }} ist eine Gruppe, dessen Eintrag zuletzt am {{ post.last-updated }} aktualisiert wurde.

{% if page.gruppenlabels %}
Die Gruppe wurde folgenden labels zugeordnet:
	{% for grlabel in post.gruppenlabels %}
	{{ grlabel }} <!-- seiten generieren für die labels? -->
	{% endfor %}
{% endif %}
Die Gruppe findet ihr hier:

{% if page.twitter %}
[Twitter](https://twitter.com/{{page.twitter}})
{% endif %}

{% if page.instagram %}
[Instagram](https://instagram.com/{{page.instagram}})
{% endif %}

{% if page.web %}
[eigene Homepage](/{{page.web}})
{% endif %}

    {{ content }}
