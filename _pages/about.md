---
permalink: /
title: "Yang Lin"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year DPhil (PhD) student at School of Computer Science, University of Sydney (USYD) and CSIRO Data61, under the supervision of Professor [Irena Koprinska](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/irena-koprinska.html), and Dr [Mashud Rana](https://people.csiro.au/r/m/mdmashud-rana). I received my B.Eng. degree in 2018 at the School of Electrical Engineering, University of Sydney, supervised by Professor [Weidong Xiao](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/weidong-xiao.html). I am fortunate to work a Research Assistant  in 2017 with Professor [Georgios Konstantinou](https://research.unsw.edu.au/people/dr-georgios-konstantinou), Dr [Harith R. Wickramasinghe](https://www.unsw.edu.au/engineering/our-people/harith-wickramasinghe) at University of New South Wales. 
My current focus is on time series forecasting and deep learning.

Publications
======
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
