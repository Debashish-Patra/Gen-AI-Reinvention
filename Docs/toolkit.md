---
layout: default
title: Toolkit
---

[Home](index.md) / [Marketing example](example-marketing.md) / Toolkit

# The toolkit

Six templates you can copy into a spreadsheet or document and fill in. Each one matches a step in the [four phases](phases.md) and a pillar in the [five pillars](pillars.md). The [marketing example](example-marketing.md) shows each one filled in.

| # | Template | Use it in | Pillar |
|---|---|---|---|
| 1 | [Ambition and baselines](#1-ambition-and-baselines) | Frame | Lead with Value |
| 2 | [Use-case scoring grid](#2-use-case-scoring-grid) | Prioritize | Lead with Value |
| 3 | [Business case worksheet](#3-business-case-worksheet) | Prioritize | Lead with Value |
| 4 | [Risk screen](#4-risk-screen) | Prioritize, Build and pilot | Responsible AI |
| 5 | [Role impact map](#5-role-impact-map) | Prioritize, Scale | Talent and new ways of working |
| 6 | [Pilot design and gate sheet](#6-pilot-design-and-gate-sheet) | Build and pilot | All five |

---

## 1. Ambition and baselines

*Use in Frame. Fill it in before anything is built.*

**Ambition, in one sentence:**

> ______________________________________________

**Sponsor:** ____________ **Finance partner:** ____________ **Date agreed:** ____________

| Measure | How it is counted | Baseline today | Source | Owner | Target |
|---|---|---|---|---|---|
| Cost | e.g. cost per asset or per campaign | | | | |
| Speed | e.g. days from brief to launch | | | | |
| Response | e.g. conversion rate | | | | |
| Loyalty or retention | e.g. repeat purchase rate | | | | |

**Tips**

- Three to five measures is enough. More than that and nobody tracks them.
- Finance should agree the baselines, not just see them.
- Write the source down. Someone will ask how a number was counted.

---

## 2. Use-case scoring grid

*Use in Prioritize. One row per idea.*

**Scoring guide (1 to 5)**

| Score | Value: how much does it matter? | Readiness: how ready are we? |
|---|---|---|
| **5** | Moves a headline number for the business | Data, tools, skills and policy all in place |
| **4** | Clear, measurable gain for a whole function | One small gap, fixable in weeks |
| **3** | Useful, but limited in reach | Some gaps, fixable in a quarter |
| **2** | Nice to have | Major gaps, such as data in separate systems |
| **1** | Marginal | Not feasible today |

**Scoring sheet**

| # | Use case | Function | Table stake or strategic bet | Value (1-5) | Readiness (1-5) | Quadrant | Decision |
|---|---|---|---|---|---|---|---|
| 1 | | | | | | | |
| 2 | | | | | | | |
| 3 | | | | | | | |
| 4 | | | | | | | |
| 5 | | | | | | | |
| 6 | | | | | | | |
| 7 | | | | | | | |

**Quadrant rule**

| | Readiness 1 to 3 | Readiness 4 to 5 |
|---|---|---|
| **Value 4 to 5** | **Long-term investment.** Build the foundation first | **Top priority.** Pilot now |
| **Value 1 to 3** | **Deprioritised.** Park it on purpose | **To be monitored.** Do it if cheap |

**Tips**

- Score as a group, then compare. Differences in scores start the best conversations.
- A table stake is something competitors already do. It needs to be done well, not argued about.
- Pair ideas that share a build, as the marketing example does with content and email.
- Record why each idea was parked. It saves the argument next quarter.

---

## 3. Business case worksheet

*Use in Prioritize. One sheet per shortlisted idea. Build an optimistic and a pessimistic case.*

**Inputs**

| Input | Pessimistic | Optimistic | Source |
|---|---|---|---|
| Volume per month (assets, campaigns, tickets) | | | |
| Cost per unit today | | | |
| Share of volume AI-assisted, year 1 | | | |
| Share of volume AI-assisted, year 2 | | | |
| Share of volume AI-assisted, year 3 | | | |
| Cost saved per AI-assisted unit | | | |
| Revenue or margin affected per year | | | |
| Uplift at full effect | | | |
| Build cost and build months | | | |
| Run cost per year, from launch | | | |
| Discount rate | | | |

**Formulas**

| Line | Formula |
|---|---|
| **Cost saved per year** | volume per month × 12 × cost per unit × share AI-assisted × cost saved per unit |
| **Uplift value per year** | revenue affected × margin × uplift × ramp |
| **Benefit per year** | cost saved + uplift value |
| **Net value per year** | benefit − run cost (and − build cost in build months) |
| **Net present value (NPV)** | sum of each period's net value ÷ (1 + discount rate)^(time in years) |
| **Return on investment (ROI)** | (total benefit − total cost) ÷ total cost |
| **Breakeven** | first month in which cumulative net value is above zero |

**Results**

| | Pessimistic | Optimistic |
|---|---|---|
| Total cost | | |
| Total benefit | | |
| NPV | | |
| ROI | | |
| Breakeven month | | |

**The hurdle (agree it before you calculate):**
NPV above zero in the pessimistic case, and breakeven within ______ months.

**Tips**

- Start with the pessimistic case. If it clears the hurdle, the decision is easy.
- Ramp adoption. Nobody reaches 90% of volume in the first month.
- Count the cost of fixing readiness gaps, not just the cost of the tool.
- Keep the two cases far enough apart to be useful but close enough to be believed.
- The pilot will replace your assumptions with measured numbers. Update the sheet at Gate 3.

---

## 4. Risk screen

*Use in Prioritize for a first pass, and again in Build and pilot. One row per shortlisted use case.*

**Questions to ask of each use case**

| Risk area | Question | Low | Medium | High |
|---|---|---|---|---|
| **Personal data** | Does the AI see or use personal or sensitive data? | None | Some, anonymised | Yes, identifiable |
| **Accuracy** | What happens if the output is wrong? | Minor edit | Customer confusion | Legal, safety or financial harm |
| **Claims** | Does it make claims about price, policy, health or performance? | No | Some | Yes |
| **Brand and tone** | Could it say something off-brand or offensive? | Unlikely | Possible | Likely without review |
| **Fairness** | Could it treat groups of people differently? | No | Possibly | Yes |
| **Intellectual property** | Could it copy or expose protected content? | No | Possibly | Yes |
| **Reach** | How many people see it before a person can stop it? | None | Some | Many |

**Risk register**

| # | Use case | Risk | Level | Control | Owner | Residual level | Reviewed on |
|---|---|---|---|---|---|---|---|
| 1 | | | | | | | |
| 2 | | | | | | | |
| 3 | | | | | | | |

**Controls to choose from**

- A person approves before anything is published.
- An approved-claims library, checked automatically.
- Consent and opt-out checks before personal data is used.
- Test sets run before each release.
- A log of every output, with who approved it.
- A named person who can switch the use case off.

**Tips**

- Any "High" with no control is a showstopper. Fix it or park the idea.
- Log near-misses as well as incidents. They show where reviewers are catching problems.
- A falling reviewer rejection rate is good news only if serious errors are not rising.

---

## 5. Role impact map

*Use in Prioritize and again in Scale. One row per role touched by the use case.*

| Role | Headcount | Tasks that shrink | Tasks that grow | Skills to build | Change | Plan |
|---|---|---|---|---|---|---|
| | | | | | Augmented, changed or new | |
| | | | | | | |
| | | | | | | |
| | | | | | | |

**How to read "Change"**

| Label | Meaning | Example |
|---|---|---|
| **Augmented** | Same job, faster or better | A copywriter drafts with AI help |
| **Changed** | Job shifts toward new tasks | A designer moves toward briefing, editing and guarding brand voice |
| **New** | A role that did not exist | A prompt and quality lead |

**Plan options:** reskill · redeploy · hire · pause hiring · no change

**Tips**

- Talk to the people in the roles. They know which tasks are routine.
- Say what freed time is for, such as testing, customer insight or new work. People notice when it is left unsaid.
- Update role descriptions, not just training.
- Name a community of practice owner so prompts and lessons are shared.

---

## 6. Pilot design and gate sheet

*Use in Build and pilot. Complete the first two sections before the pilot starts.*

**A. Scope**

| Item | Your answer |
|---|---|
| Use case | |
| Scope (one category, market or team) | |
| Channel | |
| Duration | 12 weeks, or: |
| Pilot team | |
| Control group (comparable, doing the work the normal way) | |

**B. Human and AI workflow**

| Step | Who does it | Tool or system | Human approval needed? |
|---|---|---|---|
| Brief | | | |
| Generate | | | |
| Review | | | Yes |
| Publish | | | Yes |
| Measure | | | |

**C. Gate test, written before the pilot starts**

| Measure | Control baseline | Required result | Actual | Pass? |
|---|---|---|---|---|
| Cost per unit | | | | |
| Speed | | | | |
| Response | | | | |
| Reviewer rejection rate | | Falling | | |
| Serious incidents | | None | | |

**D. Decision**

| Outcome | Tick | Reason and next step |
|---|---|---|
| **Go** | ☐ | |
| **Fix** | ☐ | |
| **Stop** | ☐ | |

**Decided by:** ____________ **Date:** ____________

**Tips**

- Never change the required result after the pilot begins.
- Usage numbers are not results. Compare with the control group.
- Update the business case with the measured numbers before taking it to the next gate.

---

## Using the toolkit

A suggested order for a first programme:

1. **Week 1:** template 1, with the sponsor and Finance.
2. **Weeks 4 to 6:** template 2 with each function, then template 5 for the top ideas.
3. **Weeks 6 to 8:** templates 3 and 4 for the shortlist.
4. **Before the pilot:** sections A to C of template 6.
5. **After the pilot:** section D, and update template 3.

---

## Next

[← Marketing example](example-marketing.md) · [**FAQ and glossary →**](faq.md)

---

**About.** Created by [Your name]. An independent, simplified framework with original diagrams and illustrative examples. It contains no confidential material from any employer or client; the example companies and figures are fictional. Content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
