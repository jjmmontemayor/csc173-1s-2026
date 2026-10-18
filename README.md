# CSC173 — Intelligent Systems

**First Semester, AY 2026–2027** · Mindanao State University–Iligan Institute of Technology
College of Computer Studies · Department of Computer Science

## Contents

1. [Course Information](#1-course-information)
2. [Course Learning Outcomes](#2-course-learning-outcomes)
3. [Alignment with Program Outcomes](#3-alignment-with-program-outcomes)
4. [Learning Plan](#4-learning-plan)
5. [Assessment and Grading](#5-assessment-and-grading)
6. [Repository and Submission Requirements](#6-repository-and-submission-requirements)
7. [Learning Resources](#7-learning-resources)
8. [Classroom and Assessment Policies](#8-classroom-and-assessment-policies)
9. [Grade Conversion and CLO Attainment](#9-grade-conversion-and-clo-attainment)

---

## 1. Course Information

| Item | Details |
|---|---|
| Course Code | CSC173 |
| Course Title | Intelligent Systems |
| Credits | 3 units |
| Prerequisite / Co-requisite | CSC171 / None |
| Scheduled instruction | Two 1.5-hour classroom meetings per week |
| Modality | Classroom instruction supported by asynchronous readings, notebooks, and repository-based activities |
| Learning-plan period | October 13 – December 11, 2026 |
| Midterm assessment window | November 9–13, 2026 (exact event date to be confirmed) |
| Final assessment window | December 7–11, 2026 (subject to the official university schedule) |
| Instructor | Jennifer Joyce M. Montemayor |
| Course-materials repository | `csc173-1s-2026` |

### Course Description

This course introduces the foundations and practical development of intelligent systems, emphasizing neural networks, deep learning, sequence modelling, attention mechanisms, and Transformers. Students investigate how models learn from data, implement and evaluate small deep-learning applications, and use pre-trained Transformer models for focused tasks.

The course develops conceptual understanding, practical implementation skills, and responsible professional practice through individual programming activities, a group Transformer project presented at an international event, and an individual final project documented on GitHub.

### Course Scope

The course prioritizes:

- Neural-network and model-development foundations.
- Training, validation, testing, optimization, and evaluation.
- Sequence modelling and attention.
- Practical use of pre-trained Transformers.
- Introductory CNNs and transfer learning.
- Responsible AI, reproducibility, and technical communication.

Detailed GAN implementation, advanced detection and segmentation, extensive RNN/LSTM/GRU programming, and training Transformers from scratch are **enrichment topics**, not required assessed units.

## 2. Course Learning Outcomes

At the end of the course, students should be able to:

| CLO | Domain | Course Learning Outcome |
|---|---|---|
| CLO1 | Cognitive / Knowledge | Analyze the fundamental concepts, architectures, and optimization techniques of deep learning in selecting appropriate intelligent-system solutions for a given problem. |
| CLO2 | Psychomotor / Skills | Develop, train, and evaluate deep-learning models using appropriate datasets, programming tools, and performance metrics to address real-world problems. |
| CLO3 | Affective / Attitude | Demonstrate responsible, ethical, and self-directed practice in the development and use of intelligent systems, considering bias, privacy, social impact, and continuous learning. |

## 3. Alignment with Program Outcomes

| Program Outcome | CLO1 | CLO2 | CLO3 |
|---|:---:|:---:|:---:|
| PO1: Apply computing and mathematical knowledge appropriate to Computer Science | ✓ | ✓ | |
| PO2: Analyze a problem and identify its computing requirements | ✓ | ✓ | |
| PO3: Apply mathematical foundations, algorithmic principles, and theory while considering design trade-offs | ✓ | ✓ | ✓ |
| PO4: Apply design and development principles in constructing software systems in accordance with applicable standards | | ✓ | ✓ |

## 4. Learning Plan

### 4.1 Weekly Plan

Date ranges are instructional weeks, not exact meeting dates. 

| Week / Dates | Topics and Lesson Learning Outcomes | Classroom Activities | Resources | Individual Assessment | Group / Project Assessment | CLOs |
|---|---|---|---|---|---|---|
| 1: Oct 13–16 | Review models, neural networks, training, and inference. Explain sequences, tokens, context, and attention. | Meeting 1: TensorFlow notebook review and sequence examples. Meeting 2: attention intuition, Transformer overview, and guided pipeline demonstration. | Course lecture and TensorFlow notebook; attention diagrams; Transformer introductory materials | Short diagnostic check; Transformer exploration begun in class | Form groups and receive midterm brief; identify candidate tasks | 1, 2, 3 |
| 2: Oct 19–23 | Explain loss, optimization, normalization, train/validation/test splits, and overfitting; interpret model results. | Guided model experiment; learning-curve interpretation; comparison of predictions and errors | Instructor notebook; selected *Deep Learning* sections; TensorFlow/Keras documentation | **PA1:** neural-network training and evaluation | Submit group concept note, roles, data source, and selected model for approval | 1, 2, 3 |
| 3: Oct 26–30 | Explain tokenization, embeddings, self-attention, positional information, and Transformer task families; distinguish inference from fine-tuning. | Guided text-classification workflow; testing contrasting inputs; error discussion | Transformer starter notebook; Hugging Face introductory course and documentation | **PA2:** pre-trained Transformer exploration | Implement group prototype; document model, input data, and evaluation plan | 1, 2, 3 |
| 4: Nov 2–6 | Evaluate a Transformer application systematically and communicate its limitations. | Task-specific evaluation workshop; technical checkpoint; presentation rehearsal | Evaluation templates; model documentation; midterm rubric; responsible-AI checklist | Brief individual explanation of model/task and assigned contribution | Submit runnable prototype, results table, limitations section, and draft slides | 1, 2, 3 |
| 5: Nov 9–13 | Present and defend a Transformer application; demonstrate individual understanding of group work. | International presentation or equivalent course presentation; individual technical checks; feedback | Group repository, presentation materials, and rubric | Individual contribution statement, reflection, oral check, and confidential peer evaluation | **Midterm Group Transformer Project and International Presentation** | 1, 2, 3 |
| 6: Nov 16–20 | Explain CNNs and transfer learning; formulate a feasible individual final-project plan. | CNN/transfer-learning demonstration; guided image-classification activity; proposal consultation | CNN notebook; framework tutorials; proposal template | **PA3:** CNN/transfer-learning activity; **individual final-project proposal** | Midterm feedback informs (but is not regraded as) the final proposal | 1, 2, 3 |
| 7: Nov 23–27 | Implement an individual project and compare results against a baseline or documented reference approach. | Project workshop; experiment planning; error analysis; consultation | Approved datasets; framework/model documentation; experiment-log template | Individual development milestone: working code, initial results, and progress log | — | 1, 2, 3 |
| 8: Nov 30–Dec 4 | Refine evaluation, document reproducibility, and analyze responsible-use limitations. | Repository review; peer feedback; technical consultation; presentation preparation | Documentation template; reproducibility checklist; project rubric | Final documentation/code submission target: **December 4** (exact deadline to be confirmed) | — | 1, 2, 3 |
| 9: Dec 7–11 | Demonstrate integrated knowledge, practical competence, and responsible project judgment. | Individual final presentations or recorded demonstrations with checks; supervised final examination | All course materials; final-project and exam rubrics | **Final presentation and final examination** | Course completion and feedback | 1, 2, 3 |

### 4.2 Benchmark and Target

- **Benchmark:** a minimum average of 70% on the evidence assigned to each CLO.
- **Target:** at least 70% of the class reaches the benchmark for each CLO.

CLO attainment and the overall passing grade are separate measures. CLO evidence is tracked through specific quiz items, programming-rubric criteria, and project criteria, not through each assessment's total score.

## 5. Assessment and Grading

### 5.1 Grading Scheme

| Assessment Component | Mode | Weight |
|---|---|---:|
| Class Participation and Learning Engagement | Individual | 10% |
| Midterm Group Transformer Project and International Presentation | Group product with individual accountability | 15% |
| Programming Assignments | Individual | 20% |
| Final Project Proposal | Individual | 10% |
| Final Project Development | Individual | 10% |
| Final Project Documentation and Code | Individual | 15% |
| Final Project Presentation | Individual | 5% |
| Final Examination | Individual | 15% |
| **Total** | | **100%** |

### 5.2 Class Participation and Learning Engagement — 10%

| Evidence | Course Weight |
|---|---:|
| In-class concept checks and application activities | 4% |
| Exit tickets and brief learning reflections | 3% |
| Constructive peer feedback and documented response to feedback | 3% |
| **Total** | **10%** |

You may demonstrate engagement through written responses as well as spoken participation. Attendance alone does not earn the full engagement score. Technical work already scored in an assignment or project is not counted again here.

### 5.3 Individual Programming Assignments — 20%

| Assignment | Required Work | Target Deadline | Course Weight |
|---|---|---|---:|
| PA1: Neural-Network Training and Evaluation | Complete or extend the assigned TensorFlow demo; document dataset splits; compare one controlled change; interpret results | October 23 | 6% |
| PA2: Transformer Exploration | Use a pre-trained model; evaluate supplied and student-selected inputs; explain inference and limitations | October 30 | 6% |
| PA3: CNN / Transfer Learning | Run a guided image-classification workflow; report appropriate metrics and error examples | November 20 | 8% |
| **Total** | | | **20%** |

The earlier TensorFlow assignment may serve as the starting artifact for PA1.

#### Common Programming Rubric

| Criterion | Share of Assignment Score |
|---|---:|
| Correct, runnable implementation | 30% |
| Appropriate data preparation and workflow | 20% |
| Evaluation and interpretation | 25% |
| Explanation, limitations, and responsible-use considerations | 15% |
| Reproducibility and documentation | 10% |
| **Total** | **100%** |

### 5.4 Midterm Group Transformer Project — 15%

Groups will implement a focused application using a pre-trained Transformer model or pipeline and present their work at the designated international event or an approved equivalent assessment.

Group arrangement for 41 students: nine groups of four and one group of five.

#### Required Scope

Each group must:

1. Define one feasible problem.
2. Identify the selected model and its intended task.
3. Use approved, non-sensitive input data.
4. Provide runnable code or a notebook.
5. Evaluate results systematically.
6. Document errors, limitations, and responsible-use concerns.
7. Present findings clearly.
8. Provide evidence of each member's contribution.

State accurately whether you performed inference, fine-tuning, or another adaptation. Merely calling a hosted service does not demonstrate training a Transformer.

#### Midterm Rubric

| Criterion | Basis | Points |
|---|---|---:|
| Problem definition and appropriate model selection | Group | 1 |
| Implementation and reproducibility | Group | 3 |
| Evaluation and interpretation of results | Group | 2 |
| Documentation and responsible-AI analysis | Group | 2 |
| Presentation and technical communication | Group | 3 |
| Individual technical understanding | Individual | 2 |
| Individual contribution evidence and reflection | Individual | 2 |
| **Total** | | **15** |

Each student's score equals the shared group score (out of 11) plus their individual score (out of 4).

GitHub commits, contribution logs, authored files, oral explanations, and confidential peer feedback provide evidence of contribution. Commit count alone is not a measure of contribution quality.

#### Required Group Repository

```text
midterm-transformer-project/
├── README.md
├── roles-and-contributions.md
├── requirements.txt
├── notebooks/
├── data/
│   └── README.md
├── results.md
├── ethics-and-limitations.md
└── presentation/
    ├── slides.pdf
    └── presentation-link.md
```

Each student also submits an individual reflection in their own CSC173 repository:

```text
midterm/Lastname_Firstname_Midterm_Reflection.md
```

External acceptance, awards, rankings, and audience reactions do not determine the course grade. Students unable to participate in the event for legitimate reasons will be given an equivalent assessment route.

### 5.5 Individual Final Project — 40% Across Four Components

Each student will develop and evaluate a manageable intelligent-systems application.

A final project may extend the group midterm, but it must contain independently attributable new work, for example a different evaluation dataset, a baseline comparison, a justified model adaptation, or a systematic robustness/error analysis. Repackaging the unchanged group notebook is insufficient.

| Component | Required Evidence | Course Weight |
|---|---|---:|
| Proposal | Problem, dataset, model plan, baseline/reference approach, metrics, feasibility, risks, and timeline | 10% |
| Development | Working implementation, experiment log, preliminary results, feedback response, and documented progress | 10% |
| Documentation and Code | Reproducible repository, complete technical report, results, error analysis, limitations, citations, and AI-use declaration | 15% |
| Presentation | Clear individual explanation, demonstration, findings, limitations, and responses to questions | 5% |
| **Total** | | **40%** |

#### Final Documentation and Code Rubric

| Criterion | Share of Component Score |
|---|---:|
| Technical implementation and correctness | 30% |
| Evaluation, comparison, and error analysis | 30% |
| Documentation and reproducibility | 25% |
| Responsible-AI analysis, limitations, and attribution | 15% |
| **Total** | **100%** |

Final presentations may take the form of a short recorded demonstration followed by selected individual checks. If presentations are held live, a timetable will be published before the final week.

### 5.6 Individual Final Examination — 15%

The final examination assesses individual understanding of:

- Model selection for a given problem.
- Training, validation, testing, and inference.
- Interpretation of evaluation results and errors.
- Neural networks, sequence modelling, attention, and Transformers.
- Introductory CNNs and transfer learning.
- Responsible-AI reasoning.

Only material that was taught and practised will be examined. Questions include explanation, interpretation, and application, not just terminology recall.

## 6. Repository and Submission Requirements

### Individual Work

Submit written reflections, proposals, progress reports, and final documentation as Markdown files in your own CSC173 repository. Programming work must include notebooks or source files and instructions for running them.

```text
student-csc173-repository/
├── activities/
│   ├── pa01/
│   ├── pa02/
│   └── pa03/
├── midterm/
│   └── individual-reflection.md
└── final-project/
    ├── README.md
    ├── proposal.md
    ├── progress.md
    ├── requirements.txt
    ├── notebooks/
    ├── results/
    └── presentation-link.md
```

### Submission Evidence

For each assessed deliverable, submit:

- Repository or file URL.
- Commit hash identifying the submitted version.
- Any required presentation or notebook link.

Deadlines will specify date, time, and timezone.

> **Do not** place grades, confidential peer evaluations, private feedback, access credentials, or sensitive data in public repositories.

## 7. Learning Resources

### Primary Reference

Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep learning*. MIT Press.

Assigned selections support foundations, neural networks, optimization, sequence modelling, and practical methodology. The Week 1 reflection requires Chapter 1 only.

### Supporting Course Materials

- Instructor lectures and annotated notebooks in this repository (`csc173-1s-2026`).
- Instructor-prepared Transformer starter notebook.
- Official TensorFlow/Keras tutorials and documentation.
- Hugging Face introductory Transformer materials and model documentation.
- Selected *Dive into Deep Learning* attention and Transformer materials.
- Dataset and model documentation for each approved project.

Transformers are taught as a supplementary modern unit; they are not covered in the 2016 textbook.

## 8. Classroom and Assessment Policies

### Academic Integrity and AI-Assisted Work

Disclose any external code, datasets, models, and generative-AI assistance. You remain responsible for verifying and explaining your submissions.

Permitted assistance does not remove the requirement to demonstrate individual understanding. Unacknowledged copied work or fabricated results will be handled under applicable university policies.

### Responsible Data Use

Projects must avoid unauthorized use of personal, medical, or confidential data. Document dataset sources, permitted use, limitations, and relevant risks.

### Feedback and Milestones

Use proposal and development feedback to improve later work. Each stage assesses distinct evidence:

- **Proposal:** planning quality.
- **Development:** implementation progress and experimentation.
- **Final submission:** completed implementation and analysis.
- **Presentation:** communication and understanding.

### Access and Participation

Report computing, connectivity, or accessibility constraints early. Equivalent participation and submission arrangements may be approved where appropriate.

### Schedule Changes

Major assessment changes will be announced.

## 9. Grade Conversion and CLO Attainment

The overall passing rate is **60%**.

| Final Rate | Grade |
|---|---:|
| 95.64–100 | 1.00 |
| 91.18–95.63 | 1.25 |
| 86.73–91.17 | 1.50 |
| 82.27–86.72 | 1.75 |
| 77.82–82.26 | 2.00 |
| 73.36–77.81 | 2.25 |
| 68.91–73.35 | 2.50 |
| 64.45–68.90 | 2.75 |
| 60.00–64.44 | 3.00 |
| Below 60.00 | 5.00 |

---

*Prepared by Jennifer Joyce M. Montemayor · Revised October 13, 2026 · Subject to departmental approval and the official academic calendar.*
