# Team Charter and RACI - DC Infrastructure TPM Function

> **DESIGN ARTIFACT.** This charter is a design written by the candidate to
> show how he would charter the function. It is not the charter of a team he
> currently manages, and adopting it (or anything like it) would be a
> decision for the hiring organization, not a description of one.

## Mission

The DC Infrastructure TPM function exists to make multi-site data center
delivery legible and decision-ready: one converged picture of schedule,
risk, and dependencies per site and across the portfolio, maintained
early enough that leadership decisions can still change outcomes.

In one sentence: **status is cheap; converged, decision-ready risk is the
product.**

## Scope

In scope:

- Integrated delivery schedule per site (construction through turnover) and
  the portfolio roll-up across concurrent sites.
- Risk, dependency, and decision records for the delivery portfolio -
  owned, current, and reviewed on cadence (see 02-program-review-pack.md).
- Handover criteria between site completion, equipment deployment, and
  operations, and the turnover gate discipline.
- Long-lead and long-pole dependency tracking across sites, in partnership
  with the supply chain delivery function (which owns equipment line items;
  this function owns the site-level integration of their dates).
- Program reviews and executive communication on delivery status, risks,
  and blockers.

Out of scope (owned by partners, interfaced - not absorbed):

- Commercial terms, sourcing strategy, and contract claims (Sourcing /
  Legal). The TPM function's product there is verified schedule evidence.
- Construction means and methods (the GC and Construction org).
- Compute capacity allocation policy (Compute org).
- Site selection decisions (Energy and Location Strategy) - the function
  supplies delivery-risk assessment into due diligence, not the decision.

## Operating principles

1. **Verify, do not relay.** A partner's date is a claim until evidence
   supports it. TPMs are accountable for the evidence layer, not for
   forwarding status.
2. **Baseline discipline.** Baselines move only through recorded decisions.
   Forecast can move freely; conflating the two is the one unforgivable
   reporting sin.
3. **Decisions over updates.** Every review item ends in a decision, a
   named owner, or an explicit "watch" with a trigger - never in "noted".
4. **Write it once, use it everywhere.** One tracker, one risk register,
   one decision log per portfolio; slides are views of those records, not
   parallel truths.
5. **Escalate early, with options.** An escalation carries the problem,
   the options, the cost of each, and a recommendation - brought while
   options still exist.

## Interfaces and RACI

R = responsible (does it), A = accountable (owns the outcome),
C = consulted, I = informed. "DC TPM" below is this function.

| Activity | DC TPM | Construction / GC | Compute | Security and Compliance | Energy / Location Strategy | Operations (receiver) | Supply Chain Delivery (OFE) |
|---|---|---|---|---|---|---|---|
| Integrated site delivery schedule | A/R | C | C | C | I | C | C |
| Portfolio risk register and delivery reviews | A/R | C | C | C | I | C | C |
| Construction execution and sequencing on site | C | A/R | I | C | I | I | I |
| Equipment line-item delivery (PO to ROS) | C | I | I | I | I | C | A/R |
| Site selection and due diligence decision | C (delivery-risk input) | C | C | C | A/R | C | I |
| Energy / utility interconnection strategy | C | C | I | I | A/R | I | I |
| Handover criteria definition | A/R | C | C | C | I | A (acceptance) | C |
| Turnover gate decision | R | C | I | C | I | A (accept or reject) | C |
| Security/compliance requirements into design | C | C | C | A/R | I | C | I |
| Capacity allocation across sites | C | I | A/R | I | C | C | I |
| Change / claim commercial process | C (schedule evidence) | C | I | I | I | I | A/R with Sourcing |
| Executive delivery reporting | A/R | C | C | C | I | C | C |

Two interface rules worth stating in the charter itself:

- **Turnover has two accountable parties on purpose:** the TPM function is
  accountable for running the gate; Operations is accountable for accepting
  or rejecting. Collapsing those into one owner is how weak handovers get
  signed.
- **The OFE boundary:** equipment delivery dates are owned by Supply Chain
  Delivery; this function owns what those dates do to the site schedule.
  Disagreement about a date is resolved on evidence (see the verification
  discipline), not on org seniority.

## Team shape (design, sized to a growing multi-site portfolio)

- TPM Lead (the founding manager role this package is written from):
  charter, review cadence, executive interface, hiring.
- Site TPMs: one per active site (or per two smaller concurrent sites),
  owning that site's integrated schedule, risks, and turnover path.
- Portfolio / program TPM: cross-site dependencies, long-pole items,
  portfolio reporting, and the shared records discipline.
- First hires are Site TPMs for the sites with the nearest turnover dates -
  the reasoning and sequence are in 03-30-60-90-plan.md.
