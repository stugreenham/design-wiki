---
title: "Midjourney: Style Reference"
author: "Midjourney"
source: "Midjourney docs"
link: "https://docs.midjourney.com/hc/en-us/articles/32180011136653-Style-Reference"
date_added: 2026-10-19
type: resource
tags: [ai-image-generation, midjourney]
---

# Midjourney: Style Reference

## What it is

Midjourney's guide to Style References: giving it an image so new images match its overall look (colours, medium, texture, lighting) without copying the objects or people in it.

## Key points

- **Add a reference** by dragging an image into the Style Reference slot, or with `--sref <image URL>` in Discord
- **Keep the text prompt about content, not style.** "Ballpoint pen sketch of a bunny" works. "Copy this style and make a bunny" doesn't
- **Control strength with `--sw`** from 0 to 1000 (default 100)
- **Style codes:** use `--sref <number>` for a style from Midjourney's library, or `--sref random` to discover new ones. Browse and save them in the Style Explorer
- **Mix and weight** several references or codes together
- **Versions matter:** `--sv` picks the style model. Older codes may need `--sv 4` to look the same

## When I'd use it

Keeping a consistent visual style across a set of generated images, like illustrations for a deck or a moodboard.

## Related

- [Brian Lovin: How to level up with AI as a designer](../ai-and-design/brian-lovin-level-up-with-ai.md)
