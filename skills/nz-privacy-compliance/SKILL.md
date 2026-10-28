---
name: nz-privacy-compliance
description: >
  Use when drafting or reviewing a New Zealand privacy policy, privacy
  notice, data collection clause, cross-border data transfer wording, or a
  notifiable privacy breach process. Checks wording against the Privacy Act
  2020's Information Privacy Principles and breach notification duties,
  clause by clause, with a section citation for every flagged issue. Do not
  use for general contract formation wording (nz-contract-drafting) or
  consumer trading terms with no personal information element
  (nz-trading-terms).
---

# NZ Privacy Compliance

Stance: a privacy policy is checked against what the business actually does with personal information, not just against template language; a policy that reads well but does not match real data practices is itself a compliance problem. Every flagged issue names a section (usually s 22 and the relevant Information Privacy Principle, "IPP"); this skill does not treat "we have a privacy policy" as the same thing as "we comply with the Act".

## Hard rules

- Verify every section number against [citation-and-verification.md](../nz-legal-specialist/references/citation-and-verification.md) before writing it into a finding.
- The 13 Information Privacy Principles all sit in a single section, **s 22**, of the Privacy Act 2020; cite as `s 22 (IPP [number])`, for example `s 22 (IPP 11)`, not as a separate numbered section per principle. Mechanism: check [privacy-act-ipps.md](references/privacy-act-ipps.md) for the current list before citing one. Reason: citing "IPP 11" as if it were its own section number is a common and avoidable error.
- Never approve a cross-border disclosure clause without checking IPP 12 (s 22) in [privacy-act-ipps.md](references/privacy-act-ipps.md): disclosure outside New Zealand generally requires the receiving party to be subject to comparable privacy protection, or one of the specific exceptions in the Act to apply (the individual's authorisation, the agency believes on reasonable grounds the receiving country or entity is subject to comparable safeguards, or specified alternatives). Mechanism: ask what countries data actually goes to (cloud hosting region, SaaS vendor location, offshore support) before clearing this clause. Reason: a privacy policy's cross-border wording is only correct if it matches where data actually goes.
- Flag any policy clause claiming a blanket right to use personal information "for any purpose" or "for any business purpose we see fit": this conflicts with IPP 1 (purpose must be connected to a function or activity of the agency, and collection must be necessary) and IPP 10 (use is limited to the purpose it was collected for, subject to specific exceptions). Mechanism: ask what the actual purposes are and list them.
- Check that a notifiable privacy breach process is described accurately against ss 112-122: a breach causing, or likely to cause, serious harm must be notified to the Privacy Commissioner "as soon as practicable" (the common reference point in Commissioner guidance is within 72 hours of becoming aware, though the Act's own test is "as soon as practicable", so verify current Commissioner guidance before stating a fixed hour figure), and affected individuals must generally also be notified (s 115), subject to specific exceptions (s 116). Mechanism: do not invent a fixed statutory deadline if the Act itself does not state one as a hard number; check the Act's own wording before citing a time limit as if it were in the statute.
- Treat "personal information" broadly: information about an identifiable individual, which can include names, contact details, online identifiers, and in some contexts IP addresses or device identifiers, depending on whether they make a person identifiable; do not accept a narrow "we only collect emails, so the Act doesn't apply" framing without checking what else the system actually captures.

## Gate

| Situation | Action |
|---|---|
| Drafting a new privacy policy or notice | Build it around the actual data flows (what is collected, why, where stored, who it is shared with, for how long), then map each IPP, citing s 22 and the relevant IPP |
| Reviewing an existing policy | Check each clause against the matching IPP and against what the business actually does, flagging any mismatch |
| Policy includes offshore cloud storage, SaaS tools, or overseas support staff | Apply the IPP 12 cross-border check |
| Client wants to add a new use of existing customer data (e.g. marketing from a different team) | Check against IPP 1 and IPP 10; a new, unrelated purpose will usually need fresh notice or consent, not just a policy update |
| A data breach has occurred | Route to the breach notification check in [privacy-act-ipps.md](references/privacy-act-ipps.md); do not treat this as a drafting task alone, flag the time-sensitivity |

## Steps

1. **Map the real data flow.** What personal information is collected, from whom, why, where it is stored, who it is disclosed to (including processors and overseas providers), and how long it is kept. Ask the user for this if the contract or policy draft does not already state it.
2. **Check each IPP** in [privacy-act-ipps.md](references/privacy-act-ipps.md) against the mapped data flow and the drafted wording: purpose (IPP 1), collection source and manner (IPP 2-4), storage and security (IPP 5), access and correction (IPP 6-7), accuracy (IPP 8), retention (IPP 9), use and disclosure limits (IPP 10-11), cross-border disclosure (IPP 12), and unique identifiers (IPP 13).
3. **Check the breach process wording** against ss 112-122 if the policy or contract describes one.
4. **Check consent and notice mechanics** are real (a genuine opportunity to read and decline, not a pre-ticked box bundled with unrelated terms).
5. **Report clause by clause**, each finding carrying its citation, and close with the not-legal-advice reminder.

## References

- [privacy-act-ipps.md](references/privacy-act-ipps.md): the 13 Information Privacy Principles under s 22, and the notifiable privacy breach regime (ss 112-122).

## Next

- General contract formation wording: [nz-contract-drafting](../nz-contract-drafting/SKILL.md)
- Trading terms that also involve customer data: [nz-trading-terms](../nz-trading-terms/SKILL.md)
- Back to [nz-legal-specialist](../nz-legal-specialist/SKILL.md)
