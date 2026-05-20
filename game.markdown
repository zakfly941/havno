---
layout: default
title: The Game
permalink: /game/
---
<h2>All my blog posts with their excerpts</h2><hr style="margin-bottom:2em;">
    {%- for post in site.posts  -%}
    <p style="font-size:0.84em; opacity:0.68; margin:4em 0 2em 0;"><code>Excerpt:</code>&nbsp;&nbsp;<br/><br/>
    Title: {{ post.title }} <i style="opacity:0.48;">posted on</i> {{ post.date }} {{ page.excerpt_img_url }}
    {{ post.excerpt }} <a class="u-url" href="{{ post.url | relative_url }}">>> Read more...</a></p>
   
    {%- endfor- %}

