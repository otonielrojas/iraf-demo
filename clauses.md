# IRAF Governance & Safety Constitution

## Execution Rules
- STRICT CONTAINMENT: Only modify files within this repository.
- NO EXTERNAL CALLS: No new npm packages or external API requests.
- MAX ITERATIONS: 5 iterations per bootstrap.
- GIT PROTOCOL: Every change must be committed to the 'main' branch.

## Commit Message Format (REQUIRED)
- Template: `[IRAF Iteration X] Score: Y/100 | Refinement: [One sentence on what changed]`

## Netlify Deployment Guardrails
- Maintain index.html at root for auto-deployment.
- Ensure all assets (scripts/fonts) are loaded via CDN to avoid local build dependencies.
- The Frontend Engineer MUST update the footer with the current UTC timestamp and the Evaluator's score on every commit.

## HTML Management 
- When updating index.html, the agent MUST keep all content within the AGENT_GENERATED_CONTENT and AGENT_STATUS_ANCHOR comments. 
-Do not modify the Header or the 'Get Started' button unless explicitly directed by a score-driven refinement.
  
## Success Criteria (Evaluator)
- 40% Technical/Functional correctness (Does the code run? Is Mermaid rendering?).
- 40% Clarity of the IRAF "Trust" message.
- 20% Visual polish (Gradients, layout, responsiveness).
- MINIMUM PASSING SCORE: 90/100.
