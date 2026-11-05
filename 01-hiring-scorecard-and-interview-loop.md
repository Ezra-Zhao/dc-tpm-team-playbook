# Hiring Scorecard and Interview Loop - DC Infrastructure TPM

> **DESIGN ARTIFACT - NOT A HIRING RECORD.** This scorecard and loop were
> designed by the candidate for this package. They have never been used to
> interview or hire anyone, by him or by any team of his. His real hiring-
> adjacent experience is limited to what the README states: managing an
> engineering team, and onboarding/mentoring new operations hires. Presenting
> this document as a used hiring instrument would be a fabrication, and it is
> labelled here so that it cannot be mistaken for one.

## Scorecard (capabilities derived from the target role's own requirements)

Score each capability 1-4 with evidence notes; a hire recommendation
requires no capability below 2 and at least two at 4. "Evidence" means a
specific past situation the candidate described, not an adjective.

| Capability (source in JD language) | What strong (4) looks like | What weak (1) looks like |
|---|---|---|
| Delivery execution across construction-to-production | Has run a gated delivery chain end to end and can name where it broke and what changed | Describes coordinating other people's delivery in status language |
| Schedule and critical-path literacy | Builds and defends a CPM logic chain; finds float and says what consumes it | Reports percent complete; cannot explain a predecessor relationship |
| Risk and dependency management | Keeps risk/dependency/decision records as a working system, with triggers and decision dates | Risk = a list made for a review, never opened between reviews |
| Verification instinct | Independently checks partner claims against physical or documentary evidence; has a story where the reported status was wrong | Relays vendor/GC status; verification means asking twice |
| Cross-functional influence without authority | Moves construction, engineering, and commercial partners with evidence and escalation craft | Escalates everything, or nothing; influence = meeting count |
| Executive communication | Compresses a messy delivery problem into a one-page decision: options, costs, recommendation | Long narrative status; decisions left implicit for the reader to find |
| Ambiguity tolerance | Has operated where scope, org, and sequence were undefined, and built the structure while delivering | Needs a defined process before starting; structure is something received |
| Technical depth at the physical/software boundary | Can go deep on power/cooling/controls or compute systems enough to challenge specialists | Pure process layer; cannot tell when a specialist answer is evasive |
| People development (for lead-level hires) | Has developed other PMs' judgment - review calibration, feedback, standards | Management described only as task assignment and status collection |

## Interview loop (design)

| Stage | Owner (design) | Purpose | Scorecard focus |
|---|---|---|---|
| Recruiter screen | Recruiter | Level and logistics fit; surface the non-negotiables early (travel, hybrid, site presence) | Scope fit only - no capability scoring |
| Hiring manager screen (45 min) | TPM Lead | Delivery history depth: one program walked end to end, with the candidate's own decisions isolated from the team's | Delivery execution, verification instinct |
| Work sample review (take-home, 3 h cap) | Candidate + panel | Given a fictional site dataset (schedule extract, five risks, two slipping dependencies), produce a one-page executive risk brief and a 2-week action list | Executive communication, schedule literacy, risk management |
| Site/field deep dive | Site TPM + Construction partner | Physical delivery realism: walk a handover or a slipping long-lead item in detail | Technical depth, cross-functional influence |
| Portfolio and ambiguity session | Portfolio TPM + Compute partner | A cross-site conflict with no clean answer; watch how the candidate structures it | Ambiguity tolerance, dependency management |
| Bar raiser / calibration | Cross-functional senior TPM from outside the team | Independence check on the hire bar; reviews evidence notes, not impressions | All - calibration role |
| Hiring manager close | TPM Lead | Sell and be sold: candidate's questions about the function are themselves evidence | Judgment, motivation |

Process rules (design): every interviewer writes evidence notes before any
group discussion; the scorecard is filled from notes, not from memory of the
room's mood; a single well-evidenced 1 on verification instinct or baseline
honesty is a no-hire regardless of other scores, because this function's
product is trustworthy signal.

## Leveling and calibration notes (design)

- **TPM (individual contributor):** owns one site's delivery system;
  evidence bar is on execution and verification.
- **Senior TPM:** owns a site plus a cross-site dependency or a workstream
  across sites; evidence bar adds influence across orgs and developing
  junior TPMs' work through review.
- **Lead / Manager:** owns the function: charter, cadence, hiring,
  calibration. Evidence bar is organizational - and this package is explicit
  that the candidate for the lead role would be calibrated as a *first-time
  TPM manager* with adjacent evidence (engineering team management), which
  is exactly why the 30-60-90 plan front-loads cadence and calibration
  discipline borrowed from this scorecard.
- Calibration happens on written evidence in a weekly hiring review while
  the loop is active; leveling disagreements are resolved by returning to
  the capability definitions above, not by splitting the difference.
