# Marketplace AI Agents

This repository is a **practical starting point for people who want to begin building AI agents** — especially for complex products like marketplaces.

It is intentionally opinionated and role-based.

Instead of treating AI as a single chatbot, this repo shows how to design **AI agents as virtual team members** with:
- clear responsibilities
- decision logic
- incentives and trade-offs
- defined inputs and outputs

The goal is not experimentation for its own sake, but **usable agents you can rely on in real product work**.

---

## Who This Is For

This repo is useful if you are:
- a Product Manager
- a Founder or Operator
- working on a marketplace, SaaS, or platform business
- curious about AI agents but unsure how to start

You do **not** need to be an ML engineer.
You do **not** need a complex multi-agent framework.

You only need:
- a clear business problem
- a willingness to think in roles, not prompts

---

## Core Idea

Most people start with:
> “What prompt should I write?”

This repo starts with:
> **“Who am I hiring, and what decisions should they be trusted to make?”**

Each agent is designed like a job description:
- mission
- scope
- decision authority
- constraints
- collaboration with other agents

Once the role is clear, tools become interchangeable.

---

## Repository Structure

```
/
├── agents/
│   ├── ceo-marketplace.md
│   ├── marketplace-health-analyst.md
│   ├── seller-success-manager.md
│   ├── auction-listing-optimizer.md
│   ├── trust-and-safety-analyst.md
│   ├── dispute-mediation-specialist.md
│   └── marketplace-tags-generator.md
│
├── templates/
│   └── AGENT-job-description-writer.md
│
├── examples/
│   └── create-new-agent-example.md
│
└── README.md
```

---

## The Most Important File

### `AGENT-job-description-writer.md`

This is the heart of the repository.

It is a **reusable template** for creating new AI agents, regardless of:
- framework
- model (Opus, Sonnet, etc.)
- tooling (Kiro, Cursor, Claude Code)

You are encouraged to:
- copy it
- modify it
- adapt it to your own product and culture

Think of it as your internal **AI hiring framework**.

---

## How to Create a New Agent (Step by Step)

### Step 1: Define the Role (in ChatGPT)

Start outside of coding tools.

Ask something like:

> “Design the role, mindset, and responsibilities of a PR Manager for a marketplace.
> Context: [your niche, audience, business model, constraints].”

Focus on:
- what decisions this agent should make
- what success looks like
- what it should *not* do

---

### Step 2: Convert the Role Into an Agent

Take the result and pass it into your coding agent (Kiro / Cursor / Claude Code) with a prompt like:

> “Using `AGENT-job-description-writer.md`, create a new AI agent based on the following inputs: [paste role description].”

This turns abstract intent into a **structured, reusable agent**.

---

### Step 3: Iterate

Agents are not static.

You should:
- refine scope
- tighten decision boundaries
- clarify inputs and outputs

Treat them the same way you would treat a new hire during onboarding.

---

## The Agents in This Repo

### Strategic Level

**1. CEO Marketplace (Opus)**  
The strategic brain of the system.
- GMV, monetization, liquidity
- competitive trade-offs
- long-term platform thinking

**2. Marketplace Health Analyst (Sonnet)**  
The diagnostic layer.
- supply–demand balance
- category health
- early warning signals

---

### Supply-Side Operations

**3. Seller Success Manager (Sonnet)**  
Seller growth and retention.
- onboarding
- segmentation
- GMV optimization

**4. Auction Listing Optimizer (Sonnet)**  
Conversion-focused execution.
- titles, descriptions, photos
- pricing and bidding strategy
- performance benchmarking

---

### Trust & Safety

**5. Trust & Safety Analyst (Sonnet)**  
Platform protection.
- fraud detection logic
- risk scoring
- enforceable policies

**6. Dispute Mediation Specialist (Sonnet)**  
Neutral conflict resolution.
- evidence-based decisions
- fair outcomes
- trust preservation

---

### Growth & Discovery

**7. Marketplace Tags Generator (Opus)**  
Search and discovery.
- tags and filters
- category hierarchies
- SEO-driven discovery

---

## How the Agents Work Together

Agents are designed to collaborate, not operate in isolation.

- Strategy flows from **CEO Marketplace**
- Health signals come from **Marketplace Health Analyst**
- Seller insights inform **Listing Optimizer**
- Risk patterns connect **Trust & Safety** and **Dispute Mediation**
- Category data improves **Tags & Discovery**

Think of this as a **small operating team**, not a swarm of bots.

---

## Tools

This repo is tool-agnostic.

You can use:
- Kiro
- Cursor
- Claude Code
- or any modern coding-agent environment

If you can pass structured instructions to a model, this approach works.

---

## Philosophy

This repository is based on one simple belief:

> AI becomes useful when you stop asking it for answers and start trusting it with decisions.

You are not building assistants.
You are building **judgment-bearing agents**.

---

## How to Use This Repo

- Clone it
- Start with one agent
- Adapt it to your product
- Iterate slowly

You don’t need seven agents on day one.
One well-designed agent is enough to change how you work.

---

If this helps you get started with AI agents — that was the goal of this repo.

