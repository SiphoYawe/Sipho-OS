# 80/20 SaaS Metrics

## Philosophy

> "If you can't measure it, you can't manage it." — Peter Drucker

Most founders either track too many metrics or none at all. This framework focuses on the 20% of metrics that drive 80% of your results.

---

## North Star Metrics

**Your two most important metrics:**

### 1. Monthly Recurring Revenue (MRR)

**What it is:** Total recurring revenue from all customers in a month.

```
MRR = Sum of (Monthly subscription value × Active customers)

Example:
50 customers @ $100/mo = $5,000 MRR
20 customers @ $200/mo = $4,000 MRR
Total MRR = $9,000
```

**Annual Recurring Revenue (ARR):** MRR × 12

### 2. Month-over-Month Growth Rate

**What it is:** Percentage change in MRR from last month.

```
Growth Rate = (Current MRR - Previous MRR) / Previous MRR × 100

Example:
Last month: $50,000 MRR
This month: $55,000 MRR
Growth rate: ($55,000 - $50,000) / $50,000 = 10%
```

**Benchmarks:**

| Growth Rate | Assessment |
| ----------- | ---------- |
| < 3% | Slow/Struggling |
| 3-5% | Decent |
| 5-10% | Good |
| 10-20% | Great |
| > 20% | Exceptional |

---

## The 3 High / 3 Low Framework

Beyond MRR and growth, track these six metrics. Push three HIGH and three LOW.

### The 3 LOW Metrics (Minimize These)

#### 1. Cost to Acquire a Customer (CAC)

**What it is:** Total cost to acquire one new customer.

```
CAC = Total Acquisition Costs / Number of New Customers

Example:
Marketing spend: $5,000
Sales salaries: $5,000
New customers: 20
CAC = $10,000 / 20 = $500
```

**How to evaluate CAC:**

Use **CAC Payback Period:**
```
Payback Period = CAC / Monthly Revenue per Customer

Example:
CAC = $500
ARPA = $100/month
Payback = 5 months
```

| Payback Period | Assessment |
| -------------- | ---------- |
| < 3 months | Excellent |
| 3-6 months | Good (bootstrapper target) |
| 6-12 months | Acceptable |
| > 12 months | Dangerous for bootstrappers |

**VC Rule:** Spend up to 1/3 of LTV or 1x ACV
**Bootstrap Rule:** 2-6 month payback maximum

#### 2. Sales Effort

**What it is:** Time and energy required to close a sale.

**Metrics to track:**
- Average days from first contact to close
- Number of touches to close
- Hours of sales time per deal

**Benchmarks by segment:**

| Segment | Typical Sales Cycle |
| ------- | ------------------- |
| Self-serve (<$100/mo) | Minutes to hours |
| SMB ($100-500/mo) | Days to weeks |
| Mid-market ($500-5K/mo) | Weeks to months |
| Enterprise ($5K+/mo) | Months |

**Ways to reduce sales effort:**
- Self-serve signup and onboarding
- One-call close structure
- Better pre-qualification
- Improved sales materials

#### 3. Churn

**What it is:** Percentage of customers/revenue lost per month.

```
Gross Revenue Churn = Lost MRR / Starting MRR × 100

Example:
Starting MRR: $100,000
Lost MRR: $5,000
Gross Churn: 5%
```

**Churn Benchmarks (Monthly):**

| Gross Churn | Assessment |
| ----------- | ---------- |
| > 10% | Catastrophic |
| 8-10% | Not good |
| 6-7% | Meh |
| 4-5% | Fine |
| 2-3% | Good |
| < 2% | Great |

**Note:** Higher price points should have lower churn. Enterprise ($25K+ contracts) should target < 1%.

---

### The 3 HIGH Metrics (Maximize These)

#### 4. Annual Contract Value (ACV)

**What it is:** Revenue per customer per year.

```
ACV = Monthly subscription × 12

Example:
$200/month plan = $2,400 ACV
```

**Why ACV over LTV:**
LTV looks impressive but takes years to realize. ACV shows near-term value and is more actionable for bootstrappers.

**Ways to increase ACV:**
- Raise prices
- Target larger customers
- Move upmarket
- Add premium tiers

#### 5. Expansion Revenue

**What it is:** Additional revenue from existing customers.

```
Expansion Rate = New Expansion MRR / Starting MRR × 100

Example:
Starting MRR: $100,000
Customers upgraded: $4,000
Expansion Rate: 4%
```

**Sources of expansion:**
- Upsells to higher tiers
- Add-ons purchased
- Additional seats/users
- Usage growth (value metrics)

**Target:** 3-5% monthly expansion rate

#### 6. Referrals

**What it is:** New customers from existing customer recommendations.

**How to measure:**
- "How did you hear about us?" at signup
- Referral program tracking
- Attribution data

**Why referrals matter:**
- Lower CAC (free acquisition)
- Higher quality leads (pre-validated)
- Faster sales cycle (trust transfer)
- Indicates product satisfaction

---

## The Plateau Formula

> "Churn helps you calculate when your revenue will plateau."

```
Plateau Revenue = Monthly New MRR / Monthly Churn Rate

Example:
Monthly new MRR: $5,000
Monthly churn: 10%
Plateau = $5,000 / 0.10 = $50,000 MRR

You will plateau at $50,000 unless something changes.
```

**This is the most important calculation for planning:**
- If plateau is too low, focus on reducing churn
- If plateau is acceptable, focus on increasing acquisition

---

## SaaS Cheat Code: Virality

**Virality** = Each user brings additional users.

### Strong Viral Loops

| Product Type | Viral Mechanism |
| ------------ | --------------- |
| Team tools (Slack) | Invite colleagues |
| Scheduling (Calendly) | Share booking links |
| Signatures (DocuSign) | Send documents |
| Social features | Natural sharing |

### Weak Viral Loops

| Product Type | Viral Mechanism |
| ------------ | --------------- |
| "Powered by" badges | Brand exposure |
| Referral programs | Incentivized sharing |
| Watermarks (free tier) | Passive exposure |

### Building Virality

- Hard to retrofit—design in from start
- Not required for success
- If you have it, it's a massive advantage
- Focus on value-driven sharing, not forced

---

## SaaS Cheat Code: Net Negative Churn

**Net negative churn** = Expansion revenue exceeds lost revenue.

```
Net Churn = (Churned MRR - Expansion MRR) / Starting MRR

Example:
Churned: $5,000
Expansion: $8,000
Net Churn = ($5,000 - $8,000) / $100,000 = -3%

Negative churn = Growth from existing customers!
```

**Requirements for net negative churn:**
- Low gross churn (< 3%)
- Strong expansion mechanisms
- Value metrics tied to growth
- High customer success

**Impact:**
- Grow without new customers
- Sustainable revenue growth
- Higher company valuation
- Lower pressure on acquisition

---

## Vanity Metrics Warning

**Vanity metrics sound impressive but don't drive business:**

| Vanity Metric | Why It's Misleading |
| ------------- | ------------------- |
| Page views | Doesn't mean conversions |
| Free signups | Don't pay bills |
| Social followers | Rarely convert to customers |
| Email list size | Open rates matter more |
| Total users | Paying users matter |

**Always ask:** "How does this metric connect to revenue?"

---

## LLM-ACTIONABLE-INSIGHTS

### Metrics Health Check

When assessing a SaaS business:

```python
def assess_metrics_health(metrics):
    issues = []

    if metrics.churn > 5:
        issues.append("High churn - investigate causes")

    if metrics.cac_payback > 6:
        issues.append("CAC too high - improve efficiency")

    if metrics.expansion_rate < 2:
        issues.append("Low expansion - add value metrics")

    if metrics.growth < 5:
        issues.append("Slow growth - check acquisition + churn")

    plateau = metrics.new_mrr / (metrics.churn / 100)
    if plateau < metrics.mrr * 2:
        issues.append(f"Will plateau at ${plateau}K - reduce churn")

    return issues
```

### Diagnostic Questions

```
1. "What's your MRR and MoM growth rate?"
2. "What's your monthly churn rate?"
3. "What's your CAC payback period?"
4. "Do you have expansion revenue mechanisms?"
5. "What percentage of customers come from referrals?"
```

### Plateau Calculator

When user provides metrics:
```
Plateau = New MRR / Churn Rate

If plateau < target MRR:
    RECOMMEND: "Focus on reducing churn before scaling acquisition"

If plateau > target MRR:
    RECOMMEND: "Churn is manageable, focus on acquisition"
```

### Key Messages

- "MRR + Growth Rate are your North Stars"
- "3 High (ACV, Expansion, Referrals) / 3 Low (CAC, Sales Effort, Churn)"
- "Calculate your plateau number—it predicts your ceiling"
- "Net negative churn = SaaS Cheat Code"
- "Beware vanity metrics that don't connect to revenue"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
