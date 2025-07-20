---
---

# AKS-DHLAB's Website

**Center for Digital Humanities @ the Academy of Korean Studies**

**디지털 인문학**이란?
- 현대 인문학이 전문화의 함정에 빠져서 점점 더 잃어가고 있는 교육과 연구의 생기를 새로운 소통과 협업, 융합의 환경(디지털 환경)에서 부활시키려는 노력입니다.

**디지털 인문학**의 교육적 과제
- 횡단적, 융합적 지식탐구를 위해서는, 전통적인 인문학 공부의 도구였던 말과 글의 구사 능력에 더하여, 체계적인 데이터의 수집과 정리, 검증을 통해 의미있는 지식 정보를 만들어내고, 그것을 새로운 디지털 콘텐츠로 표현할 수 있는 능력-‘디지털 리터러시(Digital Literacy)’의 훈련이 필요합니다.

**디지털 인문학 연구소**는
- 미래의 한국 문화를 이끌어 갈 인문학도들에게 디지털 리터러시의 역량을 강화하는 교육 환경을 제공하며, 이 토대 위에서 소통·협업·융합의 방법으로 심층적인 지식 탐구와 지식의 확산을 추구하는 디지털 기반 인문학 연구 프로젝트를 수행합니다.

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects/mokpo-thumb.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

한국학중앙연구원 디지털인문학연구소에서는 저마다의 관심에 바탕한 다양한 프로젝트를 수행하였습니다.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
