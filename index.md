---
layout: default
---

<img src="/images/headshot.jpg" alt="J. Britt Davis. I'm a PhD student at Arizona State University. I research economic interaction among the ancient Maya of the Belize Valley."/>

I'm a PhD student at Arizona State University. I research economic interaction among the ancient Maya of the Belize Valley.

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

