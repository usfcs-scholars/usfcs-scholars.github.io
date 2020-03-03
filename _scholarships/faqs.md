---
layout: default
key: 4

title: "FAQs"
icon: fas fa-question-circle
---

<article class="message is-link">
  <div class="message-body">
    <i class="fad fa-info-circle"></i>
    Questions? Join us for a live Q&A webinar on Mon March 30 or April 6th between 5:00pm and 7:00pm PT. <a href="https://usfca.zoom.us/webinar/register/WN_a2YXki29R864Mz9gZjm49w">Register now!</a>
  </div>
</article>

Please email <ces@cs.usfca.edu> if you have have a question that was not answered here.

{%- for item in site.data.faqs %}

{% include anchor.html h="h4" text=item.q %}

<p>
  {{ item.a }}
</p>

{% endfor -%}
