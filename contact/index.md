---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Do you have a question about our lab that you couldn’t find on our website? You’re welcome to write us. You can contact us by phone or through the mail.


{%
  include button.html
  type="email"
  text="adina@floridapoly.edu"
  link="adina@floridapoly.edu"
%}
{%
  include button.html
  type="phone"
  text="(863) 583-9050"
  link="+1-863-583-90509"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/EgcY1VexyLJaV7a6A"
%}


{% include section.html dark=true %}

{% capture col1 %}
[Department of Computer Science](https://floridapoly.edu/academics/undergraduate/computer-science.php)
{% endcapture %}

{% capture col2 %}
[BS in Computer Science Program](https://catalog.floridapoly.edu/preview_program.php?catoid=37&poid=1688)
{% endcapture %}

{% capture col3 %}
[Academic Calender](https://floridapoly.edu/academics/academic-calendar/)
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
