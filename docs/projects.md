# Projects

I've created a few open source projects. ✨

<!-- ## FastAPI GitHub -->
<!--  -->
<!-- Projects in the [FastAPI GitHub organization](https://github.com/fastapi){target=_blank}. -->
<!--  -->
<!-- {% for project in projects["fastapi"] %} -->
<!--  -->
<!-- * <small>⭐️ {{ project.stargazers_count }}</small> [{{ project.name }}]({{ project.html_url }}){target=_blank} {{ "- " + project.description if project.description }} -->
<!--  -->
<!-- {% endfor %} -->

## philippe's GitHub

Projects in my [personal GitHub profile: philippesamuel](https://github.com/philippesamuel){target=_blank}.

{% for project in projects["philippesamuel"] %}

* <small>⭐️ {{ project.stargazers_count }}</small> [{{ project.name }}]({{ project.html_url }}){target=_blank} {{ "- " + project.description if project.description }}

{% endfor %}
