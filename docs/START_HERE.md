# A field guide to Initiative 31

[Home](../README.md) · [Cheat sheet](CHEATSHEET.md) · [Examples](EXAMPLES.md)

## The idea

Eclipse SWT presents a Java widget API while its existing implementations rely on OS-specific components. Initiative 31 investigated whether a new implementation could preserve compatibility while sharing more work across platforms and enabling more control over widgets and rendering.

The [preserved profile](../profile/README.md) describes an evaluation project, its technology selection, and a Skia/custom-widget demonstrator. Its [final report](https://github.com/swt-initiative31/documents/blob/main/report/overall_report.md) is the detailed source for results and remaining implementation work. A feasibility demonstration and a complete production implementation are different stages.

## Three useful reading routes

### New to the topic

1. Read Summary in the [original profile](../profile/README.md#summary).
2. Read the final report's executive summary and Goal.
3. Read [the brainstorming disclaimer](../profile/Brainstorming.md#disclaimer) before interpreting the wish list.
4. Use the glossary below when a term is unfamiliar.

### Evaluating whether to contribute

1. Read the report's Results and Realization Plan.
2. Follow the specific prototype repository linked there and inspect its current branch, instructions, and limitations.
3. Choose a concrete question, documentation gap, or reproducible experiment.
4. Check the original profile's current contact guidance before contacting anyone; this repository does not establish response times or maintainer commitments.

### Checking a historical claim

1. Record the document path and commit.
2. Determine whether it is a wish, measured observation, interpretation, or proposed future work.
3. Follow the original evidence and compare its date with the final report.
4. State what you did not reproduce. Do not turn a screenshot or demonstration into a general compatibility guarantee.

## Vocabulary

| Concept | Reader-friendly meaning |
| --- | --- |
| SWT | Eclipse Standard Widget Toolkit; the API and behavior being investigated |
| OS-agnostic | Sharing implementation across operating systems while still handling necessary platform integration |
| Rendering engine | A library that draws; it does not by itself supply a complete set of widgets or SWT semantics |
| Skia | The rendering technology used in the demonstrator described by the project |
| Custom widgets | Widget behavior and appearance implemented above drawing operations instead of simply reusing every native widget |
| Prototype | A focused experiment that can answer a particular feasibility or risk question |
| Demonstrator | An integrated example showing feasibility, still distinct from a supported production product |
| Brainstorming wish | A participant preference, explicitly not a required feature in this repository's brainstorming record |

## Repository roles

| Location | Role |
| --- | --- |
| This fork | A preserved community record with added reader guides |
| [Upstream `.github` repository](https://github.com/swt-initiative31/.github) | Original organization profile and community information |
| [Upstream documents repository](https://github.com/swt-initiative31/documents) | Reports, assessments, meeting material, and links to implementation evidence |
| [Upstream organization](https://github.com/swt-initiative31) | Public home for the project's related repositories |
| Prototype repositories linked by the reports | Code-specific setup, branches, experiments, and limitations |

The fork's name `initiative31-community` does not make it the upstream organization's special `.github` repository. Editing its profile file here does not update the upstream organization profile.

## Scope and provenance

At the baseline documented in the [root README](../README.md), the parent and fork had the same commit. This added guide supplies orientation and workflows; it supplies no new implementation or independent performance/compatibility result. Original material and licensing remain in their original files.

The profile says the project has concluded and that its organization remains available for further work. That is historical/public project context, not an invitation to assume any named contributor will review a new request. Use their published contact guidance and keep requests specific.
