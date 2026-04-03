# IRAF: Iterative Refinement Agentic Framework

**A Git-native, zero-cost architecture for autonomous, self-improving AI systems.**

This repository is a living demonstration of the **Iterative Refinement Agentic Framework (IRAF)** — agents that autonomously plan, delegate, execute, self-evaluate, and rewrite their own blueprint files inside a standard Git repository.

[![Netlify Status](https://api.netlify.com/api/v1/badges/f057ab39-98e6-4431-9c9e-17d9b5aae896/deploy-status)](https://app.netlify.com/projects/iraf-demo/deploys)

**Live Demo:** https://iraf-demo.netlify.app

**Watch the full bootstrap run (6 min raw video):**  
[![Watch the video](https://img.youtube.com/vi/h0OIUTcCtGM/maxresdefault.jpg)](https://www.youtube.com/watch?v=h0OIUTcCtGM)

---

### How It Works
1. A single bootstrap prompt activates the agents in your AI IDE.
2. Agents read the three blueprint files (`agents.md`, `skills.md`, `clauses.md`).
3. They expand and iteratively improve the landing page (`index.html`), using `hero.jpg` and the Mermaid recursion diagram.
4. An independent Evaluator scores the result against strict rules in `clauses.md`.
5. If the score is below 90, the system refines the blueprints and the page — creating a true closed recursion loop.
6. Every change is automatically committed to Git with a standardized message.

The entire system state lives in Git, making evolution transparent, auditable, and reversible.

---

### Prerequisites
To get the best experience:

1. Use an AI-native IDE with strong Git integration (recommended: Windsurf, Cursor, or Claude Code).
2. Select a capable model (Claude Sonnet 4.6 or better recommended).
3. Clone the repository locally and open it as a folder/project in your IDE.
4. Ensure your IDE has permission to read/write files and run Git commands (commit & push to the `master` branch).
5. Place `hero.jpg` in the repository root (required for the landing page).
6. Be prepared to review and approve occasional permission prompts for file edits and Git operations (standard safety behavior in AI coding tools).

---

### Expected Outcome
After running the bootstrap prompt (maximum 5 iterations):

- The landing page transforms into a polished, modern design featuring the hero image, a rendered Mermaid recursion diagram, clear explanatory sections, and a live score footer.
- Git history contains clean commits in the exact format: `[IRAF Iteration X] Score: Y/100 | Refinement: …`
- The Evolution Log in this README is updated automatically.
- Netlify auto-deploys the improved page.
- Final Evaluator score reaches ≥ 90 (or as high as possible within the iteration limit).

---

### Quick Start (2–5 minutes)
1. Add `hero.jpg` to the repository root if not already present.
2. Open this repository in your AI IDE.
3. Copy and paste the **Bootstrap Prompt** below exactly once.

**Bootstrap Prompt**
You are the IRAF Architect. Your mission is to initialize and demonstrate the Iterative Refinement Agentic Framework (IRAF) in this repository.
Step 1: Read agents.md, skills.md, and clauses.md completely.
Step 2: Expand index.html into a polished, modern landing page using Tailwind CDN, the hero.jpg image in the root, and the Mermaid diagram from skills.md.
Step 3: Ensure ALL changes to index.html stay strictly within the  and  comment markers.
Step 4: Have the Evaluator score the page against clauses.md.
Step 5: Commit all changes to the 'master' branch using the EXACT format:
[IRAF Iteration X] Score: Y/100 | Refinement: [one-sentence description]
Goal: Reach a score of >= 90 within maximum 5 iterations. If below 90, refine blueprints and continue.
Begin now.


---

### Evolution Log
*(Automatically updated by the Evaluator after each iteration)*

- Iteration 0 – Initial bootstrap (score: N/A)
- Iteration 1 – Score: 89/100 | Full landing page with hero image, trust narrative, Mermaid IRAF loop diagram, feature grid, CTA, and footer with UTC timestamp. Missing: footer timestamp was initially absent; trust message could be strengthened with scoring weight details.
- Iteration 2 – Score: 92/100 | Added scoring transparency section (40/40/20 weights), live UTC timestamp in footer via JS, updated iteration/score values. Loop converged — passed minimum threshold.

**Full commit history:** https://github.com/otonielrojas/iraf-demo/commits/master

---

### Troubleshooting
- IDE asks for permission → Approve file edits and Git commits.
- Git push fails → Run `git push` manually.
- Score stays low after 5 iterations → Reply to the model: “Trigger next iteration as Architect”.
- Hero image not showing → Verify the file is named exactly `hero.jpg` and committed.
- Model appears stuck → Reply: “Continue with the IRAF bootstrap rules from clauses.md”.

---

### Contributing
Fork the repository, run the bootstrap in your own domain, and share your adaptations. The framework is intentionally simple and designed to be extended for software engineering, scientific research, content systems, or any other field.

The future of AI systems isn’t just written — it is iteratively refined inside your next Git repository.

**Ready to see recursion in action?** Paste the Bootstrap Prompt above.