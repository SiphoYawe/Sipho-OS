# Hiring Strategy

## Core Philosophy

> "When building your team, delegate roles, not tasks."

As a founder, you perform many roles. The mistake is thinking you can hire people who handle multiple disparate roles like you do. You're unique—hire specialists.

---

## The SaaS Departments

Every SaaS company has these departments (even if one person handles several):

| Department | Focus | First Hire Title |
| ---------- | ----- | ---------------- |
| **Product** | What to build, how it functions | Product Manager |
| **Design** | How it looks, UX considerations | UX Designer |
| **Engineering** | Writing code, infrastructure | Software Engineer |
| **Marketing** | Generating/converting inbound leads | Marketing Specialist |
| **Sales** | Qualifying and closing deals | Account Executive |
| **Customer Support** | Answering questions | Support Representative |
| **Customer Success** | Onboarding, reducing churn | Customer Success Manager |
| **HR/People Ops** | Compliance, payroll, people | Operations Manager |
| **Legal** | Contracts, compliance | Outsourced lawyer |
| **Finance** | Books, taxes, cash flow | Outsourced bookkeeper |

---

## Determining What to Hire Next

### The Role Prioritization Process

**Step 1: Track your time for 1-2 weeks**

Document everything you do:
- Support emails (2 hours)
- Code review (3 hours)
- Marketing content (4 hours)
- Sales demos (5 hours)
- etc.

**Step 2: Group by department/role**

| Department | Hours/Week | % of Time |
| ---------- | ---------- | --------- |
| Engineering | 15 | 37.5% |
| Sales | 10 | 25% |
| Support | 8 | 20% |
| Marketing | 5 | 12.5% |
| Admin | 2 | 5% |

**Step 3: Ask yourself these questions:**

1. Which of these am I bad at and someone else could do better?
2. Which of these am I good at but don't enjoy?
3. Which of these could I stop doing without negative impact?
4. Which of these could I hand off to a current team member?
5. Which of these, if leveled up, would most grow the company?

### Typical Hiring Sequence

| Stage | Revenue | Typical Hires |
| ----- | ------- | ------------- |
| Solo founder | $0-10K MRR | Just you |
| First hire | $10-30K MRR | Support or dev contractor |
| Early team | $30-80K MRR | 2-4: Support, dev, marketing |
| Growth team | $80-200K MRR | 5-10: Add sales, success, design |
| Scaling | $200K+ MRR | 10+: Department leads, managers |

---

## Role Combinations That Work

Early on, you'll need generalists. Some roles combine naturally:

| Combined Role | Works Because |
| ------------- | ------------- |
| Support + Success | Both customer-facing, retention focus |
| Marketing + Sales | Both revenue-focused |
| Engineering + DevOps | Both technical |
| Product + UX | Both design-thinking |
| Operations + HR | Both administrative |

### Roles That Don't Combine Well

| Bad Combination | Why It Fails |
| --------------- | ------------ |
| Support + Development | Context switching, skill mismatch |
| Sales + Engineering | Opposite skill sets |
| Marketing + Finance | Opposite mindsets |
| Design + DevOps | Completely different domains |

---

## Hiring Great People

### Be Different

> "Your job description should convince the person reading it that you have a fantastic company."

**Write job descriptions that:**
- Show personality (not corporate speak)
- Describe interesting problems
- Highlight advantages of small company
- Explain why you're picky
- Attract A-players, repel mediocrity

**Example differentiators:**
```
NOT: "Competitive salary and benefits"
YES: "You'll work directly with founders on challenging problems
     in a 10-person remote team with zero politics"
```

### Lean Into Your Advantages

Big companies have: High pay, brand recognition, stability

You have:
- No politics
- Direct founder access
- Remote/flexibility
- Interesting problems
- Real impact
- Fast-paced learning

### The Job Description Formula

1. **Hook** - Why this company is different
2. **Role** - Clear description of responsibilities
3. **Requirements** - Skills needed (not inflated)
4. **Advantages** - What makes working here great
5. **Culture** - What the team is like
6. **Process** - How to apply

---

## Interview Best Practices

### Structured Interview Process

| Stage | Purpose | Duration |
| ----- | ------- | -------- |
| Resume screen | Basic qualification | 5 min |
| Phone screen | Culture fit, communication | 15-30 min |
| Skills interview | Technical/role assessment | 30-60 min |
| Team interview | Fit with future colleagues | 30-45 min |
| Reference check | Verify claims and fit | 15 min each |
| Final decision | Founder sign-off | - |

### What to Look For

| Trait | How to Assess |
| ----- | ------------- |
| **Competence** | Skills test, portfolio, references |
| **Culture fit** | Values alignment, team chemistry |
| **Communication** | Interview clarity, writing samples |
| **Curiosity** | Questions they ask, learning examples |
| **Ownership** | Past examples of initiative |

### Red Flags

- Badmouthing previous employers
- Can't explain what they did (vs. team)
- No questions about the role
- Doesn't do homework on your company
- Overconfidence without substance

---

## Hiring Timeline Rule

> "Hire slow, fire fast."

**Hiring slow means:**
- Don't rush to fill a role
- Interview multiple strong candidates
- Do thorough reference checks
- Trust your gut on culture fit

**Firing fast means:**
- If someone isn't working out, address it quickly
- Don't let poor performers drag down the team
- "No one has ever said they fired someone too soon"

---

## Job Title Guidelines

> "Don't invent job titles."

**Why standard titles matter:**
- Candidates search for standard titles
- Salary data uses standard titles
- Next employer needs to understand their experience
- Recruiter tools use standard titles

**Standard engineering hierarchy:**
```
Chief Technical Officer
VP of Engineering
Director of Engineering
Manager of Engineering
Senior Software Engineer
Software Engineer
Junior Software Engineer
```

**Title inflation warning:**
Don't give early employees inflated titles (e.g., "Head of Customer Success" for first support person). You'll regret it when you need a real leader in that role.

---

## Compensation

### Options for Incentives

| Type | Best For | Considerations |
| ---- | -------- | -------------- |
| **Salary** | Everyone | Standard, predictable |
| **Bonuses** | Short-term incentives | Can feel arbitrary |
| **Equity** | Cofounders, key early hires | Complex tax implications |
| **Stock options** | Growth-focused teams | Requires exit to realize value |
| **Profit sharing** | Profitable, long-term companies | Aligns with company success |

### Profit Sharing Model

**The Balsamiq approach:**
- Pool of 10-20% of profits
- Distributed quarterly
- 25% split equally
- 75% based on seniority
- Adjusted for cost of living

**Why quarterly:**
- Monthly = too much paperwork
- Yearly = unhappy people stay too long

---

## LLM-ACTIONABLE-INSIGHTS

### Hiring Decision Framework

When user asks about hiring:

```python
def recommend_hire(mrr, founder_tasks, pain_points):
    if mrr < 10000:
        return "Focus on getting to PMF first. Hire contractors only."

    if support_overwhelm(pain_points):
        return "Support is usually first hire—frees founder time"

    if founder_is_technical and marketing_weak:
        return "Consider marketing/sales hire to complement skills"

    if founder_is_marketing and dev_bottleneck:
        return "Hire developer to speed product development"

    return "Track time for 2 weeks, then decide based on data"
```

### Assessment Questions

```
1. "What's your current MRR?"
2. "How do you spend your time each week?"
3. "What task would free you up most if someone else did it?"
4. "Is there work you're avoiding because you don't enjoy it?"
5. "What's your budget for a new hire?"
```

### Key Messages

- "Delegate roles, not tasks"
- "Hire slow, fire fast"
- "Support is often the first hire"
- "Standard job titles matter"
- "Your advantages are flexibility, impact, and no politics"

---

## Source

Based on **"The SaaS Playbook: Build a Multimillion-Dollar Startup Without Venture Capital"** by Rob Walling (2023).
