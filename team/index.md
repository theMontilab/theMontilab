---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are committed to fostering a diverse, equitable, and inclusive environment that supports research training and empowers scientists at all career stages to thrive and contribute their unique perspectives.

If you are interested in joining our team, please [get in touch](https://themontilab.github.io/theMontilab/contact/) with a CV and cover letter explaining your interests in our research so as to initiate a conversation regarding potential opportunities.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include grid.html style="square" content=content %}
