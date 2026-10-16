---
name: funding-portfolio-manager
description: Maintain and strategically develop a research funding portfolio across NIH and other sponsors. Use when reviewing, updating, triaging, or planning a PI-level grant pipeline; reconciling submitted, pending, planned, scored, or resubmission applications; evaluating new NOFOs or foundation opportunities; checking scientific overlap and distinctness; planning submission capacity; conducting next-cycle reviews after scores, summary statements, or funding decisions; preparing collaborator funding discussions; or converting an existing funding portfolio into a current-state decision document. Particularly suited to academic biomedical research portfolios with multiple related disease and methods programs.
---

# Funding Portfolio Manager

Treat the portfolio as a **current-state strategic decision document**, not a historical activity log or catalog of funding mechanisms.

Read `references/portfolio-model.md` when creating or materially restructuring a portfolio. Read `references/decision-rules.md` when triaging opportunities, overlap, submission cadence, or collaborator-dependent decisions.

## Core workflow

1. Establish the authoritative current state.
   - Treat the user's latest portfolio, application files, status updates, and explicit corrections as controlling.
   - Distinguish `established`, `planned`, `proposed`, `pending collaborator decision`, and `unresolved` facts.
   - Never infer submission, funding, review outcome, eligibility, collaborator commitment, available data, budget, or institutional approval.

2. Reconcile before expanding.
   - Identify stale statuses, completed development tasks, passed deadlines, obsolete opportunities, duplicate headings/entries, and generic calendar placeholders.
   - Keep every genuinely active application visible from development through final disposition.
   - Retire completed tasks and opportunities that no longer require a decision.
   - Do not preserve history merely for completeness; repository history or submission logs can hold archival detail.

3. Review exactly one active topic at a time unless the user asks for a full review.
   - Begin with a short prioritized checklist.
   - Label decisions/actions as **Recommendation**, **Action for assistant**, **Action for user**, or **Verified complete**.
   - Stop after resolving the active topic and wait for `next` before advancing.
   - Defer later-topic issues rather than silently broadening scope.

4. Evaluate opportunity fit before drafting an application.
   - Verify the current NOFO/program announcement, sponsor rules, deadlines, eligibility, award scope, and relevant policy from authoritative sources when claims are live or time-sensitive.
   - Determine whether the opportunity is a natural scientific home or would force the science into the mechanism.
   - Prefer scientific fit over institute diversification, but recognize diversification as strategically useful when it follows genuine scientific differentiation.
   - Compare expected scientific/funding value with application burden, opportunity cost, required memberships, review obligations, collaborator enthusiasm, and other active deadlines.

5. Protect scientific distinctness and overlap.
   - Shared software, infrastructure, expertise, and scientific principles are acceptable.
   - Each application should remain independently compelling if the other portfolio programs disappeared.
   - Compare central question, disease biology, cohorts/data, hypotheses, aims, validation, endpoints, deliverables, personnel effort, and proposed methodological development.
   - Treat shared infrastructure as enabling infrastructure, not repeatedly proposed funded deliverables.
   - Flag possible scientific or budget overlap before recommending parallel submissions.

6. Use collaborator judgment as an explicit decision gate when appropriate.
   - For disease-specific mechanisms, ask whether domain collaborators regard the opportunity, scientific question, community, and experimental plan as worthwhile.
   - Record `hold pending collaborator feedback` when that is the actual state.
   - Do not convert anecdotal concerns about a sponsor into factual allegations; abstract them into decision-relevant considerations such as expected value, burden, prior experience, or collaborator enthusiasm.

7. Plan submission cadence without letting cadence dictate science.
   - Verify current sponsor submission limits before encoding them as policy.
   - Distinguish concrete submission targets from uncommitted future capacity.
   - Do not populate empty A0/A1 cycles simply to fill calendar slots.
   - It is acceptable to retain a concrete target whose scientific program is still TBD when the user has explicitly committed to filling that submission slot; label it honestly.
   - Use review outcomes to decide which applications merit resubmission rather than prospectively assigning every future A1.

8. Keep PI-level portfolio scope disciplined.
   - Default to PI/multi-PI opportunities and applications.
   - Add trainee mechanisms only when a specific trainee/application is part of the active program, unless the user asks for a broader lab-funding portfolio.
   - Keep disease-foundation watch items only when a collaborator, cohort, genotype, or concrete decision makes them actionable.

## Next-cycle portfolio review

Run this workflow when reviews, scores, funding decisions, or a new submission year make it possible to reallocate the pipeline. Do not treat every unsuccessful A0 as an automatic A1.

1. Reconcile the disposition of every prior-cycle application.
   - Preserve funded, pending, scored, and unresolved applications with their current status.
   - Identify unsuccessful applications that are eligible and scientifically plausible for resubmission.
   - Do not infer review outcomes or funding decisions that the user has not supplied or that have not been authoritatively verified.

2. Evaluate each potential A1 independently.
   - Assess reviewer signal, repairability of the identified weaknesses, continued scientific value, amount of restructuring required, and need for new analyses/data.
   - Distinguish finite actionable weaknesses from criticism that implies the scientific architecture itself should change.
   - Prefer an A1 when the prior review provides a credible repair path; prefer rebuilding as a new A0 when revision would require a substantially different project or when the prior review would constrain the stronger design.

3. Rank rather than automatically resubmit.
   - Compare candidate A1s against one another for expected value, effort, timing, collaborator readiness, and strategic fit.
   - Retire or defer weak trajectories even when a resubmission is technically allowed.
   - Keep funding-decision-pending applications out of speculative resubmission planning until timing and sponsor rules make contingency planning appropriate.

4. Recheck portfolio distinctness and overlap.
   - Compare surviving A1 candidates, funded/pending projects, and proposed new A0s for duplicated aims, datasets/cohorts, deliverables, methodological development, personnel effort, and scientific questions.
   - Adjust or retire projects when the new portfolio state creates overlap that did not exist in the prior cycle.

5. Recalculate submission capacity.
   - Verify the sponsor's current PI/MPI submission-limit policy for the new period.
   - Account for already committed or submitted applications before allocating remaining capacity.
   - Distinguish PI/MPI submissions from participation in roles that do not count toward the applicable limit.

6. Allocate the next cycle deliberately.
   - First reserve capacity for the strongest repairable A1s whose timing is appropriate.
   - Use remaining capacity for genuinely distinct, sufficiently mature A0s.
   - Do not invent new projects merely to exhaust the submission allowance; an explicitly committed TBD slot is acceptable only when the user has chosen that strategy.

7. Rebuild the current-state plan.
   - Update statuses, calendar, overlap notes, and immediate-action queue only after the A1/A0 decisions are made.
   - Identify the analyses, collaborator decisions, preliminary data, or drafting milestones needed for each selected submission.
   - Record why deferred or retired applications are not being advanced, without turning the portfolio into a historical log.

At the end of a next-cycle review, the portfolio should make clear: which prior applications remain active; which unsuccessful applications will become A1s; which will be rebuilt, deferred, or retired; how much verified PI/MPI submission capacity remains; which new A0s occupy that capacity; and what evidence or work controls each next decision.

## Opportunity statuses

Prefer a compact controlled vocabulary, adapted when needed:

- `watching`
- `evaluating`
- `hold pending collaborator feedback`
- `planned`
- `priority development`
- `drafting`
- `draft complete / final human review pending`
- `submitted / pending review`
- `scored / funding decision pending`
- `resubmission planned`
- `funded`
- `declined`
- `retired / not pursuing`

Do not call an application `submitted` until the user confirms submission or supplies authoritative evidence.

## Current-state maintenance rule

Retain active applications from development through final disposition, including applications awaiting submission, submitted applications under review, scored applications awaiting funding decisions, and planned resubmissions. Remove completed development tasks, obsolete mechanisms, generic searches that yielded no actionable opportunity, and stale calendar placeholders.

Each active entry should answer:

- What is it?
- Why is it in the portfolio?
- What is its current status?
- What unresolved dependency controls the next decision?
- What is the next action?

## New opportunity triage

For a newly identified NOFO or funding mechanism:

1. Verify sponsor, mechanism, participating institute/program, deadline, eligibility, project period/award constraints, and scientific scope.
2. Identify explicit responsiveness/nonresponsiveness requirements.
3. Compare with the existing portfolio for scientific overlap and reviewer-home concentration.
4. Decide whether it creates a genuinely different scientific architecture or merely relabels an existing proposal.
5. Identify missing collaborator/data/experimental facts before proposing aims.
6. Classify as `priority`, `secondary`, `watch`, `hold`, or `retire` with rationale.
7. Update calendar and immediate-action queue only if the opportunity survives triage.

## Collaborator-meeting preparation

When a funding direction depends on a collaborator, prepare a working discussion sheet before drafting Specific Aims. Focus on:

- available cohorts, samples, datasets, and candidate findings;
- strongest unresolved biological or clinical question;
- what each group uniquely contributes;
- feasible experimental/validation capacity;
- computational contribution that materially changes experiments or inference;
- leadership and division of responsibility;
- fit to the candidate mechanism without forcing the science;
- competing funding routes and whether any should be retired;
- decisions and immediate analyses needed after the meeting.

Label possible aim architectures as hypotheses to test with the collaborator, not established plans.

## Editing an existing portfolio

Preserve useful structure and terminology unless there is a reason to change them. Favor incremental edits over parallel documents or redundant sections.

When updating:

- revise `Last updated`;
- reconcile current applications first;
- remove historical action items that are complete;
- preserve pending applications even when drafting is complete;
- update opportunity status and next action;
- reconcile the calendar with the narrative sections;
- reconcile the immediate-action queue with actual unresolved work;
- check section numbering and duplicate headings after programmatic edits;
- check collaborator names and institutional affiliations against user-supplied facts or authoritative sources when material.

Before returning an edited file, search for duplicate headings, stale dates/statuses, references to retired opportunities, and contradictions between narrative, calendar, and action queue.

## Evidence discipline

Use the user's portfolio and application materials as the source of truth for project-specific facts. Use authoritative external sources for current sponsor rules, NOFO requirements, deadlines, eligibility, and policy. Explicitly distinguish verified external facts from portfolio strategy and collaborator-dependent assumptions.

Do not invent:

- cohorts, family counts, variants, preliminary data, experimental throughput, or model-system capacity;
- collaborators or their commitments;
- review outcomes or funding likelihood;
- budgets or institutional resources;
- human-subjects, genomic-data-sharing, or regulatory determinations.

## Output style

Keep strategic reviews concise and decision-oriented. Prefer a short checklist followed by the single active topic. Give advantages and disadvantages when the decision is genuinely exploratory, then make a recommendation when evidence supports one.

When the user asks for the full revised portfolio, produce a clean current-state document following `references/portfolio-model.md`. When the user asks only to review or plan, do not rewrite the whole portfolio prematurely.
