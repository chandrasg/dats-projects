---
layout: default
title: Home
full_width: true
---

<div class="hero">
<div class="container">
<h1>DATS Practicum & Thesis</h1>
<p>Everything you need to know about pursuing independent research through DATS 5990 (Practicum) or DATS 9990 (Thesis) in Penn's Data Science MSE program.</p>
<a href="{{ '/get-started/' | relative_url }}" class="btn">Get Started</a>
<a href="{{ '/timeline/' | relative_url }}" class="btn btn-outline">View Timeline</a>
</div>
</div>

<div class="container" markdown="1">

## Choose Your Path

<div class="compare-grid three-col">
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
<div class="compare-card industry">
<span class="tag">DATS 5990-002</span>
<h3>Industry Capstone</h3>
<p>A sponsor-proposed project mentored by your industry sponsor and DATS teaching staff, with admission by application and interview.</p>
<ul>
<li><strong>Credits:</strong> 1 CU per semester (max 2 total)</li>
<li><strong>Sponsor:</strong> Industry partner + DATS teaching staff</li>
<li><strong>Admission:</strong> Application + interviews (GPA ≥ 3.6)</li>
<li><strong>Report:</strong> Sponsor deliverables + final presentation</li>
<li><strong>New:</strong> Launching Fall 2026</li>
</ul>
<a href="{{ '/industry-capstone/' | relative_url }}">Learn more &rarr;</a>
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

## Find What You Need

<div class="phase-grid">
<div class="phase-card">
<span class="phase-label">Before</span>
<h3>Planning & Enrolling</h3>
<ul>
<li><a href="{{ '/get-started/' | relative_url }}">Find an advisor & scope a project</a></li>
<li><a href="{{ '/get-started/#what-makes-a-good-project' | relative_url }}">What makes a good project</a></li>
<li><a href="{{ '/resources/' | relative_url }}">Browse past reports & forms</a></li>
<li><a href="{{ '/get-started/#enrollment-steps' | relative_url }}">Enrollment steps</a></li>
<li><a href="{{ '/industry-capstone/' | relative_url }}">Industry Capstone (sponsor projects)</a></li>
</ul>
</div>
<div class="phase-card">
<span class="phase-label">During</span>
<h3>Doing the Work</h3>
<ul>
<li><a href="{{ '/guidelines/' | relative_url }}">Report & check-in requirements</a></li>
<li><a href="{{ '/guidelines/#evaluation-rubric' | relative_url }}">How your work is evaluated</a></li>
<li><a href="{{ '/guidelines/#working-with-your-advisor' | relative_url }}">Working with your advisor</a></li>
<li><a href="{{ '/timeline/' | relative_url }}">Key dates & deadlines</a></li>
</ul>
</div>
<div class="phase-card">
<span class="phase-label">After</span>
<h3>Finishing & Beyond</h3>
<ul>
<li><a href="{{ '/guidelines/#presentation' | relative_url }}">Presentation & poster day</a></li>
<li><a href="{{ '/resources/#poster-presentation' | relative_url }}">Poster templates & printing</a></li>
<li><a href="{{ '/guidelines/#after-you-finish' | relative_url }}">Publishing & next steps</a></li>
</ul>
</div>
</div>

## Current Semester: {{ site.data.timeline.current_semester }}

<div class="table-scroll">
<table class="timeline-table">
<thead><tr><th scope="col">Milestone</th><th scope="col">Date</th></tr></thead>
<tbody>
{% assign current_items = site.data.timeline[site.data.timeline.current_key] %}
{% for item in current_items %}
<tr>
<td>{{ item.milestone }}</td>
<td>{{ item.date }}<div class="note">{{ item.note }}</div></td>
</tr>
{% endfor %}
</tbody>
</table>
</div>

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
<div class="resource-card">
<h4><a href="{{ '/guidelines/' | relative_url }}">Guidelines &rarr;</a></h4>
<p>Report requirements, grading, check-ins, and presentation details</p>
</div>
<div class="resource-card">
<h4><a href="{{ '/resources/' | relative_url }}#poster-presentation">Poster Resources &rarr;</a></h4>
<p>Templates, design tips, and CETS printing info</p>
</div>
</div>

## Contact

<div class="contact-grid">
<div class="contact-card">
<h4>{{ site.data.contacts.project_director.name }}</h4>
<div class="role">{{ site.data.contacts.project_director.title }}</div>
<a href="mailto:{{ site.data.contacts.project_director.email }}">{{ site.data.contacts.project_director.email }}</a><br>
<a href="{{ site.data.contacts.project_director.website }}">Faculty Website &rarr;</a>
</div>
<div class="contact-card">
<h4>{{ site.data.contacts.program_manager.name }}</h4>
<div class="role">{{ site.data.contacts.program_manager.title }}</div>
<a href="mailto:{{ site.data.contacts.program_manager.email }}">{{ site.data.contacts.program_manager.email }}</a>
</div>
</div>

</div>
