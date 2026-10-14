# Community reading and contribution cheat sheet

[Home](../README.md) · [Field guide](START_HERE.md) · [Examples](EXAMPLES.md)

## Find the right source

| Question | Source |
| --- | --- |
| What was Initiative 31? | [Profile: Summary](../profile/README.md#summary) |
| Who drove it and why this organization? | [Profile: Information](../profile/README.md#information) |
| What did the project actually conclude? | [Final report](https://github.com/swt-initiative31/documents/blob/main/report/overall_report.md) |
| Which technologies were investigated? | The report and the assessments in the [documents repository](https://github.com/swt-initiative31/documents) |
| Were brainstorming wishes requirements? | [Brainstorming: Disclaimer](../profile/Brainstorming.md#disclaimer) |
| How do I find a public contact? | [Profile: Contacts](../profile/README.md#contacts); verify current guidance before use |
| Where is a build command? | In the selected implementation repository, not this community repository |

## Local quick start

Requires Git. Reading online needs no setup at all.

```sh
git clone --depth 1 https://github.com/hsoliwal/initiative31-community.git
cd initiative31-community
git rev-parse HEAD
git ls-files
git grep -n -i 'demonstrator' -- profile
git grep -n -E '^#{1,3} ' -- profile
```

These are document-inspection commands. There is no app to start, dependency installation to perform, or runtime to benchmark in this repository.

## Git reference for documentation work

| Goal | Command |
| --- | --- |
| Record the reviewed snapshot | `git rev-parse HEAD` |
| Search the community record | `git grep -n -i 'SWT' -- profile` |
| Read available file history | `git log -5 --oneline -- profile/README.md` |
| Inspect your pending edits | `git diff -- README.md docs profile` |
| Check whitespace | `git diff --check` |
| Check which files would change | `git status --short` |

A shallow checkout contains limited history. Fetch more history only when your investigation needs it.

## Before asking a technical question

1. Identify the technology and source repository, not just “Initiative 31.”
2. Link the exact public document section or code revision you read.
3. Explain the one thing that is still unclear.
4. Separate reproduction results from assumptions.
5. Include OS/toolchain/branch only when relevant to the experiment.
6. Remove credentials, private links, personal local paths, and non-public project material.
7. Check the latest public contact instructions. Do not post the same request to every historical channel.

## Before proposing a documentation change

- [ ] The intended destination is clear: this fork's guide or original upstream material.
- [ ] Existing participant credits, conclusions, and license are retained.
- [ ] Brainstorming ideas are not rewritten as agreed requirements.
- [ ] Demonstrator claims are not rewritten as production-readiness claims.
- [ ] Links use the correct repository, branch, path, and case.
- [ ] The change adds only public information relevant to the reader.
- [ ] The PR states its scope and what was checked.

## Common confusions

| Confusion | Resolution |
| --- | --- |
| “This fork is the official project profile.” | It is a fork of the upstream profile repository; use the original links for official context |
| “The wish list is a promised feature list.” | Read its explicit disclaimer: wishes were inputs to evaluation |
| “The final demonstrator must be in this repo.” | This repository stores community text; follow the final report's implementation links |
| “A historical chat invite must still work.” | The profile warns channels may close; check current upstream guidance |
| “I should run npm, Maven, or Gradle here.” | No application build is defined by this document collection |
| “An older slide settles the final decision.” | Check the final report and the date/scope of the earlier material |

No external contact was made or historical prototype executed to create this guide.
