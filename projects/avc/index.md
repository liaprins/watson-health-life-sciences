---
title: IBM Access and Value Connect
shortname: AVC
team_members: Justin Wetz, Steph Daher
---

<header markdown="1">

{% include_relative project-includes/project-menu.md %}

</header>

<section markdown="1">

{% include_relative project-includes/project-what-is.md %}

{% include_relative project-includes/project-team-members.md %}	

{% for page in site.pages %}	
{% if page.url contains 'project-sections' and page.url contains 'REPLACE_WITH_YOUR_PROJECT_FOLDER_NAME_LOWERCASE' %}
  {{ page.content | markdownify }}
{% else %}
{% endif %}
{% endfor %}

</section>
