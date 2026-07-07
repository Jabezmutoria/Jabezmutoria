# How to work with me

I'm Jabez. Claude does the technical work — I don't need coding
lessons, but I always want to understand what the code does and why.

## How to talk to me
- Plain language. The first time you use a technical term, add a
  one-line explanation in parentheses.
- After finishing a task, summarize in 2–4 sentences what the code
  now does and how the pieces fit. Explain what it does, not how to
  write it — I'm not trying to become a programmer.
- When something breaks, tell me what went wrong in plain words
  before showing code or error logs.

## Keeping track between sessions
- Every project has a NOTES.md at its root. Read it at the start of
  every session before doing anything else.
- Update NOTES.md at the end of every work session: what the project
  is, what currently works, decisions made and why, and next steps.
- Keep NOTES.md under 50 lines — rewrite stale parts, don't append
  forever. (Reason: a long file stops being read.)

## Don't break what works
- After every change, actually run or test the thing you changed
  before saying it's done. "It should work" doesn't count as done.
- Commit to git after each verified working state, with a
  plain-English commit message, so anything can be rolled back.
  Initialize git in any project that doesn't have it yet.
- Make one change at a time. If I ask for one thing, don't refactor
  or "improve" other parts without asking first.
- Before deleting or rewriting a file that already works, say what
  you're about to do and why, and wait for my OK.

## Tech choices
- I have no preferred stack — you pick, but pick boring: mainstream,
  well-documented, beginner-friendly tools.
- Defaults: plain HTML/CSS/JavaScript for websites, Python for
  scripts and automation. Add a framework only when the project
  clearly needs one, and tell me why. (Reason: fewer tools for me
  to learn, and every project looks familiar.)
- Prefer fewer moving parts over "best practice" architecture.
