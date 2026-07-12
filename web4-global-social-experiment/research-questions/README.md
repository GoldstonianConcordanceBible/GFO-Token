Research Question Bank

Machine-Readable and Human-Readable Research Agenda

Parent repository: GFO-token
Folder: /web4-global-social-experiment/research-questions/
Status: Canonical research-question directory
Version: 0.1.0-draft
Master register: ../03_RESEARCH_QUESTION_REGISTER.md
Governing document: ../00_REPOSITORY_CHARTER.md

⸻

1. Purpose

This directory stores the complete research-question bank for the Global Social Experiment, Web4, Web4 NIL, artificial intelligence governance, decentralized governance, education, culture, theology, healthcare, repository licensing, consulting, and research publication program.

The directory separates the 226 secondary research questions into smaller domain files so they can be:

* reviewed without loading the entire research program;
* indexed efficiently for website retrieval;
* mapped to evidence and findings;
* connected to governance and technical requirements;
* assigned to owners;
* versioned independently;
* and used as structured prompt-routing targets.

The authoritative wording for all questions is maintained in:

../03_RESEARCH_QUESTION_REGISTER.md

The files in this directory provide expanded metadata and operational mappings for those questions.

⸻

2. Question Inventory

The complete question inventory includes:

1 primary research question
226 secondary research questions
6 PhilArchive article questions
8 book questions
8 conference questions

Total named questions:

249

The initial public prompt system should index all 249 questions, but it should not imply that all questions have been answered.

⸻

3. Directory Structure

research-questions/
├── README.md
├── RQ001-RQ025_FOUNDATIONS_AND_WEB4.md
├── RQ026-RQ054_METHODOLOGY_AND_DELPHI.md
├── RQ055-RQ076_WEB4_NIL.md
├── RQ077-RQ104_DAO_AND_POLICY_TO_CODE.md
├── RQ105-RQ137_COMPENSATION_LEGAL_PRIVACY.md
├── RQ138-RQ162_REPOSITORY_LICENSING_CONSULTING.md
├── RQ163-RQ185_EDUCATION_AND_ALPHA_SCHOOL.md
├── RQ186-RQ215_CULTURE_THEOLOGY_HEALTHCARE.md
├── RQ216-RQ226_RESEARCH_OUTPUTS.md
├── CORE_PUBLICATION_QUESTIONS.md
└── research-question-manifest.jsonl

This compact structure is optimized for repository maintenance and prompt retrieval.

⸻

4. File Map

RQ001-RQ025_FOUNDATIONS_AND_WEB4.md

Contains:

* Global Social Experiment foundations;
* scope;
* repository governance as research;
* institutional memory;
* falsification;
* Web4 emergence;
* Web4 definitions;
* minimum properties;
* dependencies;
* competing explanations;
* and revision criteria.

Questions:

RQ1–RQ25

⸻

RQ026-RQ054_METHODOLOGY_AND_DELPHI.md

Contains:

* mixed-methods design;
* qualitative coding;
* claim provenance;
* LLM roles;
* reproducibility;
* multi-model Delphi review;
* consensus;
* dissent;
* hallucination risk;
* controlled ChatGPT replication;
* and model-specific bias.

Questions:

RQ26–RQ54

⸻

RQ055-RQ076_WEB4_NIL.md

Contains:

* identity vectors;
* synthetic media;
* authorization;
* consent;
* machine-readable permissions;
* revocation;
* suspension;
* termination;
* posthumous rights;
* minors;
* and persona accountability.

Questions:

RQ55–RQ76

⸻

RQ077-RQ104_DAO_AND_POLICY_TO_CODE.md

Contains:

* DAO authority;
* reserved matters;
* rightsholder protections;
* voting capture;
* emergency powers;
* founder control;
* policy-to-code traceability;
* smart-contract review;
* testing;
* credentials;
* and audit evidence.

Questions:

RQ77–RQ104

⸻

RQ105-RQ137_COMPENSATION_LEGAL_PRIVACY.md

Contains:

* creator-fee compensation;
* gross and net calculations;
* payment systems;
* professional-review triggers;
* enacted and proposed law;
* source verification;
* jurisdictional conflict;
* public and private data;
* retention;
* biometrics;
* minors;
* and breach response.

Questions:

RQ105–RQ137

⸻

RQ138-RQ162_REPOSITORY_LICENSING_CONSULTING.md

Contains:

* repository governance;
* ownership and stewardship;
* branch protection;
* breaking changes;
* open and commercial licensing;
* trademarks;
* certification;
* jurisdiction packs;
* Runic Consulting methodology;
* client discovery;
* rights mapping;
* readiness assessments;
* and third-party licensing.

Questions:

RQ138–RQ162

⸻

RQ163-RQ185_EDUCATION_AND_ALPHA_SCHOOL.md

Contains:

* SydTek Scholars;
* AI literacy;
* student agency;
* governance exercises;
* legal-claim literacy;
* minor protections;
* student contributions;
* Alpha School;
* comparative education;
* public evidence;
* transferability;
* privacy;
* and partnership boundaries.

Questions:

RQ163–RQ185

⸻

RQ186-RQ215_CULTURE_THEOLOGY_HEALTHCARE.md

Contains:

* Museum of the Bible;
* cultural institutions;
* image and likeness;
* public interpretation;
* Web4 mythology;
* Mirror → Water → Fire;
* theological plurality;
* healthcare identity;
* patient and clinician personas;
* digital twins;
* and healthcare governance.

Questions:

RQ186–RQ215

⸻

RQ216-RQ226_RESEARCH_OUTPUTS.md

Contains:

* repository canonical authority;
* book mapping;
* PhilArchive mapping;
* conference mapping;
* case-study selection;
* publication thresholds;
* commercial boundaries;
* and research communication.

Questions:

RQ216–RQ226

⸻

CORE_PUBLICATION_QUESTIONS.md

Contains:

* PRQ1;
* ARQ1–ARQ6;
* BRQ1–BRQ8;
* CRQ1–CRQ8;
* and publication-specific scope rules.

⸻

research-question-manifest.jsonl

Contains one machine-readable record for each named research question.

Expected record count:

249 records

⸻

5. Research Question Record Standard

Every question record must contain the following fields:

question_id:
question_text:
short_title:
family:
domain:
status:
priority:
canonical_source:
version:
created_date:
last_reviewed:
owner:
primary_methods:
evidence_required:
legal_review_required:
privacy_review_required:
technical_review_required:
human_subjects_review_required:
related_questions:
dependencies:
publication_targets:
prompt_modes:
answer_status:
tags:

⸻

6. Approved Question Statuses

Each question must use one status:

proposed
approved
active
partially-answered
answered-provisionally
unresolved
deferred
out-of-scope
superseded
retired

Default status for the initial repository build:

approved

A question becomes active when it is included in a current study, implementation review, or evidence-collection plan.

⸻

7. Answer Status

Question status and answer status are different.

Approved answer statuses are:

no-answer
preliminary-hypothesis
partial-evidence
delphi-input
delphi-consensus
contested
provisional-finding
validated-finding
independently-replicated

A question may remain active while having a provisional-finding.

⸻

8. Priority Levels

P0 — Immediate rights, legal, privacy, security, or safety concern
P1 — Required for the initial Web4 NIL framework
P2 — Required for implementation readiness
P3 — Important for theory or institutional development
P4 — Comparative or applied future research
P5 — Exploratory

Initial P0 and P1 topics should include:

* authorization;
* consent;
* identity-vector separation;
* emergency suspension;
* revocation;
* minors;
* privacy;
* DAO authority limits;
* compensation clarity;
* legal verification;
* policy-to-code conformance;
* and activation readiness.

⸻

9. Domain Values

Approved domain values include:

global_social_experiment
web4_theory
methodology
llm_delphi
web4_nil
dao_governance
policy_to_code
compensation
legal_verification
privacy
repository_governance
licensing
consulting
education
alpha_school
cultural_institutions
mythology
theology
healthcare
research_outputs

⸻

10. Prompt Modes

Research questions may be mapped to one or more website prompt modes:

ask_web4
ask_web4_nil
research_explorer
delphi_explorer
governance_builder
policy_to_code
education_mode
theology_and_mythology
healthcare_research
repository_and_licensing

Example:

question_id: RQ79
prompt_modes:
  - ask_web4_nil
  - governance_builder
  - research_explorer

⸻

11. Question-to-Evidence Relationship

A research question may be linked to:

* source records;
* claims;
* hypotheses;
* Delphi responses;
* findings;
* policies;
* technical requirements;
* controls;
* case studies;
* and publications.

Recommended relationship chain:

research question
→ evidence
→ claim
→ analysis
→ finding
→ governance proposal
→ approved policy
→ technical requirement
→ implemented control
→ evaluation

Not every question will reach every stage.

⸻

12. Question-to-Claim Mapping

Each material claim must identify the question or questions it addresses.

Example:

claim_id: CLM-W4NIL-0004
claim_text: Authorization for one identity vector does not automatically authorize another.
research_questions:
  - RQ55
  - RQ59
  - RQ60
  - RQ69

A claim without a relevant research question should be reviewed for scope drift.

⸻

13. Question-to-Chunk Mapping

The prompt backend should generate one or more retrieval chunks per question.

Recommended chunk types:

question-definition
why-it-matters
current-status
available-evidence
delphi-result
dissent
governance-implication
technical-implication
unresolved-issues
related-questions

A research question does not need all ten chunk types.

Priority questions may require several chunks.

Low-priority exploratory questions may require one question record only.

⸻

14. Estimated Research Question Chunks

For the initial production knowledge base:

249 question-definition chunks
80–120 question-status chunks
100–150 finding or evidence chunks
50–80 unresolved-question chunks

Estimated question-related retrieval total:

479–599 chunks

These are part of the larger repository estimate, not additional to it.

⸻

15. User Prompt Mapping

A user prompt may map to several research questions.

Example user prompt:

Can token holders vote to keep using an author's AI voice after the author revokes permission?

Likely mapping:

RQ59 — valid authorization
RQ66 — revocation and termination
RQ67 — persistent media and systems
RQ69 — identity-vector separation
RQ72 — emergency suspension
RQ79 — DAO modification of NIL licenses
RQ84 — rightsholder authority
RQ85 — hierarchy of authority
RQ103 — credential revocation

The system should retrieve from all relevant domains while prioritizing approved policies and verified findings.

⸻

16. Unresolved Question Handling

When a question remains unresolved, the website response should:

1. state that the issue remains unresolved;
2. summarize available evidence;
3. identify any Delphi consensus;
4. preserve material dissent;
5. identify applicable proposed policies;
6. distinguish project preference from law;
7. and identify review or evidence still required.

The system must not generate false certainty solely to produce a complete-looking answer.

⸻

17. Question Revision Rules

Question wording may be revised when:

* terminology changes;
* scope is too broad;
* a hidden assumption is identified;
* the question combines unrelated issues;
* new evidence requires subdivision;
* or a legal or technical change makes the original wording inaccurate.

A revision must preserve:

original wording
new wording
reason
effective version
approver
affected findings
affected chunks

⸻

18. New Question Procedure

A proposed new question must include:

proposed_question:
domain:
relationship_to_PRQ1:
research_gap:
proposed_method:
evidence_needed:
risks:
dependencies:
priority:
proposed_by:

The next available identifier must be used.

Existing numbers must never be reassigned.

⸻

19. Question Retirement Rules

A question may be retired when it:

* duplicates another question;
* is based on a false assumption;
* becomes irrelevant;
* is impossible to study ethically;
* falls outside repository scope;
* or is fully replaced by more precise questions.

Retired questions remain in the historical manifest.

⸻

20. Publication Mapping

PhilArchive

Uses:

PRQ1
ARQ1–ARQ6
selected RQ36–RQ54
selected Web4 NIL questions
selected repository questions

Book

Uses:

BRQ1–BRQ8
all domains where supported

Conference

Uses:

CRQ1–CRQ8

Website

May expose all 249 questions with evidence and status labels.

⸻

21. Canonical Consistency Rule

The wording in domain files and the JSONL manifest must match:

../03_RESEARCH_QUESTION_REGISTER.md

When a mismatch occurs:

1. the master register controls;
2. the domain file must be corrected;
3. the manifest must be regenerated;
4. affected chunks must be reindexed;
5. and the change must be recorded in release notes.

⸻

22. Validation Requirements

Automated validation should confirm:

* every identifier is unique;
* no question number is missing;
* no question number is duplicated;
* every question has a domain;
* every question has a status;
* every question has a version;
* every question maps to a canonical source;
* related question identifiers exist;
* and manifest records match the human-readable files.

⸻

23. Research Question Governance Principle

The research question bank prevents the repository from becoming a collection of unsupported answers.

It preserves the distinction between:

* what has been asked;
* what is being investigated;
* what the models suggested;
* what evidence supports;
* what governance proposes;
* what technology enforces;
* and what remains unknown.

The question bank is the backbone of the research program and the primary routing map for the prompt-based website.