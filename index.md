---
layout: default
title: Anasayfa
---

# Intro

Elektrik-Elektronik mühendisi, araştırmayı sever, otomobillerle ilgilenir.
Burası benim kişisel not defterim. Yazı içeriklerinin doğruluk garantisi yoktur.

---

# YAZILAR

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url }})

**Yazan:** {{ site.author }}

{{ post.excerpt }}

---
{% endfor %}
