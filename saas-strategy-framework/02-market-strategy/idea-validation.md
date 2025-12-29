# Idea Validation

## The Validation Imperative

> "Better products don't always win; better-marketed products do."

Before building, you need to validate three things:
1. A problem exists worth solving
2. People will pay for a solution
3. You can reach these people

---

## Where Good Ideas Come From

### Tier 1: Scratch Your Own Itch

**The gold standard for validation.**

**Why it works:**
- You understand the problem deeply
- You're a potential first customer
- You can validate demand quickly
- You'll stay motivated through challenges

**Requirements:**
- Problem you've actually experienced
- Willingness to pay for solution
- Others share this problem

### Tier 2: Domain Expertise

**Leverage professional experience.**

**Examples:**
- 10 years in real estate → Real estate software
- Dental practice owner → Dental office tools
- Marketing agency → Marketing automation

**Advantages:**
- Know customer pain points
- Have network for validation
- Understand buying process
- Speak the language

### Tier 3: Market Research

**Systematic investigation of opportunities.**

**Methods:**
- Analyze competitor reviews (complaints = opportunities)
- Survey target market
- Interview potential customers
- Analyze search trends

**Risks:**
- Lower conviction than personal experience
- Longer learning curve
- May miss nuances

---

## Validation Methods

### Method 1: Customer Conversations

**Goal:** Understand if problem is real and painful enough

**Process:**
1. Identify 20-50 potential customers
2. Reach out with research framing (not sales)
3. Ask about current pain points
4. Listen for emotional language
5. Probe on willingness to pay

**Key Questions:**
- "How do you currently handle [problem]?"
- "What's the most frustrating part?"
- "How much time/money do you spend on this?"
- "If a solution existed, what would it need to do?"

**Validation Signal:** Multiple people describing same pain with emotional intensity

### Method 2: Landing Page Test

**Goal:** Test demand before building

**Process:**
1. Create landing page describing solution
2. Include call-to-action (email signup, waitlist)
3. Drive traffic (ads, social, communities)
4. Measure conversion rate

**Success Metrics:**
- Email signup > 10% of visitors
- Multiple signups per day
- Engagement with follow-up emails

**Warning:** This tests interest, not payment intent

### Method 3: Pre-Selling

**Goal:** Get payment commitment before building

**Process:**
1. Create offer for future product
2. Offer discount for early commitment
3. Collect payment or firm commitment
4. Only build if threshold met

**Success Metrics:**
- Actual payment received
- Multiple customers willing to wait
- Strong enthusiasm

**This is the strongest validation signal.**

### Method 4: Concierge MVP

**Goal:** Deliver value manually before automating

**Process:**
1. Find handful of early customers
2. Deliver service manually (you do the work)
3. Validate they'll pay for outcome
4. Automate based on what you learn

**Benefits:**
- Learn exactly what customers need
- Validate pricing
- Build customer relationships
- Reduce development risk

---

## Red Flags During Validation

### The "Nice" Trap

| They Say | They Mean |
|----------|-----------|
| "That sounds cool" | Not interested |
| "I'd definitely check it out" | No commitment |
| "Let me know when it launches" | Polite dismissal |
| "I can see someone using this" | Not me though |

### Actual Validation Signs

| They Say/Do | What It Means |
|-------------|---------------|
| "Can I pay now?" | Strong intent |
| "When can I have it?" | Urgency |
| Detailed questions | Evaluating seriously |
| Referrals to colleagues | Believes in value |
| Follow-up emails to you | Genuine interest |

---

## Market Size Evaluation

### Total Addressable Market (TAM)

**Question:** How big is the entire market?

**For bootstrappers:** TAM of $50M-$500M is ideal
- Big enough to build meaningful business
- Small enough that giants ignore

### Serviceable Addressable Market (SAM)

**Question:** What portion can you realistically serve?

**For bootstrappers:** SAM of $10M-$100M is target
- Your actual target market
- Accounts for geographic, language, other limits

### Serviceable Obtainable Market (SOM)

**Question:** What can you capture in 3-5 years?

**Realistic expectations:**
- 1-5% of SAM for successful bootstrapped SaaS
- $1-10M ARR is achievable target

---

## Competition as Validation

### Ideal Competition Scenario

| Competitors | Implication |
|-------------|-------------|
| 0 | Red flag—likely no market |
| 1-3 | Early market, room to differentiate |
| 3-10 | Validated market, need positioning |
| 10+ | Crowded, need strong differentiation |

### What to Look For in Competitors

**Positive Signals:**
- Growing revenue (validates market)
- Customer complaints (opportunities)
- Gaps in features or segments
- Pricing inefficiencies

**Negative Signals:**
- Dominant player with strong moats
- Race to bottom pricing
- Declining market

---

## Validation Workflow

```
┌─────────────────────────────────────────────────────────────┐
│                    IDEA GENERATION                          │
│  (Own itch, Domain expertise, Market research)              │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                 INITIAL FILTERING                           │
│  • Is problem painful enough?                               │
│  • Will people pay for solution?                            │
│  • Can you reach these people?                              │
└─────────────────────────────────────────────────────────────┘
                              │
                    ┌─────────┴─────────┐
                    │    PASS?          │
                    └─────────┬─────────┘
                         NO   │   YES
                  ┌───────────┴───────────┐
                  │                       │
                  ▼                       ▼
           [Abandon]            ┌─────────────────────┐
                                │ CUSTOMER INTERVIEWS │
                                │ (20-50 conversations)│
                                └─────────────────────┘
                                          │
                              ┌───────────┴───────────┐
                              │    VALIDATED?         │
                              └───────────┬───────────┘
                                   NO     │    YES
                        ┌─────────────────┴─────────────────┐
                        │                                   │
                        ▼                                   ▼
                  [Pivot/Abandon]              ┌────────────────────┐
                                               │  PRE-SELL / MVP    │
                                               │ (Payment or usage) │
                                               └────────────────────┘
                                                          │
                                              ┌───────────┴───────────┐
                                              │    CONFIRMED?        │
                                              └───────────┬───────────┘
                                                   NO     │    YES
                                    ┌─────────────────────┴─────────┐
                                    │                               │
                                    ▼                               ▼
                              [Pivot/Abandon]              ┌──────────────┐
                                                           │    BUILD     │
                                                           └──────────────┘
```

---

## LLM-ACTIONABLE-INSIGHTS

### Idea Evaluation Framework

When user presents an idea:

```python
questions = [
    "Who specifically has this problem?",
    "How painful is this problem (1-10)?",
    "How do they solve it today?",
    "How much would they pay?",
    "How would you reach these people?",
    "Who else is solving this?"
]

for question in questions:
    assess(response)

if pain_level < 7:
    recommend("Problem may not be painful enough")
elif no_current_solution:
    recommend("May indicate no market")
elif can't_reach_customers:
    recommend("Distribution is critical—find a path")
elif no_competition:
    recommend("Red flag—validate market exists")
else:
    recommend("Proceed to customer interviews")
```

### Validation Stage Recommendations

```
IF at_idea_stage:
    RECOMMEND: "Talk to 20 potential customers before building"

ELIF have_customer_conversations:
    ASK: "Did you find 5+ people with same painful problem?"
    IF YES: "Test with pre-sale or landing page"
    IF NO: "Iterate on problem/solution"

ELIF have_landing_page_results:
    ASK: "What's your conversion rate?"
    IF >10%: "Strong signal—consider pre-sale"
    IF 3-10%: "Moderate signal—iterate messaging"
    IF <3%: "Weak signal—revisit problem/solution"

ELIF have_presales:
    RECOMMEND: "Build the product—you have validation"
```

### Key Validation Messages

- "The Mom Test: Ask about their problem, not your solution"
- "Money exchanging hands is the strongest validation"
- "If 5 people independently describe the same pain, you're onto something"
- "Politeness is not validation—commitment is"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
