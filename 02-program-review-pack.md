# Program Review Operating Pack - Status / Risk / Decision

> **DESIGN ARTIFACT.** Templates and cadence below are a designed operating
> system for the function, written by the candidate. The one filled example
> (Section 5) uses **Project Helios, a fictional project** - the same
> invented project used in the dc-delivery-playbook - and is labelled
> fictional there. It is not a record of a review the candidate has run.

## 1. The three records (the whole system)

The pack runs on three records, and nothing else:

1. **Status** - per site: baseline vs forecast for the governing milestones,
   with variance explained in one line each. Status answers "where are we
   against what we promised?"
2. **Risk** - the portfolio risk register view: top risks by exposure, each
   with owner, mitigation, trigger signal, and decision date. Risk answers
   "what can still change the answer to question 1?"
3. **Decision** - the decision log view: what was decided, by whom, on what
   evidence, and which baseline/forecast each decision moved. Decisions
   answer "what did we choose, and what did it cost?"

Every review, at every level, is these three views in this order. New
formats are not invented per audience; seniority changes the altitude of
the same three views, not their structure.

## 2. Exec one-pager template

```text
PROGRAM: <name>            DATE: <date>        AUTHOR: <TPM>
HEADLINE: <one sentence: the decision-relevant state of the program>

MILESTONES (baseline / forecast / variance)
  <milestone>   <base>   <fcst>   <+/->   <one-line cause if variance != 0>

TOP RISKS (max 3 on this page)
  R-#: <risk> | exposure <P x I> | owner <name> | decision needed by <date>

DECISIONS ASKED TODAY (max 2)
  D-#: <decision> | options: <A/B> | costs: <...> | recommendation: <...>

WATCH LIST (no decision today; trigger stated)
  <item> | trigger: <observable event> | next check: <date>
```

Rules: one page means one page; anything that does not fit is an appendix
the reader may open, not a second page of the brief. A one-pager with no
decision asked and no variance is a valid one-pager - it says the program
is boring this week, in writing.

## 3. RAG and variance definitions

RAG is defined on the **governing milestone forecast vs baseline**, never
on effort or sentiment:

- **Green:** forecast on or ahead of baseline, and no open risk with a
  decision date inside 30 days that can move the milestone.
- **Amber:** forecast slip up to the site's float, or a Green milestone with
  a live risk whose decision date falls inside 30 days. Amber is a working
  state, not a warning colour.
- **Red:** forecast slip beyond float (the milestone date itself moves), or
  any slip whose recovery options require a decision above this forum.

Variance is always reported as six elements, in this order: Baseline /
Forecast / Variance / Impact / Owner / Mitigation + Decision date. A
variance report missing the decision date is returned for rework - a slip
without a decision date is just anxiety with formatting.

## 4. Cadence and escalation norms

| Forum | Frequency | Attendees (design) | Input | Output |
|---|---|---|---|---|
| Site delivery review | Weekly | Site TPM, Construction, OFE delivery, Cx | Site status/risk/decision views | Updated records; L1 escalations |
| Portfolio delivery review | Weekly (offset from site reviews) | TPM Lead, Site TPMs, Portfolio TPM | Portfolio roll-up; cross-site dependencies | Cross-site decisions; float trades recorded |
| Executive program review | Monthly, and on demand when a governing milestone goes Red | Leadership, TPM Lead, partner org leads | Exec one-pagers per program | Decisions at L4; re-baselines only here |

Escalation norms: escalate when the decision needed sits above your forum,
or when a recovery option expires before the next scheduled forum -
whichever comes first. Escalations carry options and a recommendation
(charter principle 5). Escalation cycle time (opened to decided) is
reviewed monthly; a slow ladder is treated as a delivery risk, not an
administrative fact.

## 5. Filled example - FICTIONAL (Project Helios)

> **FICTIONAL EXAMPLE.** Project Helios is an invented project (a fictional
> MW-scale liquid-cooled site build, shared with the dc-delivery-playbook
> so the packages read together). Names, months, and figures below are
> illustrative only. Months are relative (M0 = site handoff).

```text
PROGRAM: Helios (fictional)   DATE: Month M14 review   AUTHOR: Site TPM (example)

HEADLINE: Turnover forecast slips 1.0 month on utility energization;
recovery to +0.5 is available if the switchgear resequence is approved today.

MILESTONES (baseline / forecast / variance)
  Utility energization   M16.0 / M17.0 / +1.0   utility feeder work lags plan
  Commissioning L3 start M17.5 / M18.0 / +0.5   follows energization
  Turnover (TO-01)       M20.0 / M20.5 / +0.5   partial recovery via resequence

TOP RISKS
  R-04 Utility interconnection delay | exposure High | owner: Energy partner
       | decision needed by: this review
  R-07 Switchgear delivery drift     | exposure Med  | owner: OFE delivery
       | decision needed by: M15 W2

DECISIONS ASKED TODAY
  D-06 Approve resequencing Hall B fit-out ahead of energization, consuming
       0.5 month of Hall B float to protect turnover.
       Options: A resequence (cost: float) / B hold sequence (cost: full slip)
       Recommendation: A.

WATCH LIST
  Cooling plant factory test | trigger: FAT result notice | next check: M15 W1
```

Reading note: the example shows the discipline the pack is testing for -
baseline untouched (M20.0), forecast honest (+0.5 after recovery), exactly
one decision asked, and the float cost of the recommendation stated instead
of hidden.
