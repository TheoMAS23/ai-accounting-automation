# AI-Powered Accounting Automation

> AI and workflow automation for real-world accounting operations using **n8n, Generative AI and human-in-the-loop validation**.

## Overview

This project was created to reduce the manual effort involved in accounting reconciliation and transaction preparation.

It processes financial information from sources such as bank statements, spreadsheets and accounting documents, applies business rules and AI-assisted analysis, identifies exceptions that require human review, and prepares structured accounting entries for ERP import.

The solution is currently applied to processes involving **15 companies** in a real accounting environment.

## Impact

**Before:** 6+ hours of manual work
**After:** approximately 10 minutes with automation

The main goal is not only speed, but also:

* reducing repetitive manual work;
* improving consistency;
* identifying exceptions before ERP import;
* preserving human validation for uncertain cases;
* creating a more auditable accounting workflow.

## Main Workflow

```text
Financial Documents
        ↓
Data Extraction & Organization
        ↓
Deterministic Business Rules
        ↓
AI-Assisted Analysis
        ↓
Validation & Exception Detection
        ↓
Human Review when required
        ↓
Accounting Entry Generation
        ↓
ERP-Ready TXT Output
```

## Core Features

* Bank statement processing
* Spreadsheet and financial data organization
* Transaction classification
* Accounting reconciliation support
* Business-rule-based processing
* AI-assisted classification
* Exception and pending-item detection
* Human-in-the-loop approval
* Validation before output generation
* Structured accounting entry generation
* ERP-ready TXT output
* Continuous workflow testing and improvement

## AI & Automation Stack

### Automation

* **n8n**
* Workflow orchestration
* No-code / low-code automation

### Artificial Intelligence

* Generative AI
* AI Agents
* Prompt Engineering
* ChatGPT
* Claude / Claude Code
* OpenAI Codex

### Business Environment

* Financial spreadsheets
* Bank statements
* Accounting reconciliation
* **Domínio ERP**

## Architecture Principles

The project follows several principles designed for real business operations:

### Deterministic First

Whenever an accounting decision can be safely resolved through explicit business rules, deterministic logic is preferred.

AI is used primarily for cases where interpretation or contextual analysis is necessary.

### Human-in-the-Loop

Uncertain or exceptional situations are separated for human validation rather than automatically accepted.

### Validation Before Output

Entries are validated before generating the final ERP-ready file.

### Iterative Development

The system has evolved through multiple workflow versions, with improvements focused on:

* reliability;
* validation;
* exception handling;
* error reduction;
* workflow traceability.

## Example Processing Flow

```text
Bank Statement / Spreadsheet
            ↓
      Data Processing
            ↓
    Transaction Analysis
       ↙           ↘
Known Rule      Uncertain Case
    ↓                ↓
Automatic      AI Analysis /
Classification Human Review
       ↘           ↙
         Validation
             ↓
    Accounting Entries
             ↓
       ERP TXT File
```

## Privacy & Security

This repository is a **portfolio representation of the project**.

Production workflows, client files and confidential accounting information are intentionally not published.

No real client:

* names;
* CNPJs;
* bank statements;
* transactions;
* credentials;
* accounting documents;
* internal business rules;

are included in this public repository.

Any examples published here will use **synthetic or anonymized data**.

## Current Development

I am continuously improving both the project and my technical knowledge.

Current areas of study include:

* REST APIs
* JSON
* Git & GitHub
* Programming fundamentals
* Integration architecture

Python is planned as my next major programming focus.

## Project Status

**Active development**

The automation is already used in real accounting processes while new validations, integrations and reliability improvements continue to be developed.

## About Me

I'm **Théo Moron**, focused on **Applied AI, AI Automation, n8n and AI Agents**.

I currently work on AI and process automation initiatives inside an accounting firm, developing solutions aimed at reducing repetitive work and applying AI to real business processes.

[LinkedIn](https://www.linkedin.com/in/theo-moron-07904642b) · [GitHub Profile](https://github.com/TheoMAS23)

