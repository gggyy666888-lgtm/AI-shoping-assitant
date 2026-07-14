# Prototype Instructions

Run the local server yourself and open the preview in the browser available to this environment. Do not give the user server-start instructions when you can run it.

Before making substantial visual changes, use the Product Design plugin's `get-context` skill when the visual source is unclear or no longer matches the current goal. When the user gives durable prototype-specific design feedback, preferences, or decisions, record them in `AGENTS.md`.

When implementing from a selected generated mock, treat that image as the source of truth for layout, component anatomy, density, spacing, color, typography, visible content, and hierarchy.

## Project-specific direction

- The product is a fresh-grocery shopping platform, not a prepared-food delivery app.
- Treat `reference/01-home.jpg` through `reference/05-smart-cart.jpg` as the visual source of truth.
- Preserve the fixed flow: user request → AI understanding → dinner plan → raw ingredient selection → smart cart optimization.
- Use a 390px design baseline, support common phone widths, and center the app at a maximum width of 430px on desktop.
- Keep all visible product and robot assets centrally replaceable through `src/config/assets.js`.
- During the first implementation stage, build only the project foundation, routes, tokens, mock data, and shared shell. Do not build the detailed page UI yet.
