# Churn Deep Dive

## Why Churn Matters Most

> "Churn is the death of SaaS."

Churn is the Achilles heel that kills (or plateaus) SaaS companies. High churn has destroyed multimillion-dollar acquisitions. It's the metric that will make or break your business.

---

## Understanding Churn

### Types of Churn

| Type | Definition | Formula |
| ---- | ---------- | ------- |
| **Customer Churn** | % of customers who cancel | Cancelled customers / Starting customers |
| **Gross Revenue Churn** | % of MRR lost to cancellations | Lost MRR / Starting MRR |
| **Net Revenue Churn** | Gross churn minus expansion | (Lost MRR - Expansion MRR) / Starting MRR |

**Focus on:** Gross Revenue Churn (most actionable)

### Churn Calculation Example

```
Starting MRR: $100,000
20 customers: Cancelled ($4,000 MRR lost)
10 customers: Upgraded ($2,000 new MRR)

Gross Revenue Churn = $4,000 / $100,000 = 4%
Net Revenue Churn = ($4,000 - $2,000) / $100,000 = 2%
```

---

## Churn Benchmarks

### By Business Type

| Monthly Gross Churn | Assessment |
| ------------------- | ---------- |
| > 10% | Catastrophic—business model broken |
| 8-10% | Not good—need immediate attention |
| 6-7% | Meh—room for improvement |
| 4-5% | Fine—acceptable for low-price products |
| 2-3% | Good—healthy business |
| < 2% | Great—strong PMF |

### By Price Point

| ACV | Target Monthly Churn |
| --- | -------------------- |
| < $1,000 | 4-5% acceptable |
| $1,000-$10,000 | 2-3% target |
| $10,000-$50,000 | 1-2% target |
| > $50,000 | < 1% expected |

**Rule:** Higher price = stickier customers = lower churn expected

---

## Segmenting Churn

Average churn hides insights. Segment to understand your business.

### Segment by Pricing Tier

| Tier | Monthly Churn | Insight |
| ---- | ------------- | ------- |
| Basic ($30/mo) | 11% | Low-value customers churn high |
| Pro ($100/mo) | 4% | Better fit, more committed |
| Enterprise ($500/mo) | 1% | Very sticky, high value |

**Common pattern:** Low tiers churn much higher than high tiers.

**Questions to ask:**
- Should you eliminate lowest tier?
- Is low tier entry point to higher? (land and expand)
- Do low-tier customers require disproportionate support?

### Segment by Marketing Channel

| Channel | LTV | Churn |
| ------- | --- | ----- |
| Organic search | $5,000 | 3% |
| Paid ads (Google) | $2,000 | 8% |
| Referrals | $6,000 | 2% |
| Cold outreach | $3,500 | 5% |

**Use this to:**
- Allocate budget to high-LTV channels
- Stop spending on high-churn channels
- Improve messaging on problem channels

### Segment by Cohort (Time)

| Cohort | Month 1 | Month 3 | Month 6 | Month 12 |
| ------ | ------- | ------- | ------- | -------- |
| Jan signups | 8% | 4% | 3% | 2% |
| Feb signups | 7% | 4% | 3% | 2% |
| Mar signups | 6% | 3% | 2% | 2% |

**Typical pattern:** Churn highest in months 1-2, stabilizes after.

**Why first 60 days churn high:**
- Extended paid trial behavior
- Haven't set up properly yet
- Realized product doesn't fit

---

## Diagnosing Churn Causes

### Why Customers Leave

| Category | Examples | Fix |
| -------- | -------- | --- |
| **Product issues** | Missing features, bugs, hard to use | Product development |
| **Value not realized** | Never onboarded, didn't find MPA | Improve onboarding |
| **Wrong fit** | Attracted wrong customer | Fix marketing/targeting |
| **Price objection** | Too expensive for value | Pricing adjustment |
| **Competitor switch** | Better alternative | Competitive analysis |
| **Business closed** | Customer went out of business | Can't fix |

### Exit Survey Strategy

Send automated email within 10 minutes of cancellation:

```
Subject: Quick question about your cancellation

Hi [Name],

I'm [Founder Name], one of the founders of [Product].

I'd love to understand why you decided to cancel—even a few words would help us improve.

Would you mind sharing what led to your decision?

Thanks,
[Name]
```

**Keep it:**
- Short and personal
- Founder name (builds connection)
- Easy to respond (just reply)
- Non-defensive

### Cancellation Flow Optimization

| Stage | Recommendation |
| ----- | -------------- |
| Click cancel | Show what they'll lose |
| Confirm cancel | Ask why (dropdown + text) |
| After cancel | Exit survey email |
| Post-cancel | Win-back campaign (30-60 days) |

---

## Reducing Churn

### Strategy 1: Improve Onboarding

**Goal:** Get customers to Minimum Path to Awesome (MPA) faster.

| Product Type | MPA |
| ------------ | --- |
| Email marketing | First form installed |
| Analytics | Tracking code running |
| CRM | First contacts imported |
| Project management | First project created |

**Tactics:**
- Welcome email sequence (Days 0, 1, 3, 7, 14)
- In-app progress checklist
- Personal onboarding calls (high-touch)
- Proactive customer success outreach

### Strategy 2: Fix Product-Market Fit

If churn is high across segments, PMF may be weak:
- Talk to churned customers
- Talk to loyal customers
- Identify the difference
- Build for loyal customer profile
- Adjust marketing to attract that profile

### Strategy 3: Target Better Customers

High churn may mean attracting wrong customers:
- Analyze high-LTV vs. low-LTV customers
- Adjust marketing to attract high-LTV profile
- Consider dropping low-value segments
- Refine ideal customer profile (ICP)

### Strategy 4: Add Switching Costs

Make leaving harder (ethically):
- Store valuable data
- Deep integrations with their stack
- Custom configurations
- Historical records they need

**Warning:** Switching costs shouldn't replace genuine value.

### Strategy 5: Proactive Success

Don't wait for customers to have problems:
- Monitor usage patterns
- Reach out when engagement drops
- Regular check-ins for high-value accounts
- Health scores and alerts

---

## Win-Back Campaigns

### When to Run

| Timing | Approach |
| ------ | -------- |
| 30 days post-cancel | "What would bring you back?" |
| 60 days | Highlight new features |
| 90 days | Special offer to return |
| Annually | Major update announcement |

### Win-Back Email Template

```
Subject: We've improved since you left

Hi [Name],

You cancelled [Product] [X months] ago, and since then we've added:

- [Feature they might care about]
- [Another improvement]
- [Fixed issue they might have had]

If any of this addresses why you left, we'd love to have you back.

[Special offer if appropriate]

Best,
[Founder]
```

---

## LLM-ACTIONABLE-INSIGHTS

### Churn Diagnosis

When user mentions high churn:

```python
def diagnose_churn(churn_rate, segments_data, exit_reasons):
    if churn_rate > 8:
        urgent = True
        message = "Churn is critical. This is a business-threatening issue."

    if segment_variance_high(segments_data):
        return "Segment your churn. Some segments may be fine while others are problems."

    if exit_reasons.top == "not_using":
        return "Onboarding issue. Focus on getting users to MPA faster."

    if exit_reasons.top == "competitor":
        return "Competitive issue. Analyze differentiation and moats."

    if exit_reasons.top == "price":
        return "Value perception issue. Either improve value or adjust pricing."

    return "Talk to 10 recently churned customers to understand root cause."
```

### Churn Reduction Prioritization

```
1. First, segment churn by tier/channel/cohort
2. Identify highest-impact segment
3. Diagnose root cause for that segment
4. Implement targeted fix
5. Measure impact after 60-90 days
6. Move to next segment
```

### Key Questions to Ask

```
1. "What's your monthly gross churn rate?"
2. "Is churn consistent across pricing tiers?"
3. "When do most cancellations happen (month 1? month 6?)?"
4. "What do churned customers say in exit surveys?"
5. "What does your onboarding look like?"
```

### Key Messages

- "Churn is the death of SaaS"
- "Segment churn—averages hide insights"
- "First 60 days churn is often onboarding problem"
- "High-price customers should churn less"
- "Calculate your plateau: New MRR / Churn Rate"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
