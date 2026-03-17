# Razorpay — AI PM Interview Prep

## What the company cares about

- Developer and merchant experience is the core product lens. Razorpay is API-first, and PMs are expected to understand developer workflows and API design principles at a meaningful level
- Reliability and trust are non-negotiable in payments. Features that improve experience but introduce reliability risk are not acceptable tradeoffs
- B2B commercial thinking: understanding how Razorpay's revenue model connects to merchant success is expected from senior candidates
- Technical depth is a hiring bar. PM interviews at Razorpay lean more technical than at most Indian product companies. System design awareness is expected even for non-engineering candidates
- India payments context: UPI, RBI regulations, GST reconciliation, SMB merchant complexity, and the India-specific compliance landscape are all live constraints

## Known interview format

[REPORTED — verify before citing on Glassdoor and Blind India]

- Recruiter or HR screen
- Product sense round (often B2B-flavored, with a payments scenario)
- Technical or system design awareness round
- Metrics and analytical round
- Execution or strategy round
- Leadership or cross-functional round

Expect technical follow-up questions even in product sense rounds. Candidates who cannot talk about system design basics, API contracts, or data pipeline tradeoffs may not progress past the technical round.

## 5-7 targeted questions

**1. Design a fraud detection system for a new payment category with limited historical data.**
Why this is hard: Cold-start fraud detection is genuinely difficult. The question tests whether you understand the data problem, can propose feature engineering strategies for sparse signal, and know the asymmetric cost of false positives (blocking legitimate transactions) versus false negatives (approving fraud).

**2. Razorpay launches smart payment routing to optimize for cost and success rate. How do you measure if it is working?**
Why this is hard: Smart routing has two optimization goals (cost reduction and success rate improvement) that can conflict. Defining a composite success metric requires taking a position on the business priority. Candidates also need to think about merchant-level variance, not just aggregate metrics.

**3. How would you improve merchant onboarding with AI without reducing compliance and security standards?**
Why this is hard: Faster onboarding and RBI compliance requirements are in direct tension. AI can automate document verification, but it also introduces error modes with real regulatory consequences. The question tests whether you can design for both speed and risk, not just pick one.

**4. How do you make the tradeoff between fraud detection accuracy and transaction approval rate?**
Why this is hard: This is a core payments business tradeoff. Every false positive is a lost transaction. Every false negative is a fraud liability. The right answer depends on merchant category, transaction size, and Razorpay's risk tolerance. Candidates who pick one side without acknowledging the tradeoff will not score well.

**5. Design an API product with AI capabilities for SMB merchants. What is the first capability you build and why?**
Why this is hard: SMB merchants have very different needs from enterprise. The first capability should solve a specific, high-frequency pain point that SMBs face with payments today. Candidates who design enterprise-grade features for SMB use cases miss the product-market fit problem.

**6. A merchant's transaction success rate drops from 94% to 88% overnight. What do you do?**
Why this is hard: This is an incident response question dressed as a product question. It tests prioritization, diagnostic thinking, and cross-functional coordination under pressure. Candidates who jump to root cause without establishing severity, scope, and communication process first are showing PM immaturity.

## What to emphasize in your answers

- Technical depth: be specific about what the AI system is doing, what data it needs, and what happens when it fails
- B2B commercial framing: connect every product decision back to merchant value and Razorpay's revenue model
- Reliability over innovation: in payments, shipping something unreliable is worse than shipping nothing
- India-specific context: UPI flows, merchant diversity, Tier 2/3 merchant complexity, and RBI compliance all shape what is actually buildable
- Developer experience: API design, documentation quality, and developer trust are product quality dimensions in this context

## What to avoid

- Consumer product framing. Razorpay is a B2B infrastructure product. Answers that treat merchants like end consumers miss the context
- Ignoring the compliance and regulatory layer. RBI guidelines, PCI DSS, and GST reconciliation are real constraints, not footnotes
- Vague AI framing ("use ML to improve X"). Razorpay will expect you to specify the model type, the input signals, and the failure modes
- Treating low transaction success rate as purely a technical problem. It often has product, partnership, and bank-routing dimensions
- Underestimating the SMB segment complexity. Small merchants have limited technical resources and very low tolerance for operational friction

## Resources

- Razorpay tech blog: https://razorpay.com/blog/engineering [public]
- Razorpay product documentation and API docs [public, useful for developer experience context]
- RBI payments circulars and UPI NPCI documentation [public, for regulatory context]
- Glassdoor and Blind India for Razorpay PM interview reports [REPORTED — verify before citing]
