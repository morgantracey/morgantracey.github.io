---
title: Home
layout: page
---

Hi I'm **Morgan**. I'm an Olympic hopeful, attorney, wildland firefighter, and AmeriCorps alumni from Champion, Ohio.

I'm the youngest of 5 children (and the only girl). Whether good or bad, my older brothers made me into the woman I am today -- tough and tenacious.

Recently, I was invited to the White House by President Obama and honored as a [Champion of Change](https://www.whitehouse.gov/champions) for commitment to national service. Now, I'm part of the United States National Skeleton Program, with my sights on the 2018 Winter Olympic Games in Pyeongchang, South Korea.

Here [what I'm doing now](/now).

<h2>Recent</h2>
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} &mdash; </span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
