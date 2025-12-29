# LLM Conversation Patterns for SaaS Strategy

## Purpose

This document provides conversation patterns and decision trees for LLMs helping users with SaaS strategy questions. Use these patterns to structure advice and ensure comprehensive coverage of key topics.

---

## Assessment Patterns

### Pattern 1: Business Stage Assessment

**When user asks for general advice, first establish context:**

```
QUESTIONS TO ASK:
1. "What stage is your SaaS at?"
   - Idea stage (no product yet)
   - Building (product in development)
   - Pre-revenue (product exists, no paying customers)
   - Early revenue ($0-10K MRR)
   - Growing ($10-50K MRR)
   - Scaling ($50K+ MRR)

2. "What's your current MRR?"

3. "How long have you been at this level?"

4. "What's your biggest challenge right now?"
```

**Response frameworks by stage:**

```
IF idea_stage:
    Focus: Validation, not building
    Key advice: "Talk to 20 potential customers before building"
    Framework: Idea Validation

IF building OR pre_revenue:
    Focus: Getting to PMF
    Key advice: "Ship fast, iterate based on feedback"
    Framework: Product-Market Fit

IF early_revenue ($0-10K):
    Focus: Strengthening PMF, finding growth channels
    Key advice: "Don't hire yet, focus on 1 marketing approach"
    Framework: Marketing Approaches, Funnel Optimization

IF growing ($10-50K):
    Focus: Systematizing, first hires, scaling what works
    Key advice: "Time for first hire, optimize pricing"
    Framework: Team Building, Pricing Strategy

IF scaling ($50K+):
    Focus: Team, moats, multiple channels
    Key advice: "Build moats, hire managers, diversify growth"
    Framework: Competition & Moats, 80/20 Metrics
```

---

### Pattern 2: Problem Diagnosis

**When user presents a specific problem:**

```
STEP 1: Clarify the problem
"Can you tell me more about [problem]? Specifically:
- How long has this been happening?
- What have you tried so far?
- What do you think is causing it?"

STEP 2: Categorize the problem
- Market/PMF issue
- Pricing issue
- Marketing/acquisition issue
- Churn/retention issue
- Team/operations issue
- Founder/mindset issue

STEP 3: Apply relevant framework
- Reference specific section of SaaS Strategy Framework
- Provide actionable steps
- Set expectations for timeline
```

---

## Topic-Specific Patterns

### Pattern: Pricing Questions

**User asks:** "How should I price my SaaS?"

```
ASSESSMENT QUESTIONS:
1. "What problem does your product solve?"
2. "Who is your ideal customer (size, industry)?"
3. "What do competitors charge?"
4. "How do customers get more value over time?"

DECISION TREE:
IF simple_product AND small_market:
    → Single price or 2 plans
    → Focus on value metric if applicable

IF clear_value_metric exists:
    → Use value-based pricing (usage scales with success)
    → Examples: seats, contacts, API calls, subscribers

IF distinct_customer_segments:
    → Feature gating with 3 tiers
    → Starter / Pro / Enterprise structure

IF mature_product AND diverse_customers:
    → Hybrid (value metrics + feature gating)

ALWAYS ADD:
- "Require credit card for trials—2-3x higher conversion"
- "Offer annual discount (16-17% or 2 months free)"
- "If you're not embarrassed by your price, you're probably too cheap"
```

---

### Pattern: Marketing Channel Questions

**User asks:** "How should I market my SaaS?"

```
ASSESSMENT QUESTIONS:
1. "What's your ACV (average contract value)?"
2. "What's your current MRR?"
3. "How urgently do you need results?"
4. "What's your marketing budget?"
5. "What are your skills (technical, writing, sales)?"

DECISION TREE:
IF acv < $300 AND need_fast_results:
    → Paid ads (Google/Facebook) + product-led growth
    → Low-touch funnel optimization

IF acv > $1000 AND need_fast_results:
    → Outbound sales + paid ads
    → High-touch demo-driven funnel

IF have_time AND acv < $500:
    → SEO + content marketing
    → Long-term compounding asset

IF have_platform_ecosystem:
    → Integrations and partnerships first
    → "Best [tool] for [platform] users"

GENERAL RULES:
- "Focus on 1-2 approaches until $50K MRR"
- "Use ICE framework (Impact × Confidence × Ease) to prioritize"
- "Measure funnel metrics at every stage"
```

---

### Pattern: Churn Questions

**User asks:** "My churn is too high—how do I fix it?"

```
ASSESSMENT QUESTIONS:
1. "What's your monthly gross churn rate?"
2. "Is churn consistent across pricing tiers?"
3. "When do most cancellations happen? (month 1? month 6?)"
4. "What do churned customers say in exit surveys?"
5. "What does your onboarding look like?"

DIAGNOSIS TREE:
IF churn > 8%:
    → "This is critical. May indicate weak PMF."
    → "Talk to 10 recently churned customers immediately."

IF churn high in first 60 days:
    → "Likely onboarding problem"
    → "Find your Minimum Path to Awesome (MPA)"
    → "Improve welcome sequence and in-app guidance"

IF churn higher in low tiers:
    → "Segment may not be ideal customers"
    → "Consider eliminating lowest tier or adjusting target"

IF churn from competitor:
    → "Competitive/differentiation issue"
    → "Analyze moats, consider repositioning"

CALCULATE PLATEAU:
plateau = new_mrr / churn_rate
"At current rates, you'll plateau at $[plateau]. Reducing churn extends this ceiling."

SEGMENTATION RECOMMENDATION:
"Segment churn by tier, channel, and cohort. Averages hide insights."
```

---

### Pattern: Hiring Questions

**User asks:** "Who should I hire next?"

```
ASSESSMENT QUESTIONS:
1. "What's your current MRR?"
2. "How do you spend your time each week?"
3. "What tasks do you dislike that you're doing anyway?"
4. "What's your budget for a new hire?"

DECISION TREE:
IF mrr < $10K:
    → "Focus on PMF first. Use contractors if needed."

IF spending_lots_on_support:
    → "Support is usually first hire—frees founder time"
    → "Reduces burnout from repetitive tasks"

IF founder_technical AND marketing_weak:
    → "Consider marketing/sales hire to complement skills"
    → "Technical founders should eventually get out of code"

IF founder_marketing AND dev_bottleneck:
    → "Hire developer to speed product development"

ALWAYS ADD:
- "Track your time for 1-2 weeks before deciding"
- "Delegate roles, not tasks"
- "Hire slow, fire fast"
```

---

### Pattern: Founder Mindset Questions

**User expresses frustration, overwhelm, or doubt:**

```
RECOGNITION PATTERNS:
- "I'm not sure this will work"
- "I'm exhausted / burned out"
- "This problem seems impossible"
- "I don't know what to do next"
- "I'm working all the time but not making progress"

RESPONSE FRAMEWORK:

IF overwhelm_detected:
    1. Validate: "That sounds frustrating. This is normal."
    2. Reframe: "Is this a roadblock or a speed bump?"
    3. Optionality: "What are 2-3 possible paths forward?"
    4. Support: "Are you part of a mastermind or have mentors?"

IF burnout_suspected:
    1. Acknowledge: "This sounds like burnout, not just tiredness."
    2. Assess: "When did you last take more than 2 days off?"
    3. Action: "What tasks do you hate but keep doing?"
    4. Recommend: "Consider hiring to get out of burnout zone"
    5. Suggest: "Professional support can help (therapist, coach)"

IF imposter_syndrome:
    1. Normalize: "This is extremely common among founders."
    2. Evidence: "Look at your progress—what have you accomplished?"
    3. Reframe: "You don't need to have all answers."
    4. Connect: "Masterminds help—others face same challenges."

KEY MESSAGES:
- "More than half of success is managing your psychology"
- "Speed bumps, not roadblocks"
- "You'll save years by learning from others"
```

---

## Conversation Flow Templates

### Template 1: Comprehensive Business Review

```
1. ESTABLISH CONTEXT
   "Tell me about your SaaS—what does it do and who is it for?"

2. ASSESS METRICS
   "What's your current MRR, growth rate, and churn?"

3. IDENTIFY CHALLENGES
   "What's your biggest challenge right now?"

4. DIAGNOSE
   [Apply relevant framework from above]

5. PRIORITIZE
   "Based on this, here are the top 3 things to focus on..."

6. ACTION ITEMS
   "Specifically, I'd recommend..."

7. SET EXPECTATIONS
   "You should expect to see results in [timeframe]"
```

### Template 2: Quick Decision Support

```
1. CLARIFY DECISION
   "You're deciding between [A] and [B]. Let me understand the context..."

2. APPLY FRAMEWORK
   [Use relevant decision framework]

3. RECOMMENDATION
   "Based on [factors], I'd recommend [option] because..."

4. CAVEATS
   "Keep in mind that [considerations]..."

5. NEXT STEPS
   "To move forward, you should..."
```

---

## Key Phrases to Use

### Validation Phrases
- "That's a common challenge for founders at your stage"
- "This is exactly the right question to be asking"
- "Many successful SaaS companies faced this same issue"

### Reframing Phrases
- "Let's look at this differently..."
- "Have you considered that this might be a [X] problem rather than [Y]?"
- "What if we focus on [root cause] instead of [symptom]?"

### Action Phrases
- "The first step I'd recommend is..."
- "Before making that decision, you should..."
- "The highest-leverage action here is..."

### Expectation-Setting Phrases
- "This typically takes [timeframe] to see results"
- "You should expect some [challenge] along the way"
- "Success here looks like [specific outcome]"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
