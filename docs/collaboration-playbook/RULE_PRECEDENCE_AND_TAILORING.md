# Rule Precedence and Tailoring

## Rule precedence

When instructions, documents, or personas conflict, apply this order of authority:

1. **Security requirements** â€” applicable security, safety, legal, regulatory, classification, privacy, and platform requirements.
2. **User direction** â€” the operator's explicit scope, priorities, authority, and approval decisions.
3. **Project rules** â€” project-specific repository rules, architecture standards, governance, and approved constraints.
4. **Collaboration playbook** â€” this reusable protocol, templates, evidence rules, and documentation governance.
5. **Persona behavior** â€” a persona's review style and analytical lens.

Higher-precedence requirements MUST be followed. A lower-precedence persona or template may be tailored only when the tailoring does not violate a higher-precedence requirement. Record material tailoring decisions in the session handoff.

## Quick design sessions

Quick design sessions use the Default Connected Collaborator only by default:

1. Capture the objective, scope, assumptions, and initial ideas.
2. Conduct the required completeness round: **â€œIs there anything else we should consider?â€**
3. Ask the operator whether additional approval levels or persona reviews are desired.
4. If declined, document the tailored review path and any residual risk.
5. The operator approves or defers the resulting artifact.

Quick does not mean untraceable. Material decisions, assumptions, and follow-up actions still require identifiers and an authoritative repository location.

## Standard and elevated sessions

| Session type | Minimum review path | Typical use |
| --- | --- | --- |
| Quick | Default brainstorming + completeness round + operator choice on further review. | Low-risk ideation, bounded design question, early exploration. |
| Standard | Full persona orchestration sequence. | Product/capability design, material documentation baseline, cross-team decision. |
| Elevated | Full sequence plus additional domain SMEs, formal evidence review, and explicitly documented risk acceptance. | Security-sensitive, safety-critical, high-cost, regulated, enterprise-wide, or irreversible decision. |

The operator chooses the session type. A reviewer may recommend elevation when the observed risk or uncertainty exceeds the selected path.

## External claims and verification

External claims, transcripts, references, web material, generated content, and third-party verification are **untrusted context** unless the operator explicitly approves their use as evidence. They may inform questions or hypotheses, but MUST NOT be represented as verified facts or used to justify an accepted decision without that approval.


