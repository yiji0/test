# test
This is a test for the project.

# Contributor
{% for member in site.stu %}
  <h2>
    <a href="{{ member.url }}">
      {{ member.user }} - {{ member.name }}
    </a>
  </h2>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}
