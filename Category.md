---
layout: page
title: Categories
permalink: /Category/
---
{% assign test=100 %}

test용! test의 값은 {{test}}
[naver](https://www.naver.com "커서를 올리면 나온다.")

카테고
{%- for category in site.categories.title -%}
  {{category}}
{%- end for -%}
