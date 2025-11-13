---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: jason.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p> Columbia, New York </p>
    <p> <pre>ic2621@columbia.edu</pre> </p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hello! I am a PhD student in the IEOR department of [Columbia University](https://www.columbia.edu/), advised by [Eric Balkanski](https://ericbalkanski.com/). I am generally interested in the areas of combinatorial and stochastic optimization, with a focus on beyond-worst case analysis and online algorithms.

Before joining Columbia, I finished by undergraduate studies in the ECE department of the [National Technical University of Athens](https://www.ntua.gr/en/) where I was advised by [Dimitris Fotakis](http://www.softlab.ntua.gr/~fotakis/).

## Publications

{% bibliography --query @*[selected=true] %}