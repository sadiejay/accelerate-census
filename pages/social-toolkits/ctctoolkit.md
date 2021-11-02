---
layout: sm-toolkit-layout
title: CTC Toolkit
permalink: /ctctoolkit/
og-url: https://accelerate.census.gov/ctctoolkit/
og-image: https://accelerate.census.gov/assets/img/smtk/redis/feature-redistricting-news-release-2.png

scripts:
  - highlightNavigation.js
#   -
#     src: https://public.tableau.com/javascripts/api/viz_v1.js
#     attrs:
#       - defer
#     isExternal: true

navbar:
  - text: How to Use
    href: "#how-to"
  - text: Sample Social Media Posts
    href: "#sample-posts"
  - text: Data Visualizations
    href: "#data-viz"
  - text: Links to Other Resources
    href: "#links"

hero:
  title: "CTC Toolkit: Assets"
  subtitle: "Assets supporting the CTC effort"
  text-on-left: true
  background-img:
    src: backgrounds/USCB_RedistrictingRelease_1500x500-wSpace.jpg
    alt: "A farm house, bungalow, and apartment building each in a teal bubble with text 'United States Census 2020'"

links:
  title: Helpful Links for Partners and Stakeholders
---

<!--
{% capture mainText %}
## How To Use This Toolkit
1.	Choose the type of asset you will use (graphic, animation, or video) and the social media channel you plan to post on.
2.	Click the download button to save the graphic, animation, or video to your device.
3.	Highlight and select the text you want to use for your social media post and copy the text to your clipboard.
4.	Go to the social media channel you plan to post on, paste the copied text, and add the downloaded graphic or animation to your post.
5.	If posting on Instagram, make sure to add the relevant link to your bio so your followers can learn more.
6.	Remember to tag @uscensusbureau in your posts, use the hashtag #2020Census, and link to [Census.gov](https://www.census.gov/).
{% endcapture %}

<section id="how-to" class="smtk-section grid-container margin-top-6">
  {{ mainText | markdownify }}
</section>

{% include sm-toolkit/redis-sample-posts.html %}


<div id="data-viz">
  {% include sm-toolkit/dataviz.html class="margin-top-6"%}
</div>

{% include sm-toolkit/links.html
  data = site.data.smtk.redistricting.links
  class="margin-y-6"
  id="links" %}-->

{% include sm-toolkit/ctc-sample-posts.html %}
