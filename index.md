---
layout: default
---

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<div class="subscribe">
  <p>new posts by email</p>
  <form
    action="https://buttondown.com/api/emails/embed-subscribe/{{ site.buttondown_username }}"
    method="post"
    target="popupwindow"
    onsubmit="window.open('https://buttondown.com/{{ site.buttondown_username }}', 'popupwindow')">
    <input type="email" name="email" placeholder="your@email.com" required>
    <button type="submit">subscribe</button>
  </form>
</div>
