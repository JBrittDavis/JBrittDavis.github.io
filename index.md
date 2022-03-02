---
layout: default
---

<img src="/images/headshot.jpg" alt="J. Britt Davis. I'm an anthropological archaeologist who is currently a PhD student at Arizona State University. My current research concerns economic interaction among the Preclassic Maya of the Belize Valley."/>

I'm an anthropological archaeologist who is currently a PhD student at Arizona State University. My current research concerns economic interaction among the Preclassic Maya of the Belize Valley.

<hr>

{% for post in site.posts %}

<article class="post">

<h1>

<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>

</h1>

::: entry
    {{ post.excerpt }}
:::

<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>

</article>

{% endfor %}

