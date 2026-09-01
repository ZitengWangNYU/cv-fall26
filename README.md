---
layout: home
title: Home
nav_exclude: false
nav_order: 1
permalink: /:path/
seo:
  type: Course
  name: CSCI-GA.2271-001 (Advanced) Computer Vision
---

# CSCI-GA.2271-001 (Advanced) Computer Vision

## Overview

Welcome to CSCI-GA.2271-001, (Advanced) Computer Vision. This graduate-level course focuses on modern, deep learning-based computer vision research and applications. While we will cover traditional vision techniques, our primary emphasis will be on contextualizing these methods within the current landscape of computer vision. The course aims to provide students with both historical perspectives and a deep understanding of current applications powered by large-scale vision foundation models. We will explore cutting-edge topics such as deep learning architectures for various vision tasks, object detection and segmentation, image and video generation, 3D vision and scene understanding, and vision transformers and self-supervised learning. Additionally, we will delve into multimodal learning, examining how computer vision serves as a connective layer to many other domains. This interdisciplinary approach will highlight the broader impact and applications of computer vision in fields such as natural language processing, robotics, and augmented reality. Throughout the course, students will gain hands-on experience with state-of-the-art algorithms and frameworks, preparing them for both research and practical applications in the rapidly evolving field of computer vision.

---

## Teaching Team  
{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

## Prerequisite
Students are expected to have a solid mathematics background and strong programming skills. Students are expected to have completed at least one of these undergraduate courses: 1) Deep Learning, 2) Machine Learning, and 3) Undergraduate Computer Vision. Other requirements include: Python programming; Algorithms and data structure (CSCI-UA.102); Deep learning programming with PyTorch or JAX; Foundations of machine learning; Foundations of deep learning; Linear algebra; Probability and statistics (DS-GA.1002, MATH-UA.140, MATH-UA.235); 

---

## Logistics

**When**: Thursdays, 7:10 PM - 9:10 PM 

**Where**: 31 Washington Pl (Silver Ctr) Room 408

**Format**: Lectures and Discussions.

**Discord Group**: We will use [Discord](https://discord.com/) to faliciate discussion and host course materials. You can find the Discord link on Brightspace.

{: .note }
> Students auditing the course should email the instructor or any of the TAs to get access to the Discord server.

---

## Class Schedule
An updated schedule of individual classes and topics can be found on the [Calendar]({{ site.baseurl }}/calendar/) page.

---

## Coursework
Grading will be based on three activities:  
1. Early assignment (10%)
2. Graded Homework Assignments (15% * 3)
3. Semester-long project including report and presentation (45%) 
4. Class participation and online discussions (additional bonus)

### 1. Early assignment
This small warm-up exercise aims to give you hands-on experience and prepare you for the class.
More information is available [here]({{ site.baseurl }}/assignment/). Please follow the instructions to submit your assignment.

### 2. Semester-long project

The main deliverable of the course is a semester-long project. This year the project runs in **two tracks**. The track determines what tools you may use to *build* your project and how many people build it; within either track you choose what *kind* of project to build. Full details are on the [Project]({{ site.baseurl }}/project/) page.

#### Two Tracks

##### Artisan Track

You build it yourself. Every line of code you submit, and every word of your report, is written by a human member of your team.

**Team size: 2–5 students.** Teamwork is an explicit learning objective of this track.

**Not permitted:** LLM or agent code generation, autocompletion, or refactoring (Copilot, Cursor, Claude Code, ChatGPT, and equivalents); asking an assistant to debug your code, design your architecture, or draft your report or slides.

**Explicitly permitted** — this is a computer vision course, and these are not what the restriction is about:

- Pretrained vision models as components of your system (CLIP, SAM, diffusion models, VLMs, and so on). Using a pretrained network is the subject matter of this course, not a shortcut around it.
- Standard libraries and frameworks: PyTorch, HuggingFace, OpenCV, etc.
- Documentation, papers, textbooks, StackOverflow, and course materials.

The distinction is **AI as author** (not permitted) versus **AI as a component of the system you are studying** (encouraged).

##### Agent Track

Use whatever you want. Coding agents, LLMs, AI-assisted writing, AI-generated figures and slides — there are no tooling restrictions at any stage of this track.

**Team size: one.** Agent Track projects are individual. The premise of this track is that agents multiply what a single person can build, so your team is you and your tooling, and the unit of work and of assessment is one student.

Because the tooling is unrestricted and you are working alone, **scope expectations are calibrated accordingly**: we expect an Agent Track submission to reach well beyond what one student could hand-build in a semester.

**One additional required deliverable — the Agent Log.** Submitted as an appendix to your final report and excluded from the page limit:

1. What tooling you used, and how you divided the work between yourself and it.
2. Where it failed: the bugs it introduced, the approaches it got wrong, the things it confidently asserted that were false.
3. What you had to diagnose or build by hand, and how you verified the final system actually works.

Item 2 and item 3 carry the most weight. Anyone can point an agent at a problem; the interesting question — and the one this track is really asking — is what you learned about where it breaks and how you established that the result is correct.

##### What applies to both tracks

- **Version control.** Submit a repository with incremental commit history. A single bulk commit at the deadline is not acceptable in either track.
- **Code walkthrough.** At the final presentation you may be asked to explain any part of your submission; in the Artisan Track, that question may go to any member of the team. This applies identically to both tracks and is a significant component of the project grade.
- **Track declaration.** You declare your track in your proposal and restate it in your final report.

##### Choosing and switching

Your track determines your team structure, so the two decisions are made together and recorded in your proposal.

An Artisan team may switch to the Agent Track up to **Thursday, November 5**. Because Agent Track projects are individual, a switching team must dissolve: each member continues as their own Agent Track project. Switching therefore needs staff approval — talk to us before committing to it — and must be disclosed, with its timing, in your final report.

You may **not** switch from Agent to Artisan: once generated code is in your project, it cannot be unwound.

#### Project format

Independently of your track, choose one of two formats:

1. **Build a computer vision-powered application or demo.** Computer vision models are powerful tools for solving real-world problems. Using image processing techniques, deep learning architectures, and vision APIs, you can automate vision-based interaction with the environment, perform image-based analytics, generate or manipulate visual content, enhance real-time video, reconstruct 3D scenes, or simply build something cool.

2. **Conduct a research project.** If you would rather explore the research side of computer vision, identify a research question of your own: run comparative studies that expose the limitations of current vision models, or improve on their design through data pipelines, training objectives, or architectures.

The line between a demo and a research project can be indistinct; the teaching staff will help you categorize your idea. There is no grading preference between the two.

#### Project logistics

Team composition is determined by your track:

- **Artisan Track** — teams of **2–5 students**. Individual projects are not allowed unless directly approved by the instructor; teamwork is an explicit learning objective of this track. Every team member is expected to contribute, and individual contributions must be clearly listed in the final report.
- **Agent Track** — **individual only**, one student per project.

##### Milestones

| Milestone | Date | Due |
|---|---|---|
| Proposal | Thursday, October 1 | 6:00 PM ET, Gradescope |
| Proposal feedback sessions | Week of October 8 | 15 min per team, by appointment |
| Track switch deadline (Artisan → Agent) | Thursday, November 5 | — |
| Final presentation | Thursday, December 10 | In class |
| Final report, code, and Agent Log | Friday, December 18 | 11:59 PM ET, Gradescope |

##### Proposal

Submit a PDF via Gradescope by **6:00 PM ET on Thursday, October 1**. Your proposal should sketch the research question or application you intend to explore and the methodology you plan to use, including a concise overview of the computer vision methods involved and the metrics you will use to evaluate success. It should also state your project's significance, expected deliverables, potential risks, and a preliminary timeline.

**Your proposal must state your track and your format.**

##### Proposal feedback sessions

Each team gets a 15-minute session with the instructor during the week of October 8 to discuss the proposal and improve it. Booking details will be sent by email.

##### Final submission

Both a write-up and a code repository are required, in either track and either format.

- **Application / demo** submissions should include a working demo — for example via [Gradio](https://gradio.app/) or [Streamlit](https://streamlit.io/) — with a written explanation of the problem, the models used, and your implementation and evaluation.

- **Research project** submissions should include a report in the form of a research paper (4–9 pages excluding references) and a repository that reproduces your results. Clear, succinct writing matters; unnecessary complexity or lack of clarity will cost points. Reports must be typeset in LaTeX and submitted as PDF ([Overleaf](https://www.overleaf.com/) is strongly encouraged).

Agent Track submissions additionally include the **Agent Log** as an appendix.

##### Grading

The project is **45%** of your course grade. Both tracks are worth the same, but they are assessed against different rubrics:

- **Artisan Track** — depth and correctness of implementation, and demonstrated understanding of the system you built. A smaller system, understood completely, scores well here.
- **Agent Track** — ambition and scope, the design of your workflow, and above all *verification*: the evidence that what you shipped actually works, and the quality of your failure analysis.

The code walkthrough at the final presentation contributes to both.

##### Access to computing facilities

After your proposal is reviewed, you may be eligible for access to NYU HPC and Google Cloud credits. You are also free to use your own compute. Consider which resources suit your project and say so in your proposal. You are encouraged to build on existing open-source codebases such as [diffusers](https://github.com/huggingface/diffusers) and [LLaVA](https://github.com/haotian-liu/LLaVA).

### 3. Class attendance and participation 

Daily class attendance will be recorded.

### 4. Textbooks

The course does not closely follow a particular text; the lectures are meant to be self-contained. Nevertheless, the following texts (though not required) may be useful as general references:

* [Foundations of Computer Vision](https://mitpress.mit.edu/9780262048972/foundations-of-computer-vision/) by Antonio Torralba, Phillip Isola and William T. Freeman
* [Computer Vision: Algorithms and Applications](https://szeliski.org/Book/) by Richard Szeliski
* [Multiple View Geometry in Computer Vision](https://www.robots.ox.ac.uk/~vgg/hzbook/) by Richard Hartley and Andrew Zisserman
* [Computer Vision: A Modern Approach](http://luthuli.cs.uiuc.edu/~daf/book/bookpages/book.html) by David A. Forsyth and Jean Ponce
* [Deep Learning](https://www.deeplearningbook.org/) by Ian Goodfellow, Yoshua Bengio, and Aaron Courville
* [The Little Book of Deep Learning](https://fleuret.org/francois/lbdl.html) by François Fleuret

### Late Submission Policy
* Each student will be provided 3 grace days to submit their assignment without any penalty. They will be free to use these grace days at their convenience. Some examples of how a student could use these grace days are:
  * Student_1 submits 3 assignments each of which is one day late. They will not be penalized for any assignment.
  * Student_2 submits 1 assignment which is 1 day late and another assignment which is 2 days late. They will not be penalized for these two assignments.
  * Student_3 submits 1 assignment 3 days late. They will not be penalized for this single assignment.
* Once the student exhausts its 3 graces days, they will receive:
  * 75% grade if their assignment is late by one day
  * 50% grade if their assignment is late by two days
  * 0% grade if their assignment is late by more than two days
* Note: 
  * If assignment 1 is 20 hours late it is calculated as 1 day late.
  * If assignment 2 is 28 hours late it’s as calculated as 2 days late.
  * So the total will be 3 days late (and not 22+28 = 48 == 2 days)

### Policy on the Use of Large Language Models (LLMs)

Rules differ between assignments and the project. Read both.

#### Assignments (Assignment 0-3)

* You **may use LLMs** to assist with assignments.
* You must **explicitly acknowledge** that use (e.g. "I used ChatGPT to help brainstorm the code structure" or "I used Claude to check my explanation for clarity").
* Failure to disclose use of LLMs is a violation of academic honesty.

#### Project

Governed by your project track — see the [Project]({{ site.baseurl }}/project/) page.

* **Artisan Track**: no LLM or agent authoring at any stage — code, report, or slides. Pretrained vision models as components of your system are permitted and encouraged; the restriction is on AI writing your work, not on neural networks as subject matter.
* **Agent Track**: no restrictions on tooling. You must submit the Agent Log described on the Project page, and you remain fully accountable for everything you submit.

In both tracks, you may be asked to explain any part of your submission during the final presentation.

#### General expectations

* Treat LLMs as a tool for support, not a substitute for your own reasoning.
* Always critically evaluate any suggestion an LLM gives you.
* Submitting work you cannot explain is a problem in either track.
* If in doubt about acceptable use, ask the instructor before submitting.
