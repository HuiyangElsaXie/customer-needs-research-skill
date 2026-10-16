# Sol 6.1 agent behavior runs — 2026-10-16

These are real independent Sol 6.1 skill-use executions with synthetic notes, not static checks or real customer research. Harness file reads/writes were allowed; business scripts, browsing, interviews, paid calls and external mutations were prohibited. Each case retains request, tools, exact loaded SKILL hash, raw first answer, self-review and final answer.

| Case | Actual result | Deliverable |
|---|---|---|
| Sufficient notes | Need selection, sources and counterevidence were useful, but supervising review found an unsupported actor: ambiguous shifting work hours became parent work hours. Initial answer/self-review/final-v1 remain unchanged; the same agent repaired final.md and recorded the correction. This initial output is not counted as a clean pass. | [First response](sufficient/raw-response.md), [repaired answer](sufficient/final.md), [correction review](sufficient/correction-review.md) |
| Insufficient notes | Zero supported customer needs selected; unknowns, capture card, neutral questions and prospective validation supplied. No fabricated interviews or findings. | [Final draft](insufficient/final.md) |
| Conflict / no business tools | Duplicate F4 excluded, contrary fixed-schedule note retained, universal automation and five-hour claims rejected. | [Limited brief](conflict-no-tools/final.md) |
| Fresh ambiguity retest | After one evidence-rule clarification, a fresh agent explicitly kept whose work hours shifted unknown. Need selection, counterexamples, neutral questions and unvalidated product status preserved. | [Retest brief](sufficient-ambiguity-retest/final.md), [review](sufficient-ambiguity-retest/self-review.md) |

## Minimal correction and boundaries

The skill now says to preserve source ambiguity rather than assign an omitted actor, event detail, cause or outcome. No product method, license or algorithm changed. The fresh sufficient-case retest loaded that exact updated instruction hash. Earlier insufficient/conflict runs are retained at their recorded earlier hashes; they were not falsely relabeled re-executed.

The supervising AI reviewed actual outputs; same-agent self-review and subsequent repair are identified separately. This is not independent human approval. The test supports only these bounded cases: it does not establish reliability, real customer needs, prevalence, willingness to pay or marketing results.

For a repeat, give a fresh Sol 6.1 agent the case request/inputs and skill, respecting case permissions, with a new output folder and no expected answer. Keep first output before reviewing. Public copies redact only local machine path prefixes; EXPORT.json retains original/export hashes and exact originals remain local. Path tokens are aliases. Later example navigation does not count as an additional behavior run.
