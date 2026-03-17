# Flipkart — AI PM Interview Prep

## What the company cares about

- Scale is the defining constraint. Flipkart operates at massive volume across Tier 1 to Tier 3 India. Features need to hold up under extremely variable conditions: connectivity, device capability, language, and literacy levels
- Seller ecosystem health is as important as buyer experience. Catalog quality, seller trust, and logistics reliability are the pipes that the buyer experience runs on
- Operational excellence is valued as much as product innovation. Flipkart's competitive moat is partly in its logistics and supply chain capabilities, not just its product surface
- Vernacular and accessibility are real product problems at Flipkart's scale. A large portion of Flipkart's user base is not English-first or technically sophisticated
- Walmart ownership brings additional emphasis on supply chain efficiency, cost discipline, and structured execution

## Known interview format

[REPORTED — verify before citing on Glassdoor and Blind India]

- Recruiter or HR screen
- Product sense round (structured, scenario-based)
- Metrics and analytical round
- Execution or delivery round
- Strategy round for senior roles
- Cross-functional or leadership round

Very analytical. Expect metrics to be specified precisely. Execution rounds may include questions about managing ambiguity in large teams with multiple stakeholders.

## 5-7 targeted questions

**1. How would you use AI to improve Flipkart's seller catalog quality? Bad listings are a major trust problem.**
Why this is hard: Catalog quality has two dimensions: the system that detects problems and the seller experience that gets them fixed. AI can detect bad listings, but if the seller cannot understand what to fix, the quality does not improve. The PM question is about the full loop, not just the detection model.

**2. Design a demand forecasting system for a new product category with no historical data on Flipkart.**
Why this is hard: Cold-start demand forecasting requires you to reason about proxy signals (category adjacency, seller data, search query trends) when ground truth is unavailable. The answer needs to include a data strategy, not just a model choice.

**3. Flipkart launches AI-powered search re-ranking. How do you measure if it is actually better?**
Why this is hard: Better for whom? Better on which metric? The evaluation framework requires you to specify buyer-side metrics, seller-side fairness considerations, and business revenue impact separately before combining them. Most candidates under-specify.

**4. How do you balance seller revenue versus buyer experience in recommendation design?**
Why this is hard: This is a direct marketplace tension question. Recommendations that boost seller revenue by surfacing higher-margin or promoted products may not surface the best-fit item for the buyer. Taking a position on this tradeoff requires understanding both Flipkart's business model and its long-term user trust strategy.

**5. How would you build a vernacular AI search experience for users who type in mixed Hindi-English (Hinglish)?**
Why this is hard: This is not a pure NLP problem. It requires decisions about what language to respond in, how to handle transliteration variance, how to surface results when the query is ambiguous, and how to test quality with a user population that is harder to recruit for standard usability studies.

**6. A key seller category sees a 20% drop in listing quality scores after a catalog AI model update. What do you do?**
Why this is hard: This is an incident response question with supply-side implications. A model update that degrades catalog quality affects seller trust, search results, and buyer experience simultaneously. Candidates need to show structured thinking about scope, root cause, rollback criteria, and seller communication.

**7. How would you use AI to help small Tier 2/3 sellers create better product listings without requiring them to be technically skilled?**
Why this is hard: The user here is not the buyer. It is a small-town merchant with limited digital literacy and no product photography setup. The AI feature design must account for low-quality input (blurry photos, partial descriptions) and still produce a usable output. The interface design is as much the challenge as the model.

## What to emphasize in your answers

- Scale and operational realism: think about Tier 1 to Tier 3 India, variable connectivity, and what happens when the system handles edge cases at millions of transactions per day
- Seller ecosystem thinking: never design a buyer-facing feature without considering the seller-side implications
- Metrics precision: Flipkart will push on vague success metrics. Define numerator, denominator, and time horizon
- Execution discipline: Flipkart rewards structured thinking about how to ship, not just what to ship
- Vernacular and accessibility: a significant portion of Flipkart's users are not English-first. AI features need to account for this by default, not as a future iteration

## What to avoid

- Premium-only thinking. Flipkart's core market is mass-market India. Answers designed for urban, English-speaking, high-income users miss the product reality
- Ignoring supply chain and logistics. Flipkart's competitive moat includes its logistics layer. Product decisions often have downstream effects on fulfillment
- Treating seller health as a secondary concern. Seller experience and catalog quality are first-class product problems at Flipkart
- Generic ML recommendations without specifying the input signals, cold-start handling, and feedback loop design
- Underestimating the operational complexity of shipping anything at Flipkart's scale

## Resources

- Flipkart tech blog: https://tech.flipkart.com [public]
- Flipkart seller hub documentation and support center [public, useful for seller-side context]
- Walmart annual reports for strategic context on Flipkart's position [public]
- Glassdoor and Blind India for Flipkart PM interview reports [REPORTED — verify before citing]
- India e-commerce market reports from RedSeer or Bernstein for Tier 2/3 context [REPORTED — verify specific numbers before citing]
