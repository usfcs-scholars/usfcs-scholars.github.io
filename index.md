---
layout: default
navbar: Home

title: Welcome
icon: fas fa-home
---

<p>Welcome to the <strong><span class="has-text-primary">Community Engaged Scholars</span> <span class="has-text-usf-gold">in</span> <span class="has-text-primary">Computer Science</span></strong> scholarship program at the University of San Francisco. This is program combines scholarships with additional community-building activities such as mentoring, social events, and coursework.</p>

<h2>Latest Announcements</h2>

{% for post in site.posts limit:3 %}

<h4 class="title">{{ post.title }}</h4>
<h6 class="subtitle has-text-grey has-text-weight-normal">
  Posted {{ post.date | date: "%A %b %d, %Y" }}
  <a href="{{ post.url }}"><i class="far fa-link"></i></a>
</h6>

{% if post.content contains site.excerpt_separator %}
{{ post.excerpt }}

<p class="has-text-grey is-italic"><a href="{{ post.url }}">Click to read more...</a></p>
{% else %}
{{ post.content  }}
{% endif %}

{% unless forloop.last %}<hr/>{% endunless %}

{% endfor %}

<a href="/posts/" class="button is-link">See More &raquo;</a>
