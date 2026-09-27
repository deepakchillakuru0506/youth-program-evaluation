# Youth Program Evaluation — outcomes across three cohorts

A data and evaluation engagement with a youth-wellness nonprofit: turning program records and
open-ended participant feedback into the outcome numbers the organization needed to report to its
board and funders. I served as the volunteer Data & Evaluation Analyst.

## The problem

The organization ran three cohorts of a wellness program and collected a lot of material — session
attendance records, pre/post feedback and perception measures, and free-text comments at the end of each cycle —
but had no consistent way to say what the program was achieving. Session records were kept in separate spreadsheets per cohort with no shared definition of the
outcome measures, and the qualitative feedback had never been systematically read. The
organization needed to report outcomes to its board and funders, and did not have a consistent
answer.

## Approach

1. **Consolidate the records.** Reconciled session-level attendance and outcome data from three
   cohorts into one model — 402 participant records across 23 sessions — standardising participant
   identifiers and session labels so cohorts were comparable.
2. **Build the KPI layer.** Modelled the consolidated data in Excel Power Query so the outcome
   metrics refresh from the source files instead of being recalculated by hand each cycle. That
   running layer is the part with lasting value; the first report is not.
3. **Code the qualitative feedback.** Thematic analysis over 320+ open-ended responses, coded into
   recurring themes — 188 distinct comments and 132 explicit recommendations, grouped rather than
   counted once each.
4. **Report outcomes against the program's own goals** — retention intent, wellbeing improvement,
   and learning effectiveness — with the qualitative themes used to explain the numbers rather than
   sit beside them.

## What the evaluation found

| Outcome measured | Result |
|---|---|
| Retention intent | 82.6% |
| Wellbeing improvement | 81.8% |
| Learning effectiveness | 58.7% |
| Qualitative responses coded | 320+ (188 comments, 132 recommendations) |
| Participant records consolidated | 402 across 3 cohorts, 23 sessions |

The pattern worth reporting: participants and their families consistently intended to return and
reported improved wellbeing, while learning effectiveness scored materially lower. Read together
with the coded feedback, the weaker score traced to how content was delivered rather than to the
content itself — which is the kind of finding a program can act on within a single cycle.

## Why the raw data is not published

This repository contains the evaluation write-up and aggregate findings only. The participant-level
records, attendance rosters, and verbatim comments are withheld deliberately: the consent obtained
covered program participation and internal reporting, not public disclosure, and the cohorts are
small enough that anonymised rows and short quotations would still identify individuals. The
aggregate results above are the defensible output of the engagement, and releasing anything finer
would breach the trust the data was collected under.

## Files

| File | What it is |
|---|---|
| `findings_summary.csv` | The aggregate outcome metrics in machine-readable form |

## Method notes and next steps

The evaluation measures perception change, not causal program effect — there is no control group,
and participants self-select into the program. Reporting it honestly means saying that: these are
participant-reported outcomes across three cohorts, which is enough to steer program delivery and
not enough to claim attribution. With another cycle, the priority would be a consistent pre/post
instrument from the start, so the next comparison does not depend on reconciling three different
historical formats.
