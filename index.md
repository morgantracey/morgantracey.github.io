---
layout: page
---

**Skeleton** is a minimal jekyll theme that is focused on content. You can use it as is (see [kyletress.com](http://www.kyletress.com)) or you can customize it to fit your needs. It is a constant work in progress.

Built by [Kyle Tress](http://www.kyletress.com). 

<h2>Recent</h2>
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} &mdash; </span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
