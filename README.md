# IRAF: The Iterative Refinement Agentic Framework

[![Netlify Status](https://api.netlify.com/api/v1/badges/f057ab39-98e6-4431-9c9e-17d9b5aae896/deploy-status)](https://app.netlify.com/projects/iraf-demo/deploys)

A Git-native, 0-cost architecture for self-improving AI ecosystems. Built for transparency, auditable through every commit.

**Live Demo:** [iraf-demo.netlify.app](https://iraf-demo.netlify.app/)

This repository demonstrates IRAF in action: a minimal set of Markdown blueprints combined with clever meta-prompting that turns any Git repository into a self-sustaining, self-improving AI agent system.

---

### ⚙️ How It Works

1. A **Bootstrap prompt** activates the agents locally (or via CI/CD).
2. The agents read `agents.md`, `skills.md`, and `clauses.md` to understand their bounds.
3. They build and iteratively improve the landing page (`index.html`).
4. An independent **Evaluator** scores the result against strict criteria.
5. If the score is `< 90`, the system refines the blueprints **and** the code, creating a closed recursion loop.

---

### 📈 The Evolution Log

IRAF is a living system. Every iteration represents a self-evaluation and a recursive improvement cycle. 

* **Current Framework Version:** [Agent to update]
* **Latest Evaluator Score:** [Agent to update]/100
* **Full History:** [View the Audit Trail (Commit History)](https://github.com/otonielrojas/iraf-demo/commits/master)

> **Note:** The "Architect" agent is strictly governed by `clauses.md`. If the score drops, the agent must refine the blueprints before the next deployment.

---

### 🚀 Try It Yourself

Open this repository in your preferred AI-native IDE (like Cursor or Claude Code) and paste the following Bootstrap Prompt into the agent chat:

```text
Act as the IRAF Architect. Your mission is to initialize the Infinite Recursion Agentic Framework (IRAF) in this repository.

Step 1: Read agents.md, skills.md, and clauses.md to understand your roles, capabilities, and strict governance rules.
Step 2: Coordinate with the Frontend Engineer to build the initial index.html using the Tailwind CDN skill.
Step 3: Coordinate with the Copywriter to ensure the page accurately describes IRAF's vision of overcoming human resistance through Git-native recursion.
Step 4: Have the Evaluator score the page against the criteria in clauses.md.
Step 5: CRITICAL: Commit all changes to the 'master' branch. The commit message MUST follow this exact format: 
[IRAF Iteration 1] Score: [SCORE]/100 | Refinement: [One sentence description]

Goal: Reach a score of >= 90 within 5 iterations. If the score is below 90, proceed to the next iteration by refining the blueprints and the code.
