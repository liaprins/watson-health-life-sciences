## Life Sciences offerings {#offerings}
{% for page in site.pages %}	
{% if page.title == 'Life Sciences' %}
{% elsif page.url contains 'project-includes' or page.url contains 'project-sections' or page.url contains 'how-to' or page.url contains 'assets' %}
{% else %}
- [{{ page.title }}]({{ site.baseurl }}{{ page.url }}){:target="_blank"}
{% endif %}
{% endfor %}
