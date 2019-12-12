---
layout: "new"
title: "be thou titled"
date: "2019-12-12"
---
Some content

{% for file in site.static_files %}
{{ file.path }} <br>
{% endfor %}
