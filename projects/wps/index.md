---
title: Watson for Patient Safety
shortname: WPS
team_members: Lia Prins, Jodi Cutler, Justin Wetz, Ramiro Galan, Greg King, Raven Veal
---

<header markdown="1">

{% include_relative project-includes/project-menu.md %}

</header>

<section markdown="1">

{% include_relative project-includes/project-what-is.md %}

{% include_relative project-includes/project-team-members.md %}	

{% for page in site.pages %}	
{% if page.url contains 'project-sections' and page.url contains 'wps' %}
  {{ page.content | markdownify }}
{% else %}
{% endif %}
{% endfor %}

</section>
