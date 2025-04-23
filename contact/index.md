---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our laboratory is based in the [Bio21 Molecular Science & Biotechnology Institute](https://www.bio21.unimelb.edu.au) affiliated with the [School of Chemistry](https://chemistry.unimelb.edu.au) at [the University of Melbourne](https://www.unimelb.edu.au)

{%
  include button.html
  type="email"
  text="ludovica.monti@unimelb.edu.au"
  link="ludovica.monti@unimelb.edu.au"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/tmYAaPcnNkJCtULH7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1  %}

{% include section.html dark=true %}

{% capture col1 %}
### Mailing address 
David Penington Building<br/>
30 Flemington Road<br/>
Parkville, VIC 3052<br/>
Australia
{% endcapture %}


{% include cols.html col1=col1 %}
