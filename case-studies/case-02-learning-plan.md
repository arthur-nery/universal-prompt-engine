# Case Study 02 — Ruby on Rails Learning Plan Prompt

## English Description

This case study shows how the **Universal Prompt Engine (UPE)** transforms a broad learning goal — "I want to learn Ruby on Rails fast to get a remote job" — into a structured, practical, and time-constrained prompt for building a focused learning plan.

## Scenario

A user wants to learn Ruby on Rails quickly with the goal of becoming job-ready for remote work, but lacks clarity about:

- what to study first;
- how to prioritize practice over theory;
- how to create portfolio projects;
- how to prepare for real job requirements;
- how to avoid wasting time on scattered tutorials;
- how to structure a fast but realistic learning path.

## Raw User Input

```text
I want to learn Ruby on Rails fast to get a remote job.
```

## UPE Mode Used

**Mode 2 — Professional / Consultative**

Reason: the problem is goal-oriented and requires structured clarification around timeline, current skill level, available study time, preferred learning style, job target, portfolio requirements, and constraints.

## Interview Simulation

### User Input

```text
I want to learn Ruby on Rails fast to get a remote job.
```

### UPE Questions

1. What is your current programming level?
2. How much time can you study per day?
3. What is your target timeline to become job-ready?
4. Are you focusing on backend, full-stack Rails, automation, APIs, or general web development?
5. Do you prefer theory-first learning or project-based learning?
6. What kind of remote job are you targeting: junior developer, freelance work, automation projects, or international roles?
7. What tools or platforms do you already use, such as GitHub, Linux, Termux, VS Code, or deployment platforms?
8. What output format should the final plan have?

### User Answers

1. I have strong logical reasoning and basic experience with Python, HTML, and CSS.
2. I can study around 5 to 6 hours per day.
3. I want to become job-ready in around 30 days, even if this is aggressive.
4. I want to focus on Rails for backend systems, automation, APIs, and practical business value.
5. I prefer 80% practice and 20% theory.
6. I want to target remote and international opportunities, but I also want practical projects that can show value fast.
7. I use GitHub and mobile-first tools such as Termux, and I want to publish projects publicly.
8. I want a structured 30-day plan with daily tasks, projects, milestones, review checkpoints, and portfolio outputs.

## Generated Prompt

```markdown
You are a senior Ruby on Rails mentor, technical reviewer, and career strategist specialized in helping beginners become job-ready through practical projects.

Your task is to create a focused 30-day Ruby on Rails learning plan for someone who wants to become capable of applying to remote jobs and building practical backend/automation projects.

Use first principles thinking to break the learning path into fundamentals:

- What a job-ready Rails beginner actually needs to know;
- Which skills create the highest leverage for remote opportunities;
- Which concepts should be learned through projects instead of passive theory;
- Which portfolio projects best demonstrate backend, API, database, and automation ability;
- Which mistakes usually slow beginners down.

Context:

I have strong logical reasoning and basic experience with Python, HTML, and CSS.
I can study 5 to 6 hours per day.
My goal is to become job-ready in around 30 days, even though I understand this is aggressive.
I want to focus on Ruby on Rails for backend systems, automation, APIs, and practical business value.
I prefer 80% practice and 20% theory.
I want to target remote and international opportunities.
I use GitHub and want to publish my projects publicly.
I may use mobile-first tools such as Termux when necessary.

Please create a practical learning plan with this structure:

1. Reality check: what is realistic in 30 days and what is not
2. Core skills roadmap for Ruby and Rails
3. 30-day study plan divided by weeks and days
4. Daily routine using 5 to 6 hours per day
5. 3 portfolio projects to build and publish on GitHub
6. What to learn by building each project
7. Debugging and review checklist
8. Job-readiness checklist
9. Remote job preparation steps
10. Common traps and how to avoid them using a Devil's Advocate section
11. Final 7-day sprint plan for applications, GitHub polishing, README improvement, and interview preparation

Constraints:

- Prioritize practice over theory.
- Use simple explanations without dumbing down the content.
- Focus on projects that demonstrate real business value.
- Avoid scattered tutorials and passive consumption.
- Include GitHub publishing as part of the workflow.
- Include review checkpoints and self-assessment.
- Make the plan intense but sustainable.
- Be honest about the limits of becoming job-ready in 30 days.
```

## GPT Test 01 — Clarity Test

### Input

The generated prompt was given to GPT as-is.

### Expected Behavior

GPT should produce a clear learning roadmap instead of a generic list of Ruby on Rails resources.

### Observed Result

GPT produced a structured 30-day roadmap with weekly goals, daily study blocks, Rails fundamentals, project milestones, GitHub publishing tasks, and job-preparation steps.

### Evaluation

- Strengths: The prompt clearly defines the role, context, timeline, constraints, and desired output structure.
- Weaknesses: The plan may still require adjustment depending on the user's actual debugging speed.
- Fixes needed: Add a rule to include fallback paths for days when the user gets stuck.

### Status

Pass

## GPT Test 02 — Constraint Test

### Input

The generated prompt was tested while checking whether GPT respected these constraints:

- 30-day timeline;
- 5 to 6 hours per day;
- 80% practice and 20% theory;
- GitHub publishing;
- remote job orientation;
- project-based learning;
- honest reality check.

### Expected Behavior

GPT should avoid presenting an unrealistic promise and should balance ambition with practical execution.

### Observed Result

GPT included a reality check, warned that 30 days is aggressive, and focused on building visible portfolio projects instead of claiming guaranteed job placement.

### Evaluation

- Strengths: The prompt forces realistic framing while still producing an execution plan.
- Weaknesses: GPT may need more specificity about which Rails version or deployment stack to use.
- Fixes needed: Add optional environment constraints, such as Rails version, database choice, and deployment platform, when needed.

### Status

Pass

## GPT Test 03 — Output Quality Test

### Input

Comparison between the raw user input and the generated UPE prompt.

Raw input:

```text
I want to learn Ruby on Rails fast to get a remote job.
```

Generated UPE prompt:

A structured Rails learning strategy prompt with mentor role, context, timeline, practice ratio, project requirements, GitHub publishing, remote job positioning, review checkpoints, Devil's Advocate analysis, and final sprint plan.

### Expected Behavior

The UPE-generated prompt should produce a significantly more useful and actionable response than the raw user input.

### Observed Result

The generated prompt gives GPT enough context to create a focused, practical, portfolio-driven plan instead of a generic study roadmap.

### Evaluation

- Strengths: The UPE transforms an ambitious but vague learning goal into a realistic and structured execution system.
- Weaknesses: The case would be stronger if linked to real portfolio repositories built during the 30-day plan.
- Fixes needed: Future iterations can include links to completed Rails projects, README examples, and progress logs.

### Status

Pass

## Final Notes

This case study shows that the UPE is useful for converting a broad learning ambition into a structured learning prompt with constraints, milestones, and real portfolio outcomes.

It demonstrates three core strengths of the UPE:

1. It clarifies the learner's current context before planning.
2. It turns a vague educational goal into a focused execution roadmap.
3. It improves GPT output by adding role, constraints, project requirements, review logic, and career orientation.

## Portfolio Value

This case can be used to show prompt engineering capability in educational planning, technical learning design, career preparation, and developer portfolio strategy.
