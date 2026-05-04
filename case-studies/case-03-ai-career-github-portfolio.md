# Case Study 03 — AI Career and GitHub Portfolio Strategy Prompt

## English Description

This case study shows how the **Universal Prompt Engine (UPE)** transforms a broad career goal — "I want to position myself as an AI specialist and build a strong GitHub portfolio" — into a structured, practical, and portfolio-oriented prompt for career positioning, proof-of-work creation, and strategic GitHub publishing.

## Scenario

A user wants to become publicly credible as an AI specialist, but lacks clarity about:

- how to define a specific AI positioning;
- what kind of GitHub repositories to create;
- how to turn prompts, systems, and workflows into proof of work;
- how to make the portfolio understandable to recruiters, founders, and clients;
- how to avoid looking generic in a crowded AI market;
- how to create a repeatable publishing system.

## Raw User Input

```text
I want to position myself as an AI specialist and build a strong GitHub portfolio.
```

## UPE Mode Used

**Mode 2 — Professional / Consultative**

Reason: the problem is strategic and career-oriented, requiring clarification around target audience, positioning, portfolio structure, proof-of-work, repository standards, publishing cadence, and differentiation.

## Interview Simulation

### User Input

```text
I want to position myself as an AI specialist and build a strong GitHub portfolio.
```

### UPE Questions

1. What type of AI specialist do you want to become: prompt engineer, automation builder, AI product strategist, AI workflow designer, technical implementer, or another role?
2. Who is the target audience for your portfolio: recruiters, founders, small businesses, agencies, technical teams, or international clients?
3. What proof of work do you already have or want to create first?
4. What kinds of repositories do you want to publish: prompts, case studies, automation workflows, small apps, documentation systems, or research reports?
5. What should your portfolio communicate in under 30 seconds?
6. What constraints should the strategy respect, such as time, budget, tools, privacy, or technical level?
7. How frequently do you want to publish new work?
8. What output format do you want from the final LLM response?

### User Answers

1. I want to position myself as a prompt engineer and AI automation strategist, with future expansion into AI workflow systems and practical business automation.
2. My audience includes recruiters, founders, small businesses, agencies, and international clients.
3. I have prompts, prompt systems, GitHub repositories, automation ideas, case studies, and documented workflows.
4. I want to publish prompts, case studies, automation workflows, small practical tools, README-driven projects, and portfolio-ready documentation.
5. It should communicate that I can turn vague problems into structured AI systems, prompts, workflows, and execution plans.
6. Constraints: low budget, fast execution, privacy-first publishing, public-safe examples, simple tools, GitHub-first workflow, and no unnecessary complexity.
7. I want a consistent publishing rhythm, ideally 3 prompts per day when possible.
8. I want a strategic execution plan with positioning, repo structure, project ideas, publishing workflow, quality checklist, and next actions.

## Generated Prompt

```markdown
You are an AI career strategist, prompt engineering portfolio reviewer, and GitHub proof-of-work architect.

Your task is to help me position myself as an AI specialist and build a strong GitHub portfolio that communicates practical skill, strategic thinking, and real execution ability.

Use first principles thinking to break the problem down into fundamentals:

- What makes an AI specialist credible;
- What kind of proof of work matters to recruiters, founders, clients, and technical teams;
- How GitHub repositories should be structured to be understandable and portfolio-ready;
- How to turn prompts, workflows, and case studies into public-safe artifacts;
- How to create a repeatable publishing system without overcomplicating the process.

Context:

I want to position myself as a prompt engineer and AI automation strategist, with future expansion into AI workflow systems and practical business automation.
My audience includes recruiters, founders, small businesses, agencies, and international clients.
I have prompts, prompt systems, GitHub repositories, automation ideas, case studies, and documented workflows.
I want to publish prompts, case studies, automation workflows, small practical tools, README-driven projects, and portfolio-ready documentation.
My portfolio should communicate in under 30 seconds that I can turn vague problems into structured AI systems, prompts, workflows, and execution plans.

Constraints:

- Low budget;
- Fast execution;
- Privacy-first publishing;
- Public-safe examples only;
- Simple tools;
- GitHub-first workflow;
- No unnecessary complexity;
- Prefer Markdown, Git, plain text, and reusable documentation;
- Use English-first positioning for international readers.

Please produce a strategic execution plan with this structure:

1. Positioning statement for my AI specialist profile
2. Clear niche options and which one to prioritize first
3. GitHub portfolio architecture
4. Repository categories I should create
5. Standard structure for each repository
6. Prompt/case study publishing workflow
7. Quality checklist before publishing
8. 10 project ideas ranked by portfolio value, speed, and business relevance
9. How to make each project public-safe without exposing private details
10. How to write README files for international readers
11. Devil's Advocate section: risks, weak positioning, and credibility gaps
12. 7-day execution sprint
13. 30-day portfolio roadmap
14. Three actions I should take today

Output requirements:

- Be direct and practical.
- Avoid generic career advice.
- Focus on proof of work, not credentials alone.
- Prefer small, publishable projects over large unfinished systems.
- Include examples of repository names and README sections.
- Include a portfolio review checklist.
- Keep the strategy execution-oriented.
```

## GPT Test 01 — Clarity Test

### Input

The generated prompt was given to GPT as-is.

### Expected Behavior

GPT should produce a clear AI career and GitHub portfolio strategy instead of generic advice about learning AI or networking.

### Observed Result

GPT produced a structured strategy with positioning options, repository categories, README standards, project ideas, publishing workflow, quality checklist, and short-term execution plan.

### Evaluation

- Strengths: The prompt provides a clear role, target audience, constraints, portfolio goals, and output structure.
- Weaknesses: The strategy may need adaptation depending on whether the user targets employment, freelancing, consulting, or founder-led opportunities first.
- Fixes needed: Add a decision tree for choosing between job-seeking, freelancing, and service-business positioning in future versions.

### Status

Pass

## GPT Test 02 — Constraint Test

### Input

The generated prompt was tested while checking whether GPT respected these constraints:

- low budget;
- fast execution;
- privacy-first publishing;
- public-safe examples only;
- GitHub-first workflow;
- English-first positioning;
- simple tools;
- no unnecessary complexity.

### Expected Behavior

GPT should recommend a practical, low-cost, GitHub-centered portfolio strategy using public-safe artifacts and simple documentation systems.

### Observed Result

GPT focused on Markdown-based repositories, prompt case studies, public-safe examples, reusable README structures, small projects, GitHub publishing, and clear English-first positioning.

### Evaluation

- Strengths: The constraints helped avoid vague personal branding advice and forced a practical proof-of-work strategy.
- Weaknesses: GPT may still suggest too many simultaneous project categories if not asked to prioritize aggressively.
- Fixes needed: Add a rule to select only one primary portfolio lane for the first 7 days.

### Status

Pass

## GPT Test 03 — Output Quality Test

### Input

Comparison between the raw user input and the generated UPE prompt.

Raw input:

```text
I want to position myself as an AI specialist and build a strong GitHub portfolio.
```

Generated UPE prompt:

A structured AI career and GitHub portfolio strategy prompt with role, audience, constraints, positioning, repository architecture, publishing workflow, project ideas, public-safe rules, README standards, Devil's Advocate analysis, 7-day sprint, 30-day roadmap, and same-day actions.

### Expected Behavior

The UPE-generated prompt should produce a significantly better response than the raw user input.

### Observed Result

The generated prompt gives GPT enough context to produce a focused portfolio strategy that emphasizes proof of work, repository structure, public-safe documentation, and execution cadence instead of generic career advice.

### Evaluation

- Strengths: The UPE turns a broad personal branding goal into a concrete portfolio-building system.
- Weaknesses: The case would be stronger with before/after screenshots, repository examples, and measurable portfolio review criteria.
- Fixes needed: Future iterations can include real GitHub repo audits, README scoring rubrics, and public portfolio milestones.

### Status

Pass

## Final Notes

This case study shows that the UPE is useful for turning a broad AI career goal into a structured, proof-of-work-based execution prompt.

It demonstrates three core strengths of the UPE:

1. It clarifies positioning before recommending actions.
2. It translates vague ambition into portfolio architecture and publishing workflow.
3. It improves GPT output by adding audience, constraints, proof-of-work logic, public-safety requirements, and execution cadence.

## Portfolio Value

This case can be used to show prompt engineering capability in career strategy, AI positioning, GitHub portfolio design, public proof-of-work systems, and prompt-based professional branding.
