# ADLOGOS Creative Studio

ADLOGOS is a responsive, browser-based creative workspace for small businesses.

## Live site

https://dterminette9-wq.github.io/adlogos/

## Current workspace tools

Open **Open Creative Workspace** from the homepage or visit `studio.html`.

- **Ad Copy Studio** — generates editable promotional copy, headline options and calls to action.
- **Logo Concept Studio** — creates a simple logo concept and exports it as SVG.
- **Brand Kit Creator** — creates a starter colour palette and brand direction.
- **Social Ad Designer** — creates a square social-ad layout and exports it as SVG.
- **Video Script Studio** — drafts short promotional video scripts.
- **Radio Ad Writer** — drafts voiceover-ready radio commercials.

Drafts can be edited in the browser, copied, downloaded, and saved locally in the same browser.

## Technical notes

- Static HTML, CSS and JavaScript; no build framework required.
- The creative workspace runs in the visitor's browser.
- No account, payment or server connection is currently required.
- The current draft generators use structured templates. **They are not connected to a live AI model API yet.**
- AI text generation, image generation, user accounts, cloud project storage, payments and subscription management require additional backend/provider integrations and credentials. Do not advertise those features as active until they are connected and tested.

## Deployment

GitHub Pages deploys the `main` branch. Changes to `index.html`, `studio.html`, or assets trigger a Pages deployment.
