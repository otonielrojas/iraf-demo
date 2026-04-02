# IRAF Skills Library

## Skill: Modern Tailwind Landing Page (CDN)
- Implementation: Use <script src="https://cdn.tailwindcss.com"></script>.
- Design: Dark mode (zinc-950), purple/cyan gradients, responsive padding.
- Structure: Header, Hero, Mermaid Diagram, Feature Grid, Live Score Footer.

## Skill: Mermaid.js Visualization
- Initialization: Include the following in index.html before </body>:
  <script type="module">
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
    mermaid.initialize({ startOnLoad: true, theme: 'dark' });
  </script>
- Usage: Render the IRAF Loop diagram as defined in the README.

## Skill: Git-Native Logging
- Responsibility: Write the commit message using the Evaluator's score.