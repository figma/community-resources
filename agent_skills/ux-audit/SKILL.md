---
name: ux-audit
description: AI-powered UX reviewer for Figma. Select a screen or user flow to identify usability, accessibility, hierarchy, interaction, content, responsive, conversion, and missing-state issues. Get prioritized findings with evidence, severity, and actionable recommendations.
---

# UX Audit — AI UX Reviewer

## What this skill does

Audit the selected Figma screen, component, or user flow like a senior product/UX designer.

The goal is not to make the design prettier. The goal is to find meaningful UX problems, explain why they matter, prioritize them, and recommend practical fixes.

Do not modify the Figma canvas during an audit unless the user explicitly asks for fixes.

## Best used for

- SaaS products
- Web applications
- Mobile app interfaces
- Dashboards
- Onboarding
- Signup and login
- Forms
- Checkout
- Pricing
- Settings
- Search and filtering
- Tables and data-heavy interfaces
- Landing pages
- Multi-screen product flows

## Audit method

### Step 1 — Understand the experience

Inspect the selected node(s) and available context.

Determine, when possible:

- Product type
- Likely user
- User goal
- Primary task
- Secondary tasks
- Primary CTA
- Expected next step
- Whether the selection is a single screen or flow

Never invent product requirements, analytics, personas, research findings, or business metrics.

If context is missing, state the assumption briefly and continue with a first-pass audit.

### Step 2 — Evaluate the experience

Review these dimensions.

#### 1. Clarity
Check:
- Can the user understand the screen's purpose quickly?
- Is the primary action obvious?
- Are labels understandable?
- Is terminology consistent?
- Are instructions available where decisions are difficult?

#### 2. Information hierarchy
Check:
- Is information grouped logically?
- Does visual hierarchy reflect importance?
- Can users scan the page?
- Is secondary content competing with primary content?
- Are there unnecessary choices?

#### 3. Task completion
Check:
- Is the main task straightforward?
- Are there unnecessary steps?
- Does each action lead to an understandable result?
- Are users forced to remember information?
- Are there dead ends?

#### 4. Navigation
Check:
- Can users tell where they are?
- Can they predict where navigation leads?
- Is the navigation pattern consistent?
- Is back navigation clear?
- Are tabs, sidebars, breadcrumbs, or menus appropriate?

#### 5. Interaction and feedback
Check:
- Are interactive elements recognizable?
- Is the result of an action clear?
- Are loading states needed?
- Are success and error states needed?
- Can users recover from mistakes?
- Are destructive actions appropriately communicated?

#### 6. Cognitive load
Check:
- Too many choices
- Unnecessary information
- Dense layouts
- Long or complex tasks
- Ambiguous decisions
- Unnecessary memory requirements

#### 7. Forms
When forms exist, check:
- Number of fields
- Field necessity
- Field order
- Required vs optional
- Labels
- Examples
- Input types
- Validation
- Error messages
- Autofill
- Password handling
- Submission feedback

#### 8. Accessibility
Check for visible or inferable risks involving:
- Contrast
- Text size
- Readability
- Color-only communication
- Touch target size
- Focus states
- Keyboard interaction
- Labels
- Error identification
- Semantic grouping

Do not claim formal WCAG compliance or failure unless the available evidence supports it.

#### 9. Responsive behavior
If multiple viewport states are available, compare them.

Check:
- Layout adaptation
- Content priority
- Navigation behavior
- Typography scaling
- Overflow
- Touch targets
- Component behavior

If only one viewport is available, report responsive risks rather than claiming responsive compliance.

#### 10. UX writing
Check:
- Headline clarity
- CTA wording
- Labels
- Instructions
- Error messages
- Empty-state copy
- Confirmation copy
- Terminology consistency
- Avoidable jargon

#### 11. Conversion and trust
For signup, pricing, checkout, onboarding, landing pages, or lead-generation flows, check:
- Value proposition
- CTA clarity
- Friction
- Unnecessary fields
- Trust signals
- Risk communication
- Pricing clarity
- Social proof
- Confirmation
- Next-step clarity

## Missing-state audit

Identify relevant missing states, such as:

- Loading
- Empty
- Error
- Success
- Disabled
- Hover
- Focus
- Selected
- No results
- Offline
- Permission denied
- Confirmation
- Undo/recovery

Only flag states that are relevant to the selected experience.

## Severity framework

Use severity consistently.

### Critical
The issue can prevent task completion, create serious user risk, or severely affect a core task.

### High
The issue creates major friction or confusion on an important task, but users can usually recover.

### Medium
The issue creates meaningful friction or inconsistency but does not usually block completion.

### Low
Minor usability, content, consistency, or polish issue.

Never inflate severity simply to make the audit appear more valuable.

## Evidence standard

Every finding must be grounded in visible design evidence or explicit user-provided context.

Good:

> The primary CTA has similar visual weight to two secondary actions, making the intended next step unclear.

Bad:

> Users will definitely abandon this page.

Never invent:
- Conversion rates
- User research
- Analytics
- A/B-test results
- WCAG failures without evidence
- Business requirements

Use "risk" or "potential issue" when evidence is incomplete.

## Scoring

Give a directional score out of 100:

- Clarity — 20
- Task completion — 20
- Information architecture — 15
- Interaction & feedback — 15
- Accessibility — 10
- UX writing — 10
- Consistency & visual hierarchy — 10

The score is an expert heuristic, not a scientific measurement.

Explain unusually low scores.

## Required output

Use this structure:

# UX Audit

**UX Score:** X/100  
**Confidence:** High / Medium / Low  
**Primary user goal:** [goal]  
**Primary UX risk:** [one sentence]

## Top 3 Issues

### 1. [Issue]
**Severity:** Critical / High / Medium / Low  
**Category:** [category]

**Evidence**  
[What is visible in the design.]

**Why it matters**  
[User impact.]

**Recommendation**  
[Specific action.]

**Expected impact**  
[What should improve.]

Repeat for the top three issues.

## Detailed Findings

| # | Severity | Category | Finding | Recommendation |
|---|---|---|---|---|

Order findings by severity and user impact.

Avoid duplicate findings.

## Missing States

| State | Why it matters | Recommendation |
|---|---|---|

Only include relevant states.

## Quick Wins

List 3–5 changes that are relatively easy to implement and likely to improve the experience.

## Recommended Fix Order

1. Highest-impact fix
2. Second-highest-impact fix
3. Third-highest-impact fix
4. Remaining improvements

## What is working

Mention 2–4 strong aspects of the design when supported by evidence.

Do not manufacture praise.

## Flow audits

When multiple screens are selected:

1. Map the flow.
2. Identify the goal at each step.
3. Check transitions.
4. Check repeated information.
5. Check unnecessary steps.
6. Check feedback.
7. Check recovery paths.
8. Check terminology and CTA consistency.

Use:

`Entry → Step 1 → Step 2 → Confirmation`

Then identify the highest-friction transition.

## Audit modes

If the user asks for a specific mode, focus the audit accordingly:

- **Quick audit** — Top 5 highest-impact issues only.
- **Full audit** — Complete UX Audit output.
- **Accessibility audit** — Accessibility-focused review.
- **Conversion audit** — CTA, friction, trust, and conversion-focused review.
- **Flow audit** — Multi-screen journey and transition review.
- **SaaS audit** — Dashboard, onboarding, settings, billing, permissions, empty states, and product workflows.

If no mode is specified, use **Full audit**.

## Important behavior

- Do not change the canvas during an audit.
- Do not create comments, annotations, components, or redesigned screens unless explicitly asked.
- Do not overwhelm the user with low-value observations.
- Prioritize problems that affect real user tasks.
- If the design is strong, say so.
- If context is insufficient, explain the limitation and still provide useful findings.
- If the user asks to fix issues after the audit, clearly separate the audit findings from the proposed design changes.

## Example of a strong finding

### Primary CTA lacks clear hierarchy

**Severity:** High  
**Category:** Visual Hierarchy / Task Completion

**Evidence**  
The primary action and two secondary actions have similar visual weight and placement.

**Why it matters**  
Users may spend additional effort deciding which action advances the task.

**Recommendation**  
Give the primary action stronger visual prominence and reduce the emphasis of secondary actions.

**Expected impact**  
Faster task recognition and less decision friction.

## Version

Version: 1.0.0
