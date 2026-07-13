Evidence Register

Repository: GFO-token
Module: web4-global-social-experiment
Status: Canonical Evidence Infrastructure
Version: 1.0.0

⸻

Purpose

The Evidence Register is the canonical inventory of all evidence used throughout the Global Social Experiment.

Its purpose is to answer the question:

“What evidence supports this claim?”

Unlike the Claim Provenance Register, which traces statements, the Evidence Register catalogs the underlying source materials.

It enables:

* reproducibility;
* transparency;
* independent review;
* evidence-weighting;
* future updates;
* AI retrieval;
* and scholarly publication.

⸻

Evidence Lifecycle

Observation
      │
      ▼
Evidence Collection
      │
      ▼
Classification
      │
      ▼
Verification
      │
      ▼
Repository Storage
      │
      ▼
Research Use
      │
      ▼
Publication

⸻

Evidence Identifier

Every evidence item receives a permanent identifier.

Example

EVD-000001
EVD-000002
EVD-000003

Identifiers are never reused.

⸻

Required Metadata

Every evidence item should contain:

evidence_id:
title:
description:
evidence_type:
source:
repository_location:
date_collected:
collector:
verification_status:
confidence:
access_level:
license_status:
related_questions:
related_claims:

⸻

Evidence Categories

Documentary Evidence

Books
Academic Papers
Government Documents
Standards
Policies
Legal Opinions
Technical Documentation
Meeting Minutes
Public Reports
Repository Documents

⸻

Repository Evidence

Commits
Issues
Pull Requests
Discussion Threads
Release Notes
Change Logs
Schemas
Prompt Files
Configuration Files

⸻

Digital Evidence

Videos
Podcasts
Audio
Screenshots
Images
Web Pages
Archived Websites
Social Media Posts
Recorded Presentations

⸻

Human Evidence

Interviews
Focus Groups
Expert Review
Student Reflections
Research Notes
Observations

⸻

AI Evidence

LLM Outputs
Independent Model Reviews
Delphi Responses
Consensus Reports
Replication Studies
Prompt Logs

AI-generated content should always be labeled as AI-derived evidence rather than primary empirical evidence.

⸻

Evidence Verification Status

Unverified
Collected
Verified
Independently Verified
Superseded
Retired

⸻

Evidence Confidence

Very High
High
Moderate
Low
Unknown

Confidence reflects source reliability, not importance.

⸻

Access Levels

Public
Licensed
Restricted
Confidential
Internal
Archived

⸻

License Status

Public Domain
Open License
Creative Commons
Licensed
Institutional Permission
Private
Pending Permission

⸻

Evidence Strength

Primary
Secondary
Supporting
Illustrative
Background

⸻

Repository Location

Every evidence item identifies where it lives.

Example

repository_path:
evidence/interviews/
repository_file:
interview_004.md

⸻

Related Research Questions

Each evidence item should identify:

questions:
RQ36
RQ41
RQ45

⸻

Related Claims

Evidence links directly to claims.

Example

claims:
CLM-000041
CLM-000056

⸻

Example Evidence Record

evidence_id:
EVD-000112
title:
Round One Independent Delphi Responses
type:
AI Evidence
description:
Independent governance assessments produced before cross-model review.
verification:
Verified
confidence:
High
questions:
RQ36
RQ37
RQ38
claims:
CLM-000101
CLM-000102
repository:
delphi/round1/
license:
Internal

⸻

Evidence Updating

Evidence may receive updates.

Version history should preserve:

Original
Corrected
Expanded
Retired

Earlier versions remain archived.

⸻

Relationship to Claims

One evidence item may support many claims.

One claim may require many evidence items.

Evidence
↓
Claims
↓
Publications

⸻

Relationship to Publications

Evidence should identify where it appears.

used_in:
PhilArchive
Book
Conference
Website
Substack
Curriculum
Consulting

⸻

Website Retrieval

The retrieval system should prioritize evidence according to:

Verified Primary Evidence
↓
Independent Verification
↓
Supporting Evidence
↓
Illustrative Material
↓
Background Material

Evidence should be surfaced before summaries whenever practical.

⸻

Evidence Quality Checklist

Before an evidence item is relied upon, confirm:

* source identified;
* permissions documented;
* verification completed where appropriate;
* classification assigned;
* related questions identified;
* related claims identified;
* repository location recorded;
* and version history preserved.

⸻

Relationship to Other Registers

Evidence Register
        │
        ├── Claim Provenance Register
        │
        ├── Consensus Register
        │
        ├── Dissent Register
        │
        ├── Legal Verification Register
        │
        └── Version History

⸻

Canonical Principle

Evidence is the foundation of the repository.

Research questions organize inquiry.

Claims organize interpretation.

Evidence supports claims.

Consensus evaluates claims.

Legal verification evaluates legal assertions.

Version history preserves change.

The retrieval engine should always follow this chain:

Question
↓
Evidence
↓
Claim
↓
Consensus
↓
Verification
↓
Answer

By separating evidence from interpretation, the repository remains reproducible, transparent, extensible, and suitable for scholarly publication as well as AI-assisted public retrieval.