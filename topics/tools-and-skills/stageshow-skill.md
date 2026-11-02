---
title: "Stageshow: faux UI skill"
author: "Benji Taylor"
source: "benji.org and GitHub"
link: "https://benji.org/stageshow"
published: 2026-10-31
date_added: 2026-11-02
type: tool
tags: [ai-skills, motion, design-engineering, marketing-visuals]
---

# Stageshow: faux UI skill

## What it is

A free AI agent skill by Benji Taylor that helps coding agents make "faux UI": simplified product illustrations and animated demos for marketing, like hero animations, feature cards, cursor demos and bento grids. It's built in React, and it includes guidance on composition and motion, a kit of parts, dozens of good examples, and scripts that film the result so the agent can check its own work frame by frame.

Install: `npx skills add benjitaylor/skills --skill stageshow` (code at [benjitaylor/skills](https://github.com/benjitaylor/skills))

## Key ideas

- **The one rule:** "It reads as a real product, simplified to what the viewer needs, framed with intent, and every motion has a cause"
- **How agents get faux UI wrong:**
  - **Too much:** real words in every cell, packed tight
  - **Too little:** a wireframe that doesn't read as a product
  - **Boxed:** the whole window shrunk into a card, like a pasted screenshot
  - **Flat:** nothing stands out
- **Real words only where the story is.** Everything else becomes placeholder lines
- **Crop with intent.** Let the window run off the edge, and slide in only the one card the story needs
- **A cursor gives each change a cause.** Loops should end exactly where they began, with no visible seam
- **Seven step workflow,** mostly before any code: medium, look, story (three to five beats), closest example, screen, choreography, then rehearse by filming it
- **Film it to check it.** Screenshots miss motion bugs, like a one-frame jump. The skill makes a contact sheet of frames and flags problems
- **Uses your design tokens,** so demos match your real product's colours, fonts and radii
- **Still needs a few rounds of feedback,** but the first pass is a big step up

## When I'd use it

Making product demos or illustrations for a landing page, launch or docs, with an AI agent doing the build.

## Related

- [Transitions.dev](transitions-dev.md)
- [Jakub Krehel's /state-machine skill](jakub-krehel-state-machine-skill.md)
- [Karl Koch's design engineering skills](karl-koch-design-engineering-skills.md)
- [Vibrant Design](../craft/vibrant-design.md)
