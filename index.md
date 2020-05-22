## IaaC's Master in Robotics and Advanced Construction

---

### Projects

[Project 1 Title](/sample_page)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 2 Title](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
