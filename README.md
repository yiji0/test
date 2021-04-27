# test
This is a test for the project.

# Contributor
{% for member in site.stu %}
  <p>{{ member.user }} - {{ member.name }}</p>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}
