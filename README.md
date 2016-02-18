# Introduction
# Authors


{% for author in book.authors %}
  - {{ author.name }}
{% endfor %}


My file is {{ file.path }}
Modified at {{ file.mtime }}



| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
