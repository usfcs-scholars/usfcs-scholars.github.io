---
layout: default
navbar: About

title: About
icon: fas fa-info-circle
---

The <strong><span class="has-text-primary">Community Engaged Scholars</span> <span class="has-text-usf-gold">in</span> <span class="has-text-primary">Computer Science</span></strong> scholarship program at the [University of San Francisco](https://www.usfca.edu/) combines four-year scholarships for low-income students majoring in [Computer Science](https://www.usfca.edu/catalog/undergraduate/arts-sciences/computer-science/major) with additional with a [suite of activities](scholarships/included.html) designed to promote the engagement in the departmental, professional, and local communities. These activities include an immersive [head start](curriculum/start.html) program, cohort enrollment in lower division CS major courses, and alumni mentoring. Scholars also participate in specialized coursework designed to support their academic and professional success, including a [first-year course](curriculum/cs101.html) introducing students to campus and community resources, a junior [career preparation](curriculum/cs301.html) course, and a CS focused [service learning](curriculum/service.html) course.

{% include anchor.html h="h2" text="Team" %}

Below you can find our core team. We also work with many other amazing staff and faculty throughout the university to make this program possible, as well as our awesome alumni that sign up as mentors!

{%- assign groups = site.data.team.team -%}
{%- for group in groups %}

{% include anchor.html h="h3" text=group.role %}

{% assign people = group.people | sort: 'last' %}
{%- for person in people %}
<div class="media">
  <div class="media-left">
    <p class="image is-128x128">
      {%- if person.image %}
      <img src="{{ person.image }}" class="is-rounded">
      {%- else -%}
      <img src="{{ "/images/user.png" | relative_url }}" class="is-rounded">
      {% endif -%}
    </p>
  </div>
  <div class="media-content">
    <div class="level is-marginless">
      <div class="level-left">
        <div class="level-item has-text-weight-bold is-size-5">
          {{ person.first }} {{ person.last }}
        </div>
      </div>
    </div>

    <div class="has-text-weight-light has-text-usf-gray">
      {{ person.title | join: " &bullet; " }}
    </div>

    <div class="">
    {%- for item in person.links %}
      <a href="{{ item.link }}">
        <i class="{{ item.icon }}"></i>&nbsp;{{ item.text }}
      </a>
      {%- unless forloop.last -%}
      &bullet;
      {%- endunless -%}
    {% endfor -%}
    </div>
  </div>
</div>
{% endfor -%}
{% endfor -%}

{% include anchor.html h="h2" text="Papers" %}

See below for the papers, posters, and reports published as part of this project.

<ul>

{%- assign papers = site.data.papers -%}
{%- for paper in papers %}

<li><p>
  {{ paper.authors }}, "<a class="has-text-weight-bold" href="{{ paper.link }}">{{ paper.title }}</a>"{% if paper.info %} <span class="has-text-grey">({{ paper.info }})</span>{% endif %}, in <em>{{ paper.venue }}</em> on {{ paper.date | date: "%B %Y"}}.
</p></li>

{%- endfor %}

</ul>

{% include anchor.html h="h2" text="Funding" %}

This project is supported by the [National Science Foundation](https://www.nsf.gov/) under Grant No. [1833718](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1833718). It is part of the [NSF Scholarships in Science, Technology, Engineering, and Mathematics (S-STEM) Program](https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=5257). The program addresses the need for "a high quality STEM workforce in STEM disciplines" and the "increased success of low-income academically talented students with demonstrated financial need."

Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.

{% include anchor.html h="h2" text="Contact" %}

Please email <ces@cs.usfca.edu> if you have questions or comments regarding this program.
