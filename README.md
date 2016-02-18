# Introduction
# Authors


{% for author in book.authors %}
  - {{ author.name }}
{% endfor %}


My file is {{ file.path }}
Modified at {{ file.mtime }}
