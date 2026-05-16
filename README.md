# Design Style Intelligence

[![skills.sh](https://skills.sh/b/phalla-doll/design-style-intelligence)](https://skills.sh/phalla-doll/design-style-intelligence)

A comprehensive AI agent skill that transforms vague product ideas into precise, implementation-ready visual design systems using 50 established design styles.

## Install

```bash
npx skills add phalla-doll/design-style-intelligence
```

Install to a specific agent:

```bash
# Claude Code
npx skills add phalla-doll/design-style-intelligence -a claude-code

# Cursor
npx skills add phalla-doll/design-style-intelligence -a cursor

# Cline / Windsurf / Codex / Gemini CLI / etc.
npx skills add phalla-doll/design-style-intelligence -a cline
npx skills add phalla-doll/design-style-intelligence -a windsurf
npx skills add phalla-doll/design-style-intelligence -a codex
npx skills add phalla-doll/design-style-intelligence -a gemini-cli
```

Install globally (available across all projects):

```bash
npx skills add phalla-doll/design-style-intelligence -g
```

## What It Does

When activated, the skill turns your AI agent into a senior UI design director that can:

- **Detect emotional tone** from a product description and infer target audience
- **Recommend 1–3 fitting design styles** with full reasoning (why it fits, not just what it is)
- **Provide implementation-ready design guidance** — typography, color, layout, motion, UI components
- **Generate AI prompts** for Midjourney, v0, Lovable, Cursor, and Figma AI
- **Output frontend engineering notes** — Tailwind, CSS techniques, accessibility, performance

## What's Included

### 50 Design Styles

Full catalog spanning both digital/UI and visual arts styles:

| Category | Styles |
|---|---|
| **Modern Digital** | Glassmorphism, Neo-Brutalism, Bento Box, Neo Frutiger Aero, Aurora |
| **Minimal & Clean** | Minimalism, Japandi, Swiss Design, Wabi Sabi, Bauhaus |
| **Luxury & Editorial** | Editorial Luxury, Luxury Typography, Art Deco, Neoclassical, Baroque |
| **Retro & Nostalgic** | Y2K, Vaporwave, Synthwave, Pixel Art, Mid-Century, Memphis |
| **Dark & Edgy** | Cyberpunk, Cybercore, Brutalism, Gothic, Dark Magic Academia |
| **Soft & Organic** | Ethereal, Art Nouveau, Bohemian, Shabby Chic, Coquette |
| **Playful & Expressive** | Kawaii, Pop Art, Kitsch, Graffiti, Anthropomorphic |
| **Functional & Structural** | Utilitarian, Modular Typography, Brutalism, Bauhaus |

Each style includes core elements, mood, best use cases, and digital adaptation notes. Digitally-relevant styles get deep-dive treatment with emotional psychology, UI patterns, motion language, and engineering specifics.

### Fontshare Typography System

All font recommendations use **only** fonts from [fontshare.com](https://www.fontshare.com/) — free, high-quality typefaces. Includes proven pairing tables for 10+ style directions (e.g., Cabinet Grotesk + General Sans for Neo-Brutalism, Gambetta + Switzer for Editorial Luxury).

### Style Compatibility Matrix

Know which styles mix well and which clash:

- **Strong**: Swiss + Minimalism, Glassmorphism + Aurora, Cyberpunk + Y2K
- **Medium**: Brutalism + Swiss, Editorial + Minimalism
- **Dangerous**: Japandi + Cyberpunk, Brutalism + Luxury Editorial (use intentionally)

### Style Decision Rules

Map product personality to style automatically:

| Product Personality | Recommended Style |
|---|---|
| Calm + Premium | Japandi + Minimalism |
| Futuristic + Premium | Glassmorphism + Aurora |
| Experimental + Youthful | Neo-Brutalism + Y2K |
| Corporate + Trustworthy | Swiss Design + Minimalism |
| Luxury + Artistic | Editorial Luxury |

### Accessibility & Engineering

Every recommendation includes accessibility checks (contrast, motion, font sizing) and frontend engineering notes (Tailwind patterns, `backdrop-filter`, fluid typography with `clamp()`, `prefers-reduced-motion`, font loading optimization, design tokens).

## Usage Examples

Once installed, just describe your product to your AI agent:

> "I'm building a meditation app for busy professionals. It should feel calm but premium, like a spa meets a fintech dashboard."

> "Design a portfolio site for an indie game studio. Bold, rebellious, Gen Z energy."

> "Create a visual direction for a luxury perfume brand. Editorial, cinematic, fashion-forward."

The skill will return a structured design system with style recommendations, typography pairings, color palettes, UI component behavior, motion language, AI prompts, and engineering notes.

## Supported Agents

Works with any agent that supports the [Agent Skills specification](https://agentskills.io):

Claude Code, Cursor, Windsurf, Codex, Cline, OpenCode, Gemini CLI, Roo Code, GitHub Copilot, AMP, and [40+ more](https://skills.sh).

## Source Material

- [`50-design-styles.md`](50-design-styles.md) — Complete catalog of all 50 design styles with descriptions, core elements, and mood
- [`CONTENT.md`](CONTENT.md) — Design style intelligence system with response structure, typography, decision rules, and engineering notes

## License

MIT
