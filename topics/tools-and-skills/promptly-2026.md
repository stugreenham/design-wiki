---
title: "Promptly 2026"
author: "Moby and Chelsea"
source: "GitHub"
link: "https://github.com/mubarakmarafa/Promptly-2026"
date_added: 2026-11-02
type: tool
tags: [ai-skills, claude]
---

# Promptly 2026

## What it is

"Spotify Wrapped for your prompting." A free AI agent skill by Moby and Chelsea. Run `/promptly` in Claude Code or Codex, and your agent reads your local chat history from Claude Code, Codex and Cursor, works out your "prompting personality", and builds a shareable, tappable story.

The story includes:
- Your archetype, plus three "tells" your writing gives away
- Stats drawn as charts: when you prompt, how long your prompts are, your catchphrases, your manners, your top projects
- A few of your own prompts marked up like a design crit, with a verdict
- How your prompting has changed over time

Install: `npx skills add mubarakmarafa/Promptly-2026 -g`

## Privacy notes

- It reads your history on your own machine, and redacts secrets, emails and file paths first
- Only stats and a sample of redacted prompts go to your agent's model
- It hides project names on shared images, and only publishes online if you ask

## When I'd use it

A fun look back at how I work with AI agents, and a nudge to prompt better. It's also a nice example of a well-designed skill that renders a polished HTML story.

## Related

- [Peter Yang's /human-review skill](peter-yang-human-review-skill.md)
- [Stageshow: faux UI skill](stageshow-skill.md)
