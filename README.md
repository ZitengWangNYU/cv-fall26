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

**Team size: 2-5 students.** Teamwork is an explicit learning objective of this track.

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

##### Choosing your track

Your track determines your team structure, so the two decisions are made together and recorded in your proposal.

Your track is final once your proposal is submitted. There is no switching between tracks during the semester, in either direction.

#### Project format

Within either track, the project is designed to give you the open-ended opportunity to either:

1. **Build a computer vision-powered application or demo**. Computer vision models are powerful tools to solve exciting real-world problems. Utilizing various image processing techniques, deep learning architectures, and computer vision APIs, these models can function as ready-to-use tools. They can be employed to automate vision-based interactions with the environment, perform image-based data analytics, generate or manipulate visual content, enhance real-time video streams, reconstruct 3D scenes, or simply build something cool.

2. **Conduct a research project**. Should you wish to explore the research aspects of computer vision more thoroughly, we invite you to undertake a research project tailored to your interests. Your focus could be on identifying a specific research topic within the realms of computer vision. You can conduct comparative studies to uncover the limitations of current vision models, or enhance the overall design—be it through optimizing data pipelines, training objectives, or architectures.

Be aware that the line separating a demo from a research project can be somewhat indistinct; the instructor will assist you in appropriately categorizing your project idea. Additionally, there is no grading preference for either application/demo or research projects, so feel free to select the option that most excite you!

#### Project logistics

Team composition is determined by your track. **Artisan Track** projects may be done in **teams of 2-5 students** (individual projects are not allowed unless directly approved by the instructor. Teamwork is an essential learning objective). We expect every team member to contribute to the project (and individual contributions should be clearly listed). **Agent Track** projects are individual, one student per project.

We will organize your project progress into **two key milestones**: (1) a preliminary proposal, and (2) a final submission/presentation.

The **preliminary proposal** should sketch out the research question or application you're keen to explore, along with the methodology you intend to employ. This should feature a concise overview of the CV methods you aim to utilize, as well as a list of potential metrics for evaluating success.

For the **final submission**, both write-up and code repo will be required, regardless of the project format. We will schedule a **presentation/poster session** for each team to present their work during the final week of the semester. Additional specifics will be provided soon, but anticipate the following:

- **Application/demo** submissions to include a functional demo of your application, possibly through platforms like [Gradio](https://gradio.app/) or [Streamlit](https://streamlit.io/). This should be accompanied by a brief written explanation that outlines the problem you're addressing, the CV model(s) you've employed, and your implementation and evaluation process.

- **Research project** submissions to a final report resembling a research paper (ranging from 4 to 9 pages, excluding references) and a code repository to replicate your findings. Clear and succinct writing is crucial; any lack of clarity or unnecessary complexity may lead to point deductions. For projects involving multiple contributors, a delineation of each participant's role is mandatory. All submissions must be LaTeX-formatted and provided in PDF format (exceptions must be approved by the instructor). Utilizing user-friendly web platforms like [Overleaf](https://www.overleaf.com/) is strongly encouraged.

Agent Track submissions additionally include the **Agent Log** as an appendix.

#### Project Proposal Submission Instructions

Please submit your project proposal via Gradescope. Your submission should be in PDF format and include detailed information about your project idea, significance, expected deliverables, potential risks, and a preliminary timeline to monitor progress. **Your proposal must state your track and your format.**

#### Grading

The project is **45%** of your course grade. Both tracks are worth the same, but they are assessed against different rubrics:

- **Artisan Track** — depth and correctness of implementation, and demonstrated understanding of the system you built. A smaller system, understood completely, scores well here.
- **Agent Track** — ambition and scope, the design of your workflow, and above all *verification*: the evidence that what you shipped actually works, and the quality of your failure analysis.

The code walkthrough at the final presentation contributes to both.

#### Access to Computing Facilities

Upon reviewing your proposal, you might be eligible to get access to both NYU HPC and Google Cloud credits. You are free to use your own computing resources. As you draft your proposal, consider which of these resources would be best suited for your project and mention it in your submission. You are encouraged to build upon current open-source codebases such as [Diffuser](https://github.com/huggingface/diffusers), [LLaVA](https://github.com/haotian-liu/LLaVA), etc.

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

To support learning while maintaining academic integrity, the following rules apply to the use of large language models (e.g., ChatGPT, Claude, Gemini, etc.) in this course:
#### Assignments
* You **may use LLMs** to assist with **assignments**.
* If you use an LLM, you must **explicitly acknowledge** this use (e.g., “This assignment used ChatGPT to help brainstorm code structure” or “I used Claude to check my explanation for clarity”).
* Failure to disclose use of LLMs will be considered a violation of academic honesty.

#### Project

Governed by your project track — see the [Project]({{ site.baseurl }}/project/) page.

* **Artisan Track**: no LLM or agent authoring at any stage — code, report, or slides. Pretrained vision models as components of your system are permitted and encouraged; the restriction is on AI writing your work, not on neural networks as subject matter.
* **Agent Track**: no restrictions on tooling. You must submit the Agent Log described on the Project page, and you remain fully accountable for everything you submit.

#### General Expectations
* Treat LLMs as a tool for support, not as a substitute for your own reasoning, coding, or analysis.
* Always critically evaluate any suggestions provided by an LLM.
* If in doubt about acceptable use, ask the instructor before submitting work.
