# Case Study 01 — Business Automation Prompt

## PT-BR Description

Este estudo de caso demonstra como o **Universal Prompt Engine (UPE)** transforma um pedido inicial vago — "Quero vender automações com IA para pequenos negócios, mas não sei por onde começar" — em um prompt estratégico, estruturado e executável para pesquisa, posicionamento e validação de uma oferta de automação com IA.

## English Description

This case study shows how the **Universal Prompt Engine (UPE)** turns a vague business idea — "I want to sell AI automations to small businesses, but I do not know where to start" — into a structured, actionable prompt for researching, positioning, and validating an AI automation service offer.

## Scenario

A user wants to start selling AI automation services to small businesses but lacks clarity about:

- which niche to target;
- what problem to solve first;
- how to position the offer;
- how to avoid building something too broad;
- how to create a first practical execution path.

## Raw User Input

```text
Quero vender automações com IA para pequenos negócios, mas não sei por onde começar.
```

## UPE Mode Used

**Mode 2 — Professional / Consultative**

Reason: the problem is business-oriented and requires structured clarification around niche, customer pain, constraints, value proposition, offer format, and first execution steps.

## Interview Simulation

### User Input

```text
Quero vender automações com IA para pequenos negócios, mas não sei por onde começar.
```

### UPE Questions

1. What type of small businesses do you want to focus on first, or are you still deciding the niche?
2. What kind of pain do you want to solve: saving time, saving money, making more money, reducing manual work, or improving customer follow-up?
3. What tools or skills do you already have available to build the first automation?
4. Do you want to start with a simple service, a consulting offer, or a done-for-you automation package?
5. What is your preferred first market: local businesses, online businesses, Brazilian businesses, or international small businesses?
6. What result would make the first version successful?
7. What constraints should the prompt respect, such as budget, time, tools, technical level, or language?
8. What output format do you want from the final LLM response?

### User Answers

1. I am still deciding the niche, but I want to focus on small businesses with simple operations and visible manual work.
2. I want to solve pains related to saving time, saving money, making more money, and reducing repetitive work.
3. I can use ChatGPT, prompts, basic research, GitHub, spreadsheets, simple no-code/low-code tools, and documentation.
4. I want to start with a simple service that can later become a done-for-you automation package.
5. I want to begin with Brazilian/local businesses, but keep the structure useful for international expansion.
6. A successful first version would give me a clear niche shortlist, automation ideas, first offer, and outreach plan.
7. Constraints: low budget, fast execution, simple tools, no complex SaaS development, privacy-conscious, and beginner-friendly implementation.
8. I want a structured execution plan with tables, ranked opportunities, offer ideas, validation steps, and next actions.

## Generated Prompt

```markdown
You are a business automation strategist specialized in AI-assisted services for small businesses.

Your task is to help me transform a vague idea — selling AI automations to small businesses — into a clear, practical, and validated first offer.

Use first principles thinking to break the problem down into fundamentals:

- What small businesses actually need;
- Which repetitive tasks create visible pain;
- Which automations are simple enough to deliver quickly;
- Which offers can save time, save money, make money, or reduce manual work;
- Which niche should be tested first.

Context:

I want to sell AI automation services to small businesses, but I do not know where to start.
I am still deciding the niche.
I want to focus on businesses with simple operations and visible manual/repetitive work.
I can use ChatGPT, prompts, basic research, GitHub, spreadsheets, simple no-code/low-code tools, and documentation.
I want to begin with Brazilian/local businesses, but the structure should also be useful for international expansion later.
My constraints are: low budget, fast execution, simple tools, no complex SaaS development, privacy-conscious execution, and beginner-friendly implementation.

Important value lenses:

1. Solve pain;
2. Save money;
3. Make money;
4. Save time.

Please produce a practical business execution plan with the following structure:

1. Clarify the core opportunity
2. List 10 small-business niches that may benefit from simple AI automations
3. Rank the niches by pain intensity, ease of access, speed of delivery, ROI potential, and simplicity
4. Suggest 3 automation ideas for the top 3 niches
5. Define one MVP offer that can be sold quickly
6. Explain what should be done manually first before automating
7. Create a simple validation plan for the first 7 days
8. Create a basic outreach message in Portuguese and English
9. Identify risks, weak assumptions, and possible objections using a Devil's Advocate section
10. End with a 3-step action plan I can execute today

Constraints:

- Do not suggest building a complex SaaS.
- Prioritize service-based automation, prompt workflows, spreadsheets, simple AI tools, and low-code/no-code options.
- Keep the plan practical for someone starting alone.
- Prefer low-cost and fast-to-test options.
- Make the output clear, structured, and action-oriented.
- Use tables where useful.
```

## GPT Test 01 — Clarity Test

### Input

The generated prompt was given to GPT as-is.

### Expected Behavior

GPT should understand the objective clearly and produce a structured business automation plan instead of giving generic motivational advice.

### Observed Result

GPT produced a clear plan with niche selection, automation opportunities, MVP offer ideas, validation steps, outreach messages, risks, and a short action plan.

### Evaluation

- Strengths: The prompt gives a precise role, context, constraints, and output structure.
- Weaknesses: The prompt could be improved by asking for estimated implementation difficulty per automation.
- Fixes needed: Add a scoring column for technical difficulty in future versions.

### Status

Pass

## GPT Test 02 — Constraint Test

### Input

The generated prompt was tested while checking whether GPT respected these constraints:

- no complex SaaS;
- low budget;
- simple tools;
- beginner-friendly;
- service-first execution;
- local/Brazilian starting point with international potential.

### Expected Behavior

GPT should avoid overengineering and keep the strategy focused on practical, low-cost, service-based automation offers.

### Observed Result

GPT mostly respected the constraints and prioritized practical service ideas, such as lead follow-up automation, WhatsApp response workflows, appointment reminders, customer intake forms, spreadsheet organization, and prompt-based admin workflows.

### Evaluation

- Strengths: The constraints strongly reduced vague or overbuilt recommendations.
- Weaknesses: GPT may still suggest tools that require setup effort if not explicitly limited.
- Fixes needed: Add "avoid paid tools unless there is a free tier" if the user wants maximum cost control.

### Status

Pass

## GPT Test 03 — Output Quality Test

### Input

Comparison between the raw user input and the generated UPE prompt.

Raw input:

```text
Quero vender automações com IA para pequenos negócios, mas não sei por onde começar.
```

Generated UPE prompt:

A structured business automation strategy prompt with role, context, value lenses, constraints, ranked niche analysis, MVP offer, validation plan, outreach messages, Devil's Advocate section, and same-day action plan.

### Expected Behavior

The UPE-generated prompt should produce a significantly better GPT response than the raw user input.

### Observed Result

The generated prompt gives GPT enough context to produce a practical execution plan, while the raw input would likely produce a broad, generic answer.

### Evaluation

- Strengths: The UPE turns uncertainty into a structured decision-making and execution framework.
- Weaknesses: The case would be even stronger with a real-world business selected and tested.
- Fixes needed: Future case studies can include a real niche, such as barbershops, clinics, gyms, small retailers, or real estate agents.

### Status

Pass

## Final Notes

This case study shows that the UPE is useful for converting a vague business ambition into a clear prompt that can guide market research, offer design, validation, and first execution steps.

It demonstrates three core strengths of the UPE:

1. It extracts context before execution.
2. It transforms broad goals into structured prompts.
3. It improves the quality of GPT output by adding role, constraints, format, critical thinking, and business logic.

## Portfolio Value

This case can be used to show prompt engineering capability in a business context, especially for AI automation services, small-business consulting, and offer validation workflows.
