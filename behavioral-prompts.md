# Behavioral Prompts

## What interviewers are testing
Behavioral rounds in AI PM interviews are rarely generic culture checks. Interviewers want proof that you can lead through ambiguity, handle cross-functional tension, recover from messy launches, and make trust-sensitive decisions when the product includes AI behavior you do not fully control. They are testing judgment, communication, ownership, and whether you can turn a difficult product situation into a clear decision narrative.

## How to structure your answer
Use **STAR-T**:
- **Situation:** What was happening and why it mattered
- **Task:** What you owned and what success looked like
- **Action:** What you specifically did
- **Result:** What changed in measurable terms
- **Tradeoff:** What you had to balance, especially speed vs quality, user value vs risk, or stakeholder needs vs technical reality

A strong AI PM answer also includes one sentence on what you learned and how it changed your operating model.

## 3 practice prompts
1. "Act as an AI PM interviewer at a growth-stage company. Ask me a behavioral question about shipping an AI feature that underperformed after launch. After my answer, score me on ownership, clarity, tradeoff thinking, and learning velocity."
2. "Run a mock interview focused on cross-functional conflict. Ask me how I handled disagreement with engineering or research over quality, timeline, or scope in an AI product. Push back if my answer sounds vague."
3. "Help me practice a failure story for an AI PM role. Ask for a real example where trust, quality, or operational risk became visible late. After my answer, rewrite it into a sharper STAR-T format."

## Evaluation rubric
**Strong answer looks like:**
- Opens with a clear business or user problem
- Explains the candidate's specific ownership
- Shows tension, not just smooth execution
- Makes the tradeoff explicit
- Ends with a result and an operating lesson

**Weak answer looks like:**
- Overuses "we" without clarifying personal role
- Describes a project, not a decision
- Avoids numbers, user impact, or concrete outcomes
- Ignores trust, risk, or stakeholder conflict
- Ends without reflection or changed behavior

## 1 real example question with a model answer outline
**Example question:** "Tell me about a time you had to launch an AI feature with imperfect quality signals."

**Model answer outline:**
- Situation: Early version of an AI drafting feature showed promising engagement, but outputs still failed on edge cases for enterprise users
- Task: Decide whether to launch to a limited beta without damaging trust
- Action:
  - Split risks into acceptable versus launch-blocking
  - Built a small golden dataset and manual review loop
  - Added visible human-review language and narrowed the pilot segment
  - Set a rollback threshold before launch
- Result:
  - Beta launched on time to a limited cohort
  - Collected proof of value without exposing the highest-risk segment
  - Reduced support load by fixing the top two failure modes before broader rollout
- Tradeoff:
  - Chose narrower reach and slower rollout in exchange for safer learning
- Learning:
  - Now define release gates before roadmap discussions, not after the feature is nearly built
