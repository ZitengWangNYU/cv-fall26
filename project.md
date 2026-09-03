---
layout: page
title: Project
description: Description of the semester-long project.
nav_exclude: false
nav_order: 5
---

# Project

The main deliverable of the course is a semester-long project. This year the project runs
in **two tracks**. The track determines what tools you may use to *build* your project; within either track you choose what *kind* of project to build.

---

## Two Tracks

### Artisan Track

You build it yourself. Every line of code you submit, and every word of your report, is
written by a human member of your team.

**Not permitted:** LLM or agent code generation, autocompletion, or refactoring (Copilot,
Cursor, Claude Code, ChatGPT, and equivalents); asking an assistant to debug your code,
design your architecture, or draft your report or slides.

**Explicitly permitted** — this is a computer vision course, and these are not what the
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
slides — there are no tooling restrictions at any stage of this track.

Because the tooling is unrestricted, **scope expectations are calibrated accordingly**: we
expect an Agent Track submission to reach well beyond what the same team could hand-build in a
semester.

**One additional required deliverable — the Agent Log.** Submitted as an appendix to your
final report and excluded from the page limit:

1. What tooling you used, and how you divided the work between yourselves and it.
2. Where it failed: the bugs it introduced, the approaches it got wrong, the things it
   confidently asserted that were false.
3. What you had to diagnose or build by hand, and how you verified the final system
   actually works.

Item 2 and item 3 carry the most weight. Anyone can point an agent at a problem; the
interesting question — and the one this track is really asking — is what you learned about
where it breaks and how you established that the result is correct.

### What applies to both tracks

- **Version control.** Submit a repository with incremental commit history. A single
  bulk commit at the deadline is not acceptable in either track.
- **Code walkthrough.** At the final presentation, any member of the team may be asked to
  explain any part of the submission. This applies identically to both tracks and is a
  significant component of the project grade.
- **Track declaration.** You declare your track in your proposal and restate it in your
  final report.

### Choosing your track

Your track is final once your proposal is submitted. There is no switching between tracks
during the semester, in either direction.

---

## Project format

Within either track, the project is designed to give you the open-ended opportunity to either:

1. **Build a computer vision-powered application or demo**. Computer vision models are powerful tools to solve exciting real-world problems. Utilizing various image processing techniques, deep learning architectures, and computer vision APIs, these models can function as ready-to-use tools. They can be employed to automate visual inspection processes, perform image-based data analytics, generate or manipulate visual content, enhance real-time video streams, or simply build something visually cool.

2. **Conduct a research project**. Should you wish to explore the research aspects of computer vision more thoroughly, we invite you to undertake a research project tailored to your interests. Your focus could be on identifying a specific research topic within the realms of computer vision, image processing, and deep learning. You can conduct comparative studies to uncover the limitations of current CV models, or enhance the overall design—be it through optimizing data pipelines, training objectives, or architectures.

Be aware that the line separating a demo from a research project can be somewhat indistinct; the instructor will assist you in appropriately categorizing your project idea. Additionally, there is no grading preference for either application/demo or research projects, so feel free to select the option that most excites you!

## Project logistics

Both project formats may be done in **teams of 2-5 students** (individual projects are not allowed unless directly approved by the instructor). We expect every team member to contribute to the project (and individual contributions should be clearly listed).

We will organize your project progress into **two key milestones**: (1) a preliminary proposal, and (2) a final submission/presentation.

The **preliminary proposal** should sketch out the research question or application you're keen to explore, along with the methodology you intend to employ. This should feature a concise overview of the computer vision methods you aim to utilize, as well as a list of potential metrics for evaluating success.

For the **final submission**, both write up and code repo will be required, regardless of the
project format. We will schedule a **presentation/poster session** for each team to present
their work during the final week of the semester. Additional specifics will be provided soon,
but anticipate the following:

- **Application / demo** submissions to include a functional demo of your application, possibly through platforms like [Gradio](https://gradio.app/) or [Streamlit](https://streamlit.io/). This should be accompanied by a brief written explanation that outlines the problem you're addressing, the computer vision model(s) you've employed, and your implementation and evaluation process.

- **Research project** submissions to a final report resembling a research paper (ranging from 4 to 9 pages, excluding references) and a code repository to replicate your findings. Clear and succinct writing is crucial; any lack of clarity or unnecessary complexity may lead to point deductions. For projects involving multiple contributors, a delineation of each participant's role is mandatory. All submissions must be LaTeX-formatted and provided in PDF format (exceptions must be approved by the instructor). Utilizing user-friendly web platforms like Overleaf is strongly encouraged.

Agent Track submissions additionally include the **Agent Log** as an appendix.

## Project Proposal Submission Instructions

Please submit your project proposal via Gradescope. Your submission should be in PDF format and
include detailed information about your project idea, significance, expected deliverables,
potential risks, and a preliminary timeline to monitor progress. **Your proposal must state
your track and your format.**

## Grading

The project is **45%** of your course grade. Both tracks are worth the same, but they are
assessed against different rubrics:

- **Artisan Track** — depth and correctness of implementation, and demonstrated
  understanding of the system you built. A smaller system, understood completely, scores
  well here.
- **Agent Track** — ambition and scope, the design of your workflow, and above all
  *verification*: the evidence that what you shipped actually works, and the quality of
  your failure analysis.

The code walkthrough at the final presentation contributes to both.

## Access to Computing Facilities

Upon reviewing your proposal, you might be eligible to get access to both NYU HPC and Google Cloud Credit. You are free to use your own computing resources. As you draft your proposal, consider which of these resources would be best suited for your project and mention it in your submission. You are encouraged to build upon current open-source codebases.
