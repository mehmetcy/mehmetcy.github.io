---
layout: default
title: Anasayfa
---

# Merhaba!

Ben Mehmet Can. Gömülü sistemler, IoT, otomotiv ve yazılım üzerine çalışıyorum. Burası benim kişisel not defterim.
Araştırırken öğrendiklerimi yazıya dökmeye gayret gösteriyorum.

---

### Blog Yazıları

{% for post in site.posts %}
- **{{ post.date | date: "%d.%m.%Y" }}** — [{{ post.title }}]({{ post.url }})
{% endfor %}
