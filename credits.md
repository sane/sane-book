# Credits

{% for author in book.authors %}
  - [{{ author.name }}](https://github.com/{{author.githubUserName}})
{% endfor %}
