# Business AI Prompt Lab

A practical project demonstrating how Prompt Engineering can be applied to solve real-world business problems across Marketing, Human Resources, Finance, and Operations.

The project focuses on transforming business problems into structured AI tasks, designing controlled prompts, evaluating AI-generated outputs, refining prompts, and using human judgment before making business decisions.

## Overview

Business Prompt Engineering is not simply about writing longer prompts. The objective is to use Generative AI to support clearly defined business problems while maintaining human oversight.

This project demonstrates the complete workflow:

```text
Business Problem
       ↓
Required Information
       ↓
AI Task
       ↓
Prompt
       ↓
AI Output
       ↓
Human Review
       ↓
Business Decision
```

The project covers practical business scenarios involving marketing campaigns, recruitment, financial analysis, operational improvements, and cross-functional business problems.

## Objectives

The project aims to demonstrate the ability to:

* Convert business problems into clear AI tasks
* Design structured business prompts
* Apply Role, Context, Task, Constraints, Format, and Check
* Use Generative AI across multiple business functions
* Improve AI outputs through prompt refinement
* Evaluate AI recommendations for accuracy and feasibility
* Identify assumptions and information requiring verification
* Use AI as decision support rather than as a replacement for human judgment
* Create portfolio-ready business AI projects

## Business Prompt Framework

The core framework used in this project is:

```text
Role
  ↓
Context
  ↓
Task
  ↓
Constraints
  ↓
Output Format
  ↓
Verification / Check
```

### Role

Defines the professional perspective AI should use.

**Example:**

> Act as a marketing manager for a café located near a university.

### Context

Explains the business situation and relevant background.

**Example:**

> The café wants to increase weekday visits from college students aged 18–24.

### Task

Defines exactly what AI needs to accomplish.

**Example:**

> Create a 7-day promotional campaign.

### Constraints

Defines limitations and rules.

**Example:**

> Keep the total budget below ₹20,000 and avoid expensive influencer campaigns.

### Format

Defines how the output should be presented.

**Example:**

> Present the answer in a table with Day, Campaign Activity, Channel, Estimated Cost, and Expected Benefit.

### Check

Defines what needs to be verified or reviewed.

**Example:**

> Clearly identify any assumptions used.

## Business Applications

### Marketing

**Business Problem**

A café near a university wants to increase weekday visits from college students.

**AI Application**

Generate and structure a 7-day promotional campaign using a fixed budget and defined marketing channels.

Key considerations:

* Target audience
* Budget
* Campaign duration
* Marketing channels
* Expected benefits
* Assumptions

---

### Human Resources

**Business Problem**

An e-commerce company needs to recruit a Digital Marketing Intern.

**AI Application**

Generate structured interview questions designed to evaluate:

* Communication
* Basic marketing knowledge
* Creativity
* Problem-solving
* Teamwork

The project also evaluates AI-generated questions for:

* Relevance
* Repetition
* Ambiguity
* Potential bias
* Suitability for the role

AI can assist recruitment, but the final hiring decision remains a human responsibility.

---

### Finance

**Business Problem**

A café needs a simple monthly financial analysis.

**Input Data**

| Item           |    Amount |
| -------------- | --------: |
| Revenue        | ₹5,00,000 |
| Rent           |   ₹80,000 |
| Salaries       | ₹1,50,000 |
| Ingredients    | ₹1,20,000 |
| Electricity    |   ₹25,000 |
| Marketing      |   ₹20,000 |
| Other Expenses |   ₹30,000 |

**AI Task**

Calculate:

1. Total expenses
2. Profit
3. Profit margin

The calculations are independently verified before being used for analysis.

### Verified Calculation

```text
Total Expenses = ₹4,25,000

Profit = ₹75,000

Profit Margin = 15%
```

The workflow follows:

```text
AI Analysis
     ↓
Verification
     ↓
Human Review
     ↓
Business Decision
```

---

### Operations

**Business Problem**

An online retailer is receiving complaints about:

* Late deliveries
* Damaged packaging
* Wrong products
* Slow refunds

**AI Application**

Analyze each problem and generate:

* Possible Cause
* Business Impact
* Recommended Action
* Suggested KPI

Example KPIs include:

| Problem          | KPI                            |
| ---------------- | ------------------------------ |
| Late delivery    | On-time delivery rate          |
| Damaged products | Damage rate                    |
| Wrong products   | Order accuracy rate            |
| Slow refunds     | Average refund processing time |

## Cross-Functional Business Case

The project also applies prompt engineering to a fictional online fashion retailer, **StyleHub**.

### Marketing

Problem:

> Low repeat purchases.

AI can assist with customer-retention strategies.

### HR

Problem:

> Customer-service employees require better training.

AI can assist with training-plan development.

### Finance

Problem:

> Management wants to reduce unnecessary costs.

AI can assist with expense analysis.

### Operations

Problem:

> Customers are experiencing delivery delays.

AI can assist with identifying possible causes and operational improvements.

## Prompt Evaluation Framework

Every important AI response is evaluated using:

### Business Relevance

Does the response solve the actual business problem?

### Accuracy

Are the facts and calculations correct?

### Feasibility

Can the recommendation realistically be implemented?

### Cost

Is the recommendation financially practical?

### Risk

Could the recommendation create additional problems?

### Ethics

Could the recommendation result in unfair treatment?

### Evidence

Which claims require external verification?

### Human Judgment

What should management decide after reviewing the AI output?

## AI Output vs Business Decision

A central principle of this project is:

```text
AI Recommendation ≠ Final Business Decision
```

For example, AI might recommend:

> Introduce a 20% discount.

Management should then evaluate:

* Impact on profit margin
* Affordability
* Customer targeting
* Campaign objective
* Whether a smaller discount could achieve the same goal

AI provides **decision support**.

Management remains responsible for the **final decision**.

## Prompt Improvement

Prompts are improved iteratively rather than assuming the first response is perfect.

### Version 1

> Create a marketing campaign for a café.

### Version 2

> Create a marketing campaign for a café targeting college students.

### Version 3

> Act as a marketing manager for a café near a university. Create a 7-day promotional campaign targeting students aged 18–24. Keep the total budget below ₹20,000 and present the campaign in a structured table.

The goal is not simply to make prompts longer. The goal is to make them **more precise and useful for the business problem**.

## Human-in-the-Loop Approach

This project follows a human-in-the-loop model:

```text
Business Problem
      ↓
AI Assistance
      ↓
Output Evaluation
      ↓
Verification
      ↓
Human Judgment
      ↓
Business Action
```

AI is used to generate ideas, organize information, analyze inputs, and support decision-making.

It is not treated as an autonomous decision-maker.

## Project Structure

```text
business-ai-prompt-lab/
│
├── README.md
│
├── marketing/
│   ├── business-problem.md
│   ├── prompt.md
│   ├── ai-output.md
│   └── evaluation.md
│
├── hr/
│   ├── business-problem.md
│   ├── prompt.md
│   ├── ai-output.md
│   └── evaluation.md
│
├── finance/
│   ├── financial-data.md
│   ├── prompt.md
│   ├── calculations.md
│   └── evaluation.md
│
├── operations/
│   ├── business-problem.md
│   ├── prompt.md
│   ├── ai-output.md
│   └── evaluation.md
│
└── portfolio/
    ├── prompt-version-1.md
    ├── prompt-version-2.md
    ├── evaluation.md
    └── final-recommendation.md
```

## Portfolio Evidence

Each business prompt should document:

```text
1. Business Problem
2. Prompt Version 1
3. AI Output
4. Evaluation
5. Prompt Version 2
6. Improved Output
7. Business Recommendation
8. Learning Reflection
```

The portfolio therefore captures not just the final prompt, but the reasoning and improvement process behind it.

## Responsible AI

AI-generated business outputs should not automatically be treated as factual or correct.

Important information should be independently verified, particularly:

* Financial calculations
* Market information
* Business statistics
* Legal requirements
* Performance data
* External sources

Confidential, private, or personal information should not be uploaded to unapproved AI systems.

## Tools & Technologies

* Generative AI
* Prompt Engineering
* Business Analysis
* Structured Prompting
* AI Output Evaluation
* Markdown
* Git
* GitHub

## Key Takeaways

* Business prompting should begin with a clearly defined problem.
* Good prompts provide relevant context and constraints.
* Structured output makes AI responses easier to analyze and use.
* AI can support Marketing, HR, Finance, and Operations.
* AI-generated calculations should be independently verified.
* Assumptions should not be treated as facts.
* Recommendations should be evaluated for feasibility, cost, risk, and ethics.
* AI should support business decisions rather than replace human accountability.
* A strong portfolio should demonstrate both prompt development and critical evaluation.

## Academic Context

This project was developed as part of a **Business Prompt Engineering** module focused on applying Generative AI to practical business problems.

## Author

**Gurkirat Singh Brar**

BBA FinTech & AI
Chitkara University

---

> **AI provides analysis and suggestions. Humans provide judgment, accountability, and the final business decision.**
