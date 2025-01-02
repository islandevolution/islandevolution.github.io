---
---

# Welcome to our Group's website



{% include section.html %}

## Highlights

{% capture text %}

Read more on our research - broadly what we do.

{%
  include button.html
  link="research"
  text="Read about our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/scalesia.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Read on our current projects and study systems.

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
  image="images/hawaii.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Learn more about us!

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
  image="images/galapagos.jpg"
  link="team"
  title="Our Team"
  text=text
%}
