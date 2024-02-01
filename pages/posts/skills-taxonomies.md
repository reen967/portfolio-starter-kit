---
title: Skills Taxonomies
date: 2024/01/30
description: Why we need them, what's out there, and other bits to consider.
tag: skills taxonomies
author: Arina
---

# Skills Taxonomies

<h1 style="color:blue;">A Blue Heading</h1>

A taxonomy is a classification system. A skills taxonomy provides a framework for understanding skills allowing us to assess:

- what people can do,
- what organizations need people to do,
- identify the people who can do those things,
- identify and recommend learning content.

In higher education skills taxonomies can help institutions assess prior learning, preventing learners from unnecessarily repeating material they are already competent in, and identify knowledge gaps to make recommendations on the learning materials that can be used to fill them.

In the workplace skills taxonomies can help employers in the recruitment process by identifying qualified candidates. They also serve to help employers identify current talent in their organization and develop personalized learning plans to upskill individuals with the potential to fulfill organizational needs.

Existing Skills Taxonomies

- [O*NET (Occupational Information Network)](https://www.onetonline.org/)
- [ESCO (European Skills, Competences, Qualifications and
Occupations)](https://esco.ec.europa.eu/en)

_tbh taxonomies are confusing and I'm not a data scientist so won't delve any further into the details._

I started this website as a sort of container of ideas. If you've stumbled across this, hi! Feel free to point out the flaws in my logic. Now onto the taxonomy. 

When I was working on Let Me Graduate (if you don't know about it, I suggest you read _this_. It's the anchor of my thought process and most of what I discuss can be traced back to what I wanted to achieve with the startup.)

We're really bad at understanding what people can do. We're also really bad at describing what we need from people to achieve what we're trying to do. Resumes are bad. Job descriptions are bad. Degrees aren't _actually_ useful ways of understanding the skills someone has acquired, nor are they equitable ways of doing so. It feels like everyone is trying to communicate and add value but doesn't have the language to do so, leading to a ton of misunderstanding and inefficiency.

Imagine this: you are an employer looking to hire a junior accountant and you receive three applications for the position. For the purpose of the exercise, this is all the information you have about the candidates:

- `Candidate #1` has a Bachelor of Accounting from the University of Southern California (USC)
- `Candidate #2` also has a Bachelor of Accounting from the University of Southern California (USC)
- `Candidate #3` has a Bachelor of Accounting from Southern New Hampshire University (SNHU)

How do you determine which candidate is best suited for the position? There's no way to do this based on the candidates' suitability for the role, so you'd have to draw from irrelevant information (the university where they earned their degree) to reach a conclusion.

The candidates all have the same degree (Bachelor of Science in Accounting.) `Candidate #1` and `Candidate #2` earned their degrees from the same university (USC), and `Candidate #3` earned their degree from SNHU. `Candidate #3` will likely be ruled out on the basis that SNHU's acceptance rate of 92.1% is much higher than USC's 12.5%, thereby it is a more prestigious university and must be better. This process uses the reasoning that prestige = competency. Not only is this reasoning flawed but there must be a better way. Other than the obvious inequity perpetuated by this type of reasoning, the employer misses out on identifying a candidate who may be much better suited to the role they are looking to fill.

Candidates are evaluated on prestige rather than competency and the employer still doesn't understand the skills gained from a Bachelor of Science in Accounting from either university.

Let's say you had a bit more information about the learning opportunities the candidates undertook to earn their degrees. 

`Candidate #1`, Bachelor of Science in Accounting, USC 
```js
- BUAD 280 Introduction to Financial Accounting
- BUAD 281 Introduction to Managerial Accounting
- BUAD 302 Communication Strategy in Business
- BUAD 304 Organizational Behavior and Leadership
- BUAD 306 Business Finance
- BUAD 307 Marketing Fundamentals
- BUAD 310g Applied Business Statistics
- BUAD 311 Operations Management
- **BUAD 351 Economic Analysis for Business Decisions**
- **BUAD 352 Macroeconomic Analysis for Business Decisions**
- BUAD 497 Strategic Management
- **MATH 118gx Fundamental Principles of Calculus**
- ACCT 370 External Financial Reporting Issues
- ACCT 371 Introduction to Accounting Systems
- ACCT 372 Internal Reporting Issues
- ACCT 373 Introduction to Auditing and Assurance Services
- ACCT 374 Introduction to Tax Issues
- ACCT 377 Valuation for Financial Statement Purposes
- ACCT 430 Accounting Ethics
- ACCT 470 Advanced External Financial Reporting Issues
- **ACCT 474 Tax Issues for Business Units**
- **ACCT 462 Detecting Fraudulent Financial Reporting**
```

`Candidate #2`, Bachelor of Science in Accounting, USC

```js
- BUAD 280 Introduction to Financial Accounting
- BUAD 281 Introduction to Managerial Accounting
- BUAD 302 Communication Strategy in Business
- BUAD 304 Organizational Behavior and Leadership
- BUAD 306 Business Finance
- BUAD 307 Marketing Fundamentals
- BUAD 310g Applied Business Statistics
- BUAD 311 Operations Management
- **ECON 351x Microeconomics for Business**
- **ECON 352x Macroeconomics for Business**
- BUAD 497 Strategic Management
- **MATH 125g Calculus I**
- ACCT 370 External Financial Reporting Issues
- ACCT 371 Introduction to Accounting Systems
- ACCT 372 Internal Reporting Issues
- ACCT 373 Introduction to Auditing and Assurance Services
- ACCT 374 Introduction to Tax Issues
- ACCT 377 Valuation for Financial Statement Purposes
- ACCT 430 Accounting Ethics
- ACCT 470 Advanced External Financial Reporting Issues
- **ACCT 473 Financial Statement Auditing**
- **ACCT 416 Financial Reporting and Analysis**
```

`Candidate #3`, Bachelor of Science in Accounting, SNHU

- Course Name
- Course Name
- Course Name
