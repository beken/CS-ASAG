# CS-ASAG

This repository contains a student answer dataset collected from Software Engineering and Computer Science courses for research on Automated Short Answer Grading (ASAG).

The dataset includes short-answer responses evaluated using both numerical scores and categorical labels. It is intended to support research on LLM-based and traditional ASAG methods, including analyses of grading agreement, prompt sensitivity, question types, and answer language.

## Dataset Overview

The dataset contains:

* 43 short-answer questions
* 517 student answers
* Questions from multiple courses, including Software Project Management, Web Programming, Natural Language Processing, and Concepts of Programming Languages
* Conceptual, coding, and calculation question types
* Answers in English and Turkish
* Human-assigned numerical grades and categorical labels

The student answers were evaluated by a human grader using a numerical scoring scale from 0 to 5 and categorical labels of correct, partially correct but incomplete, irrelevant, contradictory, and non-domain.

## Repository Structure

```text
SWE-ASAG/
├── data/
│   ├── dataset.xlsx
├── prompts/
│   ├── P1.txt
│   ├── P2.txt
│   ├── P3.txt
│   ├── P4.txt
│   └── P5.txt
├── results/
│   ├── RQ1/
│   ├── RQ2/
│   ├── RQ3/
│   ├── RQ4/
│   └── RQ5/
└── README.md
```

The `data` directory contains the dataset and `prompts` directory contains the grading prompts used in the experiments. The `results` directory contains analysis outputs, figures, and supplementary result files corresponding to the research questions investigated in the study.

## Associated Paper

This repository accompanies a manuscript currently under review. A link to the preprint will be added once it becomes available.
