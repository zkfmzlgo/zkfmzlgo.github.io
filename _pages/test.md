---
title: "test"
layout: archive
permalink: /test
---
하나씩 테스트 해보기
{% assign posts = site.categories.test %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
