# Product Design Prompts

## What interviewers are testing
AI PM design questions test whether you can find a real user problem, decide where AI meaningfully helps, define trust boundaries, and shape a workflow that users can understand. They are not looking for a list of features. They want to see whether you know when AI belongs in the flow, how to handle failure states, and how to define success beyond novelty.

## How to structure your answer
Use **U-T-A-S-T**:
- **User:** Who is the user and what job are they trying to do
- **Task:** What outcome matters most
- **AI fit:** Why AI improves this job versus a non-AI workflow
- **Solution:** What the end-to-end flow looks like
- **Trust:** How the product handles uncertainty, failure, and review

Close with success metrics and one scoped MVP.

## 3 practice prompts
1. "Act as an interviewer for a senior AI PM role. Ask me to design an AI feature for an existing product. After my answer, critique my user segmentation, AI fit, trust design, and MVP scope."
2. "Give me a product-sense case for an AI PM interview where I need to improve an existing AI assistant that has low adoption. Push me to define user pain, not just new features."
3. "Run a mock design interview where I must design an AI workflow for a high-trust domain. After my answer, ask follow-up questions on failure states, guardrails, and success metrics."

## Evaluation rubric
**Strong answer looks like:**
- Starts with one user and one important job
- Explains why AI is useful in this workflow
- Defines the value moment clearly
- Includes trust, review, or fallback behavior
- Narrows to a believable MVP with measurable success

**Weak answer looks like:**
- Jumps straight into feature brainstorming
- Assumes AI is always the right answer
- Ignores failure states and user trust
- Describes a platform instead of a first release
- Uses vague success language such as "users will love it"

## 1 real example question with a model answer outline
**Example question:** "Design an AI note-taking feature for professionals."

**Model answer outline:**
- User: Client-facing professionals who need usable follow-up notes immediately after meetings
- Job: Capture action items, decisions, and next steps without writing everything manually
- AI fit:
  - AI helps summarize unstructured conversations quickly
  - Human review is still required before notes are shared
- Solution:
  - Upload or sync meeting transcript
  - Generate summary with action items, decisions, and risks
  - Let user edit and approve before sharing
- Trust:
  - Highlight low-confidence sections
  - Show source excerpt links
  - Never auto-send without approval
- MVP:
  - Support only one meeting type and one summary format at launch
- Success metrics:
  - Approval rate, time saved, repeat usage, correction rate
