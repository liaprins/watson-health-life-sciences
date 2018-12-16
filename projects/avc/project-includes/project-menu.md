# [{{ page.title }}]()

- [Team members](#team)
{% for page in site.pages %}	
{% if page.url contains 'project-sections' and page.url contains 'REPLACE_WITH_YOUR_PROJECT_FOLDER_NAME_LOWERCASE' %}
- [{{ page.section }}](#{{ page.anchorlink }})
{% else %}
{% endif %}
{% endfor %}
