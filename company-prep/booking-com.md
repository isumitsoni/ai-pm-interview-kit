# Booking.com — AI PM Interview Prep

## What the company cares about

- Experimentation culture is a defining identity. Booking.com reportedly runs thousands of simultaneous A/B tests [REPORTED — verify before citing]. Candidates who cannot reason through experiment design will not pass the analytical rounds
- Data and metrics precision matters more here than at most companies. Vague qualitative reasoning will not land
- Moving from accommodation platform to full travel platform is the current strategic direction. AI trip planning, flight search, and transport are active bets
- Supply side (property managers, accommodation partners) is as important as demand side (travelers). Features that improve one and break the other create real business risk
- Trust is a product asset. Booking.com's business depends on travelers trusting recommendations and prices. AI features that erode that trust have outsized downside

## Known interview format

[REPORTED — verify before citing]

- Recruiter screen
- Product sense round (structured, metrics-heavy)
- Analytical round (A/B test design, data reasoning, sometimes SQL-adjacent questions)
- Execution or strategy round
- Team fit / values round

Expect data and metrics questions in almost every round. This is not a company where strong product instincts alone will get you through.

## 5-7 targeted questions

**1. Design a pricing transparency feature for Booking.com. How do you balance clarity with conversion impact?**
Why this is hard: Full pricing transparency may reduce conversion. Booking.com has a business interest in certain price displays. Candidates need to take a real position on the tradeoff and back it up with how they would test it.

**2. How would you measure the success of AI-powered search ranking versus the previous rule-based ranking?**
Why this is hard: The comparison is not apples-to-apples. AI ranking may win on some metrics and hurt on others. You need to define the right composite metric before you can declare a winner, and that requires taking a position on what Booking.com optimizes for.

**3. How do you decide when an AI recommendation is better than a human filter?**
Why this is hard: "Better" is not self-defining. Better for whom, on which metric, over what time horizon? This question tests whether you can define the evaluation criteria before you can answer the question itself.

**4. Design an A/B test for a recommendation algorithm change on the Booking.com search page.**
Why this is hard: This is a metrics and experiment design question wearing a product disguise. You need to define the primary metric, guard metrics, minimum detectable effect, sample size, and what would kill the test. Most candidates under-specify.

**5. What is the north star metric for AI-powered trip planning on Booking.com?**
Why this is hard: Trip planning is multi-session and multi-intent. Booking conversion is the business metric but is a lagging indicator. Candidates need to reason through the leading indicators that predict healthy trip planning behavior before settling on a north star.

**6. A/B test shows AI-powered search ranking increases bookings by 3% but decreases return visits by 2%. What do you do?**
Why this is hard: This is a direct tradeoff question. There is no universally right answer. The quality of reasoning matters more than the conclusion. Candidates who pick one metric without acknowledging the lifetime value implications will not score well.

**7. How would you use AI to improve review quality and trustworthiness on Booking.com?**
Why this is hard: Review quality has supply-side dimensions (getting quality reviews), demand-side dimensions (surface the right reviews), and trust dimensions (detect fake reviews). Candidates who design for only one of these miss the systemic problem.

## What to emphasize in your answers

- Metrics precision: define your metrics specifically, including the denominator
- Experiment design: know how to frame a hypothesis, define a primary metric and guard metrics, and say when you would stop a test
- Supply and demand balance: never design a feature for travelers without thinking through the property partner implications
- Trust as a product asset: Booking.com's business model depends on traveler trust. AI features that create opacity or unpredictability have a cost that goes beyond the immediate metric
- Scale and personalization: Booking.com serves hundreds of millions of users across wildly different travel contexts. Solutions need to hold up at scale

## What to avoid

- Qualitative reasoning without data anchoring. This company will ask "how would you measure that?" after almost every statement you make
- Ignoring the supply side (property managers, hosts, transport providers)
- Assuming all travelers are the same. Business vs leisure, first-time vs frequent, budget vs premium all produce very different product requirements
- Proposing AI features without an evaluation framework for whether the AI is actually performing better
- Treating every metric improvement as unambiguously good without checking for guard metric deterioration

## Resources

- Booking.com tech blog: https://medium.com/booking-com-development [public]
- Booking Holdings annual reports [public, for strategic context]
- Glassdoor and Blind reviews for Booking.com PM interviews [REPORTED — verify before citing]
- Booking.com UX research and design content on YouTube and conference talks [public]
