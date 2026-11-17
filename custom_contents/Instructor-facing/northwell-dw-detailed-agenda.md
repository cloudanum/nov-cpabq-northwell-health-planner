# Northwell Health: Data Warehousing with BigQuery (CPABQ / T-DWBQ-I) - Delivery Guide

**Dates:** Wednesday Nov 18 - Friday Nov 20, 2026 | **9:00 AM-5:00 PM US/Eastern** | **Microsoft Teams:** https://www.roi-links.com/teams-ROI-17475  
**Instructor:** Imran Ahmad, PhD (`imran@cloudanum.com`) | **Classroom:** https://www.skills.google/ilt/classrooms/38842  
**Day 3 Evaluation (Protected 14:45-15:00 ET):** https://cloudlx.sjc1.qualtrics.com/jfe/form/SV_e2wogp4l1a2ByZL?qualtricsID=oylvffxykg

## Final Consolidated Course Package

- **Master Instructor Guide PDF (Slide-Above-Notes + Design Patterns + Kahoots + Handouts + All 11 Lab Guides):** [Northwell_CPABQ_Instructor_Complete_Guide.pdf](Northwell_CPABQ_Instructor_Complete_Guide.pdf)
- **Master Student Guide PDF (Slides + Design Patterns + Handouts + All 11 Lab Guides):** [Northwell_CPABQ_Student_Complete_Guide.pdf](../Student-facing/Northwell_CPABQ_Student_Complete_Guide.pdf)
- **Editable Instructor PowerPoint Decks (`M00`-`M11` + Design Patterns, with 8 Embedded YouTube Videos):** [slides/](slides/)
- **Interactive Animated Architecture Atlas (26 Inlined SVGs):** [Northwell_Animated_Architecture_Atlas.html](Northwell_Animated_Architecture_Atlas.html)
- **Customized Instructor Profile:** [instructor-profile.pdf](instructor-profile/instructor-profile.pdf) | [instructor-profile.docx](instructor-profile/instructor-profile.docx)
- **Six Live Course Kahoots (60 Questions):** [kahoots/README.md](kahoots/README.md)
- **Captioned Lab Walkthrough Videos (11 MP4s) & Trainer Prep Links:** [lab-walkthroughs/practice-lab-links.md](lab-walkthroughs/practice-lab-links.md)
- **Cohort Survey & Live Lab Tracker:** https://survey.anum.cloud ([Google Sheet](https://docs.google.com/spreadsheets/d/1gA36tgWXHf6m_zpWfhFy2IC8Mi-AsFjelbxSzivcr6g/edit?usp=sharing) | [Lab-Progress-Tracker.xlsx](Lab-Progress-Tracker.xlsx))

## Eight Embedded Course Videos (< 10 Minutes Each)

| Module | Day | Video Title | Duration | Watch Link |
|---|---|---|---|---|
| `M00` | Day 1 | **BigQuery Roadmap: From SQL Queries to Machine Learning** | `5:53` | https://www.youtube.com/watch?v=SpgwyB6xGQc |
| `M01` | Day 1 | **How BigQuery Actually Works: Storage, Slots, and Shuffle** | `8:52` | https://www.youtube.com/watch?v=zuQ2niZNPlI |
| `M02` | Day 1 | **Partition, Cluster, Nest: BigQuery Layout Levers That Cut Costs 200x** | `9:22` | https://www.youtube.com/watch?v=Zor9Ec6I2Cc |
| `M03` | Day 2 | **Getting Data Into BigQuery: Every Door, Priced (Batch, Streaming, CDC)** | `7:55` | https://www.youtube.com/watch?v=QUYIYLjTCwM |
| `M05` | Day 2 | **Never Pay Twice: BigQuery Read Performance (Cache, MVs, Read Paths)** | `9:05` | https://www.youtube.com/watch?v=YdqdKXC1fYo |
| `M06` | Day 2 | **BigQuery Query Optimization: Read the Plan, Then Spend Less** | `8:48` | https://www.youtube.com/watch?v=WlfLBep53Hg |
| `M09` | Day 3 | **BigQuery Security: Share the Answer, Not the Table** | `7:34` | https://www.youtube.com/watch?v=5cBMICQVlZs |
| `M11` | Day 3 | **BigQuery ML: Train Where the Data Lives** | `9:37` | https://www.youtube.com/watch?v=MivHYd2kznU |

## Six Live Course Kahoots (`create.kahoot.it`)

| Slot | Title | Live Host URL |
|---|---|---|
| Day 1 AM (11:45 ET) | BigQuery Architecture & Dremel Internals | https://create.kahoot.it/details/2baa6d25-bf33-492f-b600-c24991d615c7 |
| Day 1 PM (16:45 ET) | Partitioning, Clustering & Nested Schemas | https://create.kahoot.it/details/c32114b7-9c8c-4d7c-83b1-328de432b818 |
| Day 2 AM (11:45 ET) | Healthcare Ingestion, MERGE & Time Travel | https://create.kahoot.it/details/9cd6f2b1-4ace-4c06-94fe-d679b10e0a2a |
| Day 2 PM (16:45 ET) | BI Acceleration, Joins & Query Tuning | https://create.kahoot.it/details/f6184e47-5845-4dad-994e-be289d6fc5cf |
| Day 3 AM (11:50 ET) | Editions FinOps, Reservations & Audit Logs | https://create.kahoot.it/details/a23a007b-5dc6-4d5b-a5e2-207497669572 |
| Day 3 PM (16:35 ET) | PHI Governance, Dataform & Responsible BQML | https://create.kahoot.it/details/5ca3bfe9-4afa-49ed-ba60-657fa903b633 |

## Three-Day Instructional Schedule (390 Instructional Min/Day)

### Day 1 - Wednesday, Nov 18: Architecture, Storage & Nested Grain
- `09:00-09:30` **M00:** Welcome, Classroom 38842 Setup, Privacy Guardrails + Embedded Video (`5:53`)
- `09:30-10:30` **M01:** Colossus, Jupiter, RAM Shuffle & Dremel Execution Details
- `10:30-10:45` Break
- `10:45-11:30` **Lab 01 (`398` / Focus `295207`):** Using BigQuery to do Analysis
- `11:30-12:00` M01 Shuffle Review, Embedded Video (`8:52`) + **Kahoot 1A (10 Qs)**
- `12:00-13:00` Lunch
- `13:00-14:15` **M02 (Part 1):** Partitioning & Clustering Physical Design
- `14:15-14:30` Break
- `14:30-15:30` **Lab 02 (`2014` / Focus `295208`):** Creating Partitioned and Clustered Tables
- `15:30-16:15` **M02 (Part 2):** Nested `ARRAY<STRUCT>` Encounter Grain & Native `JSON`
- `16:15-16:45` **Lab 03 (`1897` / Focus `295209`):** Working with JSON and Array Data 2.5
- `16:45-17:00` Embedded Video (`9:22`) + **Kahoot 1B (10 Qs)**

### Day 2 - Thursday, Nov 19: Ingestion, DML, BI Acceleration & Query Tuning
- `09:00-09:15` Day 1 Recap
- `09:15-10:15` **M03:** Batch, Storage Write API, BigLake & Schema Contracts + Embedded Video (`7:55`)
- `10:15-10:30` Break
- `10:30-11:15` **Lab 04 (`349` / Focus `295210`):** Ingesting New Datasets into BigQuery v1.5
- `11:15-12:00` **M04:** Idempotent `MERGE`, SCD2, Time Travel + **Kahoot 2A (10 Qs)**
- `12:00-13:00` Lunch
- `13:00-13:45` **M05:** Cache, Smart-Tuned Materialized Views, BI Engine & Looker + Embedded Video (`9:05`)
- `13:45-14:30` **Lab 05 (`2015` / Focus `295211`):** Working with BI Engine and Looker
- `14:30-14:45` Break
- `14:45-16:00` **M06:** Execution Graph, Broadcast vs Hash Joins, Skew & Window Rewrites + Embedded Video (`8:48`)
- `16:00-16:45` **Lab 06 (`1662` / Focus `295212`):** Optimizing Queries - Beginner (plus self-paced `1663` & `1661`)
- `16:45-17:00` **Kahoot 2B (10 Qs)**

### Day 3 - Friday, Nov 20: FinOps, Observability, Security, Dataform & Responsible BQML
- `09:00-09:15` Day 2 Recap
- `09:15-10:15` **M07:** Editions Slot Autoscaling, Reservations & FinOps Guardrails
- `10:15-10:30` Break
- `10:30-11:15` **M08:** Regional `INFORMATION_SCHEMA`, Jobs Explorer & Cloud Audit Log Sinks
- `11:15-12:00` **Lab 09 (`2050` / Focus `295215`):** Cloud Logging and Monitoring + **Kahoot 3A (10 Qs)**
- `12:00-13:00` Lunch
- `13:00-13:45` **M09:** Group IAM, Authorized Views, RLS, Dynamic Masking & CMEK + Embedded Video (`7:34`)
- `13:45-14:30` **Lab 10 (`152` / Focus `295216`):** Creating a BigQuery Authorized View
- `14:30-14:45` Break
- `14:45-15:00` **Protected Course Evaluation** (`15 min`)
- `15:00-15:30` **M10:** Dataform SQLX DAGs & Gatekeeper Assertions
- `15:30-15:50` **M11:** Responsible BQML (`AI.FORECAST`, Splits & Explainability) + Embedded Video (`9:37`, self-paced `1905`)
- `15:50-16:35` **Capstone Workshop:** Synthetic Regional Capacity & Access Architecture Defense (`45 min`)
- `16:35-17:00` **Championship Kahoot 3B (10 Qs)** & Course Close
