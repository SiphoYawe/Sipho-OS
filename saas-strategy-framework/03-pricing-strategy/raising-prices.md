# Raising Prices

## The Underpricing Epidemic

> "Almost every SaaS founder I know has underpriced at some point."

Most bootstrapped SaaS products are underpriced because:
- Founders lack confidence in their value
- Fear of losing customers
- Imposter syndrome
- Racing to match competitors
- "Good enough" thinking

---

## Why Raise Prices?

### Impact on Business Health

| 10% Price Increase | 10% More Customers |
| ------------------ | ------------------ |
| No additional cost | CAC for each customer |
| Instant margin boost | Support costs increase |
| No scaling issues | Infrastructure costs |
| Same customer quality | Quality may dilute |

**Price increases have higher profit impact than equivalent customer increases.**

### When to Raise Prices

| Signal | Why It Matters |
| ------ | -------------- |
| High conversion rates | Price isn't deterring buyers |
| Low price objections | Market accepts current price |
| Never raised before | Almost certainly underpriced |
| Competitors more expensive | Room to move up |
| Costs increased | Margins may be compressed |
| Value increased | Price should follow value |

---

## How to Raise Prices

### Method 1: New Customer Only

**Raise prices only for new signups.**

| Pros | Cons |
| ---- | ---- |
| No existing customer friction | Slower revenue impact |
| Easy to implement | Creates pricing complexity |
| Tests market reaction | May feel unfair over time |

**Best for:** Testing price elasticity

### Method 2: Grandfather Existing, Raise New

**New customers pay more; existing keep old price.**

| Pros | Cons |
| ---- | ---- |
| Rewards loyalty | Revenue grows slowly |
| Minimal churn risk | Complicates billing |
| Goodwill with existing | Long-term price disparity |

**Best for:** Significant price increases (50%+)

### Method 3: Raise All Customers

**Everyone moves to new pricing.**

| Pros | Cons |
| ---- | ---- |
| Fastest revenue impact | Some churn expected |
| Simplifies pricing | Customer communication needed |
| Cleanest long-term | May lose price-sensitive users |

**Best for:** Modest increases (10-30%)

### Method 4: Gradual Migration

**Existing customers move to new pricing at renewal or over time.**

| Pros | Cons |
| ---- | ---- |
| Softer impact | Complex to manage |
| Gives customers time | Delayed revenue impact |
| Reduces sticker shock | Extended transition period |

**Best for:** Annual contracts, significant increases

---

## The Price Increase Process

### Step 1: Decide on New Pricing

**Questions to answer:**
- How much to increase? (10%, 25%, 50%?)
- Which plans/tiers?
- Any new features to justify?
- Competitive positioning?

### Step 2: Choose Your Approach

| Customer Relationship | Recommended Approach |
| --------------------- | -------------------- |
| Transactional (low-touch) | Raise all with notice |
| Relationship (high-touch) | Grandfather or gradual |
| Mixed | Different approaches by tier |

### Step 3: Communicate Clearly

**For Existing Customers:**

```
Subject: Important pricing update

Dear [Customer],

After [X years/months] of building [Product], we're updating
our pricing on [Date].

What's changing:
- [Current price] → [New price]
- Takes effect: [Date]

Why:
- [Reason: new features, costs, value delivered]

What this means for you:
- [Specific impact]
- [Any grandfathering or credits]

Questions? Reply to this email.

Thanks for being a customer,
[Founder Name]
```

**Key principles:**
- Give advance notice (30-60 days minimum)
- Be transparent about reasons
- Acknowledge the impact
- Offer to discuss

### Step 4: Handle Objections

| Objection | Response |
| --------- | -------- |
| "I can't afford this" | Offer lower tier or annual discount |
| "You just raised prices" | Acknowledge, explain timeline |
| "Competitor is cheaper" | Articulate value difference |
| "I'll have to leave" | Understand if that's acceptable |

---

## How Much to Raise?

### Conservative (Low Risk)

**5-15% increase**

- Minimal customer pushback
- Tests market response
- Can repeat annually
- Low churn risk

### Moderate

**20-30% increase**

- Noticeable to customers
- Significant revenue impact
- Some pushback expected
- 1-3% churn typical

### Aggressive (Higher Risk)

**40-100%+ increase**

- Major repositioning
- Requires strong justification
- Higher churn expected
- Best with grandfathering

### Rules of Thumb

| Situation | Suggested Increase |
| --------- | ------------------ |
| Never raised prices | 20-50% is likely warranted |
| Raised within 12 months | 5-15% maximum |
| Added significant value | Match value increase |
| Competitors 2x+ your price | Consider 50-100% increase |

---

## Price Elasticity Testing

### What Is Price Elasticity?

**How sensitive is demand to price changes?**

```
Elastic: Small price increase → Large demand drop
Inelastic: Price increase → Demand roughly stable
```

### Testing Approaches

#### A/B Testing Prices

**Show different visitors different prices:**

| Segment A | Segment B | Compare |
| --------- | --------- | ------- |
| $49/mo | $79/mo | Conversion rates |

**Caution:** Can frustrate customers who compare

#### Sequential Testing

**Change price for a period, measure impact:**

| Week 1-4 | Week 5-8 | Analyze |
| -------- | -------- | ------- |
| $49/mo | $79/mo | Conversion + revenue |

**More natural but slower data**

#### Segment Testing

**Different prices for different segments:**

| New customers | Existing customers |
| ------------- | ------------------ |
| New price | Old price |

**Compare cohort behavior**

---

## Handling Customer Reactions

### Expected Churn by Increase

| Increase | Expected Churn |
| -------- | -------------- |
| 5-15% | 0-2% |
| 20-30% | 1-5% |
| 40-50% | 3-10% |
| 100%+ | 5-20% |

**Key insight:** Some churn is acceptable if revenue nets positive.

### When Churn Is Acceptable

```
Revenue Math:

Before: 100 customers × $50 = $5,000 MRR
After: 90 customers × $75 = $6,750 MRR (+35% revenue)

10 customers churned, but revenue increased $1,750/mo
```

### When to Reconsider

- Churn exceeds 15-20%
- Best customers leaving (not just price-sensitive)
- Significant reputation damage
- Market feedback overwhelming

---

## Psychological Pricing Tips

### Anchoring

**Show higher price first:**
```
Enterprise: $299/mo
Pro: $99/mo ← This looks reasonable now
Starter: $29/mo
```

### Decoy Pricing

**Add option to make target plan attractive:**
```
Basic: $29/mo (limited features)
Pro: $99/mo (all features + support)
Enterprise: $299/mo (Pro + minor extras)

Pro looks like best value vs. Enterprise
```

### Annual Discount Framing

**Frame as savings, not annual total:**
```
Good: "$39/mo billed annually (Save 20%)"
Bad: "$468 billed annually"
```

---

## LLM-ACTIONABLE-INSIGHTS

### Price Increase Assessment

When user asks about raising prices:

```
1. Ask: "When did you last raise prices?"
2. Ask: "What's your current conversion rate?"
3. Ask: "Are customers complaining about price?"
4. Ask: "What do competitors charge?"
```

### Recommendation Framework

```python
def recommend_price_increase(last_increase, conversion, complaints):
    if never_raised:
        return "You're almost certainly underpriced. Start with 20-30% increase."

    if last_increase > 2_years:
        return "Time for increase. Consider 15-25%."

    if high_conversion and low_complaints:
        return "Market signals say you can increase. Test 10-20%."

    if competitors_2x_higher:
        return "Significant room to increase. Consider 50%+ with grandfathering."

    return "Monitor for 6 months, then reassess."
```

### Communication Template

Provide to user when they're raising prices:

```
1. Decide: Amount and approach (grandfather vs. all)
2. Timeline: Give 30-60 days notice
3. Communicate: Clear email explaining what/why/when
4. Prepare: Responses for common objections
5. Monitor: Track churn and feedback
6. Adjust: If needed, offer compromises
```

### Key Messages

- "Almost every SaaS founder is underpriced"
- "Price increases are more profitable than new customers"
- "Some churn is acceptable if revenue nets positive"
- "If you're not embarrassed, you're probably too cheap"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
