---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

한국학중앙연구원 디지털인문학연구소에 관심이 있다면 편히 연락 바랍니다.

{%
  include button.html
  type="email"
  text="ddokbaro@gmail.com"
  link="ddokbaro@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(031) 728-9884"
  link="+82-31-728-9884"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/BGkJRNNy876uoWPm7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="사진"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="사진"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
문구1
{% endcapture %}

{% capture col2 %}
문구2
{% endcapture %}

{% capture col3 %}
문구3
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
