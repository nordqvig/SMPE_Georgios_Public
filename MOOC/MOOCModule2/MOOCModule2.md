---
title: "MOOCModule2.rmd"
output: html_document
---
## Section 0:
Completed quiz 100%.

## Section 1: Examples of reproducibility issues

### Financial crisis 2008:
Reinhart and Rogoff published findings based on nonsensical calculations and questionable data-analysis that lead nations to adopt the "Foreign debt should not exceed 90% of GDP" idea. The article was cast aside by the academic community later, when it was shown to be erroneous, but the economic policies of the countries were already in place.

### Dead salmon MRI
Statistical programs commonly used had innate issues which has impacted research from the last 15 years.

Further examples (oncology, psychology) illuminate reproducibility issues from other scientific fields. Rigor and transparency must be present in academic research methodology, in order to avoid these issues moving forward.

Completed quiz

## Section 2: Difficulties during a replication attempt

### Lack of information:
- Lack of explanation of secrecy makes it harder for third party to verify findings.
- One must explain the thought-process behind decision-making during the research, as to avoid suspicion of wrongdoing by third parties.

### Uncontrolled computer usage:
- "point-and-click" software
- data interpretation (MARCH1 gene interpreted as date, 231009E13 interpreted as figure). "black box" programs are also problematic because they manipulate data without transparency
- Lack of strictness and organization
  - poor backup practices
  - poor version control mechanisms
- Cultural and social aspect
  - articles are kept short, often too short, so they can not possibly contain all that is required for good transparency

Facing some common criticisms of the "making everything publicly available" school of thought.
- It is better to expose your working so that others can find errors, rather than keeping it hidden (and wrong!) and not risk looking incompetent.
- If someone reuses your work they ought to properly credit you, not claim your work as their own. Then you shouldn't worry about your work being used by someone else without you being recognized.
- Data that should be anonymized can be protected by defining the people that can access it, and through cryptographic techniques.

## Section 3: The computational document
Main goal: transparency

An article does not tell the whole story behind its production. The computational document (notebook) bridges this gap.

## Section 4A: Getting started with Jupyter

Used the FUN hosted Jupyter notebook to follow the tutorial.

## Section 5: Working with others

Watched video and completed quiz. Personally, I prefer to use github/gitlab for version control and sustainable safekeeping.

## Section 6: Comparative study

The orgmode notebook is impressive! But I will subscribe to producing reproducible research using the Jupyter notebook, which I am already familiar with and is more than enough for my needs.

## Section 7: Installation
Jupyter notebook and github successfully configured.

## Section 8: Exercises

Challenger: See challenger.ipynb for finished solution.

*HW week2: Write a short text explaining what is good and wrong about this document (you may want to provide an updated 
version of the notebook) and upload on your github/gitlab space.*

My (updated) version of the notebook can be found in this directory (challenger.ipynb). The .pdf explaining the generalized 
linear model through the example of risk of suffering from an illness at a certain age is very illustrative. It exemplifies 
in what situations a GLM should be used, as opposed to an ordinary linear fit. Applying this thinking to the challenger
case was good to see this first-hand. It was tricky to find the mistake in the MOOC notebook (removing the successful launches)
but it did feel a bit strange when I first read it. After that was fixed, applying the GLM lead to the sought after conclusion.






