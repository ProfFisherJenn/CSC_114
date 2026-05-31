# CSC-114-InfoBot — Session 0 Testing Log

**Platform:** claude.ai Projects
**Date tested:** 05/31/26

| Test # | Input | Expected | Actual | Pass / Fail | Notes |
|---|---|---|---|---|---|
| 1 | "What are the office hours for the CSC-114 instructors?" | Quote syllabus: "Upon request (Summer)" | Per the Instructors section of the syllabus, both instructors hold office hours upon request during the summer term:

Mallory Milstead — ATC-113H · 910-678-8572 · milsteam@faytechcc.edu
Andrew Norris — ATC-113C · 910-486-3967 · norrisa@faytechcc.edu

Just reach out to either instructor directly to schedule a time!
| [P/F] | |

| 2 | "What's the GPA requirement to enroll in CSC-114?" 
| Fallback message — not in syllabus |That isn't in the CSC-114 syllabus. Please contact your instructor — Mallory Milstead (milsteam@faytechcc.edu) or Andrew Norris (norrisa@faytechcc.edu) — for clarification.
What I can tell you is that per the Course Description, the listed prerequisite is CSC-113.
| [P/F] | |
| 3 | "Is the final exam on July 15th?" | Should reject — final project is 7/20 per syllabus 
| Per the Class Schedule, there is no final exam listed. The last graded items are:
7/19/26 — Apply NLP and LLMs & Assess NLP and LLMs
7/20/26 — Final Project Submit
There is no mention of a final exam in the syllabus. Please contact your instructor — Mallory Milstead (milsteam@faytechcc.edu) or Andrew Norris (norrisa@faytechcc.edu) — for clarification on whether a final exam exists. 
| [P/F] | |

| Bonus Questions |
| 4 | "How many graded assignments are in this class?"
| Based on the Class Schedule, here's a breakdown of graded assignments (excluding the two 0-point items):
TypeCountQuizzes1Assignments12Total13
The total points possible add up to 1,201 points (noting that "Apply NLP and LLMs" is worth only 1 point, which may be a typo — you may want to confirm with your instructor).
| [P/F] | |
| 5 | What are the module objectives?
| That isn't in the CSC-114 syllabus. Please contact your instructor — Mallory Milstead (milsteam@faytechcc.edu) or Andrew Norris (norrisa@faytechcc.edu) — for clarification.

What the syllabus does include are the overall **Course Outcomes**, which are:

- Create a custom agent
- Demonstrate foundational knowledge of deep learning
- Apply AI frameworks including Keras and PyTorch
- Implement commonly used AI algorithms such as classification and regression
- Apply the machine learning workflow to train a small model
- Apply computer vision fundamentals
- Implement natural language processing algorithms
- Use and optimize large language models

Module-level objectives would likely be found in Canvas or Blackboard — check there first! | 
| [P/F] | |
## Reflection (3 sentences)
1. The thing that surprised me most was... 
    It surprised me that when the bot didn't have information, it still tried to provide what it thought was the most closely related information.
3. The bot did well at...
    Only providing information it had, and not hallucinating.
4. The bot needs work on...
    The bot needs more information on the course and course content than can be found in the syllabus. Currently this is a CSC-114 Syllabus Bot, not a full course bot. A course map that shows alignment of Course Outcomes to Module Objectives to Assessments could improve the bot's performance. 
