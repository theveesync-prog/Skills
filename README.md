# vee-ai-skills

Reusable skills for Claude Code, kept in one place and installable into any project.

## Skills

| Name | Use when | Invoke |
|------|----------|--------|
| `karpathy` | Writing, reviewing or refactoring code: keeps changes simple, surgical and verifiable | `/karpathy` |
| `taste` | Main anti-slop frontend skill: landing pages, portfolios, redesigns | `/taste` |
| `taste-v1` | Original v1 of taste (exact old behavior) | `/taste-v1` |
| `taste-gpt` | GSAP motion, bento grids, AIDA page structure | `/taste-gpt` |
| `soft` | High-end agency look: fonts, spacing, shadows, motion | `/soft` |
| `minimalist` | Clean editorial UI, warm monochrome | `/minimalist` |
| `brutalist` | Raw industrial / terminal-style UI | `/brutalist` |
| `redesign` | Upgrade an existing site without breaking it | `/redesign` |
| `full-output` | Stops truncation and placeholder code | `/full-output` |
| `image-to-code` | Generate design images first, then build the site to match | `/image-to-code` |
| `imagegen-web` | Image-generation direction for website sections | `/imagegen-web` |
| `imagegen-mobile` | Image-generation direction for mobile app screens | `/imagegen-mobile` |
| `brandkit` | Brand-guidelines boards and logo systems | `/brandkit` |
| `stitch` | Generates DESIGN.md for Google Stitch | `/stitch` |
| `emil-design-eng` | Emil Kowalski's UI polish and design-engineering philosophy (main one) | `/emil-design-eng` |
| `animate` | Build a web animation from scratch, decisions in the right order | `/animate` |
| `animate-expo` | Animations, gestures and haptics in React Native / Expo | `/animate-expo` |
| `review-animations` | Strict review of motion code (manual only) | `/review-animations` |
| `improve-animations` | Audit a codebase's motion and write fix plans | `/improve-animations` |
| `find-animation-opportunities` | Find places that should animate | `/find-animation-opportunities` |
| `animation-vocabulary` | Turn "the bouncy thing" into the exact term | `/animation-vocabulary` |
| `apple-design` | Apple-style fluid, physical interfaces for the web | `/apple-design` |
| `mobile-native` | Make a web app feel native on a phone | `/mobile-native` |
| `prototype` | Build several versions of a UI behind a live picker (manual only) | `/prototype` |
| `pick-ui-library` | Pick a frontend library for a task (manual only) | `/pick-ui-library` |
| `ask-sonner` | Sonner toast library guide | `/ask-sonner` |
| `write-swift` | Modern Swift, concurrency and performance | `/write-swift` |

## Install in another project

```
/plugin marketplace add theveesync-prog/Skills
/plugin install vee-ai-skills@vee-ai-skills
```

## Adding a skill

Create `skills/<name>/SKILL.md` with `name` and `description` frontmatter (the description says *when* to use it), then list it in `.claude-plugin/plugin.json`.

## Credits

- `taste` … `stitch` (13 design skills): adapted from [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) (MIT, license in `licenses/`). Renamed for short slash commands.
- Emil Kowalski's 13 skills (`emil-design-eng` … `write-swift`): from [emilkowalski/skills](https://github.com/emilkowalski/skills) (MIT, license in `licenses/`), names unchanged.
- `karpathy`: adapted from [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) (MIT).
