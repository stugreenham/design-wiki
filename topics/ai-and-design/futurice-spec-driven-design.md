---
title: "Spec-driven design: Designing for agentic software development"
author: "Tuomas Härkönen (Futurice)"
source: "Futurice blog"
link: "https://futurice.com/blog/spec-driven-design"
date_added: 2026-10-19
type: article
tags: [spec-driven-development, ai-agents, knowledge-base, design-handoff, atomic-research]
---

# Spec-driven design: Designing for agentic software development

## Summary

Tuomas argues that design is slow because of two "leaks": knowledge reaches designers too slowly, and design intent gets lost on its way to production. The fix is "spec-driven design": a shared product knowledge base that AI agents can query, plus one living spec per feature that designers write into from discovery all the way to handover. In this model, design's value isn't producing screens, which AI makes cheap. It's supplying high quality intent, which only comes from time with real users.

## Key takeaways

- **Two kinds of coordination work.** "Retrieval" (hunting for context, re-explaining decisions) is waste caused by badly stored knowledge. "Co-creation" (iterating, debating trade-offs, talking to users) is the real job
- **Mockups aren't specs.** They show the happy path and hide edge cases, errors and rules. Walkthrough decks and redlines are read once and dead within a sprint
- **Build a Product Knowledge Base** in plain Markdown in the code repo: agent instructions, product vision, decision logs, research insights, standards (design system, accessibility) and feature specs
- **Store research as atomic insights.** Small, tagged findings linked to their source, so research keeps paying off long after the study
- **The spec is born in problem definition.** For design, "the open questions are the spec". Prototypes answer them, and rejected directions get written down too
- **Agents check the craft, humans judge the meaning.** Spacing, states and design system use can be checked automatically against standards, freeing designers for usability testing and decisions
- **Handover becomes a property of the spec,** not a meeting
- **Start small:** a local knowledge base and one spec for your next feature

## Related

- [OpenSpec](../tools-and-skills/openspec.md)
- [specs.md: spec-driven AI development](../tools-and-skills/specs-md.md)
- [getdesign.md: DESIGN.md files for AI agents](../design-systems/getdesign-md-design-files-for-ai.md)
- [NN/g: AI for UX Work Study Guide](nng-ai-for-ux-work-study-guide.md)
