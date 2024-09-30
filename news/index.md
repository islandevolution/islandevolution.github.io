---
title: News
nav:
  order: 4
  tooltip: What's up with us
header: images/hawaii.jpg
footer: images/hawaii.jpg
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

---

### Our latest news - conferences, grants, publications, new members, events, etc.

---

#### 2024
September - We are advertising a PhD position. [See here](https://www.jobbnorge.no/en/available-jobs/job/268466/phd-research-fellow-in-evolutionary-genomics-and-island-biology)<br>
June - José was awarded a Young Researcher Grant from the Norwegian Research Council (8,000,000 NOK) - we will be hiring soon!)<br>
Website created. More news to follow!

<!--- 
***Note to self*** - If I want to add imaegs and not keep just a list, I need to remove the {% comment %} {% endcomment %} sections. the arrow above and below, hide this comment.
-->

{% comment %}

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}

{% endcomment %}

