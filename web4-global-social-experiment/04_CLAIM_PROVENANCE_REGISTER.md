Claim Provenance Register

Repository: GFO-token
Module: web4-global-social-experiment
Status: Canonical Evidence Infrastructure
Version: 1.0.0

⸻

Purpose

Every factual statement, theoretical proposition, governance recommendation, legal assertion, educational claim, implementation proposal, or AI-generated synthesis within the Global Social Experiment must have traceable provenance.

The purpose of this register is to answer one question:

“Where did this claim come from?”

Without provenance:

* research cannot be reproduced;
* theory cannot be validated;
* governance cannot be audited;
* AI responses cannot be trusted;
* and future contributors cannot distinguish evidence from interpretation.

⸻

Core Principle

Every significant claim must map to:

Research Question
        ↓
Evidence
        ↓
Analysis
        ↓
Claim
        ↓
Consensus Status
        ↓
Legal Verification
        ↓
Repository Version

⸻

Claim Lifecycle

Observation
      │
      ▼
Candidate Claim
      │
      ▼
Evidence Collection
      │
      ▼
Researcher Review
      │
      ▼
LLM Delphi Review
      │
      ▼
Consensus / Dissent
      │
      ▼
Legal Verification
      │
      ▼
Canonical Claim
      │
      ▼
Publication

⸻

Claim Identifier Format

Every claim receives a permanent identifier.

Example

CLM-000001
CLM-000002
CLM-000003

Identifiers are never reused.

If a claim is retired, the identifier remains archived.

⸻

Claim Metadata

Each claim should contain:

claim_id:
title:
summary:
claim_type:
research_question:
repository_path:
repository_version:
author:
date_created:
last_modified:
status:
confidence:

⸻

Claim Types

Observation
Empirical Finding
Methodological Finding
Theoretical Proposition
Interpretive Claim
Governance Principle
Policy Recommendation
Implementation Recommendation
Educational Finding
Legal Statement
Technical Requirement
Future Research
Hypothesis
Negative Finding
Retired Claim

⸻

Claim Status

Draft
Under Review
Delphi Round 1
Delphi Round 2
Delphi Round 3
Consensus
Partial Consensus
Dissent
Rejected
Retired
Archived

⸻

Confidence Levels

Very High
High
Moderate
Low
Speculative

Confidence should never replace evidence.

⸻

Evidence Sources

Every claim should list supporting evidence.

Possible evidence:

Interview
Transcript
Repository Commit
Issue Discussion
Pull Request
Policy Document
Government Source
Academic Article
Technical Documentation
Book
Case Study
Observation
Experiment
Public Dataset
LLM Analysis
Independent Replication

⸻

Evidence Strength

Primary
Secondary
Supporting
Illustrative
Speculative

⸻

Research Question Mapping

Every claim maps to at least one research question.

Example

research_questions:
- PRQ1
- RQ36
- RQ45

⸻

Evidence Identifier Mapping

Evidence should also receive identifiers.

Example

EVD-000221
EVD-000222

A claim references evidence IDs instead of embedding large source material.

⸻

Consensus Mapping

Each claim references Delphi status.

Example

delphi:
    round1: consensus
    round2: consensus
    round3: consensus
    chatgpt_replication: matched

or

round1: disagreement
round2: partial
round3: dissent

⸻

Legal Verification Mapping

Every legal statement references the Legal Verification Register.

Example

legal_verification:
    verified: yes
    register_id: LEG-000112

If not verified:

verified: pending

⸻

Repository Version Mapping

Claims always identify the repository version.

Example

repository:
    version: 1.2.4
    release: v1.2.4

⸻

Publication Mapping

Each claim identifies where it appears.

Example

publications:
book
PhilArchive
conference
website
Substack
consulting

⸻

Example Claim

claim_id:
CLM-000021
title:
Modified multi-model Delphi improves governance review transparency.
claim_type:
Methodological Finding
research_questions:
RQ36
RQ40
RQ41
RQ48
evidence:
EVD-000011
EVD-000022
EVD-000028
confidence:
High
consensus:
Strong
legal:
Not Applicable
repository:
v1.0.0

⸻

Retired Claims

Claims are never deleted.

Instead:

status:
Retired
reason:
Superseded by evidence
replacement:
CLM-000442

⸻

Website Retrieval

When answering prompts:

The retrieval engine should first identify:

Relevant Question
↓
Relevant Claims
↓
Supporting Evidence
↓
Consensus
↓
Legal Status
↓
Response

This prevents unsupported summaries.

⸻

Relationship to Other Registers

Claim Provenance Register
        │
        ├── Evidence Register
        │
        ├── Consensus Register
        │
        ├── Dissent Register
        │
        ├── Legal Verification Register
        │
        └── Version History

⸻

Repository Principle

No significant statement should exist inside the repository without traceable provenance.

Every answer produced by the website should be capable of tracing its reasoning back through:

Question
↓
Claim
↓
Evidence
↓
Consensus
↓
Verification
↓
Repository Version

This register transforms the repository from a document archive into an auditable knowledge system that supports reproducibility, transparency, scholarly publication, and AI-assisted retrieval.