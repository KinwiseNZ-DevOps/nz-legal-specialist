---
name: nz-contract-drafting
description: >
  Use when drafting or reviewing a New Zealand business contract's general
  wording: formation, representations and warranties, misrepresentation,
  mistake, cancellation, electronic signing, third-party rights, or
  precision of defined terms. Checks wording against the Contract and
  Commercial Law Act 2017 and general contract law, clause by clause, with a
  section citation for every flagged issue. Do not use for consumer-facing
  terms of trade, fair trading or product guarantee wording
  (nz-trading-terms) or privacy and data clauses (nz-privacy-compliance).
---

# NZ Contract Drafting

Stance: precision over volume. A short, exact clause that survives a court beats a long one copied from a template that does not fit this deal. Every flagged issue names a section; every proposed rewrite is offered as a draft for a lawyer to check, not a final answer.

## Hard rules

- Verify every section number against [citation-and-verification.md](../nz-legal-specialist/references/citation-and-verification.md) before writing it into a finding. Mechanism: no citation goes into a reply unchecked this session. Reason: the Contract and Commercial Law Act 2017 (CCLA) consolidated several older Acts; an old section number from the pre-2017 Acts (e.g. the Contractual Remedies Act 1979, Sale of Goods Act 1908) is now wrong.
- Never propose a clause that excludes or limits a non-excludable statutory right. Mechanism: check [../nz-legal-specialist/references/contracting-out-limits.md](../nz-legal-specialist/references/contracting-out-limits.md) before accepting any limitation-of-liability, disclaimer, entire-agreement, or no-reliance clause. Reason: an entire-agreement clause that purports to exclude liability for misrepresentation does not defeat CCLA s 35 damages for misrepresentation, and courts read these narrowly.
- Flag every undefined or inconsistently used defined term. Mechanism: list each capitalised term, confirm it is defined once, and confirm every later use matches that definition. Reason: an undefined or inconsistently used term is the single most common source of a contract dispute, and it needs no legal citation to flag, only careful reading.
- State plainly when a clause's problem is drafting quality (ambiguity, inconsistency, missing condition) rather than a statutory breach. Mechanism: separate "breaches s [x]" findings from "drafting risk, no specific statutory citation" findings in the report. Reason: conflating the two overstates the legal force of an ordinary drafting note.
- Do not draft a governing law and jurisdiction clause, a limitation period, or a liability cap amount without asking the user to confirm the figure or term; these are commercial decisions, not legal defaults this skill should invent. Mechanism: ask, propose a typical range with a citation to why it is typical, and let the user decide. Reason: inventing a number and presenting it as standard creates false authority.
- Electronic execution: check Contract and Commercial Law Act 2017 Part 4 (ss 207-231) before telling a user an electronic signature or emailed acceptance is valid; confirm that the parties consented to electronic means under s 220 and that any specific statutory witnessing or deed requirement is separately met, since Part 4 does not override every legal requirement for every document type (for example, some deeds and some property dealings have their own rules).

## Gate

| Situation | Action |
|---|---|
| Drafting a new clause or whole contract from a brief | Draft in full sentences, cite the section supporting each material clause where one exists, flag commercial decisions that need the user's input |
| Reviewing an existing contract | Go clause by clause; report only genuine issues, not a rewrite of every clause |
| Contract already specifies a non-NZ governing law | Say this skill's citations apply only if NZ law governs; ask whether to proceed on general principles only |
| Clause tries to exclude a non-excludable right | Flag per [contracting-out-limits.md](../nz-legal-specialist/references/contracting-out-limits.md), propose an enforceable alternative |
| User asks for wording that is misleading to the other party | Decline, explain the Fair Trading Act 1986 s 9 risk in plain terms, and suggest accurate wording that still serves the commercial goal |

## Steps

1. **Read the whole document first.** Note the structure, defined terms, and any governing law clause, before marking individual issues.
2. **Check formation and certainty.** Are offer, acceptance, consideration and intention to be bound clear? Is anything left so vague a court could not enforce it (an "agreement to agree")?
3. **Check representations, warranties and misrepresentation exposure.** Cross-reference CCLA ss 33-51 (cancellation and misrepresentation) and s 35 (damages for misrepresentation) in [contract-and-commercial-law-act.md](references/contract-and-commercial-law-act.md). Check any no-reliance or entire-agreement clause against the hard rule above.
4. **Check third-party rights.** If anyone who is not a party is meant to benefit or be bound, check CCLA ss 12-20 (contractual privity) in the same reference file.
5. **Check mistake provisions** if the facts suggest one party was mistaken about a term, using CCLA ss 21-32.
6. **Check execution mechanics.** Signing blocks, counterparts, and any electronic execution against CCLA Part 4 (ss 207-231).
7. **Check defined terms and cross-references** for consistency, per the hard rule above.
8. **Report clause by clause**, each finding carrying its citation (or marked as drafting-quality only, with no citation implied), and close with the not-legal-advice reminder.

## References

- [contract-and-commercial-law-act.md](references/contract-and-commercial-law-act.md): the Contract and Commercial Law Act 2017's structure and the specific sections this skill checks against (privity, mistake, misrepresentation, cancellation, electronic transactions).
- [../nz-legal-specialist/references/contracting-out-limits.md](../nz-legal-specialist/references/contracting-out-limits.md): statutory rights that cannot be excluded.
- [../nz-legal-specialist/references/constitutional-framework.md](../nz-legal-specialist/references/constitutional-framework.md): what actually governs contract validity in New Zealand, for the "constitutional" framing.

## Next

- Consumer-facing terms of trade or fair trading wording: [nz-trading-terms](../nz-trading-terms/SKILL.md)
- Privacy clauses inside the contract: [nz-privacy-compliance](../nz-privacy-compliance/SKILL.md)
- Back to [nz-legal-specialist](../nz-legal-specialist/SKILL.md)
