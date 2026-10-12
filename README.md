# Issue/PR closure and bounded improvement

## Use the implementation

The runnable entry for an agent is [SKILL.md](SKILL.md). It directs the agent to perform the task with existing authorized tools; it is not a daemon or a deterministic classifier. An LLM/agent host capable of reading skill files and using the required tools is needed. No sibling repository is required.

1. Obtain this repository through your normal authorized Git workflow, retaining all package files together. Review the skill and resources before adoption.
2. Install the repository folder as a skill named `bounded-improvement` through your host's documented skill installer or skill directory. Do not overwrite an existing customized installation; compare and preserve it first. Hosts without skill discovery can explicitly read `SKILL.md` and its task-relevant resources from the checked-out folder.
3. Invoke it on an actual authorized work item: “Use $bounded-improvement for this actual closed work item. Find an existing retrospective before writing, save the authorized result, and verify readback. For an assigned method experiment, use Entry B instead.” Supply the original goal, existing work-item/destination reference and permitted effects. Let the agent recover available facts rather than supplying fictitious observations.
4. Inspect the actual output and tool effects. A successful file load or syntax check is not actual-use acceptance. Missing tools/authority must be reported precisely rather than replaced with a simulated success.

Updates replace only this package after review; preserve customization, active obligations and history. Removing its skill folder stops future discovery after the host refreshes, not obligations or pending work already created. Follow the host's documented reload behavior; no current-session activation is promised.

Implementation and real-use evidence belong on the [owning work item](https://github.com/jack61714z/bounded-improvement/issues/1) and its linked candidate review. Until those observations are saved, actual use remains pending. Explicit invocation does not prove automatic selection or background event coverage.


## Purpose and adoption boundary

Use actual Issue/PR closure to learn proportionately and validate justified improvements. This guide works with existing review text, closure comments and work-item history. It requires no particular work-order template, tracker product, shared schema/runtime, or companion document/version.

This repository includes an independently invocable agent skill. The package is not activated merely by publication. It grants no operational permission, changes no installed rules and demonstrates no efficacy. Use and redistribution are governed by the MIT license in this repository. Current host privacy, writer, review and effect-specific approval requirements remain effective. Progressive Investigation (PI), an investigation method, and an existing Chat–Codex handoff system (C2C) remain independent with their existing contracts unchanged.

## Cover actual closure and preserve work identity

Here PI means Progressive Investigation, an investigation method, and C2C means Chat/Codex communication tooling. Neither is required to use this guide.

Every actual Issue or PR closure, including cancellation and an unmerged PR, receives a lightweight retrospective from the responsible closure owner. The host must identify that owner and the supported place to save it. A document cannot detect external events: identify whether the real workflow covers all closures or only those it handles, and make any coverage gap explicit rather than inventing a background service.

Use the existing work-unit identity and verified Issue/PR relationships to find a prior retrospective. At a second closure for the same unit, reference the existing retrospective and add only materially new events. Matching titles alone are insufficient for deduplication. Reopening retains history; later closure captures new outcomes where relevant. Updating a tracker does not trigger another task or recursive review.

Related Issues and PRs may share a retrospective reference without being the same work unit. Preserve distinct events, outcomes, failures and decisions; deduplication removes repeated accounts, not independent evidence or unfinished obligations.

## Write the smallest useful retrospective

Use the original intended result, actual cumulative outcome and evidence, closure reason, applicable guidance, and material identity/candidate/scope/authority context. Ordinary prose suffices; no universal list of five fields substitutes for facts needed to make the conclusion reliable.

Record:

- Actual outcome or reason for closure, including what remains unfinished.
- Supported causes or lessons, competing explanations and relevant unknowns. Do not present a hypothesis as a demonstrated cause.
- Whether current guidance already addresses the problem and whether it was actually followed.
- A justified reversible improvement, no change, or deferral, with its reason.
- For an adopted improvement: authority, intended applicability, responsible owner/next action, proportionate validation, failure and rollback conditions.

A single well-supported severe event can justify action; repeated failure is not a prerequisite. Successful recovery is not proof of sustained prevention. No change is a valid outcome, and unnecessary investigation or additional controls should stop when they no longer have decision value.

Place the retrospective in the existing review or equivalent closure account, not a required new record family. If the active host contract requires it inside REVIEW or CHAT_REVIEW, retain that exact obligation. New adopters may use equivalent ordinary text without adopting a named template.

Save only at an authorized destination and read back actual contents before claiming persistence. If a required write or permission is missing, identify it precisely, keep the persistence gap visible and continue unrelated authorized work. Do not claim that a draft or unsaved assertion is stored evidence.

## Improve and verify later use

Apply an improvement only with the authority its effects require. Keep it proportionate and reversible. Check the lesson on the next comparable task, preserving legitimate positive behavior, and record the actual action, result, failures and applicability limits. An improvement can be tracked through the team's existing owner/task mechanism; this guide does not require a new tracker or autonomous hook.

Keep three evidence claims distinct in ordinary result/evidence text:

1. Lesson stored: what was saved and the readback that establishes it.
2. Later application observed: the subsequent task/action, evidence of actual use, and outcome or limits.
3. Application recording verified: the later account was saved in its authorized destination and read back.

None proves the others. Stored advice does not prove use; observed use does not prove its account was saved; a saved claim does not prove the behavior. Unknown claims remain unknown. Evaluate actual end-to-end and overall effects before treating guidance as stable. Better task performance alone does not establish improved self-improvement ability.

An Issue/PR may be closed while a parent outcome, later validation or other obligation remains open. Identify its owner and next action. Do not falsely close the parent merely because a retrospective exists or a local recovery succeeded.

## Bounded recursive improvement of the method

When recursive self-improvement is an intended outcome, explicitly identify the improvement mechanism being changed: for example, how candidates are generated, causes distinguished, experiments designed, or changes evaluated and selected. Fixing a task output or saving a lesson alone does not demonstrate this outcome. Ordinary no-change closures do not require a recursive experiment.

Preserve the current method M0 and the exact proposed change M1 with its rationale and applicable scope. Before evaluation, specify the baseline, comparable task conditions, observable benefit, success criterion, legitimate positive behavior and other non-regression limits, cost budget, and rollback or stopping conditions. Use cases not already consumed to tune the change when claiming generalization. If an evaluation is faulty, preserve the original result and explain the independently justified correction; do not silently relax the target to make a candidate pass.

Evaluate M1 against the baseline and authorize any adoption only within the permitted effects. Record benefit, regression, inconclusive evidence or failure separately from storage and use. Keep a recoverable prior method. A candidate may be rejected, deferred or rolled back; a change that is observed in use is not thereby beneficial.

After bounded adoption or an explicitly bounded trial, observe whether M1 actually participates in generating or evaluating the next improvement-method candidate M2. Preserve which method was loaded, the relevant inputs, actual decisions and evaluation results. A later ordinary task performed better, or a second proposal produced by an unchanged external process, does not by itself establish this recursive link. M2 is evaluated on its own evidence and need not be accepted.

Use the existing responsible actor and authorized records; no autonomous runtime, new tracker or mandatory companion guide is required. Stop or roll back the affected experiment when its predefined conditions require it, evidence is invalid, budget is exhausted, or necessary authority is absent. Do not recursively create new tasks merely because a report was updated. Candidates cannot grant themselves permission, weaken safety boundaries, or redefine the original goal and their own acceptance standard.

Report separately whether a recursive path was observed and whether it improved outcomes at acceptable cost. A bounded M0/M1/M2 lineage provides limited evidence of recurrence, not proof of sustained acceleration, general effectiveness or open-ended autonomous RSI. Until those actions and results exist, this is an unvalidated design.

## Independent use and maintenance

Example: a team adds a short retrospective to its current PR closure review. Its linked Issue later closes and points to that retrospective, adding only new events. Existing rules already covered the defect, so no new rule is adopted. No new template, Notion integration, PI installation or C2C migration is required.

This document owns closure-triggered learning, deduplication and verification of adopted improvements. It does not own seven-axis drift policy, work-order format, task-registration mechanics, event detection or transport. It can receive equivalent existing goal/result records without importing another deliverable. Update it independently; current deployment duties cannot be removed merely by splitting documents or adopting only part of new guidance.

A saved retrospective is not proof of later application, benefit or automatic coverage. No document-revision experiment or efficacy result is claimed.

Replace or remove this guide independently under the active host's authority. Preserve saved retrospectives and assign outstanding validation or rollback duties for adopted changes; removal does not cancel those duties or require sibling changes.

## Revision, maintenance and license

Initial public document revision: 2026-10-12. Maintainer: jack61714z. Corrections may be proposed through this repository. Revised independently; sibling versions are not prerequisites. Publication does not activate this guidance, and behavioral efficacy remains unverified.

This document includes adapted policy and record material from [codex-with-chatgpt](https://github.com/jack61714z/codex-with-chatgpt), licensed under MIT, Copyright (c) 2026 codex-with-chatgpt contributors. New contributions are Copyright (c) 2026 jack61714z. See [LICENSE](LICENSE) for the complete MIT terms and preserved notices.

