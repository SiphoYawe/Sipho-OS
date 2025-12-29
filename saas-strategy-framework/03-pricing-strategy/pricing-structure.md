# Pricing Structure

## Pricing Philosophy

> "Build businesses, not products."

Pricing is a lever you can control that has outsized impact on revenue, customer quality, and business sustainability.

---

## The Four Approaches to Pricing Plans

### 1. Single Price (Simple)

**One price for full access to the product.**

| Pros | Cons |
| ---- | ---- |
| Easy to understand | Leaves money on table |
| Simple to implement | No expansion revenue |
| Quick decisions | No segmentation |

**Best for:**
- Early-stage validation
- Simple products with one use case
- Markets with uniform needs

### 2. Value Metrics (Recommended)

**Price scales based on usage or value received.**

| Pros | Cons |
| ---- | ---- |
| Captures more value | Harder to predict revenue |
| Natural expansion | Requires tracking usage |
| Aligns with customer success | More complex billing |

**Common Value Metrics:**

| Business Type | Metric |
| ------------- | ------ |
| Email marketing | Subscribers |
| CRM | Contacts or seats |
| Analytics | Page views or events |
| API services | API calls |
| File storage | Storage used |
| Team tools | Users/seats |

**Best for:**
- Products where value scales with usage
- Building expansion revenue engine

### 3. Feature Gating

**Different plans unlock different features.**

| Pros | Cons |
| ---- | ---- |
| Easy to implement | Pricing debates over features |
| Clear upgrade path | May frustrate customers |
| Predictable tiers | Features become commoditized |

**Tier Structure Example:**

| Tier | Price | Target Segment |
| ---- | ----- | -------------- |
| Basic | $29/mo | Small business, testing |
| Pro | $99/mo | Growing business |
| Enterprise | $299/mo | Large teams |

**Best for:**
- Products with distinct feature sets
- Clear user segmentation

### 4. Hybrid (Value Metrics + Feature Gating)

**Combine both approaches.**

| Pros | Cons |
| ---- | ---- |
| Maximizes revenue | Most complex to implement |
| Multiple upgrade paths | Harder to explain |
| Captures all value | Requires more analysis |

**Structure:**
```
Each tier includes:
- Specific features
- Usage limits (value metric)
- Overage charges or forced upgrades
```

**Best for:**
- Mature products with diverse customers
- Maximizing LTV

---

## Setting Initial Price

### The Bootstrapper Pricing Rule

> "If you're not embarrassed by your pricing, you're probably too cheap."

Most bootstrappers underprice. Your price should make you slightly uncomfortable.

### Starting Price Framework

1. **Research competitors** - What do similar products charge?
2. **Calculate value delivered** - How much money/time do you save customers?
3. **Set initial price** - Start higher than feels comfortable
4. **Test and iterate** - Raise until conversion drops

### Price Positioning Matrix

| Position | Target | Pricing Approach |
| -------- | ------ | ---------------- |
| **Budget** | Price-sensitive buyers | Lower than competitors |
| **Mid-market** | Value-conscious buyers | Competitive pricing |
| **Premium** | Quality-focused buyers | Higher than competitors |

**For bootstrappers:** Mid-market or premium is usually best. Racing to bottom is dangerous.

---

## Number of Plans

### The Three-Plan Standard

| Plan | Purpose |
| ---- | ------- |
| **Starter/Basic** | Entry point, builds trust |
| **Pro/Growth** | Where most customers land |
| **Enterprise** | High-value, custom needs |

### Why Three Works

- Offers choice without overwhelm
- Middle option seems "just right" (anchoring)
- Clear upgrade path
- Captures different market segments

### When to Use Fewer

| Scenario | Plans |
| -------- | ----- |
| Simple product | 1-2 plans |
| Early validation | 1 plan |
| Niche market | 2 plans |

### When to Use More

| Scenario | Plans |
| -------- | ----- |
| Wide market range | 4-5 plans |
| Distinct segments | One per segment |
| Usage-based + features | Multiple combinations |

---

## Annual vs. Monthly Billing

### The Cash Flow Advantage

> "Offering a yearly price gives you access to a cash cushion."

**Yearly Discounts:**
- Industry standard: 16-17% discount (2 months free)
- Aggressive: 20-25% discount
- Conservative: 10-15% discount

### Yearly Plan Benefits

| Benefit | Impact |
| ------- | ------ |
| Cash flow | Money upfront to invest |
| Commitment | Lower churn from yearly customers |
| Psychology | Customers more invested |

### Implementation

**Messaging approach:**
```
Monthly: $49/month
Annual: $39/month (20% off)

NOT: "$468/year" (sticker shock)
```

**Conversion tactics:**
- Show monthly equivalent prominently
- Default to annual selection
- Highlight savings clearly

---

## Credit Card Requirements

### Always Require Credit Card for Trial

**Why:**
- Filters out tire-kickers
- Trials convert 2x-3x higher
- Attracts serious customers
- Reduces support burden

**Data shows:**
- With CC: 40-60% trial conversion
- Without CC: 10-20% trial conversion

**Customer quality:**
- CC trials attract buyers, not browsers
- Reduces "professional free users"
- Filters for intent

### The Objection Response

> "But I'll get fewer signups!"

**Reality:**
- 5x fewer signups, 3x higher conversion = Net positive
- Better quality customers
- Less wasted effort
- Faster path to revenue

---

## Freemium Considerations

### When Freemium Works

| Condition | Why It Matters |
| --------- | -------------- |
| Large market | Needs huge volume |
| Viral product | Free users spread product |
| Low marginal cost | Serving free users is cheap |
| Clear upgrade trigger | Obvious reason to pay |

### When Freemium Fails

| Condition | Problem |
| --------- | ------- |
| High support costs | Free users drain resources |
| No viral loop | Free doesn't drive growth |
| Small market | Not enough volume |
| Enterprise focus | Free devalues product |

### The Freemium Math

```
Freemium success requires:

Free to Paid Conversion Rate: 2-5% typical
Viral coefficient: > 0 (free drives new signups)
Cost to serve free: Very low

If conversion is <2% AND no virality: Freemium is wrong model
```

### Alternative: Very Low Entry Tier

Instead of free, offer $9-19/month entry tier:
- Still accessible
- Customers have commitment
- Revenue from day one
- Filters for intent

---

## LLM-ACTIONABLE-INSIGHTS

### Pricing Assessment Questions

When user asks about pricing:

```
1. "What's your current pricing structure?"
2. "What value metric would scale with customer success?"
3. "Who are your ideal customers and what do they pay for similar tools?"
4. "When did you last raise prices?"
```

### Pricing Recommendation Framework

```python
def recommend_pricing(stage, product_type, market):
    if stage == "early":
        return "Start simple (1-2 plans), require CC for trials"

    if has_clear_value_metric(product_type):
        return "Use value metric pricing for expansion revenue"

    if distinct_customer_segments(market):
        return "Feature gating with 3 tiers"

    return "Hybrid: Value metrics + feature gating"
```

### Price Increase Guidance

```
IF never_raised_prices:
    RECOMMEND: "You're probably underpriced. Test a 20% increase."

ELIF last_raise > 1_year_ago:
    RECOMMEND: "Time to reevaluate. Inflation alone justifies 5-10%."

ELIF conversion_dropping:
    ASSESS: "Is it price or product-market fit?"
```

### Key Pricing Messages

- "If you're not embarrassed by your price, you're too cheap"
- "Always require credit card for trials"
- "Value metrics enable expansion revenue (SaaS Cheat Code)"
- "Three plans works for most SaaS products"
- "Freemium rarely works for bootstrapped B2B"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
