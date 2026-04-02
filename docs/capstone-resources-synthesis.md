# Capstone Best Practices: Synthesis from Peer Programs

Compiled from publicly accessible resources at CMU, MIT, Berkeley, UW, Cornell, UBC, Georgia Tech, Columbia, and NYU. Organized by phase: scoping, execution, writing, and advising.

---

## 1. Scoping Your Project

### The Heilmeier Catechism (MIT EECS CommLab)
A set of questions developed at DARPA that sharpen any research proposal. Every DATS student should be able to answer these before submitting their proposal:

1. What are you trying to do? Articulate your objectives using absolutely no jargon.
2. How is it done today, and what are the limits of current practice?
3. What is new in your approach, and why do you think it will succeed?
4. Who cares? If you succeed, what difference will it make?
5. What are the risks?
6. How much will it cost, and how long will it take?
7. What are the midterm and final exams — how will you know you're succeeding?

Source: [MIT EECS Communication Lab — Thesis Proposal Guide](https://mitcommlab.mit.edu/eecs/commkit/thesis-proposal/)

---

### The Vision Document Framework (CMU MCDS 11-634)
CMU's capstone planning seminar formalizes scope through a layered document:

- **Research Questions (RQs):** The high-level questions your project will explore.
- **General Hypotheses (GHs):** Broad claims your project will test.
- **Specific (Testable) Hypotheses (SHs):** Operationalizable versions of those claims — these become your success metrics.
- **Requirements Document:** What the system/analysis must do.
- **Design Document:** How you'll build it, with a work breakdown structure and timeline.

The key discipline: don't write a design document until you have testable hypotheses. Scope drift almost always traces back to unclear hypotheses.

Source: [CMU MCDS 11-634 Syllabus](https://mcds-cmu.github.io/11634/s24/syllabus/)

---

### What Makes a Good vs. Poor Project (UBC MDS)
UBC's MDS program publishes unusually direct criteria for evaluating project scope:

**Good projects:**
- Open-ended with no predetermined solution
- Multi-faceted — decomposable into parallel milestones
- Require genuine analysis and methodological decisions
- Deep enough to sustain 2+ months of focused work

**Poor projects (anti-patterns):**
- Database setup or data pipeline work with no research component
- Pre-specified algorithm — "just implement X and run it"
- Pure data cleaning with no analytical output
- Projects where the answer is already known

Source: [UBC MDS Capstone Project Guide](https://masterdatascience.ubc.ca/employers/capstone-project)

---

### MIT's Thesis Proposal Structure
MIT MEng students are required to write a 1,500–2,500 word proposal before any work begins. The structure:

1. **Introduction** — problem statement and motivation
2. **Related Work** — what exists and where the gaps are
3. **Proposed Work** — your approach, with technical detail
4. **Timeline** — milestones with dates
5. **Bibliography**

The proposal functions as "an agreement between you and your thesis advisor on the scope of your thesis." This framing is useful: a proposal is not a formality, it's a scope contract.

Source: [MIT EECS MEng Thesis Proposal Page](https://www.eecs.mit.edu/academics/undergraduate-programs/meng-program/thesis-proposal/)

---

## 2. Executing the Project

### Week-by-Week Execution (CMU MCDS 11-632)
CMU's two-semester capstone operates on bi-weekly advisor feedback cycles throughout. Key structural principles:

- **Bi-weekly advisor check-ins** with written status updates each time
- **Draft milestones** early in the semester — content-complete draft before polish
- **Peer review** of drafts before final submission
- **GitHub repo** maintained throughout, reviewed as part of the grade
- Student teams are expected to "take initiative in driving the development forward" — advisors guide, students own

The semester structure: Fall = planning + early experiments + draft; Spring = results + final report + poster/presentation.

Source: [CMU MCDS 11-632 Syllabus](https://mcds-cmu.github.io/11632/f24/syllabus/)

---

### Individual Development Plans (Cornell)
Cornell's graduate advising guide recommends that every research student maintain a written Individual Development Plan (IDP) with:

- Long-term goals
- Short-term milestones (semester-by-semester)
- Skills to develop
- Publication and presentation targets

The IDP is reviewed annually with the advisor. The key benefit: both student and advisor have a shared written record of expectations, making mid-course corrections easier and less fraught.

Source: [Cornell Graduate School Advising Guide (2025)](https://gradschool.cornell.edu/academic-progress/opportunities-resources-support/advising-guide-for-research-students-2025/)

---

### Anatomy of a Data Science Capstone (UW MSDS)
UW's two-quarter MSDS capstone with industry partners follows this arc:

1. **Quarter 1:** Problem framing, data acquisition, EDA, baseline models
2. **Quarter 2:** Refined methods, evaluation, stakeholder presentation, final deliverable

Deliverable types across recent cohorts: dashboards, ML pipelines, predictive models, data analysis reports. Past poster PDFs are publicly available and useful for calibrating scope.

Source: [UW MSDS Capstone Projects](https://www.washington.edu/datasciencemasters/capstone-projects/)

---

## 3. Writing & Presenting

### Progress/Status Reports
One of the most underused tools in student research is the written status report. Michael Ernst (UW) maintains a curated page of advice, including guidance on writing progress reports for advisors:

- What you set out to do this period
- What you actually did
- What's blocked and why
- What you plan to do next

Regular written updates keep the advisor relationship productive and create a running log that feeds directly into the final writeup.

Source: [Michael Ernst — Advice for CS Researchers](https://homes.cs.washington.edu/~mernst/advice/)

---

### Thesis Writing Resources
The CMU compilation by Mark Leone aggregates the most widely cited classic guides:

- *How to do Research in the MIT AI Lab* — project selection, advisor relationships, getting unstuck
- *The Art of Writing a Research Paper* — structure, argumentation, figures
- *How to Write a Dissertation* — from proposal to defense
- *Surviving Your Dissertation* — mental and practical advice

Source: [CMU Research and Writing Advice Compilation](http://www.cs.cmu.edu/~mleone/how-to.html)

---

### Poster Guidelines (Practicum students)
From Georgia Tech's CS Capstone Expo model and general best practice:

- **One sentence per section** — a poster is scanned in 30 seconds, not read
- **Lead with the result** — don't bury findings at the bottom
- **Figures over tables** — wherever possible
- **Prepare a 60-second verbal summary** — most visitors won't read the poster, they'll ask you to explain it

---

## 4. The Advisor Relationship

### Choosing the Right Advisor
From the Cornell advising guide and MIT's MEng program:

- Distinguish between an **advisor** (guides your research) and a **mentor** (invests in your development). The best advisors are both, but don't assume they are.
- Before committing, ask: How do you prefer to communicate? How often do you meet with students? What does a good weekly update look like to you?
- Find out how previous students in the group fared — graduation rate, time-to-completion, post-program placements.

---

### Managing the Relationship
- Meet regularly even when there's nothing to report — the meeting creates the progress, not the reverse.
- Send a written agenda 24 hours before each meeting.
- After each meeting, send a one-paragraph summary of decisions made and next steps.
- If you're stuck, say so explicitly. Advisors cannot help with problems they don't know about.

---

### When Scope Creep Happens
It will. The discipline is catching it early:

- Check: does this new direction still answer your original research question?
- If yes — absorb it. If no — park it for future work and write it down as a limitation.
- Use the testable hypotheses from your Vision Document (or equivalent) as a scope anchor.

---

## 5. Summary: Key Principles Across All Programs

| Principle | Where it comes from |
|---|---|
| Formalize scope in writing before starting | MIT, CMU |
| Use testable hypotheses as a scope anchor | CMU 11-634 |
| Bi-weekly written updates to advisor | CMU 11-632, Cornell |
| Separate "what you planned" from "what you did" | Cornell IDP |
| Draft early, polish late | CMU 11-632 |
| A poster is a conversation starter, not a document | Georgia Tech, general |
| A proposal is a scope contract with your advisor | MIT |
| Anti-patterns are as useful as patterns | UBC MDS |
