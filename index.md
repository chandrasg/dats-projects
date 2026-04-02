---
layout: default
title: Home
---

<div class="hero">
<div class="container">
<h1>DATS Practicum & Thesis</h1>
<p>Everything you need to know about pursuing independent research through DATS 5990 (Practicum) or DATS 9990 (Thesis) in Penn's Data Science MSE program.</p>
<a href="{{ '/get-started/' | relative_url }}" class="btn">Get Started</a>
<a href="{{ '/timeline/' | relative_url }}" class="btn btn-outline">View Timeline</a>
</div>
</div>

## Thesis vs. Practicum at a Glance

<div class="compare-grid">
<div class="compare-card">
<span class="tag">DATS 5990</span>
<h3>Practicum</h3>
<p>An independent study where you lead one or more parts of a research project. Your contribution is similar to that of a co-author on a publication — you lead a distinct piece of the work within a larger collaborative effort.</p>
<ul>
<li><strong>Credits:</strong> 1 CU (2 CU possible with approval)</li>
<li><strong>Advisor:</strong> Any Penn faculty member</li>
<li><strong>Report:</strong> 5–10 pages</li>
<li><strong>Presentation:</strong> Poster session</li>
<li><strong>Industry projects:</strong> Allowed with academic product</li>
</ul>
</div>
<div class="compare-card">
<span class="tag">DATS 9990</span>
<h3>Thesis</h3>
<p>A deeper research endeavor where you lead all aspects of a project — problem formulation, materials, methods, results, and interpretation — with the goal of answering a research question that could result in a peer-reviewed publication.</p>
<ul>
<li><strong>Credits:</strong> 2 CU (1 CU per semester, two semesters)</li>
<li><strong>Advisor:</strong> Any Penn faculty member</li>
<li><strong>Report:</strong> Full thesis (SEAS format)</li>
<li><strong>Presentation:</strong> 5-minute talk</li>
<li><strong>Reader:</strong> Additional Penn faculty reader required</li>
</ul>
</div>
</div>

Both courses count as technical and depth area electives toward the ten required credits for the MSE degree.

## Current Semester: {{ site.data.timeline.current_semester }}

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

<a href="{{ '/timeline/' | relative_url }}">View full timeline &rarr;</a>

## Quick Links

<div class="compare-grid">
<div class="resource-card">
<h4><a href="https://forms.gle/fYeA2nXtkgzqLpio6" target="_blank">Project/Thesis Submission Form &rarr;</a></h4>
<p>Submit your project details and proposal</p>
</div>
<div class="resource-card">
<h4><a href="https://drive.google.com/file/d/19d3zkQQ5TE014Onx_T0yOSQOgVGeGfKO/view" target="_blank">Advisor Agreement Form &rarr;</a></h4>
<p>Download, get signed by your advisor, and upload</p>
</div>
</div>

## Contact

<div class="contact-grid">
<div class="contact-card">
<h4>{{ site.data.contacts.project_director.name }}</h4>
<div class="role">{{ site.data.contacts.project_director.title }}</div>
<a href="mailto:{{ site.data.contacts.project_director.email }}">{{ site.data.contacts.project_director.email }}</a><br>
<a href="{{ site.data.contacts.project_director.website }}">{{ site.data.contacts.project_director.website }}</a>
</div>
<div class="contact-card">
<h4>{{ site.data.contacts.program_manager.name }}</h4>
<div class="role">{{ site.data.contacts.program_manager.title }}</div>
<a href="mailto:{{ site.data.contacts.program_manager.email }}">{{ site.data.contacts.program_manager.email }}</a>
</div>
</div>
