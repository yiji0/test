# test
This is a test for the project.

# Contributor
{% for member in site.stu %}
  <h2>{{ member.user }} - {{ member.name }}</h2>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}
