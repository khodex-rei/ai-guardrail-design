# TokenLens Design System

> Version: 3.0.0
> Last updated: 2026-05-08
> Scope: static marketing and design-system surfaces in `tokenlens-design`

## Product framing

TokenLens is an observability product for teams building with LLM APIs.

Core promise:

> Add TokenLens to your app in minutes and understand token usage, cost, latency, errors, and model behavior without building internal observability from scratch.

## Tone

All touched design surfaces should feel:

- Calm
- Technical
- Practical
- Trustworthy
- Developer-first

Avoid:

- Hype-heavy AI copy
- Fantasy or dreamcore language
- Safety-platform framing as the primary message
- Decorative visual noise

## Visual direction

Use a restrained observability aesthetic:

- Dark neutral base
- Blue/violet technical accents
- Subtle borders and soft panels
- Strong typography hierarchy
- Minimal gradients
- Code blocks that feel familiar to developers
- Dense information without clutter

## Marketing priorities

The marketing pages should quickly explain:

1. What TokenLens is
2. What problems it solves
3. How simple the SDK path is
4. What visibility users get after first integration
5. How pricing scales with usage and team needs

Recommended landing page emphasis:

- Explain TokenLens in a few seconds.
- Show the SDK integration example early.
- Show a dashboard preview with explanation, not decoration.
- Keep primary CTAs concrete: Getting Started, Pricing, Docs.

Recommended pricing page emphasis:

- Explain Free, Pro, and Team clearly.
- Show pricing dimensions such as tracked events, retention, projects, teammates, and alerts or exports.
- Include FAQ and a final CTA.

## IA for this repo

- `index.html` is the repo entrypoint and review hub.
- `landing.html` is the public marketing home concept.
- `pricing.html` is the pricing concept.
- `about.html` is optional trust/context support.
- `styles/design-system.css` is the shared asset for touched marketing pages.

## Implementation rules

- Static HTML/CSS only
- Keep relative links working
- Prefer reusable shared CSS over page-local styling
- Keep copy aligned with TokenLens docs terminology:
  - tokens
  - requests
  - latency
  - errors
  - cost
  - providers
  - models
  - projects
  - first event received

## CTA guidance

Prefer concrete developer actions:

- Start tracking for free
- Create project
- Install SDK
- Read docs

Avoid vague or purely promotional CTAs.

## Content constraints

- No emoji
- No legacy product naming in touched files
- No dreamcore/pastel/kawaii language
- No promises of features that conflict with current docs direction

## Accessibility and review

- Maintain readable contrast
- Preserve semantic headings
- Keep pages lightweight for static browsing
- Favor clarity over decoration
