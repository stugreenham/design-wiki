---
title: "getdesign.md: DESIGN.md files for AI agents"
author: "Brett Cooper"
source: "LinkedIn"
link: "https://www.linkedin.com/posts/uxbybrett_getdesignmd-designmd-collection-for-ai-share-7493646617976229888-MKUO/"
date_added: 2026-10-19
type: post
tags: [design-md, design-tokens, ai-agents, claude]
---

# getdesign.md: DESIGN.md files for AI agents

## Summary

Brett shares [getdesign.md](https://getdesign.md/), a catalogue of 300+ DESIGN.md files based on well known design systems like Airbnb, Google, IBM and Figma. Each file follows Google Labs' open DESIGN.md spec: YAML tokens for colour, type, spacing and radius, plus written notes that explain to an AI agent *why* those values exist. The idea is you never start a system from scratch.

## Key takeaways

- **DESIGN.md is becoming a standard** way to hand a design system to AI tools. Tokens give the values, prose gives the reasoning
- **Visual route:** download a DESIGN.md, give it to Claude Design, and have it build the tokens and components on a canvas. Easier to edit if you're less confident with GitHub, but uses more tokens
- **Technical route:** use the getdesign CLI to add a DESIGN.md to a repo, lint it against Google's spec, then export to a Tailwind theme or a DTCG `tokens.json`
- **Tell the agent to read DESIGN.md first** and structure the code as primitive tokens, then semantic tokens, then component tokens
- Both routes end up in the same repo, since Claude Design can hand off to Claude Code

## Also see

- [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) by VoltAgent: the open source GitHub collection behind getdesign.md. Each file is extracted from a real website (Claude, Cursor, Vercel, Raycast and many more). It pitches DESIGN.md as the design partner to `AGENTS.md`: one tells agents how to build, the other how it should look and feel

## Related

- [specs.md: spec-driven AI development](../tools-and-skills/specs-md.md)
- [Peter Yang's /human-review skill](../tools-and-skills/peter-yang-human-review-skill.md)
- [Spec-driven design (Futurice)](../ai-and-design/futurice-spec-driven-design.md)
- [Graphical](../tools-and-skills/graphical.md)
