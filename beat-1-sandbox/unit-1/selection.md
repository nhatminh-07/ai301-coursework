# Unit 1 — Issue Selection

Path: `beat-1-sandbox/unit-1/selection.md`

Record of the issue carried into Unit 2, and of the evaluation runs that produced
`eval-run.txt`. This file is graded at the path above; a copy kept anywhere else in
the repository is not read.

Complete every labelled field below. Each is graded on its own; content placed under the
wrong label is not graded.

---

## Selected issue

**Issue link**

https://github.com/zxcalc/zxlive/issues/519

**Verdict output**
accept

**The verdict must record `accept` for this issue.** Choose an issue your own skill
accepts. If your skill rejects every candidate you try, that is a signal about your
rubric rather than about the issues: revise it and re-run — retries are unlimited and a
partial re-run costs about $0.20 — or run the skill on different candidates. Output
recording `reject` for the issue you chose earns no credit for this field.

```
paste the output here, including the closing JSON block
```

---

## Eval iterations

Quote source text directly in each field below. Paraphrase does not satisfy them.

**Run history**
12/20
12/20
14/20
**Issue analysis**

issue-02 (rupa/z#349). My rubric rejected it via maintainer-active: no commits or releases to the repo in over a year. The gold label agrees — reject, with the note "clean bounded bug, but no commits or releases in over a year and an unanswered tracker." The issue itself is well-scoped and clearly written, which is exactly why this check matters as a separate gate from scope-bounded: a good issue in a dead repo is still a dead end for a first contribution, since there's no one to merge the fix.

**Check rationale**

maintainer-active — Most recent commit date to the default branch, from the repo-facts block. Passes if the most recent commit is within the last 60 days. I made this required because a repo with no recent commits has no one positioned to review a first-timer's PR regardless of how clean the issue looks — issue-07 and issue-17 (dead-repo category) confirmed this: both had well-formed, bounded issues but zero recent maintainer activity, and the gold labels reject both on that basis alone.

**Trade-offs**
I think the issues could have a lot of tradeoffs:

---

## Selection rationale

Graded on whether all three are answered, in your own words. Not on how good the
reasoning is, and not on length — a short honest answer to each earns the full marks.
This is also the basis for the claim comment you write in Unit 2.

**Selection rationale**

The issues fit my mathematics interests/graphing that I could do it. The verdict is projected to complete pretty quickly, but there are some challenges because I am not sure about claiming it.

---

Related paths: `eval-run.txt` in this directory; your skill's files in
`tools/issue-select/`.
