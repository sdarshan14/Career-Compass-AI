# CareerCompass AI

## Personalized Career Readiness Assessment and Growth Planning System for Engineering Students

---

## Overview

CareerCompass AI is a data-driven career guidance and student success analytics platform designed to help engineering students understand their current academic standing, evaluate career readiness, identify risk factors, and receive personalized growth roadmaps.

Unlike traditional career recommendation systems that focus only on interests, CareerCompass AI considers multiple real-world factors including:

- Department
- CGPA
- Backlogs
- Academic Performance
- Career Interests
- Placement Readiness

The system provides realistic and actionable guidance tailored to each student's current situation.

---

## Problem Statement

Many engineering students face challenges such as:

- Low CGPA
- Multiple Backlogs
- Lack of Career Direction
- Placement Anxiety
- Skill Gaps
- Uncertainty About Future Opportunities

Most career guidance platforms provide generic recommendations without considering academic constraints.

CareerCompass AI aims to bridge this gap by generating personalized career plans and recovery strategies based on a student's academic profile.

---

## Objectives

The primary objectives of this project are:

- Assess student career readiness.
- Analyze academic risk factors.
- Provide department-specific career recommendations.
- Generate personalized action plans.
- Suggest realistic career paths.
- Help students recover from academic setbacks.
- Improve placement readiness.

---

## Key Features

### Student Readiness Assessment

Evaluates:

- CGPA
- Backlogs
- Department
- Career Interests

---

### Career Readiness Score

Generates a score between:

```text
0 - 100
```

to measure overall placement and career readiness.

---

### Risk Classification

Students are categorized into:

```text
Excellent
Good
Needs Improvement
High Risk
```

---

### Department-Specific Recommendations

Provides tailored career options for:

- Computer Science Engineering
- Information Technology
- Electronics and Communication Engineering
- Electrical and Electronics Engineering
- Mechanical Engineering
- Civil Engineering
- Aerospace Engineering

---

### Personalized Career Guidance

Generates recommendations based on:

- Academic profile
- Current performance
- Career interests
- Placement readiness

---

### Recovery Roadmap

Provides:

- 3-Month Plan
- 6-Month Plan
- 12-Month Plan

with realistic milestones.

---

## Dataset Information

Dataset Name:

```text
CareerCompass_AI_Student_Dataset.csv
```

The dataset contains student records covering a wide range of academic situations.

---

## Dataset Features

| Feature | Description |
|----------|----------|
| StudentID | Unique Student Identifier |
| StudentName | Student Name |
| Department | Branch of Engineering |
| Year | Current Academic Year |
| CGPA | Current CGPA |
| Backlogs | Number of Active Backlogs |

---

## Backlog Classification System

| Backlogs | Category | Status |
|-----------|----------|----------|
| 0 | Excellent | No Academic Risk |
| 1-5 | Safe | Low Risk |
| 6-10 | Moderate Risk | Improvement Needed |
| 11-15 | High Risk | Immediate Attention Required |
| 16-20 | Very High Risk | Recovery Needed |
| 20+ | Critical Risk | Urgent Academic Intervention |

---

## Color Coding

| Category | Color |
|----------|---------|
| 0 Backlogs | Blue |
| 1-5 Backlogs | Green |
| 6-10 Backlogs | Yellow |
| 11-15 Backlogs | Orange |
| 16-20 Backlogs | Brown |
| 20+ Backlogs | Red |

---

## Career Readiness Score Calculation

The system calculates a Career Readiness Score using:

- Academic Performance
- Backlogs
- Risk Factors

Higher scores indicate stronger career readiness.

---

## Risk Assessment Levels

### Excellent

```text
80 - 100
```

Strong academic profile with high placement potential.

---

### Good

```text
60 - 79
```

Moderate readiness with scope for improvement.

---

### Needs Improvement

```text
40 - 59
```

Requires focused effort in academics and skill development.

---

### High Risk

```text
Below 40
```

Immediate intervention required.

---

## Department-Wise Career Recommendations

### Computer Science Engineering

Recommended Paths:

- Software Development
- Data Analytics
- Data Science
- Artificial Intelligence
- Cloud Computing
- Cybersecurity

---

### Electronics and Communication Engineering

Recommended Paths:

- Embedded Systems
- VLSI
- IoT
- Telecommunications
- Data Analytics

---

### Electrical and Electronics Engineering

Recommended Paths:

- Power Systems
- Electrical Design
- Automation
- Energy Analytics

---

### Mechanical Engineering

Recommended Paths:

- Manufacturing
- Design Engineering
- Quality Engineering
- Supply Chain Analytics
- Data Analytics

---

### Civil Engineering

Recommended Paths:

- Site Engineering
- Project Planning
- Construction Analytics
- GIS Analytics

---

### Aerospace Engineering

Recommended Paths:

- Aerospace Design
- Aircraft Maintenance
- Simulation Engineering
- Research
- Data Analytics

---

## Workflow

### Step 1

Load Student Dataset

---

### Step 2

Perform Data Validation

---

### Step 3

Generate Career Readiness Score

---

### Step 4

Classify Risk Level

---

### Step 5

Analyze Student Profile

---

### Step 6

Recommend Career Paths

---

### Step 7

Generate Personalized Roadmap

---

### Step 8

Export Career Report

---

## Visualizations

The project generates multiple charts.

### Student Distribution by Backlogs

Shows the academic risk distribution.

---

### CGPA Distribution

Analyzes academic performance trends.

---

### Career Readiness Distribution

Shows overall readiness levels.

---

### Department Analysis

Compares student performance across departments.

---

### Risk Level Analysis

Shows distribution across risk categories.

---

### Placement Readiness Analysis

Highlights overall employability trends.

---

## Example Input

```text
Department:
Mechanical Engineering

CGPA:
6.1

Backlogs:
4

Interest:
Data Analytics
```

---

## Example Output

```text
Career Readiness Score:
68

Risk Level:
Good
```

Recommended Career Paths:

```text
Manufacturing Engineer
Quality Engineer
Supply Chain Analyst
Data Analyst
```

---

## Sample 6-Month Action Plan

### Month 1

- Clear priority backlog subjects.

### Month 2

- Learn Excel.

### Month 3

- Learn SQL.

### Month 4

- Learn Python.

### Month 5

- Build Projects.

### Month 6

- Resume Preparation and Internship Applications.

---

## Technologies Used

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Environment

- Google Colab

### Version Control

- GitHub

---

## Project Structure

```text
CareerCompass-AI/
│
├── data/
│   └── CareerCompass_AI_Student_Dataset.csv
│
├── notebooks/
│   └── CareerCompass_AI_Career_Recovery_and_Growth_Planner.ipynb
│
├── charts/
│
├── reports/
│
├── src/
│
├── README.md
│
├── requirements.txt
│
├── LICENSE
│
└── .gitignore
```

---

## Future Enhancements

### Student Skill Assessment

Add:

- Excel Skills
- SQL Skills
- Python Skills
- Communication Skills

---

### Placement Probability Engine

Predict:

```text
Placement Probability
```

for every student.

---

### Resume Evaluation System

Analyze:

- Resume Quality
- ATS Compatibility

---

### Internship Recommendation Engine

Suggest:

- Internships
- Learning Resources
- Career Tracks

---

### AI Career Mentor

Provide conversational career guidance.

---

## Expected Outcomes

CareerCompass AI helps students:

- Understand their academic standing.
- Identify risk factors.
- Build realistic career plans.
- Improve placement readiness.
- Make informed career decisions.

---

## Author

Bhashyam Sree Darshan

---

## License

This project is intended for educational, analytical, and research purposes.
