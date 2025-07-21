---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

한국학중앙연구원 디지털인문학연구소에서 함께하고 있는 구성원들을 소개합니다.

{% include section.html %}

## Principal Investigators
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

## Members
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

언제든 연락 주세요!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
