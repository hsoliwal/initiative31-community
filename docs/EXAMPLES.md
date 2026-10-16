# Useful first contributions and questions

[Home](../README.md) · [Field guide](START_HERE.md) · [Cheat sheet](CHEATSHEET.md)

## Example 1: ask about an unclear technical result

An effective question can be short while still being reproducible:

```text
Topic: <specific technology or behavior>
Source: <public report/code URL at a commit, plus section>
My understanding: <one sentence grounded in that source>
Question: <the precise missing fact>
What I checked: <documents or experiment actually reviewed>
Environment, if relevant: <OS, toolchain, branch, revision>
```

For example, if you are unsure whether a limitation concerns the historical VCL/UNO prototype or the later custom-widget demonstrator, name both sections and ask which implementation the result describes. This is more answerable than asking whether “the SWT replacement works.”

## Example 2: turn a wish into an evaluation question

The [brainstorming record](../profile/Brainstorming.md) includes browser integration among its wishes and explicitly says the list is not a feature requirement.

A useful investigation question is: “What browser-integration behavior was demonstrated by this specific prototype, and what remains unverified?”

Record the source, version, observed behavior, and limitations. Avoid writing “browser integration is guaranteed” or “all prototypes must implement this” unless a separate authoritative specification establishes that claim.

## Example 3: submit a small navigation improvement

Choose one problem: an ambiguous repository name, a broken link, or a missing explanation of a term. In the proposed change, include:

```text
Reader problem: <what a new reader cannot find or understand>
Public evidence: <original source and exact revision>
Proposed change: <the small documentation correction>
Preserved: historical conclusions, participant credits, and licensing
Checked: relative links, spelling/case, Markdown, and docs-only diff
Not checked: historical channels' responsiveness or prototype runtime
```

For this fork's added guides, propose the change in this fork. For an upstream profile correction, first inspect the upstream repository's current instructions and context.

## Example 4: collect a compact evidence note

```text
Question:
Repository and commit:
Document and heading:
Type of evidence: wish / observation / conclusion / proposal
What the source establishes:
What it does not establish:
Next verification needed:
```

This format keeps research useful without inventing commitments. Keep any non-public work context out of public issues, pull requests, and documentation.

## Example 5: rewrite an overconfident community summary

Consider this hypothetical sentence: “Initiative 31 guarantees a fast SWT replacement with browser integration.”

The [brainstorming record](../profile/Brainstorming.md) lists browser integration and performance among wishes and explicitly says those wishes are not required features. The [profile](../profile/README.md) provides the project's context; the [final report](https://github.com/swt-initiative31/documents/blob/main/report/overall_report.md) is the place to investigate outcomes.

A defensible replacement is: “Participants identified browser integration and performance as desirable evaluation topics. To assess what was demonstrated, consult the final report and the relevant prototype's recorded results.”

Why this is stronger:
- It identifies who expressed the wishes without inventing a contractual promise.
- It keeps evaluation preferences separate from implementation results.
- It gives the next evidence source rather than asserting universal speed or compatibility.

For your own summary, mark each sentence as **community context**, **wish**, **reported result**, or **proposal**. If a sentence combines categories, split it and attach the right source to each. A report's conclusion should remain attributed to that report.

## Maintaining the community guide

| Change being proposed | Check first | Preserve |
| --- | --- | --- |
| Contact or chat link replacement | Current public upstream guidance and the actual destination | Historical context; do not promise a response |
| Project status update | Explicit public announcement and its date | The distinction between completed research and later work |
| New prototype link | Correct repository, branch, README, and implementation role | Clear separation of community and source repositories |
| Brainstorming clarification | The disclaimer and surrounding text | Wishes must remain wishes |
| Fork guide improvement | Whether [START_HERE](START_HERE.md) and [CHEATSHEET](CHEATSHEET.md) need matching navigation | Original profile, participant credits, and licensing |

A link that redirects is not automatically broken; verify its destination before replacing it. A channel that is historical should not be labelled active merely because its URL still opens. Editing this fork's profile does not change the upstream organization's public profile.

### FAQ: who should receive a question?

- **Confusing fork navigation:** propose a focused change here.
- **Prototype setup or behavior:** use the specific implementation repository's current contribution guidance and include its revision.
- **Original project conclusions:** start from the public report and verify the upstream project's current contact guidance.
- **Private implementation context:** remove it from the public question; provide only a minimal public reproduction or source-reading question.

These examples do not contact anyone or verify that historical channels are currently staffed.
