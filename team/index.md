---
title: 汉化组成员
nav:
  order: 3
  tooltip: About our team
header: images/header-background.jpg
footer: images/header-background.jpg
---

# {% include icon.html icon="fa-solid fa-users" %}汉化汉化组成员组组员

偶像大师SP汉化组目前成员信息介绍

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include grid.html style="square" content=content %}
