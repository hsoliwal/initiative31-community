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
