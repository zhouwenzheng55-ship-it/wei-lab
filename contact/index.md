---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}联系方式

欢迎来信交流与合作（占位信息，请替换为真实联系方式）。

{% include section.html %}

{%
  include button.html
  type="email"
  text="wei.lab@jiangnan.edu.cn"
  link="wei.lab@jiangnan.edu.cn"
%}
{%
  include button.html
  type="address"
  tooltip="江南大学机械工程学院（占位地址）"
  link="https://www.google.com/maps/search/江南大学机械工程学院"
%}

{% include section.html %}

{% capture col1 %}

{% include figure.html image="images/photo.jpg" caption="江南大学（占位）" %}

{% endcapture %}

{% capture col2 %}

江苏省无锡市滨湖区蠡湖大道 1800 号  
江南大学机械工程学院  
（占位地址，请核实）

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
