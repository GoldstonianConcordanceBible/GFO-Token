LLM Review Process

Repository: GFO-token
Module: web4-global-social-experiment/methodology
Status: Canonical Methodology
Version: 1.0.0

⸻

Purpose

This document defines how large language models (LLMs) participate in the Global Social Experiment as structured analytical reviewers.

The process is designed to maximize transparency while minimizing common sources of bias, including anchoring, prompt contamination, orchestration effects, and unsupported factual claims.

LLMs are used to generate critiques, identify gaps, compare governance approaches, and propose revisions. They are not treated as authoritative experts or independent sources of empirical evidence.

⸻

Reviewer Role

Each participating model serves as a structured reviewer.

Reviewer responsibilities include:

* identifying missing governance controls;
* evaluating methodological consistency;
* identifying implementation risks;
* proposing repository improvements;
* highlighting unclear terminology;
* distinguishing observation from interpretation;
* identifying possible legal issues;
* and documenting uncertainty.

Reviewers should avoid presenting speculation as established fact.

⸻

Reviewer Independence

Independent review is the foundation of the methodology.

During the first review round:

* reviewers receive the same research materials;
* reviewers do not receive other model outputs;
* reviewers produce complete independent assessments;
* and all outputs are preserved without modification.

Repository Draft
↓
Reviewer A
Reviewer B
Reviewer C
Reviewer D
↓
Independent Reviews

⸻

Prompt Discipline

To reduce unnecessary variability:

* prompts should clearly define reviewer responsibilities;
* instructions should distinguish analysis from implementation;
* legal claims should be labeled as requiring verification;
* reviewers should identify confidence where appropriate;
* and reviewers should explicitly acknowledge uncertainty when evidence is limited.

Prompt changes should be documented within the repository.

⸻

Cross-Model Review

Beginning in Round Two:

reviewers receive:

* anonymized summaries;
* identified areas of agreement;
* unresolved disagreements;
* and selected methodological observations.

Reviewers reconsider—but are not required to change—their earlier conclusions.

The objective is reflection rather than forced convergence.

⸻

Controlled Replication

Following the primary Delphi rounds:

a separately controlled reviewer may independently evaluate:

* repository architecture;
* governance framework;
* methodological approach;
* unresolved issues;
* and overall coherence.

Replication helps determine whether conclusions remain stable when evaluated outside the primary synthesis process.

⸻

Reviewer Outputs

Each review should include:

Executive Summary
Strengths
Weaknesses
Missing Controls
Governance Recommendations
Methodological Concerns
Legal Observations
Implementation Risks
Future Research

Outputs should remain available for future replication.

⸻

Confidence Statements

Reviewers should distinguish:

High Confidence
Moderate Confidence
Low Confidence
Speculative

Confidence reflects reviewer assessment—not factual certainty.

⸻

Hallucination Risk

The methodology explicitly recognizes that LLMs may:

* fabricate citations;
* misidentify legislation;
* overstate confidence;
* invent technical capabilities;
* merge unrelated concepts;
* or generate unsupported summaries.

Reviewer outputs therefore require:

* provenance;
* evidence mapping;
* and independent verification where appropriate.

⸻

Legal Claims

Legal statements generated during review require separate verification.

Reviewers should distinguish:

Enacted Law
↓
Proposed Legislation
↓
Agency Guidance
↓
Commentary
↓
Repository Interpretation

The protocol prohibits treating these categories as interchangeable.

⸻

Research Question Mapping

Reviewer comments should reference applicable research questions whenever practical.

Example:

questions:
RQ41
RQ44
RQ94
RQ123

This improves traceability and later retrieval.

⸻

Claim Mapping

Reviewer recommendations should map to candidate claims rather than becoming policy automatically.

Reviewer Observation
↓
Candidate Claim
↓
Evidence Review
↓
Consensus Review
↓
Repository Decision

⸻

Consensus and Dissent

Reviewer agreement is recorded in the Consensus Register.

Reviewer disagreement is preserved in the Dissent Register.

Neither outcome automatically changes repository policy.

⸻

Repository Editor Responsibilities

Repository editors:

* evaluate reviewer recommendations;
* compare supporting evidence;
* verify legal statements;
* determine whether repository revisions are justified;
* preserve rejected recommendations;
* and document change rationale.

Editors—not reviewers—approve canonical updates.

⸻

Data Preservation

The repository should retain:

* original prompts;
* reviewer identities;
* timestamps;
* outputs;
* synthesized summaries;
* change recommendations;
* and publication mappings.

Historical reviewer outputs should remain accessible whenever possible.

⸻

Ethical Considerations

The review process should:

* disclose AI participation;
* distinguish AI from human review;
* preserve attribution;
* avoid deceptive representation;
* protect confidential information;
* and respect licensing restrictions.

⸻

Methodological Limitations

The review process is limited by:

* prompt sensitivity;
* model updates;
* training-data overlap;
* incomplete domain knowledge;
* lack of external accountability;
* inability to independently verify all factual claims;
* and changing legal and technical environments.

These limitations should accompany every major publication.

⸻

Relationship to Other Methodology Files

LLM Review Process
        │
        ├── Research Design
        ├── Unknown Unknowns
        ├── Modified Delphi
        ├── Claim Provenance
        ├── Evidence Classification
        ├── Consensus
        ├── Dissent
        ├── Legal Verification
        ├── Replication
        └── Limitations

⸻

Relationship to Publications

PhilArchive Article

Documents the review protocol and methodological safeguards.

Book

Expands on reviewer interactions, examples, and lessons learned.

Conference Presentation

Summarizes the review process and its implications.

Website

Provides an accessible explanation of how AI-assisted governance reviews are conducted.

⸻

Success Criteria

The LLM review process is successful when it demonstrates:

* independent analysis;
* transparent documentation;
* traceable recommendations;
* preserved disagreement;
* legal verification;
* reproducibility;
* and responsible AI disclosure.

Success is not measured by the quantity of reviewer agreement but by the quality and transparency of the review process.

⸻

Canonical Principle

LLMs are participants in the research methodology—not the final authority.

Their outputs become valuable only after passing through the repository’s governance pipeline:

Prompt
↓
Independent Review
↓
Evidence Mapping
↓
Claim Development
↓
Consensus and Dissent
↓
Legal Verification
↓
Repository Decision
↓
Publication
↓
Replication

By embedding AI review within a transparent, version-controlled process, the Global Social Experiment seeks to harness the strengths of frontier models while openly documenting their limitations and preserving human responsibility for final research decisions.