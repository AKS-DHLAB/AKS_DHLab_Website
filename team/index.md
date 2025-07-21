---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

한국학중앙연구원 디지털인문학연구소에서 함께하고 있는 구성원들을 소개합니다.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

우리는 각기 다른 학문적 배경을 지닌 연구자들로 구성된 팀입니다. 인문학, 정보기술 등 다양한 분야에서 출발했지만, 디지털 인문학이라는 새로운 지적 지평을 향한 공통된 열정을 바탕으로 협업하고 있습니다. 서로의 전문성을 존중하며, 함께 배우고 성장하는 열린 연구 공동체를 지향합니다.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/team/team1.jpg" %}
{% include figure.html image="images/team/team2.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
