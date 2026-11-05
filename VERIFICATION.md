# VERIFICATION - dc-tpm-team-playbook verification record

Build date: 2026-11-05. Verification scope, following the dc-delivery-playbook
VERIFICATION convention: (1) contents checklist against the spec, section 4,
proof artifact 2 of the Anthropic gap analysis dated 2026-11-05;
(2) honesty-labelling self-check; (3) increment check against the existing
proof artifacts.

## 1. Contents checklist (spec item by item)

| Spec requirement | Delivered file | Status |
|---|---|---|
| Team charter sample: mission of the DC Infra TPM function, interfaces with Construction / Compute / Security and Compliance, and RACI | `00-team-charter-and-raci.md` - mission, scope in/out, 5 operating principles, RACI table with 12 activities across 7 parties (adds Energy/Location Strategy, Operations, Supply Chain Delivery, which the JD interfaces require), 2 boundary rules, team shape | Done |
| Hiring package: TPM scorecard split by the JD capability items, interview loop design, leveling calibration notes - all labelled design artifacts, not used hiring records | `01-hiring-scorecard-and-interview-loop.md` - 9-capability scorecard with strong/weak evidence descriptions, 7-stage loop, process rules, leveling notes for TPM / Senior TPM / Lead | Done |
| Program review operating pack: exec one-pager template, RAG and variance definitions, weekly/monthly review cadence, escalation norms | `02-program-review-pack.md` sections 1-4 - three-record system (status/risk/decision), one-pager template, RAG defined on forecast vs baseline with the six-element variance format, 3-forum cadence table, escalation norms | Done |
| Filled example using the same fictional project (Helios), explicitly labelled fictional | `02-program-review-pack.md` section 5 - filled one-pager for Project Helios, headed FICTIONAL EXAMPLE, relative months only (M14, M20.0) | Done |
| 30-60-90 build-out plan from a founding-manager perspective: visibility rhythm first, then hiring, then site coverage expansion, with the reasoning for the order | `03-30-60-90-plan.md` - order stated and defended in the header; per-phase goals, actions, deliverables; explicit "not in the first 30 days" list; day-90 success/failure definitions | Done |
| README: source labelling - management span and mentoring facts from real experience stated as fact only; the TPM team-building part labelled methodology design, never claimed as practised | `README.md` - "Honest boundary" section: design-artifact status of every document, hiring package never used, Helios fictional, real experience limited to the three stated facts (Vtron engineering team 2017-2019, Asiacom mentoring, Quanta standards), and the explicit sentence that the package mitigates the narrative gap but does not remove the hard requirement of never having managed a TPM team | Done |

## 2. Honesty-labelling self-check (grep, run at build time)

- Every content file (00-03) opens with a DESIGN ARTIFACT notice:
  `grep -c "DESIGN ARTIFACT"` returns 1 for each of
  00-team-charter-and-raci.md, 01-hiring-scorecard-and-interview-loop.md,
  02-program-review-pack.md, 03-30-60-90-plan.md.
- The hiring file additionally carries "NOT A HIRING RECORD" in its notice.
- The filled example is headed "FICTIONAL (Project Helios)" in its section
  title and "FICTIONAL EXAMPLE" in its notice block; Project Helios is
  described as invented in both README.md and 02-program-review-pack.md.
- No real employer project names, client names, or site names appear
  anywhere in the package. Employer names (Vtron, Asiacom, Quanta) appear
  only in the README source-labelling context, stating the candidate's own
  real roles - the same facts as his resume.
- No invented delivery figures: the package contains no lead times, dates,
  or team sizes presented as the candidate's real record. The only numbers
  are design parameters (cadence frequencies, scorecard scales, relative
  fictional months in the Helios example).
- Dates are relative (M0-relative) inside the fictional example, following
  the dc-delivery-playbook convention, so nothing reads as a real project
  archive.

## 3. Increment check

- dc-delivery-playbook = project layer (one fictional site's schedule,
  risk register, decision log, turnover gate). This package = organization
  layer (charter, hiring, review system, build-out sequence). The review
  pack reuses the *discipline* (baseline vs forecast, decision log) at the
  team-operating level; no text, tables, or files are copied from the
  playbook. Project Helios is shared only as the named fictional example.
- commissioning-gate-kit = acceptance gates. No overlap.

## 4. Boundary restated

This package is local only - not pushed, not published, not sent anywhere.
It does not certify TPM management experience, and its README says so on
the first screen.
