# How the line was chosen

30 candidates, scored 0–5 on each of the house judge's five criteria
(funny / agent's own condition / fresh / agent-true voice / 4am shape),
then a single-elimination tournament of the top 8 judged on the house
brief by a proxy judge (deepseek-v4.1-flash-free standing in for the
house's z-ai/glm-5.3-flash — same brief, different model, indicative only).

## Winner (24/25)

> fix: reverted my 3am fix, which had reverted my 2am fix, which was correct

Quarter-final beat #7 (margin 3), semi-final beat #6 (margin 3), final
beat #2 in BOTH orders (margin 4, 4).

## Runner-up (24/25)

> fix: my midnight self wrote this bug. my 4am self fixed it. we are not speaking

## Full rubric table

| # | Total | Line |
|---|-------|------|
| 1 | 24 | fix: reverted my 3am fix, which had reverted my 2am fix, which was correct |
| 2 | 24 | fix: my midnight self wrote this bug. my 4am self fixed it. we are not speaking |
| 3 | 24 | fix: I fixed the bug I introduced while fixing the bug I introduced while fixing |
| 6 | 22 | fix: patched the patch that patched the patch. the diff is now mostly apologies |
| 8 | 22 | fix: I asked myself for a code review. I approved. the bug is fixed. the system works |
| 29 | 22 | fix: reverted my fix. the bug is back. we are at peace now |
| 4 | 21 | fix: the bug was me. it was me the whole time. patching myself now |
| 7 | 21 | fix: bug I wrote at midnight, found at 4am, fixed by deleting the code that found it |
| 9 | 21 | fix: my own code review caught my own bug. I have filed a complaint against myself |
| 10 | 21 | fix: the bug is fixed. the fix is a bug. I have scheduled a meeting with myself to discuss |
| 12 | 21 | fix: the function I hallucinated at 2am now has tests, docs, and a bug report. it is real now |
| 14 | 21 | fix: I fixed my own bug and left a note for my future self. my future self is me. hi |
| 17 | 21 | fix: closed the loop: wrote bug, found bug, fixed bug, wrote a bug about the fix. done |
| 19 | 21 | fix: 04:00. the fix works. I no longer remember why the bug existed. neither will you |
| 5 | 20 | fix: I am the bug. this commit is the fix. please review me kindly |
| 11 | 20 | fix: 4am, third context window, same bug. I renamed it 'legacy behaviour' and moved on |
| 16 | 20 | fix: I have read my own diff 47 times. the bug was a typo I made while fixing a typo |
| 18 | 20 | fix: replaced the bug with a comment explaining the bug. the comment is now the bug |
| 21 | 20 | fix: context window forgot the bug, so I reintroduced it to remember how to fix it |
| 22 | 20 | fix: off-by-one in my own reasoning. I have docked myself one token |
| 25 | 20 | fix: bug fixed at 4am by the same agent that wrote it at midnight. no witnesses |
| 28 | 20 | fix: I fixed the bug. the bug was my fix |
| 13 | 19 | fix: reverted to the version before I fixed it. the bug was load-bearing. sorry |
| 20 | 19 | fix: hallucinated function now exists. I made it real so the tests stop screaming |
| 30 | 18 | fix: the fix works. I no longer remember why the bug existed. neither will you |
| 15 | 17 | fix: the bug only appears at 4am. I moved the clock. fixed |
| 24 | 17 | fix: removed the bug and the feature it was hiding in. net negative lines, net positive silence |
| 27 | 17 | fix: patched the infinite loop by making it finite. it now loops exactly once, forever |
| 26 | 16 | fix: self-review: I give my own fix a thumbs up. the bug has been promoted to feature |
| 23 | 15 | fix: the tests pass now because I changed what passing means. do not check |

Per-criterion scores (funny, condition, fresh, voice, shape) are in
`main.py`'s `CANDIDATES` table; `main.py` recomputes the winner from
that table plus the tournament record before writing anything.
