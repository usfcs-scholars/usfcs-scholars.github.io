---
layout: default
key: 3

title: "How to Apply"
icon: fas fa-edit

---

<!--<article class="message is-danger">
  <div class="message-body">
    <i class="fad fa-calendar-exclamation"></i>
    <strong>Scholarship applications are now closed.</strong> It may still be possible to participate in the programming associated with this program. Check the latest announcements for details.
  </div>
</article>
-->

<article class="message is-danger">
  <div class="message-body">
    <i class="fad fa-calendar-exclamation"></i>
    The priority application deadline for Spring 2022 is <strong>{{ site.data.dates.application_deadline.date | date: "%A %B %d, %Y"}}</strong>. Applications received after that date will be considered for the waiting list. See below for details.
  </div>
</article>

<!--
<article class="message is-link">
  <div class="message-body">
    <i class="fad fa-info-circle"></i>
    Questions? Join us for a live Q&A webinar on Mon March 30 or April 6th between 5:00pm and 7:00pm PT. <a href="https://usfca.zoom.us/webinar/register/WN_a2YXki29R864Mz9gZjm49w">Register now!</a>
  </div>
</article>
-->

Potentially eligible applicants are first invited via email to submit an application to the {% include ces.html %} program. The committee then selects the top candidates and invites them to the scholarship program. If any candidate declines, the committee invites individuals from the waitlist until enough scholars are identified.

{% include anchor.html h="h2" text="Eligibility" %}

Applicants must meet the following eligibility criteria to receive this scholarship:

  1. You must be admitted to USF as a full-time degree-seeking student majoring in Computer Science.

  2. You must be citizens of the United States, OR nationals of the United States (as defined in section 101(a) of the Immigration and Nationality Act), OR aliens admitted as refugees under section 207 of the Immigration and Nationality Act, OR aliens lawfully admitted to the United States for permanent residence (You only need to meet ONE of these requirements.)

  3. Incoming first-year students must have either a high school GPA of 3.0 or higher, OR a SAT score of 1250 or higher, OR an ACT score of 28 or higher. (You only need to meet ONE of these requirements.) Continuing students must have a Computer Science major GPA of 3.0 or higher. Students in their first semester who have not yet completed a computer science class are eligible to apply.

  4. You must be Pell Grant eligible or have a total family income of $50,000 or below on your FAFSA.

Applications can be submitted even if the last item (4) is unknown. We will determine whether your application meets those requirement before awarding the scholarships.

For additional eligibility details, such as the requirements for continued funding, see the [Eligibility](/scholarships/eligibility.html) guide.

{% include anchor.html h="h2" text="Application" %}

Potentially eligible applicants are contacted via email and asked to fill out a form with the following questions:

  - Applicants will be asked to consent to the selection committee accessing their declared major, citizenship status, GPA, SAT, ACT, FAFSA, and financial aid information from their USF applications to verify eligibility.

  - Applicants will be asked to upload a 1 to 3 page resume in PDF format.

The application also includes the essay questions about the applicant's choice of major, challenges encountered on the path to or in college, responsibilities outside of school, and potential impact of the scholarship. The responses should be approximately 2-3 paragraphs; there is a 2000 character maximum per essay responses:

<!--
  - Applicants will be asked to discuss any **challenges they have encountered on their path to college**, including challenges encountered at home, work, or school.

  - Applicants will be asked to discuss any **responsibilities they have outside of school**, including familial obligations, work obligations, and extra curricular activities.

  - Applicants will be asked to discuss **why they decided to major in computer science**.

  - Applicants will be asked to discuss the **single most important factor that will determine which university they choose** to attend, including class sizes, location, cost, diversity, available majors, and others.
-->

<strong class="has-text-danger">Applications are due {{ site.data.dates.application_deadline.date | date: "%A %b %d, %Y" }}.</strong> The form is also available below:

[<i class="fas fa-edit"></i> Apply Now](https://forms.gle/t6M7pBN5ePgdnEuh8)
{: .button .is-primary .is-large .inherit }

{% comment %}
{% include anchor.html h="h2" text="Interviews" %}

The selection committee will review all of the applications submitted by the deadline and invite semi-finalists to a 15 minute video interview with one or more of the committee members.

Video interviews will be scheduled to start on {{ site.data.dates.video_interviews.date | date: "%A %b %d, %Y" }}.

Interviews will be conducted online via the free <a href="https://zoom.us/">Zoom</a> video conference software. Please <a href="https://zoom.us/download">download</a> this software or install the mobile app prior to the scheduled interview time.
{% endcomment %}

{% include anchor.html h="h2" text="Notification" %}

The selection committee will notify students who have been selected for the scholarship before the tuition payment deadline. Notifications will be sent to the email address entered in the application form. Scholars must **promptly** respond to the scholarship offer via email to accept the scholarship.

If any of the finalists decline, the scholarship will be offered to someone on the waitlist instead.


{% comment %}
{% include anchor.html h="h2" text="Finalists" %}

The selection committee will offer the {% include ces.html %} scholarship to the top 6 applicants on {{ site.data.dates.finalist_notification.date | date: "%A %b %d, %Y" }}. Notifications will be sent to the email address entered in the application form. To accept the scholarship, these finalists:

  - Must respond to the scholarship offer via email to accept the scholarship.

  - Must formally accept admission to USF and submit a deposit by the deposit deadline of {{ site.data.dates.deposit_deadline.date | date: "%A %b %d, %Y" }}.

  - Must formally apply for on-campus housing by {{ site.data.dates.deposit_deadline.date | date: "%A %b %d, %Y" }}.

If any of the finalists decline, the scholarship will be offered to someone on the waitlist instead.

<article class="message is-warning">
  <div class="message-body">
    <i class="fad fa-exclamation-triangle"></i>
    Be prepared for a quick turnaround between notification and the accept deadline. There will be just over 10 days to decide!
  </div>
</article>
{% endcomment %}


{% comment %}
{% include anchor.html h="h2" text="Waiting List" %}

The selection committee will invite a select number of semi-finalists to join a waiting list for the {% include ces.html %} program. If space opens up, the scholarship will be offered to someone on the waiting list instead. Please note this might be *after* the deposit deadline, so only applicants that decided to attend USF and deposited will be eligible to accept at that point.

If you are on the waiting list, be prepared for a quick turnaround! There may be only 1 week after notification to accept. Applicants must accept the scholarship and apply for on-campus housing by the guaranteed housing deadline of {{ site.data.dates.housing_deadline.date | date: "%A %b %d, %Y" }}.

{% endcomment %}

{% comment %}
{% include anchor.html h="h2" text="Important Dates" %}

Here are various dates relevant to the application process:

<table class="table is-hover">
<thead>
  <tr>
    <th></th>
    <th class="has-text-centered">Date</th>
    <th>Description</th>
    <th>Calendar</th>
  </tr>
</thead>

<tbody>
  {%- assign dates = site.data.dates.all | sort: "date" -%}
  {%- for item in dates %}
  <tr>
    <td>{% if item.icon %}<i class="{{ item.icon }} {{ item.type }}"></i>{% endif %}</td>
    <th class="has-text-right" nowrap>{{ item.date | date: "%b %d, %Y" }}</th>
    <td>{{ item.text }}</td>
    <td nowrap><a href="{{ item.link }}">{{ item.info }}</a></td>
  </tr>
  {%- endfor %}
</tbody>
</table>

<div class="has-text-centered is-size-7">
  <a href="https://www.usfca.edu/admission/undergraduate/dates-and-deadlines">Admissions Calendar</a>
  &bullet;
  <a href="https://myusf.usfca.edu/housing/important-dates">Housing Calendar</a>
  &bullet;
  <a href="https://myusf.usfca.edu/registration/registration-calendar">Registration Calendar</a>
  &bullet;
  <a href="https://myusf.usfca.edu/registration/academic-calendar">Academic Calendar</a>
</div>
{% endcomment %}
