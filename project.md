---
layout: page
title: Project
description: Description of the semester-long project.
nav_exclude: false
nav_order: 5
---

# Project

The main deliverable of the course is a semester-long project. This year the project runs
in **two tracks**. The track determines what tools you may use to *build* your project and
how many people build it; within either track you choose what *kind* of project to build.

---

## Two Tracks

### Artisan Track

You build it yourself. Every line of code you submit, and every word of your report, is
written by a human member of your team.

**Team size: 2â5 students.** Teamwork is an explicit learning objective of this track.

**Not permitted:** LLM or agent code generation, autocompletion, or refactoring (Copilot,
Cursor, Claude Code, ChatGPT, and equivalents); asking an assistant to debug your code,
design your architecture, or draft your report or slides.

**Explicitly permitted** â this is a computer vision course, and these are not what the
restriction is about:

- Pretrained vision models as components of your system (CLIP, SAM, diffusion models,
  VLMs, and so on). Using a pretrained network is the subject matter of this course, not
  a shortcut around it.
- Standard libraries and frameworks: PyTorch, HuggingFace, OpenCV, etc.
- Documentation, papers, textbooks, StackOverflow, and course materials.

The distinction is **AI as author** (not permitted) versus **AI as a component of the
system you are studying** (encouraged).

### Agent Track

Use whatever you want. Coding agents, LLMs, AI-assisted writing, AI-generated figures and
slides â there are no tooling restrictions at any stage of this track.

**Team size: one.** Agent Track projects are individual. The premise of this track is that
agents multiply what a single person can build, so your team is you and your tooling, and
the unit of work and of assessment is one student.

Because the tooling is unrestricted and you are working alone, **scope expectations are
calibrated accordingly**: we expect an Agent Track submission to reach well beyond what
one student could hand-build in a semester.

**One additional required deliverable â the Agent Log.** Submitted as an appendix to your
final report and excluded from the page limit:

1. What tooling you used, and how you divided the work between yourself and it.
2. Where it failed: the bugs it introduced, the approaches it got wrong, the things it
   confidently asserted that were false.
3. What you had to diagnose or build by hand, and how you verified the final system
   actually works.

Item 2 and item 3 carry the most weight. Anyone can point an agent at a problem; the
interesting question â and the one this track is really asking â is what you learned about
where it breaks and how you established that the result is correct.

### What applies to both tracks

- **Version control.** Submit a repository with incremental commit history. A single
  bulk commit at the deadline is not acceptable in either track.
- **Code walkthrough.** At the final presentation you may be asked to explain any part of
  your submission; in the Artisan Track, that question may go to any member of the team.
  This applies identically to both tracks and is a significant component of the project
  grade.
- **Track declaration.** You declare your track in your proposal and restate it in your
  final report.

### Choosing your track

Your track determines your team structure, so the two decisions are made together and
recorded in your proposal.

Your track is final once your proposal is submitted. There is no switching between tracks
during the semester, in either direction.

---

## Project format

Independently of your track, choose one of two formats:

1. **Build a computer vision-powered application or demo.** Computer vision models are
   powerful tools for solving real-world problems. Using image processing techniques, deep
   learning architectures, and vision APIs, you can automate vision-based interaction with
   the environment, perform image-based analytics, generate or manipulate visual content,
   enhance real-time video, reconstruct 3D scenes, or simply build something cool.

2. **Conduct a research project.** If you would rather explore the research side of
   computer vision, identify a research question of your own: run comparative studies that
   expose the limitations of current vision models, or improve on their design through
   data pipelines, training objectives, or architectures.

The line between a demo and a research project can be indistinct; the teaching staff will
help you categorize your idea. There is no grading preference between the two.

---

## Project logistics

Team composition is determined by your track:

- **Artisan Track** â teams of **2â5 students**. Individual projects are not allowed unless
  directly approved by the instructor; teamwork is an explicit learning objective of this
  track. Every team member is expected to contribute, and individual contributions must be
  clearly listed in the final report.
- **Agent Track** â **individual only**, one student per project.

### Proposal

Submit a PDF via Gradescope by **6:00 PM ET on Thursday, October 1**. Your proposal should
sketch the research question or application you intend to explore and the methodology you
plan to use, including a concise overview of the computer vision methods involved and the
metrics you will use to evaluate success. It should also state your project's significance,
expected deliverables, potential risks, and a preliminary timeline.

**Your proposal must state your track and your format.**

### Final submission

Presentations are in class on **Thursday, December 10**. The write-up, code repository,
and — for Agent Track — the Agent Log are due at **11:59 PM ET on Friday, December 18**
via Gradescope.

Both a write-up and a code repository are required, in either track and either format.

- **Application / demo** submissions should include a working demo â for example via
  [Gradio](https://gradio.app/) or [Streamlit](https://streamlit.io/) â with a written
  explanation of the problem, the models used, and your implementation and evaluation.

- **Research project** submissions should include a report in the form of a research paper
  (4â9 pages excluding references) and a repository that reproduces your results. Clear,
  succinct writing matters; unnecessary complexity or lack of clarity will cost points.
  Reports must be typeset in LaTeX and submitted as PDF
  ([Overleaf](https://www.overleaf.com/) is strongly encouraged).

Agent Track submissions additionally include the **Agent Log** as an appendix.

### Grading

The project is **45%** of your course grade. Both tracks are worth the same, but they are
assessed against different rubrics:

- **Artisan Track** â depth and correctness of implementation, and demonstrated
  understanding of the system you built. A smaller system, understood completely, scores
  well here.
- **Agent Track** â ambition and scope, the design of your workflow, and above all
  *verification*: the evidence that what you shipped actually works, and the quality of
  your failure analysis.

The code walkthrough at the final presentation contributes to both.

### Access to computing facilities

After your proposal is reviewed, you may be eligible for access to NYU HPC and Google Cloud
credits. You are also free to use your own compute. Consider which resources suit your
project and say so in your proposal. You are encouraged to build on existing open-source
codebases such as [diffusers](https://github.com/huggingface/diffusers) and
[LLaVA](https://github.com/haotian-liu/LLaVA).
