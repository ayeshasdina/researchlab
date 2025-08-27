---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are continually seeking dedicated and hard-working students, as well as post-doctoral researchers, who possess 
strong technical skills, a genuine enthusiasm for intellectual growth, and a willingness to collaborate on complex and meaningful problems within a team-oriented environment. If this resonates with your interests and aspirations, we encourage you to explore the opportunities listed on our openings page..

{% include section.html %}
Current Members
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="group != 'alum'" %}

Alumni
{% include list.html data="members" component="portrait" filter="group == 'alum'" %}
{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
