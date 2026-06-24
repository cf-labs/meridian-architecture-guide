# Project Meridian: System Architecture Visual Guide

**Contents**

1. [System Architecture & Tech Stack](#system-architecture--tech-stack)
2. [Data Ingestion Pipeline](#data-ingestion-pipeline)
3. [Deduplication & Ground-Truth Precision](#deduplication--ground-truth-precision)
4. [AI Enrichment & Custom Evals](#ai-enrichment--custom-evals)
5. [Database & API Contract Design](#database--api-contract-design)
6. [Frontend Architecture & Design System](#frontend-architecture--design-system)
7. [AI-Native Engineering Practices](#ai-native-engineering-practices)

## System Architecture & Tech Stack

![Project Meridian system architecture overview: four layers from source integrations through an AI-enriched processing pipeline and a managed Postgres data layer to the iOS app, a services layer for identity, location, data and access control, and notifications, the full tech stack inventory, and headline metrics (2 languages, 12 source integrations, 3 external service APIs, 0 custom servers or middleware, 420 automated tests, 96.4% geocode coverage).](images/page-1-dark.png)

## Data Ingestion Pipeline

![Four ingestion patterns. One normalized contract. Every source normalizes to a single canonical schema.](images/page-2-dark.png)

## Deduplication & Ground-Truth Precision

![Precision over recall by design. Tuned on a 157-pair hand-labeled ground truth.](images/page-3-dark.png)

## AI Enrichment & Custom Evals

![New events only. Closed-set classification. Evals built for our data, run on our data.](images/page-4-dark.png)

## Database & API Contract Design

![API-ready data layer. Row-level security. Schema designed for multi-consumer access.](images/page-5-dark.png)

## Frontend Architecture & Design System

![40+ components. Atomic hierarchy. Accessibility-first. WCAG 2.1 AA compliant.](images/page-6-dark.png)

## AI-Native Engineering Practices

![Spec-driven development orchestrates AI-native agentic engineering.](images/page-7-dark.png)
