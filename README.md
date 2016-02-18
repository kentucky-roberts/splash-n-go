# Introduction
# Authors


{% for author in book.authors %}
  - {{ author.name }}
{% endfor %}


My file is {{ file.path }}
Modified at {{ file.mtime }}




![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
