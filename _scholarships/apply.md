---
layout: default
key: 2

title: "How to Apply"
icon: fas fa-edit

---

There is a multi phase application process. Eligible applicants are first invited to submit an application. The selection committee identifies semi-finalists based on these applications to video interview. The committee will then select the top 6 candidates and invite them to the scholarship program. If any candidate declines, the committee will invite individuals from the waitlist until 6 scholars are identified.

{% include anchor.html h="h2" text="Eligibility" %}

Applicants must meet the following eligibility criteria to receive this scholarship:

  1. Must be admitted as a full-time degree-seeking student in the CS major for Fall 2019.

  2. Must be a U.S. citizen or permanent resident.

  3. Must be classified as low-income according to their FAFSA.

  4. Must have either a high school GPA of 3.0 or higher, a SAT score of 1250 or higher, or an ACT score of 28 or higher (only one of these must be met).

To continue receiving funding, scholars must meet the following criteria at the end of every semester:

  1. Must remain a full-time student in the CS major.

  2. Must have both a major GPA and overall GPA of 3.0 or higher.

  3. Must continue to qualify as low-incoming according to their FAFSA.

  4. Must participate in all required program activities.

Scholars that fails to meet the criteria for a semester will be placed on probation. Scholars that fail to meet the criteria for two semesters in a row will not be eligible to renew the scholarship.

{% include anchor.html h="h2" text="Application" %}

Eligible applicants will be contacted via email after being admitted to USF, and asked to fill out a form with the following questions:

  - Applicants will be asked to confirm they meet the eligibility criteria.

  - Applicants will be asked to discuss any challenges they have encountered on their path to college in 2000 characters or less. This may include challenges encountered at home, work, or school.

  - Applicants will be asked to discuss any responsibilities they have outside of school in 2000 characters or less. Responsibilities might include familial obligations, work obligations, and extra curricular activities.

  - Applicants will be asked to upload a 1 to 3 page resume in PDF format.

  - Applicants will be asked to consent to releasing their GPA, SAT, and/or ACT scores from their USF applications to the {% include ces.html %} selection committee.

<strong class="has-text-danger">Applications are due {{ site.data.dates.application_deadline.date | date: "%A %b %d, %Y" }}.</strong> The link to the application form is emailed directly to eligible applicants after being admitted to the university.

{% include anchor.html h="h2" text="Interviews" %}

The selection committee will review all of the applications submitted by the deadline and invite semi-finalists to a 15 minute video interview with one or more of the committee members.

Video interviews will be scheduled to start on {{ site.data.dates.video_interviews.date | date: "%A %b %d, %Y" }}.

Interviews will be conducted online via the free <a href="https://zoom.us/">Zoom</a> video conference software. Please <a href="https://zoom.us/download">download</a> this software or install the mobile app prior to the scheduled interview time.

{% include anchor.html h="h2" text="Finalists" %}

After the video interviews, the selection committee will offer the scholarship to the top 6 applicants on {{ site.data.dates.finalist_notification.date | date: "%A %b %d, %Y" }}. To accept the scholarship, these finalists:

  - Must respond to the scholarship offer to accept the scholarship.

  - Must formally accept admission to USF and submit a deposit by the deposit deadline of {{ site.data.dates.deposit_deadline.date | date: "%A %b %d, %Y" }}.

  - Must formally apply for on-campus housing by {{ site.data.dates.deposit_deadline.date | date: "%A %b %d, %Y" }}.

After {{ site.data.dates.deposit_deadline.date | date: "%A %b %d, %Y" }}, the scholarship will be offered to someone on the waitlist instead.

{% include anchor.html h="h2" text="Waiting List" %}

After the video interviews, the selection committee will invite a select number of semi-finalists to join a waiting list. If space opens up after {{ site.data.dates.deposit_deadline.date | date: "%b %d, %Y" }}, it will be offered to someone on the waiting list instead.

Please note this will be *after* the deposit deadline, so only applicants that decided to attend USF and deposited  will be eligible to accept. These applicants must accept the scholarship and apply for on-campus housing by the guaranteed housing deadline of {{ site.data.dates.housing_deadline.date | date: "%A %b %d, %Y" }}.

The list of scholarship recipients will be finalized on {{ site.data.dates.housing_deadline.date | date: "%A %b %d, %Y" }}.

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
