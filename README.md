# Deceased-Debtor-Workflow-Case-Study
## Executive Summary
This anonymized case study is based on a real internal process improvement project in a financial-services environment.
The project focused on improving how deceased debtor cases were reported, validated, approved, and monitored between partner banks and an internal operations team. The original process relied on manual messages, scanned documents, email follow-ups, and direct status-code changes, which created risks around data mismatch, weak traceability, manual error, and possible misuse of fake supporting documents.
The proposed solution moved the process into a structured web-based workflow with partner-bank submission, document attachment, approval routing, internal validation, and final status update control.

> **Confidentiality Note**
> 
> 
> This repository does not include real company names, real customer data, internal system screenshots, production code, database structure, or confidential documents.
> 
> All examples, diagrams, and sample data are anonymized or synthetic.
>

## Business Context

In this environment, customers could access loans through partner banks. Their pension payment bank was locked in the internal system using a flagging code until the loan was completed.

The loan could be marked as completed when one of these conditions happened:

- The customer fully paid the loan
- The customer passed away
- The loan was transferred or closed through another approved process

When a customer passed away, the flagging status had to be opened so the insurance claim or benefit process could continue.

However, if the deceased customer still had an active loan flag, branch staff could not continue the claim process smoothly, especially when the heirs requested the payment through a different bank.

---

## Problem

The original process was too manual.

Branch staff or partner bank staff would send requests through messages or email, attach death certificates, and ask the internal team to update the flag status manually in the operating system.

This created several risks:

| Risk Area | Problem |
| --- | --- |
| Data accuracy | Debtor identity, bank information, or claim status could be mismatched |
| Document validity | Death certificates had to be checked manually |
| Fraud risk | Fake or invalid death certificates could be used to escape an active loan |
| Traceability | Requests were not always recorded in a structured workflow |
| Process control | Manual code changes depended too much on individual staff handling |
| Reporting quality | Different status codes could cause cases to be missing from the deceased debtor recap |

The original internal project document also identified that manual email-based reporting could create human error risks, including outdated partner-bank emails, wrong data delivery, and incorrect attachments.

---

## Project Goal

The goal was to improve the deceased debtor process by making it:

- More structured
- More traceable
- Easier to validate
- Less dependent on manual messages
- Safer from data mismatch and potential fraud
- Easier for partner banks and internal teams to monitor

---

## Proposed Solution

I proposed enhancing the existing web-based partner-bank portal with a dedicated deceased debtor workflow.

The workflow allowed partner banks to:

1. Search debtor data through the checking menu
2. Submit an open-flag request for deceased debtor cases
3. Attach the required death certificate
4. Send the request to partner-bank head office for review
5. Forward approved requests to the internal team
6. Allow the internal team to validate the data and attachment before final approval

The original project documented this flow: partner branches submit the request, partner head office approves it, and the internal team checks the data and attachment before approving the open flagging request. 

---

## Before vs After Process

### Before
<img width="340" height="747" alt="diagram" src="https://github.com/user-attachments/assets/64685cfd-c370-4df8-ade1-ea1ab45aef74" />

### After
<img width="299" height="551" alt="image" src="https://github.com/user-attachments/assets/e2b4d824-0498-421d-9d59-dc27987a8bb4" />

## Data Quality Controls

The workflow introduced stronger controls around data and document validation.

| Control | Purpose |
| --- | --- |
| Debtor identity checking | Ensures the submitted case matches the correct customer record |
| Partner bank validation | Moves the first validation step closer to the loan-owning bank |
| Document attachment requirement | Ensures the request is supported by formal evidence |
| Approval workflow | Reduces uncontrolled manual status changes |
| Separate deceased debtor reason code | Prevents deceased cases from being mixed with normal loan completion cases |
| Search and export feature | Supports monitoring, recap, and follow-up analysis |
| Request status tracking | Improves traceability and audit readiness |

---

## How This Project Follows the V.E.R.I.F.Y. Framework

| VERIFY Step | How It Appears in This Project |
| --- | --- |
| Validate | Debtor identity, bank information, claim status, and supporting documents are checked before approval. |
| Examine | Manual request handling, email follow-ups, document gaps, and status-code risks are reviewed. |
| Reconcile | Partner bank submissions are matched against internal debtor records and claim-related status information. |
| Identify Signals | Fake documents, mismatched debtor data, unsupported requests, and irregular status changes are treated as risk signals. |
| Flag and Escalate | Requests move through partner-bank and internal approval stages before final action. |
| Yield Standards | The workflow creates a repeatable process for deceased debtor validation, monitoring, and audit review. |

## My Role

My role was to identify the process issue, map the existing workflow, define the improvement opportunity, and propose the system-based workflow.

I worked on:

- Understanding the manual flagging and claim-related process
- Identifying data quality and fraud-risk gaps
- Mapping the before and after workflow
- Defining the required menu and approval flow
- Translating operational problems into system requirements
- Supporting a more structured reporting and validation process

---

## Methods Used

- Process mapping
- Root cause analysis
- Stakeholder interview
- Data quality risk review
- Workflow redesign
- Requirement definition
- Approval flow design
- Reporting and monitoring improvement

The original project used observation and interviews with data, IT, and partner-bank stakeholders to understand the existing workflow and identify what needed to be improved.

---

## Business Impact

This project helped improve the control of deceased debtor flagging by moving the process from manual request handling into a structured workflow.

Key business value:

- Reduced dependency on informal staff messages
- Improved traceability of open-flagging requests
- Reduced data mismatch risk
- Strengthened document validation before claim processing
- Improved audit readiness
- Helped prevent inaccurate or unsupported status-code changes
- Supported cleaner reporting for deceased debtor cases

---

## Skills Demonstrated

- Data quality control
- Data validation
- Process improvement
- Fraud risk awareness
- Financial data governance
- Reporting workflow design
- Stakeholder communication
- Requirement gathering
- Operational risk analysis
- Documentation accuracy

## Mockup UI

<img width="1700" height="925" alt="ChatGPT Image Jul 1, 2026, 10_15_29 PM" src="https://github.com/user-attachments/assets/cb794e46-c1c3-4246-812f-09d70a33a7eb" />

<img width="1746" height="901" alt="ChatGPT Image Jul 1, 2026, 10_22_23 PM" src="https://github.com/user-attachments/assets/6e226c7f-ef7f-4bf5-8fc8-1843825dba02" />




















