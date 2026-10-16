# Initiative 31 community reader hub

**Understand the SWT research, find the original results, and enter the conversation with context.**

This public fork preserves the community profile from [swt-initiative31/.github](https://github.com/swt-initiative31/.github). Initiative 31 investigated an OS-agnostic implementation of Eclipse's Standard Widget Toolkit. Its published profile says the project concluded with a Skia-based demonstrator and a final report, with further work needed for a production-ready implementation.

<!-- fork-homepage:start -->
## Understand the project without confusing its repositories

Initiative 31 asked whether Eclipse SWT could retain its familiar Java API while sharing more implementation across operating systems. The community record explains the motivation and directs readers to the final research and prototypes. Use this repository to orient yourself, understand participant wishes, and prepare a source-backed question. The implementation lives in the repositories linked by the report.

The original organization profile belongs to `swt-initiative31/.github`. This fork's name, `initiative31-community`, does not make it the official organization profile: editing a file here changes only this fork. Its added guides are documentation contributions, not a new SWT implementation or a commitment from the original participants.

## Concepts in plain language

| Term | Meaning |
| --- | --- |
| SWT | Eclipse Standard Widget Toolkit: the API and behavior the project investigated |
| OS-agnostic | Sharing code across operating systems while retaining necessary platform integration |
| Renderer | A drawing engine; it does not by itself supply every widget, event, or accessibility behavior |
| Custom widget | Widget behavior and appearance implemented above drawing operations |
| Prototype / demonstrator | A focused experiment / integrated feasibility example; neither word guarantees a production release |
| Brainstorming wish | A participant preference, explicitly not an agreed feature requirement |
| Reported / reproduced result | What a source says happened / what a documented experiment independently observed |

## Quick start: a five-minute reading route

1. Read the [preserved profile](profile/README.md) for the initiative's scope and conclusion.
2. Open the [final report](https://github.com/swt-initiative31/documents/blob/main/report/overall_report.md) for the demonstrated result and remaining implementation work.
3. Read the [brainstorming disclaimer](profile/Brainstorming.md) before treating any wish as a requirement.
4. Pick a specific question or contribution, then use the [field guide](docs/START_HERE.md) to find the appropriate repository.

There is no application to install here. If you want local searchable documents, Git is enough:

```sh
git clone --depth 1 https://github.com/hsoliwal/initiative31-community.git
cd initiative31-community
git rev-parse HEAD
git ls-files
git grep -n -i 'demonstrator' -- profile
```

The commands only obtain and inspect files. They do not verify historical contacts, build a prototype, or reproduce a research result; a shallow clone includes limited history.

## Worked example: turn a wish into an answerable question

The brainstorming record mentions browser integration. Instead of converting it into “browser support is guaranteed,” ask: “Which browser-integration behavior was shown by this particular prototype, at which revision, and what remains unverified?” Link the relevant assessment or code, explain what you read, and identify one missing fact.

A compact question can contain:

```text
Topic: the specific technology or behavior
Source: public report or code link, revision, and section
My understanding: one statement supported by that source
Question: the remaining uncertainty
Checked: documents read or experiment actually run
```

For code behavior, include the environment and expected/actual result. For historical text, include its date and distinguish a wish, observation, conclusion, and proposal. Use public evidence; remove credentials and non-public context before posting elsewhere.

## Community cheat sheet

| Need | Best next step |
| --- | --- |
| Understand the original initiative | [Preserved profile](profile/README.md) |
| Check what was actually concluded | [Final project report](https://github.com/swt-initiative31/documents/blob/main/report/overall_report.md) |
| Interpret a participant wish | [Brainstorming record and disclaimer](profile/Brainstorming.md) |
| Find a focused contribution | [Field guide](docs/START_HERE.md) and [worked examples](docs/EXAMPLES.md) |
| Inspect document history locally | `git log -5 --oneline -- profile/README.md` |
| Review your changes | `git diff -- README.md docs profile` and `git diff --check` |
| Locate contact guidance | The preserved profile's Contacts section; check current availability before use |

A finished demonstrator does not establish full platform parity, funding, a release date, or participant availability. The [collection map](docs/CONTENT_MAP.md) explains the document boundaries, and the [full cheat sheet](docs/CHEATSHEET.md) helps keep future corrections evidence-backed.

<!-- fork-homepage:end -->

## Start here

| You want to… | Open |
| --- | --- |
| Understand the initiative in five minutes | [Original project profile](profile/README.md) |
| Find the goals, results, and next implementation steps | [Final project report](https://github.com/swt-initiative31/documents/blob/main/report/overall_report.md) |
| See every document and contribution boundary | [Collection map](docs/CONTENT_MAP.md) |
| Learn the vocabulary and repository roles | [Community field guide](docs/START_HERE.md) |
| Choose the right project or contribution destination | [Next-step map](docs/START_HERE.md#choose-a-next-step-not-just-a-repository) |
| Distinguish wishes, results, and future work | [Evidence guide](docs/START_HERE.md#what-evidence-supports-a-community-answer) |
| Find a quick reading or contribution workflow | [Community cheat sheet](docs/CHEATSHEET.md) |
| Ask a useful technical question | [Worked examples](docs/EXAMPLES.md) |
| See historical participant wishes | [Brainstorming notes](profile/Brainstorming.md), including their disclaimer |

## What this fork adds

This fork adds a repository landing page and practical reader/contributor guides. The inherited [profile](profile/README.md), [brainstorming record](profile/Brainstorming.md), and [EPL-2.0 license](LICENSE) are preserved. These guides do not announce a new initiative, change the project's conclusions, or speak on behalf of its participants.

This repository contains community documents, not a runnable SWT distribution. No application installation or build step is required to read it.

At the documentation baseline checked on 2026-10-14, this fork and its parent's `main` both pointed to `3ce94fcff27976129040d98abc53b6bcc11719be`. See the [fork baseline](https://github.com/hsoliwal/initiative31-community/tree/3ce94fcff27976129040d98abc53b6bcc11719be) and [parent baseline](https://github.com/swt-initiative31/.github/tree/3ce94fcff27976129040d98abc53b6bcc11719be). The added guides are the fork-specific contribution documented here.

For project contacts and communication channels, consult the [original profile's Contacts section](profile/README.md#contacts). That profile warns that historical channels may close; their continued availability is not guaranteed by this fork.
