420-4C1-DW - Incident Management

EZ07

This is the list of all of the Course' materials into GitHub :

<ul>
{% for file in site.static_files %}
{% comment %} Check for both PDF and HTML files {% endcomment %}
{% if file.extname == ".pdf" or file.extname == ".html" %}
<li><a href="{{ file.path | relative_url }}">{{ file.basename }}</a></li>
{% endif %}
{% endfor %}
</ul>
