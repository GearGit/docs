# Source: https://onlinesurvey.ai/blog/what-is-conjoint-analysis

ON THIS PAGE

[What Is Conjoint Analysis?](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#what-is-conjoint-analysis) [How Conjoint Analysis Works](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#how-conjoint-analysis-works) [Types of Conjoint Analysis](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#types-of-conjoint-analysis) [When to Use Conjoint Analysis](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#when-to-use-conjoint-analysis) [How to Run a Conjoint Analysis Study](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#how-to-run-a-conjoint-analysis-study) [MaxDiff vs Conjoint Analysis](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#maxdiff-vs-conjoint-analysis) [Limitations and Common Mistakes](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#limitations-and-common-mistakes) [Running Conjoint-Style Research Without Specialist Software](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#running-conjoint-style-research-without-specialist-software) [Frequently asked questions](https://onlinesurvey.ai/blog/what-is-conjoint-analysis#frequently-asked-questions)

## What Is Conjoint Analysis?

Conjoint analysis is a quantitative research method that measures consumer preferences by asking people to make choices, just as they do when deciding what to buy. Instead of asking "how important is price to you?" (which almost always produces inflated importance scores), conjoint analysis forces respondents to trade off between competing attributes. The result is a realistic picture of what drives decisions.

The term comes from the idea that preferences are revealed _conjointly_, through the combined evaluation of multiple features at once. A smartphone buyer, for example, does not choose purely on battery life or purely on camera quality. They weigh both, along with price, brand, and storage capacity, and make a single decision. Conjoint analysis replicates that process in a controlled survey environment.

The output is a set of **utility scores** (also called **part-worth utilities**) that quantify how much each feature and each level of that feature contributes to overall preference. These scores can then be used to model demand, simulate market scenarios, and prioritise product decisions.

## How Conjoint Analysis Works

### Trade-off scenarios

In a conjoint study, respondents are shown a series of product profiles, each profile is a combination of attribute levels, and asked to choose their preferred option, rank the profiles, or rate them. The task is repeated multiple times with different combinations.

For example, a study about coffee subscriptions might show respondents three bundles at once:

- Bundle A: Premium beans, fortnightly delivery, $25/month
- Bundle B: Standard beans, weekly delivery, $18/month
- Bundle C: Premium beans, weekly delivery, $32/month

By observing which bundles respondents choose across many such scenarios, the analysis extracts how much value they place on bean quality, delivery frequency, and price independently, even though they were never asked directly.

### Attributes and levels

An **attribute** is a feature of the product (e.g. price, delivery speed, warranty length). A **level** is a specific value that attribute can take (e.g. $18, $25, $32 for the price attribute).

Good conjoint design requires:

- Choosing attributes that are genuinely decision-relevant
- Selecting levels that are realistic and span the plausible range
- Keeping the number of attributes manageable, typically four to six to avoid respondent fatigue

### Part-worth utilities

Statistical analysis of respondent choices produces a **utility score** (part-worth) for each attribute level. Higher utility = more preferred. These scores allow you to answer questions like: how much does adding a 12-month warranty increase preference? How much price increase will the market tolerate for premium packaging?

Importance scores (derived from the range of utilities across each attribute's levels) show which attributes drive decisions most, and which are relatively unimportant.

:::cta heading: Run your first conjoint-style study, _free_ to start. primary: Create your first survey :::

## Types of Conjoint Analysis

### Choice-based conjoint (CBC)

The most widely used form. Respondents choose one option from a set of product profiles, mirroring the real-world decision process. CBC produces realistic preference data and is well-suited to market simulation. It is the default choice for most product and pricing research.

### Adaptive conjoint analysis (ACA)

Designed for studies with many attributes (seven or more). The survey adapts in real time based on a respondent's earlier answers, focusing subsequent questions on the attributes they find most relevant. ACA reduces respondent fatigue but requires more sophisticated survey software.

### Full-profile conjoint

An older approach in which respondents are shown complete product descriptions and asked to rank or rate them. Full-profile conjoint becomes unwieldy quickly as the number of attributes grows, because the number of possible profiles increases exponentially.

## When to Use Conjoint Analysis

Conjoint analysis is the right tool when you need to understand trade-offs, not just stated importance. Common applications include:

- **Product development**: determining which feature combinations to build into a new product or how to tier features across product versions
- **Pricing research**: identifying price sensitivity and the price premium consumers will pay for specific attributes
- **Feature prioritisation**: understanding which features genuinely drive purchase decisions versus features respondents claim to value but would not actually pay for
- **Packaging and presentation decisions**: testing how changes to format, delivery, or bundling affect preference
- **Competitive positioning**: simulating how your product performs relative to competitors under different attribute configurations

Conjoint analysis is less appropriate when you have a very short list of items to rank (MaxDiff handles this better) or when your research goal is exploratory rather than quantitative.

## How to Run a Conjoint Analysis Study

### Step 1: Define attributes and levels

Start by identifying the product dimensions that matter most to buyers. Keep attributes to a manageable number. Four to six is a practical range for most studies. For each attribute, define two to four realistic levels. Avoid levels that are obviously dominated (always better or always worse). They add noise without information.

Common sources for attribute selection: customer interviews, sales team input, competitor feature comparisons, and prior survey data.

### Step 2: Design the survey tasks

Use an experimental design to create the combinations of attributes that respondents will evaluate. A full-factorial design (every possible combination) quickly becomes too large to be practical, so most conjoint studies use a **fractional factorial design**, a statistically efficient subset of all possible profiles that still allows utilities to be estimated accurately.

For choice-based conjoint, a common structure is three to four product profiles per choice task, with eight to fifteen tasks per respondent.

### Step 3: Collect responses

Field the survey to a representative sample of your target audience. Sample size matters more in conjoint than in simple rating studies because the statistical model needs sufficient observations at every attribute-level combination.

A rough starting point for choice-based conjoint is 150–200 respondents for stable utility estimates, though the exact requirement depends on the number of attributes, levels, and tasks.

Ensure respondents are screened to represent genuine buyers or users. Preference data from people outside the target market produces misleading utilities.

### Step 4: Analyse utilities and importance scores

Statistical analysis (typically hierarchical Bayes or logit models) converts respondent choices into individual and aggregate utility scores. The output tells you:

- How much each attribute level contributes to overall preference
- Which attributes are most important (largest range of utilities across levels)
- How preference varies across different customer segments

Review utilities at the segment level, not just overall. Different customer groups often value features very differently.

### Step 5: Simulate market scenarios

The utility scores feed into a **market simulator**, a model that predicts how a defined product configuration would perform against a competitive set. You can ask questions like:

- If we add Feature X, what share of preference do we gain against Competitor A?
- What happens to our preference share if we increase price by 15%?
- Which product configuration maximises preference among the high-value segment?

Market simulation is where conjoint analysis translates from research into decision support.

## MaxDiff vs Conjoint Analysis

MaxDiff (maximum difference scaling) and conjoint analysis are both trade-off methods, but they serve different purposes.

| | MaxDiff | Conjoint Analysis |
| --- | --- | --- |
| **What it measures** | Relative importance of items in a list | Value of attributes in a full product profile |
| **Task format** | Best/worst choices from a list of items | Choose between complete product concepts |
| **Best for** | Prioritising a list of features, messages, or ideas | Product design, pricing, and bundling decisions |
| **Complexity** | Simpler to design and analyse | More complex; requires experimental design |
| **Output** | Importance ranking of items | Part-worth utilities and market simulation |

Use **MaxDiff** when you have a list of features, benefits, or messages and need to know which resonate most, without the complexity of full product profiles. Use **conjoint analysis** when you need to understand how features combine and what trade-offs consumers will make in realistic purchase scenarios.

Many research projects use both: MaxDiff to shortlist which attributes to include, then conjoint to quantify trade-offs.

## Limitations and Common Mistakes

**Poorly chosen attributes.** Including attributes that respondents cannot meaningfully distinguish, or omitting attributes that actually drive decisions, produces unreliable utilities. Qualitative research before a conjoint study is not optional.

**Unrealistic levels.** If respondents do not believe a level is achievable (e.g. a price point that seems implausibly low), they will not engage with it honestly. All levels should reflect real options in the market.

**Too many attributes.** Respondents can only hold a limited number of dimensions in mind at once. Studies with eight or more attributes without adaptive design produce fatigue and lower-quality data.

**Small or non-representative samples.** Conjoint utilities are estimated statistically. A sample that is too small or that over-represents one segment will produce unstable estimates.

**Treating stated preferences as actual behaviour.** Conjoint data reflects what respondents say they would choose under survey conditions. It is a strong predictor of relative preference, but it does not account for inertia, brand loyalty, or real-world friction. Use it as a directional input, not a precise market share forecast.

**Ignoring segment-level differences.** Reporting only aggregate utilities can obscure important variation between customer groups. Always examine whether utilities differ meaningfully by segment before drawing product conclusions.

## Running Conjoint-Style Research Without Specialist Software

Traditional conjoint analysis has historically required dedicated statistical software and specialist methodology knowledge, a barrier for many product and research teams. Platforms that support advanced survey logic, branching, and structured response formats make it practical to build conjoint-adjacent studies without a separate research stack.

onlinesurvey.ai supports the survey complexity needed for structured preference research, including trade-off task formats and AI-powered analysis that surfaces patterns and priorities from response data automatically. For teams looking to run systematic preference research without building a specialist toolchain, it is worth exploring what the platform's enterprise research capabilities support. Details are available on the [onlinesurvey.ai pricing page](https://onlinesurvey.ai/pricing).

## Frequently asked questions

### What is conjoint analysis in simple terms?

Conjoint analysis is a survey method that reveals which product features matter most to customers by making them choose between realistic product options, just as they would in a real purchase decision. Rather than asking people to rate features in isolation, it forces trade-offs, producing more accurate data about what actually drives preference and purchase decisions.

### What is the difference between conjoint analysis and a simple preference survey?

A simple preference survey asks people how much they value individual features, which tends to produce inflated and undifferentiated importance scores. Conjoint analysis asks respondents to choose between complete product profiles, so the relative value of each attribute is revealed through actual trade-offs. The result is a realistic utility score for each feature, not just a self-reported ranking.

### How many respondents do I need for a conjoint analysis study?

A common starting point for choice-based conjoint is 150 to 200 respondents. The exact requirement depends on the number of attributes, levels, and choice tasks per respondent. Studies with more attributes or that require segment-level analysis will need larger samples to produce stable, reliable utility estimates. Always design the sample to match the actual buyer population.

### What is a part-worth utility in conjoint analysis?

A part-worth utility (also called a utility score) is the numerical value assigned to each level of each attribute in a conjoint study. It represents how much that specific attribute level contributes to overall preference. Higher utility means greater preference. By comparing part-worth utilities across levels within an attribute, you can see how much preference changes as that attribute changes.

### When should I use MaxDiff instead of conjoint analysis?

Use MaxDiff when you have a list of features, messages, or ideas and need to rank them by importance or appeal without the complexity of full product profiles. Use conjoint analysis when you need to understand how product features combine, what trade-offs consumers will accept, and what configurations will perform best against competitors. Many studies use MaxDiff first to shortlist attributes, then conjoint to quantify trade-offs.

### Can conjoint analysis be used for pricing research?

Yes. Pricing is one of the most common applications of conjoint analysis. By including price as one of the attributes in the study, you can estimate how much preference decreases as price increases and identify the price premium the market will pay for specific features. This is more robust than direct price sensitivity questions, which typically produce overly conservative answers.

## Put your research into practice, _fast._

Free to start. No credit card. Every plan has the intelligence built in.

[Create a survey](https://app.onlinesurvey.ai/signup) [Book a demo](https://cal.com/sales-team-y7ofqn/30min)

RELATED ARTICLES

[![Conjoint Analysis Software: A Buyer's Guide for 2026](https://ik.imagekit.io/somanshu/onlinesurvey.ai/blog/conjoint-analysis-software-guide.svg?updatedAt=1780351659094)\\ \\ COMPARISONS\\ \\ Conjoint Analysis Software: A Buyer's Guide for 2026\\ \\ Conjoint analysis software must handle complex survey logic, utility scoring, and market simulation. Here are the 8 features to evaluate before you buy.\\ \\ APR 23 2026 · 11 MIN READ→](https://onlinesurvey.ai/blog/conjoint-analysis-software-guide) [![MaxDiff vs Conjoint Analysis: Which Should You Use?](https://ik.imagekit.io/somanshu/onlinesurvey.ai/blog/maxdiff-vs-conjoint-analysis.svg?updatedAt=1780351659435)\\ \\ COMPARISONS\\ \\ MaxDiff vs Conjoint Analysis: Which Should You Use?\\ \\ MaxDiff ranks feature importance. Conjoint measures trade-off preferences. Learn which method fits your research question, and when to combine both.\\ \\ APR 21 2026 · 9 MIN READ→](https://onlinesurvey.ai/blog/maxdiff-vs-conjoint-analysis) [![Best Free Survey Tools in 2026: Features, Pricing and Limits Compared](https://ik.imagekit.io/somanshu/onlinesurvey.ai/blog/best-free-survey-tools-2026.svg)\\ \\ COMPARISONS\\ \\ Best Free Survey Tools in 2026: Features, Pricing and Limits Compared\\ \\ A side-by-side comparison of the top free survey tools, based on their documented features, pricing and plan limits. See which ones offer real AI insights, unlimited responses, and no hidden paywalls.\\ \\ JUL 16 2026 · 12 MIN READ→](https://onlinesurvey.ai/blog/best-free-survey-tools-2026)