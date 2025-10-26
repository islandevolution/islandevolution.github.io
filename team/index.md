---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a diverse group of people interested in understanding island biology, diversification dynamics and genome evolution. Click on group member profiles to learn more about us!

If you would like to join us, feel free to contact the group coordinator. Contact information can be found under the Contact section.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|alumni$)" %}

{% include section.html background="images/hawaii.jpg" dark=true %}

## Alumni

We're proud of our former group members and their contributions to science.

{% include list.html data="members" component="portrait" filters="role: alumni" %}

{% include section.html background="images/hawaii.jpg" dark=true %}

{% include section.html %}

{% capture content %}

{% endcapture %}

<!--- 
***Note to self*** - If I want to add images I need to remove the {% comment %} {% endcomment %} sections. the arrow above and below, hide this comment.
-->

{% comment %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcomment %}

{% include grid.html style="square" content=content %}
