+++
title = "Trustworthy Machine Learning"
semester = "Winter Semester 2023-2024"
university = "University of Tübingen"
image = "compass.png"
sort_position = 1
description = "As machine learning technology gets applied to actual products and solutions, new challenges have emerged. Models unexpectedly fail to generalise well to small changes in the distribution; some models are found to utilise sensitive features that could treat certain demographic user groups unfairly; models tend to be confident on novel types of data; models cannot communicate the rationale behind their decisions effectively with the end users like medical staff to maximise the human-machine synergies. Collectively, we face a trustworthiness issue with the current machine learning technology. A large fraction of the machine learning research nowadays is dedicated to expanding the frontier of Trustworthy Machine Learning (TML). The course covers a theoretical and technical background for key topics in TML. We conduct a critical review of important classical and contemporary research papers on related topics and provide hands-on practicals to implement TML techniques."
+++

## Overview

### Goal

1. Students will be able to critically read, assess, and discuss research work in Trustworthy Machine Learning (TML).
2. Students will gain the technical background to implement basic TML techniques in a deep learning framework.
3. Students will be ready to conduct their own research in TML and make contributions to the research community.

### Prerequisites

- Familiarity with Python and PyTorch coding.
- A pass grade from the Deep Learning Course (or equivalent).
- Basic knowledge of machine learning concepts.
- Basic maths: multivariate calculus, linear algebra, probability, statistics, and optimisation.

### Reading list



## Policies

### Registration & Exercise 0

The **registration** link is here: https://forms.gle/NQ8ZgqZhZadkG1dq6. We start accepting registration from **29 September 2023 at 12:00 pm (noon)** Central European Time (Berlin time).

Upon registration, you will get access to Exercise 0.
The Exercise 0 is an individual exercise and will be based on the prerequisite materials for the course.
Students who wish to enrol must submit their work on Exercise 0.
The necessary prerequisite materials will be taught in the first lecture.
Exercise 0 serves two purposes:
- For us to admit students who are sufficiently motivated for the course.
- For you to gauge your own readiness for the course.

Submit Exercise 0 by **22 October 2023**. **If you do not submit Exercise 0, we'll assume that you do not wish to register for the course and the exams.**

The timeline for registration is as follows:
- Now-28.09.2023: Decide whether to take the lecture.Check time & location for the course.
- 29.09.2023 at 12:00: Register for the course ([link](https://forms.gle/NQ8ZgqZhZadkG1dq6)).
- 29.09.2023-22.10.2023: Work on Exercise 0 and submit. 

### Grading policy

![TML_grading](/img/TML2324-policy.png)

The final grade is essentially based on your exam performance. However, to encourage the participation in the exercises,
we award top-ups on the final grade based on the exercise performance.
We make sure, though, that it is still possible to get the maximal perfomance (grade 1,0) even without any top-up from the exercises.

**Exercise 0**

- Submission of Exercise 0 is the minimal requirement for taking the exam.

**Exercise 1-3 average score E (0 - 100%)**

- Average score from Exercises 1-3.
- Exercises 1-3 are group exercises.

**Admission to exam**

- When you have submitted Exercise 0 and the average score for Exercises 1-3 is $E\geq 60$%, you are granted the right to sit the exam.

**Exam score X (0 - 100%)**

- Based on your performance on your exam.
- The pass threshold for the course will be $X\geq 50$% on the exam, independent of the exercise performance.
- There will be two exams: Exam 1 and Exam 2.
    - Case A: Sit Exam 1 and pass → Exam 1 score will be final (cannot sit Exam 2).
    - Case B: Sit Exam 1 and fail → You may sit Exam 2; Exam 2 score will be final.
    - Case C: Choose to skip Exam 1 and take Exam 2 → Exam 2 score will be final.


**Final score S (0 - 100%)**

- The final score is your exam score with possible increments from your exercise performance.
- Top-up from exercise: $T=(E-60$%$)/40$%$\times 10$%p, where $E$ is your average exercise score.
- The final score is clipped at 100%: $S=\min (100$%$, X+T)$.
- Examples:
    - If $E=100$% and $X=100$%, there will be no further top-up from the exercise scores $S=100$%.
    - If $E=100$% and $X=80$%, you will get $T=$ 10%p additional points on top of your exam grade $S=90$%.
    - If $E=100$% and $X=45$%, you may still fail the course because of the minimal requirement for passing the exam $X\geq 50$%.
    - If $E=60$%, no additional points will be awarded $T=0$.
    - If $E< 60$%, you will not be admitted to the exam.

**Final grade G (1,0 - 5,0)**

- The mapping from final score to final grade $S\mapsto G$ is determined after each exam, taking the overall difficulty of the exam into account.



## Communication

### Lecturer

- [Seong Joon Oh](../../member/joon/)

### Tutors

- [Arnas Uselis](../../member/arnas/)
- [Bálint Mucsányi](../../member/balint/)
- [Evgenii Kortukov](../../member/evgenii/)

### Central email

Please use the STAI group email `stai.there@gmail.com` to
- Submit your Colab exercises;
- Ask questions; and
- Send us feedback.

### Discord forum

For those who're registered for the course, ask the lecturer or tutors to add you to the Discord channel. We need your name and email address. Use it for

- Asking questions;
- Sending us feedback;
- Receiving official announcements; and
- Communicating others (e.g. finding partners).


## When & where

### Lecture & tutorial location

Hörsaal N09 (Hörsaalzentrum Morgenstelle)
https://goo.gl/maps/GYZPcZm7skgowqK78

### Lecture times

- Mondays
- 1st session: 08:15-09:00
- 5-min break: 09:00-09:05
- 2nd session: 09:05-09:50

### Tutorial times



### Exam dates and locations

- Exam 1: 10:00 - 11:30, Monday 12.02.2023 (may be updated), Location TBD
- Exam 2: 10:00 - 11:30, Monday 08.04.2023 (may be updated), Location TBD 


## Schedule & exercises

{{<table "table table-striped table-bordered">}}
|   #  	|   Date  	|   Content  	|   Exercises  	|
|---	|---	|---	|---	|
|   L1      |   16/10/2023   |   Introduction, OOD Generalisation (Definitions & evaluation)   |   Exercise 1 (Due:12.11.2023) - [Arnas](../../member/arnas/)  |
|   L2      |   23/10/2023   |   OOD Generalisation (Cue selection)   |   Exercise 0 recap - [Joon](../../member/joon/)  |
|   L3      |   30/10/2023   |   OOD Generalisation (Diversity)   |   -   |
|   L4      |   06/11/2023   |   OOD Generalisation (Adversarial attacks)   |   -   |
|   L5      |   13/11/2023   |   Explainability (Definitions & evaluation)   |   Exercise 2 (Due:10.12.2023) - [Evgenii](../../member/evgenii/)   |
|   L6      |   20/11/2023   |   Explainability (Feature attribution)   |   Exercise 1 recap - [Arnas](../../member/arnas/)  |
|   L7      |   27/11/2023   |   Explainability (Training data attribution)   |   -   |
|   L8      |   04/12/2023   |   Explainability (Foundational models)   |   -   |
|   L9      |   11/12/2023   |   Uncertainty (Definitions & evaluation)   |   Exercise 3 (Due:28.01.2024) - [Bálint](../../member/balint/)   |
|   L10      |   15/01/2024   |   Uncertainty (Aleatoric uncertainty)   |   Exercise 2 recap - [Evgenii](../../member/evgenii/)  |
|   L11      |   22/01/2024   |   Uncertainty (Epistemic uncertainty)   |   -   |
|   L12      |   29/01/2024   |   Uncertainty (Foundational models), Conclusion   |   -   |
|         |   05/02/2024   |   -   |   Exercise 3 recap - [Bálint](../../member/balint/)   |
{{</table>}}
