Evidence Classification Method

Repository: GFO-token
Module: web4-global-social-experiment/methodology
Status: Canonical Research Methodology
Version: 1.0.0

⸻

Purpose

This document defines how evidence is identified, classified, evaluated, stored, and reused throughout the Global Social Experiment.

The methodology separates evidence from claims.

Evidence supports claims.

Claims interpret evidence.

This distinction preserves transparency, reproducibility, and scholarly rigor while improving AI-assisted retrieval.

⸻

Evidence Philosophy

Evidence is not limited to experimental measurements.

The repository recognizes that governance research may require:

* documentary evidence;
* qualitative evidence;
* repository activity;
* legal materials;
* educational artifacts;
* implementation records;
* and structured AI review.

Each evidence type receives explicit classification.

⸻

Core Principle

Every evidence item should answer:

“What exactly is this, and how should it be used?”

Classification determines:

* evidentiary weight;
* verification requirements;
* access permissions;
* publication suitability;
* and retrieval priority.

⸻

Evidence Lifecycle

Observation
↓
Collection
↓
Classification
↓
Verification
↓
Repository Storage
↓
Claim Support
↓
Publication
↓
Archival Preservation

⸻

Evidence Identifier

Each item receives a permanent identifier.

Example

EVD-000001
EVD-000002
EVD-000003

Identifiers remain stable even if metadata changes.

⸻

Primary Evidence Categories

Documentary Evidence

Examples

Academic Articles
Books
Government Publications
Repository Documents
Technical Standards
Policies
Legal Materials
Official Reports

⸻

Repository Evidence

Repository history is itself evidence.

Examples

Git Commits
Issues
Pull Requests
Release Notes
Version Changes
Discussion Threads
Schemas
Configuration Files

⸻

Human Evidence

Examples

Interviews
Observations
Expert Reviews
Workshop Notes
Student Reflections
Research Journals

Appropriate permissions are required.

⸻

Digital Evidence

Examples

Web Pages
Videos
Audio
Images
Archived Sites
Presentations
Podcasts
Recorded Demonstrations

⸻

AI-Derived Evidence

Examples

LLM Reviews
Consensus Reports
Replication Reviews
Prompt Logs
Model Comparisons
Structured Syntheses

AI-derived evidence should always remain distinguishable from empirical observations.

⸻

Evidence Strength

Evidence strength reflects the relationship between the source and the research question.

Primary
Secondary
Supporting
Illustrative
Background

Primary evidence receives priority whenever available.

⸻

Verification Levels

Evidence should receive one of the following statuses.

Collected
Verified
Independently Verified
Pending
Superseded
Retired

Verification requirements differ by evidence type.

⸻

Confidence Levels

Very High
High
Moderate
Low
Unknown

Confidence reflects source reliability—not the importance of the evidence.

⸻

Access Classification

Repository evidence may be classified as:

Public
Licensed
Restricted
Internal
Confidential
Archived

Access classification is independent of evidentiary strength.

⸻

Licensing Classification

Every evidence item should identify usage rights.

Examples

Public Domain
Open License
Creative Commons
Licensed
Institutional Permission
Private
Pending Permission

Licensing affects publication—not evidence quality.

⸻

Evidence Metadata

Each item should include:

evidence_id:
title:
description:
category:
subcategory:
source:
verification_status:
confidence:
access:
license:
collection_date:
collector:
repository_path:
related_questions:
related_claims:
repository_version:

⸻

Evidence Relationships

Evidence should reference:

Research Questions
Claims
Consensus
Dissent
Legal Verification
Publications

The repository forms a connected knowledge graph.

⸻

Evidence Weighting

When multiple evidence sources exist, retrieval should prioritize:

Verified Primary Evidence
↓
Independent Verification
↓
Repository Evidence
↓
Supporting Evidence
↓
Illustrative Material
↓
Background Context

Lower-ranked evidence should not override stronger evidence without explicit justification.

⸻

AI Evidence Rules

AI-derived evidence should always be labeled.

It should never be represented as:

* eyewitness testimony;
* experimental measurement;
* legal authority;
* or primary empirical observation.

AI evidence is analytical input.

⸻

Repository Evidence as Longitudinal Data

Repository activity itself becomes research evidence.

Examples include:

* issue discussions;
* governance revisions;
* prompt evolution;
* schema changes;
* release history;
* and policy refinement.

This allows the repository to function as both:

* research infrastructure;
* and research data.

⸻

Evidence Updating

Evidence records may be expanded over time.

The repository should preserve:

Original
Corrected
Expanded
Superseded
Archived

Earlier evidence should remain available for replication.

⸻

Quality Checklist

Before accepting evidence:

Confirm:

* source identified;
* permissions documented;
* classification assigned;
* verification completed where applicable;
* related questions identified;
* related claims identified;
* repository location recorded;
* repository version assigned.

⸻

Relationship to Other Methodology Files

Evidence Classification
        │
        ├── Research Design
        ├── Unknown Unknowns
        ├── Modified Delphi
        ├── Claim Provenance
        ├── Consensus
        ├── Dissent
        ├── Legal Verification
        ├── Replication
        └── Limitations

⸻

Relationship to Repository Registers

Evidence Classification Method
        │
        ├── Evidence Register
        ├── Claim Provenance Register
        ├── Consensus Register
        ├── Dissent Register
        ├── Legal Verification Register
        └── Version History

⸻

Website Retrieval

The backend retrieval engine should evaluate evidence before generating summaries.

Preferred sequence:

Question
↓
Evidence Classification
↓
Verification
↓
Claims
↓
Consensus
↓
Legal Verification
↓
Repository Version
↓
Answer

This reduces the likelihood that unsupported summaries replace traceable evidence.

⸻

Canonical Principle

Evidence is the foundation of every repository conclusion.

Classification allows researchers, reviewers, AI systems, and future contributors to distinguish:

* observation from interpretation;
* documentation from implementation;
* AI analysis from empirical evidence;
* public materials from licensed resources;
* and verified sources from preliminary observations.

The repository therefore preserves not only what evidence exists, but how that evidence should responsibly be interpreted and reused.