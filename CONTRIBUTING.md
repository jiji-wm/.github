# Contributing to jiji-wm projects

Issues and PRs are welcome on every repo in this organization. Each repo's
README (and CLAUDE.md, where present) documents its build, test, and commit
conventions — match them. The compositor repo has additional, jiji-specific
guidance in its own
[CONTRIBUTING.md](https://github.com/jiji-wm/jiji/blob/main/CONTRIBUTING.md).

The quality bar is the existing code. Match the conventions and rigor of the
code around your change — you won't be held to a higher standard than the
codebase itself meets, and its current limitations are fair game to point
out, or fix.

## AI-assisted contributions

AI-assisted PRs are explicitly welcome across all jiji-wm repos; these
projects are themselves developed with heavy AI assistance under a
structured review loop. The conditions:

- You are the author and fully accountable: submit only what you have read,
  understood, verified (build + tests + the changed behavior), and can
  defend in review.
- Disclose substantial AI involvement with a commit trailer. Use the
  Linux-kernel convention `Assisted-by: AGENT:MODEL`; these repos' own
  commits carry the equivalent house trailer
  `AI-Assisted: <mode> (<model-id>)`, which is also accepted. Trivial
  assistance (autocomplete-level) needs no disclosure.
- Follow the repo's normal conventions. For bigger ideas, you're always
  welcome to open an issue and chat about it first — happy to point at
  what's already planned and help find the approach most likely to land.
  Optional, but it can spare you wasted effort: when a big PR dies, it's
  usually not for code quality but for things visible up front — the
  feature was already designed differently, collides with an invariant you
  couldn't see from outside, or sits outside the project's scope. An issue
  is also a great place to announce what you're building: it prevents
  duplicate work and can draw in ideas, interest, and collaborators.

If a contribution looks unreviewed by its author, expect it to be returned
with a request to review it first rather than a detailed code review; if
there's no follow-up after a while, it may be closed — reopening with the
review done is always welcome.
