# Document and record control

## Purpose

Control documented information so people use the correct version, approvals are traceable, and evidence remains accessible for as long as required. GitBook is the documentation interface; it should not automatically be treated as the authoritative store for every project, accounting, personnel, or restricted record.

## Document classes

| Class | Examples | Typical control |
|---|---|---|
| Policy | Quality or governance policy | Leadership approval and review |
| Framework / standard | IMS framework, KPI standard | Named owner, version, approval status |
| Procedure | Contract review, change control | Process owner approval |
| Work instruction / checklist | Site inspection, project closeout | Technical validation and revision control |
| Template / form | Risk assessment, decision log | Controlled blank master |
| Record | Approved proposal, inspection report, handover | Integrity, access, retention, retrieval |
| External document | Law, regulation, client specification | Source, applicability, edition, owner, update check |

## Minimum metadata

Each controlled document should state document ID, title, purpose, owner, approver, approval date, version, status, effective date where applicable, scope, intended users, related documents, review date or trigger, and change history.

Use clear statuses: Draft, In Review, Approved, Superseded, or Obsolete. Draft documents must be visibly distinguished from approved instructions.

## Naming and identifiers

Suggested prefixes: IMS (integrated management system), GOV (governance), PRC (process/procedure), QMS (quality), RSK (risk), KPI (performance), FRM (form/template), REC (record), AUD (audit), CAPA (corrective action tracking). Example: PRC-ENG-001 Contract Review, revision 0.1, status Draft. This is illustrative, not an assigned document number.

## Approval and revision workflow

1. Owner drafts or proposes a change.
2. Relevant process, technical, legal, finance, safety, or information-security reviewers assess it as applicable.
3. Authorized approver approves or returns it for revision.
4. The published controlled version is identified as current.
5. Affected users are notified or trained where necessary.
6. Superseded versions are removed from normal use but retained when needed for traceability.
7. Effectiveness is checked after significant changes or recurring failures.

GitHub pull requests and GitBook change requests can support review and version history, but Khesht must define who is authorized to approve each document class.

## Records and retention

For each record type, define its owner, source system, access classification, retention period, legal or contractual basis, backup requirements, and disposal method. Retention periods must be confirmed against applicable law, contracts, and business needs.

Restrict personal, financial, contractual, and security-sensitive records. A public documentation site must not contain confidential project data, credentials, personal data, or unrestricted copies of controlled records.

## Review triggers

Review a document when governing law or contract changes, ownership or workflow changes, a system changes, an audit finds a gap, a material incident occurs, a KPI signals persistent failure, or a scheduled review date arrives.
