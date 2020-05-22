## IaaC's Master in Robotics and Advanced Construction

---

### Projects

{% for repository in site.github.public_repositories %}
[{{ repository.name }}]({{ repository.html_url }}) {% for topic in repository.topics %}  `{{ topic }}`  {% endfor %}
{% endfor %}
