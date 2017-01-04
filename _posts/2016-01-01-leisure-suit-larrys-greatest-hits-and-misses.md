---
game:       leisure-suit-larrys-greatest-hits-and-misses
layout:     post
title:      Leisure Suit Larry's Greatest Hits and Misses
categories: pc boxed
extra_pics: 1
---

[![{{ page.game }}]({{ site.baseurl }}/images/{{ page.game }}--main.jpg)]({{ site.baseurl }}/images/{{ page.game }}--main.jpg)

{% assign pics = page.extra_pics %}
{% for counter in (1..page.extra_pics) %}
  <!-- the stuff to be done followed by an increase in the 'counter' variable -->
  [![{{ page.game }}]({{ site.baseurl }}/images/{{ page.game }}--{{ counter }}.jpg)]({{ site.baseurl }}/images/{{ page.game }}--{{ counter }}.jpg)
{% endfor %}
