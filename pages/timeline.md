---
layout: default
title: Timeline
permalink: /timeline/
---

# Timeline & Key Dates

## {{ site.data.timeline.current_semester }}

<table class="timeline-table">
<thead><tr><th>Milestone</th><th>Date</th></tr></thead>
<tbody>
{% for item in site.data.timeline.spring_2026 %}
<tr>
<td>{{ item.milestone }}</td>
<td>{{ item.date }}<div class="note">{{ item.note }}</div></td>
</tr>
{% endfor %}
</tbody>
</table>

## Fall 2026

<table class="timeline-table">
<thead><tr><th>Milestone</th><th>Date</th></tr></thead>
<tbody>
{% for item in site.data.timeline.fall_2026 %}
<tr>
<td>{{ item.milestone }}</td>
<td>{{ item.date }}<div class="note">{{ item.note }}</div></td>
</tr>
{% endfor %}
</tbody>
</table>

## What to Expect at Each Milestone

### 1. Project/Thesis Submission
Submit your [Project/Thesis Submission Form](https://forms.gle/fYeA2nXtkgzqLpio6){:target="_blank"} and [signed Advisor Agreement](https://drive.google.com/file/d/19d3zkQQ5TE014Onx_T0yOSQOgVGeGfKO/view){:target="_blank"} before the add/drop deadline. Request DATS 5990 or DATS 9990 in Path@Penn.

### 2. Mid-Term Check-In
Meet with your faculty advisor and the Project Director to review progress. Prepare a brief PowerPoint, progress demo, or report outline.

### 3. Final Check-In
Submit your project report to your faculty advisor and the Project Director before the withdrawal deadline.

### 4. Thesis Submission (Thesis students only)
Submit your completed, signed thesis electronically to [grad-affairs@seas.upenn.edu](mailto:grad-affairs@seas.upenn.edu).

### 5. DATS Presentation Day
Thesis students give 5-minute talks. Practicum students present posters. All students upload their presentations/posters to the shared Google Drive folder before the event.

<div class="info-box">
<strong>How to update this page:</strong> Dates are stored in <code>_data/timeline.yml</code>. Edit that file on GitHub to update dates each semester — no HTML knowledge needed.
</div>
