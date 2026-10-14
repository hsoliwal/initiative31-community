# Community documents and contribution boundaries

[Home](../README.md) · [Field guide](START_HERE.md) · [Cheat sheet](CHEATSHEET.md) · [Examples](EXAMPLES.md)

## What this project contains

This public fork preserves the community documents from [swt-initiative31/.github](https://github.com/swt-initiative31/.github) and adds reader guides. It describes the initiative, its research context, and routes to the original results. It is not a widget implementation, build project, or a replacement for the upstream organization's profile.

The complete tracked tree at [commit `95af118`](https://github.com/hsoliwal/initiative31-community/tree/95af118cc6ce7d24d522248780100a35e258cb27), inspected on 2026-10-14 before this map was added, has seven files: six Markdown documents and one license. Its two directories are `docs/` and `profile/`. No source packages, build manifests, executable tests, workflow definitions, submodules, `AGENTS.md`, or `CONTRIBUTING` files occur in that snapshot. Java/module/API documentation therefore belongs to the linked implementation repositories, not to invented modules in this one.

## Every tracked document and its role

| Path | Role | Interpretation boundary |
| --- | --- | --- |
| [README.md](../README.md) | Fork landing page and reader index | Fork-specific orientation; does not announce a new initiative |
| [profile/README.md](../profile/README.md) | Preserved project summary, organization rationale, results links, and contact guidance | The project's own description of its concluded evaluation and demonstrator; not a current runtime test or a promise of maintainer availability |
| [profile/Brainstorming.md](../profile/Brainstorming.md) | Prioritized participant wishes from a hackathon | Its [disclaimer](../profile/Brainstorming.md#disclaimer) explicitly says these are not required features |
| [docs/START_HERE.md](START_HERE.md) | Vocabulary, reading routes, repository roles, and evidence distinctions | Navigation/interpretation, rather than implementation or new research |
| [docs/CHEATSHEET.md](CHEATSHEET.md) | Reading commands, question/change checklists, and citation workflow | Document inspection; no application build or test instructions |
| [docs/EXAMPLES.md](EXAMPLES.md) | Sample technical question, wish-to-question conversion, navigation proposal, and evidence note | Reviewable templates with placeholders, not measured experiment results |
| [LICENSE](../LICENSE) | Retained Eclipse Public License 2.0 text | Preserve it and original attribution; this guide does not establish new licensing permissions |

This map is an additional fork guide. `profile/` is the preserved community record; `docs/` is the reader/contributor layer. Neither directory is a runtime module, namespace, or distributable package.

## Evidence flows outward to the research

The [profile](../profile/README.md#results) links to the original documents repository and its final report. Those reports link onward to implementation experiments. The relationship is:

1. **Community record:** explains the initiative and how to find its published material.
2. **Research documents:** explain the goals, assessments, reported outcomes, and proposed next steps.
3. **Implementation repositories:** own the actual code, manifests, packages, setup instructions, and test evidence.

The repository links are references, not build dependencies. Reading a profile can establish what the project says about itself; it cannot establish a method signature, package export, passing build, or present-day platform support in another repository.

The profile describes the custom-widget/Skia demonstrator as a successful feasibility result and says a production-ready implementation still required further work. The guides retain that distinction. They do not treat the brainstorming wishes as requirements or the profile's confidence in feasibility as independent production certification.

## Choose the destination by what changes

| Reader need or change | Destination and boundary |
| --- | --- |
| Correct this fork's navigation or explain a term | This fork's `README.md` or `docs/`; cite the relevant public record |
| Correct the original profile or published contact guidance | The [upstream `.github` repository](https://github.com/swt-initiative31/.github), after checking its current instructions; a fork edit does not update that profile |
| Clarify a historical research result | The document/section linked by the profile, with its exact revision and experiment scope |
| Document or fix a widget, GC behavior, package, or build | The particular implementation repository, after inspecting its code and contribution instructions |
| Propose a feature mentioned in brainstorming | Begin with an evaluation question, not an assertion that maintainers promised the feature |

Do not assume that a historical contact is still responsive. The [Contacts section](../profile/README.md#contacts) warns that channels may close. This documentation pass did not send messages, join channels, or verify invitations.

## Worked example: browser integration

The [brainstorming list](../profile/Brainstorming.md#the-list) places browser integration first. The adjacent disclaimer limits that statement to participant wishes. A faithful summary is: “Participants prioritized browser integration as an evaluation concern.” It would not support “browser integration is implemented in every prototype.”

To ask the next useful question, identify the technology and report section, then distinguish reported behavior from an experiment you actually ran:

```text
Question: What browser behavior did this particular prototype demonstrate?
Public report and commit: <URL and revision>
Technology / phase: <the exact experiment>
Source says: <reported result and its limitation>
My reproduction: <actual steps and result, or not run>
Still unknown: <the precise missing evidence>
```

Keep private project context out of public contributions. A clear question and public source are enough; no personal contact details or unrelated documents need to be copied into an issue.

## Review and completion criteria

- **Inventory:** account for all seven baseline files and the new guide; the baseline is a complete recursive tree, not just the root listing
- **Meaning:** compare project summaries with `profile/README.md` and wishes with the brainstorming disclaimer; preserve credits and uncertainty
- **Navigation:** check the exact paths and heading fragments of local links, and verify new external targets separately
- **Presentation:** preview the changed Markdown; static path checks alone do not prove rendered layout
- **Scope:** inspect changed paths and the diff; documentation changes do not authorize code, build, workflow, license, or upstream-profile changes
- **Verification record:** record the documentation revision, checks actually performed, results, and checks not run; distinguish prototype tests from document review

All six baseline Markdown documents were read for this map. The repository/package/module classification is complete for this pinned document-only snapshot; it does not complete any external implementation's package or API documentation. There is no repository application build/test surface to execute here. Prototype builds and GUI/platform checks were **not run**, and historical external services and contact availability remain unverified.
