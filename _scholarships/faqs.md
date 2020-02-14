---
layout: default
key: 4

title: "FAQs"
icon: fas fa-question-circle
---

Please email <ces@cs.usfca.edu> if you have have a question that was not answered here.

{%- for item in site.data.faqs %}

{% include anchor.html h="h4" text=item.q %}

<p>
  {{ item.a }}
</p>

{% endfor -%}
