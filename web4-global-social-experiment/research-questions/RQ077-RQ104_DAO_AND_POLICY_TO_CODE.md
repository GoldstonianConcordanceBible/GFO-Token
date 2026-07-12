RQ077–RQ104: DAO Governance, Human Authority, and Policy-to-Code Conformance

Parent repository: GFO-token
Folder: /web4-global-social-experiment/research-questions/
Status: Canonical domain question file
Version: 0.1.0-draft
Master register: ../03_RESEARCH_QUESTION_REGISTER.md
Directory guide: README.md

⸻

1. Purpose

This file contains the research questions governing:

1. DAO authority, voting, reserved matters, appeals, founder control, treasury protection, and human-rights boundaries; and
2. the translation of repository policies into schemas, workflows, permissions, code, tests, deployments, and audit evidence.

The questions establish a central distinction:

A governance decision is not technically enforced merely because it is written in policy, approved by a vote, or described in public documentation.

DAO authority, contractual authority, legal authority, repository authority, and runtime authority must be separately identified.

⸻

Part VI — DAO Governance and Human Rights

RQ77 — Legitimately Delegable Decisions

Research Question

What decisions may legitimately be delegated to a DAO?

Short Title

Permitted DAO Authority

Purpose

This question defines which decisions may be governed through community proposals and voting.

Candidate Delegable Matters

* community grants;
* nonreserved treasury allocations;
* public programming;
* ecosystem priorities;
* approved parameter changes;
* working-group formation;
* public-goods funding;
* and nonbinding recommendations.

Required Conditions

A decision should be delegated only when:

* the DAO has documented authority;
* the matter is not legally or contractually reserved;
* affected rights are protected;
* conflicts are disclosed;
* and the decision can be implemented safely.

Status

active

Priority

P0

Related Questions

RQ78
RQ79
RQ80
RQ85
RQ86

⸻

RQ78 — Reserved Decisions

Research Question

What decisions should remain legally, contractually, ethically, or institutionally reserved?

Short Title

Reserved Matters

Candidate Reserved Matters

* modifying an individual’s NIL authorization;
* waiving privacy rights;
* exposing confidential records;
* changing executed compensation terms;
* overriding legal obligations;
* activating a human-linked persona;
* authorizing healthcare actions;
* changing minor protections;
* and transferring authority that the DAO does not possess.

Status

active

Priority

P0

Related Questions

RQ77
RQ79
RQ84
RQ85
RQ86

Working Principle

Token voting must not manufacture authority that the organization, contract, or rightsholder never delegated.

⸻

RQ79 — DAO Modification of NIL Licenses

Research Question

Can DAO governance ever modify an existing NIL license?

Short Title

DAO Authority Over NIL Agreements

Purpose

This question examines whether token holders may alter authorization, compensation, duration, permitted use, or termination rights.

Preliminary Position

A DAO should not unilaterally modify an existing NIL license unless:

* the agreement expressly grants that authority;
* applicable law permits it;
* the affected rightsholder provides any required authorization;
* and the change follows the approved amendment procedure.

Status

active

Priority

P0

Related Questions

RQ59
RQ66
RQ77
RQ78
RQ84
RQ85
RQ112
RQ113

⸻

RQ80 — Out-of-Scope Proposals

Research Question

How should an out-of-scope proposal be identified?

Short Title

Proposal Scope Review

Candidate Scope Tests

A proposal may be out of scope when it:

* exceeds delegated authority;
* conflicts with law or contract;
* affects a reserved matter;
* exposes protected data;
* changes rights without authorization;
* bypasses required professional review;
* or cannot be technically implemented as represented.

Required Output

proposal-status
scope-basis
affected-authority
reviewer
appeal-right
technical-effect

Status

active

Priority

P0

Related Questions

RQ77
RQ78
RQ81
RQ82
RQ85

⸻

RQ81 — Null-Proposal Determination

Research Question

Who should determine that a proposal exceeds DAO authority?

Short Title

Proposal Validity Authority

Candidate Reviewers

* governance administrator;
* independent scope reviewer;
* legal reviewer;
* rights committee;
* security council;
* or multisignature review group.

Required Safeguards

* published criteria;
* conflict disclosure;
* written reasoning;
* appeal process;
* and review deadlines.

Status

active

Priority

P1

Related Questions

RQ80
RQ82
RQ83
RQ90

⸻

RQ82 — Appeals of Scope Decisions

Research Question

Who should hear an appeal of a null-proposal determination?

Short Title

Governance Appeals

Purpose

This question establishes a review mechanism for disputed scope decisions.

Candidate Appeal Bodies

* independent governance panel;
* rightsholder panel;
* mixed human-review committee;
* external mediator;
* or limited community review.

Required Qualities

* independence;
* procedural fairness;
* expertise;
* conflict controls;
* and authority to issue a final disposition.

Status

active

Priority

P1

Related Questions

RQ80
RQ81
RQ83
RQ84

⸻

RQ83 — Preventing Token-Weight Capture in Appeals

Research Question

How can an appeals system avoid token-weight capture?

Short Title

Independent Appeals Design

Candidate Controls

* one-person or one-seat voting;
* conflict-based recusals;
* rightsholder representation;
* non-token expert reviewers;
* randomly selected panels;
* capped voting weight;
* and published reasoning.

Status

active

Priority

P1

Related Questions

RQ82
RQ84
RQ87
RQ88
RQ89

⸻

RQ84 — Rightsholder Authority in Disputes

Research Question

What authority should affected rightsholders have in governance disputes?

Short Title

Rightsholder Standing and Protection

Candidate Rights

* notice;
* access to relevant records;
* objection;
* temporary suspension;
* participation in review;
* appeal;
* correction;
* and consent where modification is required.

Working Principle

A person whose identity or contractual rights are directly affected should not be treated as merely one token-weighted voter among unrelated holders.

Status

active

Priority

P0

Related Questions

RQ79
RQ82
RQ83
RQ85
RQ92

⸻

RQ85 — Hierarchy of Authority

Research Question

How should conflicts between law, contracts, entity documents, standards, project policies, DAO votes, and runtime systems be resolved?

Short Title

Governance Authority Hierarchy

Proposed Order

applicable-law
binding-contracts
entity-governance-documents
approved-standards
approved-project-policies
dao-decisions
technical-implementation
runtime-output

Principle

Technical capability does not override higher-order authority.

Status

active

Priority

P0

Related Questions

RQ77
RQ78
RQ79
RQ80
RQ86
RQ97

⸻

RQ86 — Representing Reserved Matters in Policy and Code

Research Question

How should reserved matters be represented in policy and code?

Short Title

Reserved-Matter Enforcement

Candidate Controls

* explicit policy list;
* proposal validation rules;
* schema-level restrictions;
* contract-level permissions;
* approval thresholds;
* multisignature gates;
* human authorization checks;
* and automated rejection of prohibited actions.

Status

active

Priority

P0

Related Questions

RQ78
RQ80
RQ85
RQ94
RQ96
RQ97

⸻

RQ87 — Whale Capture

Research Question

How can a DAO prevent whale capture?

Short Title

Concentrated Voting Power

Candidate Controls

* voting caps;
* quorum design;
* delegated-power disclosure;
* quadratic mechanisms where appropriate;
* bicameral governance;
* time-weighted participation;
* and reserved human-rights protections.

Caution

No mechanism eliminates capture risk in every context.

Status

active

Priority

P1

Related Questions

RQ83
RQ88
RQ89
RQ90
RQ93

⸻

RQ88 — Sybil Resistance

Research Question

How can a DAO reduce Sybil attacks?

Short Title

Identity and Voting Integrity

Candidate Controls

* proof of personhood;
* verified membership;
* contribution history;
* rate limits;
* reputation systems;
* stake requirements;
* and anomaly detection.

Risks

Sybil controls may create:

* privacy risks;
* exclusion;
* centralization;
* identity exposure;
* or discrimination.

Status

active

Priority

P1

Related Questions

RQ83
RQ87
RQ89
RQ130
RQ131

⸻

RQ89 — Vote Buying and Delegation Manipulation

Research Question

How should vote buying and delegated-voting manipulation be addressed?

Short Title

Voting Manipulation

Candidate Controls

* delegation disclosure;
* anti-bribery rules;
* vote-market restrictions;
* snapshot requirements;
* suspicious-activity review;
* conflict reporting;
* and sanctions for proven manipulation.

Status

active

Priority

P1

Related Questions

RQ83
RQ87
RQ88
RQ90

⸻

RQ90 — Founder Domination

Research Question

How should founder domination be disclosed and constrained?

Short Title

Founder Authority Disclosure

Relevant Forms of Control

* repository administration;
* treasury access;
* multisignature seats;
* upgrade keys;
* emergency powers;
* communication channels;
* brand ownership;
* and release authority.

Candidate Controls

* public authority matrix;
* term limits;
* independent reviewers;
* multisignature separation;
* succession planning;
* and periodic decentralization reports.

Status

active

Priority

P0

Related Questions

RQ81
RQ87
RQ89
RQ92
RQ93
RQ139
RQ140

⸻

RQ91 — Proposal Spam and Treasury Extraction

Research Question

What controls reduce proposal spam and treasury extraction?

Short Title

Proposal and Treasury Protection

Candidate Controls

* proposal deposits;
* eligibility thresholds;
* rate limits;
* budget caps;
* staged funding;
* milestone-based release;
* conflict disclosure;
* and independent expenditure review.

Status

active

Priority

P1

Related Questions

RQ77
RQ87
RQ89
RQ92
RQ99

⸻

RQ92 — Emergency Powers

Research Question

How should emergency powers be limited, logged, reviewed, and terminated?

Short Title

Emergency Governance Controls

Required Elements

* defined emergency conditions;
* limited authority;
* named operators;
* logging;
* notification;
* expiration;
* retrospective review;
* restoration process;
* and prohibition on unrelated use.

Candidate Technical Controls

* pause functions;
* credential suspension;
* transaction limits;
* access revocation;
* and temporary publishing blocks.

Status

active

Priority

P0

Related Questions

RQ72
RQ84
RQ90
RQ91
RQ99
RQ100

⸻

RQ93 — Claims of Decentralization

Research Question

Can a project claim decentralization when founders retain repository, wallet, upgrade, or emergency authority?

Short Title

Decentralization Claims

Purpose

This question establishes disclosure requirements for practical versus claimed decentralization.

Candidate Disclosure Areas

* token concentration;
* repository ownership;
* treasury authority;
* smart-contract permissions;
* emergency controls;
* upgrade authority;
* frontend control;
* and governance participation.

Working Principle

Decentralization should be described dimension by dimension rather than as a single unsupported label.

Status

active

Priority

P0

Related Questions

RQ87
RQ90
RQ92
RQ99
RQ100

⸻

Part VII — Policy-to-Code Conformance

RQ94 — Translating Policy Into Technical Requirements

Research Question

How can repository policies be translated into technical requirements?

Short Title

Policy Translation

Translation Chain

policy
→ obligation
→ responsible-system
→ technical-requirement
→ control
→ test
→ evidence

Example

Policy:
A suspended persona must not publish new content.
Technical requirement:
Publishing credentials must be disabled upon approved suspension.
Test:
Attempted publishing after suspension must fail.
Evidence:
Timestamped test result and audit log.

Status

active

Priority

P0

Related Questions

RQ86
RQ95
RQ96
RQ97
RQ104

⸻

RQ95 — Evidence of Smart-Contract Conformance

Research Question

What evidence demonstrates that a smart contract conforms to a governance policy?

Short Title

Smart-Contract Conformance Evidence

Candidate Evidence

* mapped requirements;
* reviewed source code;
* deployment records;
* verified bytecode;
* unit tests;
* integration tests;
* invariant tests;
* access-control tests;
* and independent audit where required.

Status

active

Priority

P0

Related Questions

RQ94
RQ96
RQ98
RQ100
RQ101
RQ102

⸻

RQ96 — Policy-Control Traceability

Research Question

How should policy requirements map to code, schemas, workflows, permissions, tests, and audit evidence?

Short Title

End-to-End Traceability

Required Mapping Fields

policy-id
requirement-id
system
control-id
implementation-location
test-id
evidence-id
owner
status
version
exceptions

Status

active

Priority

P0

Related Questions

RQ61
RQ86
RQ94
RQ95
RQ104

⸻

RQ97 — Unsupported Enforcement Claims

Research Question

What should happen when a policy claims technical enforcement but no technical control exists?

Short Title

Policy-Control Gap

Required Response

* mark the claim as documentation-only;
* record the implementation gap;
* remove misleading enforcement language;
* assign an owner;
* establish a remediation deadline;
* and prevent activation where the missing control creates material risk.

Status Values

documented-not-enforced
partially-enforced
manually-enforced
technically-enforced
verified-enforcement

Status

active

Priority

P0

Related Questions

RQ85
RQ86
RQ94
RQ96
RQ104

⸻

RQ98 — Source Code and Deployed Bytecode

Research Question

How should discrepancies between audited source code and deployed bytecode be documented?

Short Title

Deployment Verification

Required Records

* source commit;
* compiler version;
* build settings;
* deployment address;
* chain;
* deployment transaction;
* bytecode hash;
* verification status;
* and discrepancy explanation.

Principle

An audit of source code does not establish that identical code was deployed.

Status

active

Priority

P0

Related Questions

RQ95
RQ99
RQ100
RQ102

⸻

RQ99 — Administrative Permissions Disclosure

Research Question

What administrative permissions must be publicly disclosed?

Short Title

Privileged Authority Disclosure

Candidate Permissions

* ownership;
* minting;
* burning;
* pausing;
* freezing;
* blacklisting;
* fee changes;
* treasury movement;
* upgrades;
* liquidity controls;
* oracle changes;
* credential issuance;
* and emergency actions.

Status

active

Priority

P0

Related Questions

RQ90
RQ91
RQ92
RQ93
RQ98
RQ100

⸻

RQ100 — Review of Critical Contract Controls

Research Question

How should ownership, minting, pause, freeze, fee, blacklist, upgrade, and liquidity controls be reviewed?

Short Title

Critical Permission Review

Review Questions

* Who holds the permission?
* Is it individual or multisignature?
* Can it be revoked?
* Is there a delay?
* Is use logged?
* Is use publicly disclosed?
* Can holders appeal or exit?
* Is the permission necessary?
* Has it been tested?

Status

active

Priority

P0

Related Questions

RQ92
RQ93
RQ95
RQ98
RQ99
RQ101

⸻

RQ101 — Testing by Contract Risk Class

Research Question

What level of testing is appropriate for different classes of smart contracts?

Short Title

Risk-Based Testing

Candidate Risk Classes

low-risk informational
standard token
fee-routing
treasury
upgradeable
identity-linked
governance
cross-chain
autonomous-agent
healthcare-related

Testing Levels

* unit testing;
* integration testing;
* static analysis;
* fuzzing;
* invariant testing;
* fork testing;
* independent review;
* and formal methods where justified.

Status

active

Priority

P1

Related Questions

RQ95
RQ100
RQ102
RQ104

⸻

RQ102 — Advanced Testing and Audit Triggers

Research Question

When are static analysis, fuzzing, invariant testing, formal methods, or independent audit necessary?

Short Title

Assurance Triggers

Candidate Triggers

* custody of significant assets;
* upgradeability;
* complex fee logic;
* cross-chain operations;
* identity-linked actions;
* irreversible permissions;
* autonomous execution;
* large public exposure;
* and regulated or high-impact use.

Status

active

Priority

P1

Related Questions

RQ95
RQ98
RQ100
RQ101
RQ104

⸻

RQ103 — Revoking Agent Credentials

Research Question

How should API keys, agent credentials, and model access be revoked when authorization is suspended?

Short Title

Credential Revocation

Required Controls

* centralized credential inventory;
* immediate key disablement;
* token revocation;
* session termination;
* publishing-access removal;
* wallet-action suspension where authorized;
* audit logging;
* propagation checks;
* and restoration approval.

Status

active

Priority

P0

Related Questions

RQ66
RQ67
RQ72
RQ74
RQ94
RQ96

⸻

RQ104 — Traceability as a Maturity Indicator

Research Question

Can policy-to-control traceability be measured as a governance maturity indicator?

Short Title

Governance Traceability Maturity

Candidate Metrics

percentage-of-policies-mapped
percentage-of-requirements-implemented
percentage-of-controls-tested
percentage-of-evidence-current
number-of-open-gaps
average-remediation-time
number-of-unverified-enforcement-claims

Proposed Maturity Levels

Level 0 — Undocumented
Level 1 — Policy documented
Level 2 — Requirements mapped
Level 3 — Controls implemented
Level 4 — Controls tested
Level 5 — Independently verified

Status

active

Priority

P1

Related Questions

RQ94
RQ95
RQ96
RQ97
RQ101
RQ102

⸻

Cross-Question Dependency Map

RQ77 → RQ78, RQ79, RQ80
RQ78 → RQ79, RQ84, RQ86
RQ80 → RQ81, RQ82
RQ82 → RQ83
RQ83 → RQ84, RQ87, RQ88, RQ89
RQ85 → RQ86, RQ94, RQ97
RQ87 + RQ88 + RQ89 → governance-integrity controls
RQ90 → RQ92, RQ93, RQ99
RQ92 → RQ99, RQ100
RQ94 → RQ95, RQ96, RQ97
RQ95 → RQ98, RQ100, RQ101, RQ102
RQ96 → RQ103, RQ104

⸻

Prompt Routing Map

User Intent	Primary Questions
What can a DAO vote on?	RQ77–RQ80
Can a DAO change a NIL agreement?	RQ78, RQ79, RQ84, RQ85
Who decides whether a proposal is invalid?	RQ80–RQ83
How are rightsholders protected?	RQ79, RQ84–RQ86
How do you prevent whale capture?	RQ83, RQ87–RQ89
How should founder control be disclosed?	RQ90, RQ92, RQ93
What should emergency powers look like?	RQ92, RQ99, RQ100
How does policy become code?	RQ94–RQ97
How do you prove deployed code matches reviewed code?	RQ95, RQ98
What permissions must be disclosed?	RQ99–RQ100
What testing is required?	RQ101–RQ102
How are AI-agent credentials revoked?	RQ103
How is governance maturity measured?	RQ104

⸻

Initial Answer Status

Questions	Answer Status
RQ77–RQ86	Proposed governance architecture
RQ87–RQ93	Proposed anti-capture and disclosure controls
RQ94–RQ97	Proposed policy-to-code framework
RQ98–RQ103	Technical requirements requiring implementation evidence
RQ104	Proposed maturity model

⸻

Priority Implementation Questions

Before live DAO or agentic implementation, the project should resolve:

RQ77
RQ78
RQ79
RQ80
RQ81
RQ82
RQ84
RQ85
RQ86
RQ90
RQ92
RQ93
RQ94
RQ95
RQ96
RQ97
RQ98
RQ99
RQ100
RQ103
RQ104

⸻

Canonical Principle

A DAO may exercise only the authority validly delegated to it.

A vote does not override:

* law;
* binding contracts;
* human identity rights;
* privacy protections;
* reserved matters;
* or technical safety requirements.

Likewise, a written policy does not establish technical enforcement.

Governance maturity requires traceability from:

authority
→ policy
→ requirement
→ control
→ test
→ evidence
→ review