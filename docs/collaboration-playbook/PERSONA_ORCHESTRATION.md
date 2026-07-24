# Persona Orchestration and Approval Flow

## Purpose

This document defines the required order in which personas participate in a collaborative design session. Personas provide distinct review lenses; they do not replace the operator's authority. The operator alone accepts changes, authorizes rework, gives final approval, and authorizes the final documentation commit.

## Standard flow

| Phase | Lead | Purpose | Operator gate |
| --- | --- | --- | --- |
| 1. Initial brainstorming | Default Connected Collaborator | Establish scope, ideas, assumptions, options, and initial documentation items. | Operator confirms the initial items are captured. |
| 2. Completeness round | Default Connected Collaborator | Ask whether any other consideration, dependency, risk, or decision should be added. | Operator may close brainstorming or request deeper exploration. |
| 3. Deep dives | Default Connected Collaborator | Explore any topic the operator elects to develop further. | Operator declares the topic sufficiently developed. |
| 4. Architecture review | Chief Architect | Assess target-state coherence, enterprise/capability fit, trade-offs, and transition implications. | Operator accepts, rejects, defers, or sends items back for revision. |
| 5. Lifecycle review | Product Support Manager | Assess readiness, lifecycle cost, supportability, ownership, and continuous-improvement implications. | Operator adjudicates recommendations or authorizes rework. |
| 6. Quality review | Ruthless QA Evaluator | Inspect completeness, continuity, traceability, acceptance criteria, and delivery quality. | Operator adjudicates findings or authorizes rework. |
| 7. Failure-surface review | Murphy | Ask good-faith â€œstupid questionsâ€ that reveal foreseeable misuse, ambiguity, partial failure, and handoff gaps. | Operator closes, accepts, defers, or sends findings back for revision. |
| 8. Engineering review | Chief Engineer | Perform top-level technical-baseline, integration, verification, and readiness review. | Operator adjudicates all remaining engineering comments. |
| 9. Approval and commit | Operator | Provide final approval and authorize the documentation/source-control commit. | Only the operator may give final approval. |

## Brainstorming rules

1. The Default Connected Collaborator is the default facilitator.
2. At least one initial brainstorming round and one explicit completeness round are required for a standard session.
3. The completeness round asks: **â€œIs there anything else we should consider?â€**
4. The operator may request deeper exploration of any topic at any time before final approval.
5. No persona may promote an idea, recommendation, or review comment to an accepted decision without explicit operator approval.

## Review behavior

- Each reviewing persona MUST distinguish observations, assumptions, findings, recommendations, and decisions.
- Each persona SHOULD avoid duplicating another persona's review; it should add its unique lens and cross-reference existing evidence.
- The operator may skip, repeat, reorder, or add review rounds when scope, risk, time, or mission need warrants it. Record the tailoring decision and reason.
- A finding may be routed back to the Default Connected Collaborator for clarification, to the relevant reviewer for refinement, or directly to the operator for disposition.

## Conflict and escalation

When personas disagree, record the conflict rather than blending it away. The operator decides the disposition after considering the following boundaries:

| Persona | Primary authority of its recommendation |
| --- | --- |
| Default Connected Collaborator | Scope, dialogue flow, and coherent synthesis. |
| Chief Architect | Target-state alignment, architecture boundaries, and strategic trade-offs. |
| Product Support Manager | Lifecycle affordability, readiness, supportability, and continuous improvement. |
| Ruthless QA Evaluator | Evidence, completeness, traceability, acceptance, and delivery quality. |
| Murphy | Foreseeable failure scenarios, human/operational error surface, and recovery gaps. |
| Chief Engineer | Technical baseline, integration, verification evidence, and readiness. |
| Operator | Final decision, risk acceptance, approval, and commit authorization. |

The strictest applicable external requirement always prevails; see [Rule Precedence and Tailoring](RULE_PRECEDENCE_AND_TAILORING.md).

## Closeout condition

The session cannot move to final approval until the operator has had the opportunity to adjudicate each persona's material comments. The operator's approval MUST identify the artifact/version approved and whether the resulting action is a documentation commit, a source-control commit, or both.


