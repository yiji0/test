# test
This is a test for the project.

# Contributor
{% for member in site.stu %}
  <h2>
    <a href="https://github.com/{{ member.user }}">
      {{ member.user }} - {{ member.name }}
    </a>
  </h2>
  ![image]({{ member.image }})
  <p>{{ member.content | markdownify }}</p>
{% endfor %}
