# How entries are written and filed

## Works in Obsidian and GitHub

This repo is set up to open as an Obsidian vault and still read well on GitHub.

- Open the repo folder in Obsidian with "Open folder as vault"
- In Settings, Files and links: turn **off** "Use [[Wikilinks]]" and set "New link format" to **Relative path to file**. This keeps links working on GitHub too
- In Settings, Core plugins: turn on **Templates** and set the template folder to `templates`
- Tags live in the front matter, so they show up in Obsidian's tag pane and properties

## File naming

- One entry per file, in the topic folder that fits best
- Name: `short-title.md`, lowercase with hyphens. The date lives in the front matter, not the filename, so notes read cleanly in Obsidian
- Example: `topics/ai-and-design/ai-prototyping-replaces-wireframes.md`
- If an entry fits two topics, pick the main one and use tags for the rest
- Images go in [`assets/`](assets)

## How pages link together

- `README.md` is the home page. It lists the topics and the five newest entries, nothing more
- Each topic folder has its own `README.md` that lists every entry in it, grouped into **Articles**, **Videos**, **Posts** and **Tools and resources** (only the headings that have entries)
- Each topic page links back to home, and entries link to related entries

## Two kinds of entry

- **Full entry** for articles, reports, posts, threads, videos and talks. Use [`templates/entry.md`](templates/entry.md)
- **Resource card** for tools, websites, galleries and podcasts. Use [`templates/resource.md`](templates/resource.md). Just "What it is" and "When I'd use it"

A full entry has:

- **Front matter**: title, author, source, link, published date (if known), date added, type, tags
- **Summary**: two or three sentences, in my own words
- **Key takeaways**: three to five bullets
- **Related**: links to other entries in this wiki

## Types

`article` · `post` · `thread` · `tool` · `video` · `podcast` · `resource` · `talk` · `report`

## Ground rules

- **Summarise, don't copy.** Write in my own words and link to the original. Short quotes are fine, whole posts are not.
- **Always credit.** Name the author and link to the source.
- **Public means public.** Nothing from internal work channels that is confidential, names colleagues, or reveals company information. Rewrite the idea in general terms or leave it out.

## Tags

Keep tags lowercase and hyphenated. Reuse existing tags before adding new ones.

Current tags: `ai-agents` `ai-chatbots` `ai-image-generation` `ai-skills` `ai-workflows` `ai-output-review` `app-patterns` `atomic-research` `career-growth` `claude` `component-states` `conversational-ui` `decision-making` `design-engineering` `design-handoff` `design-leadership` `design-md` `design-principles` `design-tokens` `future-of-design` `hiring` `inspiration` `interaction-design` `interviews` `knowledge-base` `learning-resources` `midjourney` `motion` `mobile` `newsletters` `nngroup` `portfolio-sites` `podcasts` `portfolios` `prototyping` `review-workflow` `spec-driven-development` `usability-research` `visual-craft`

## Inbox

Not sure where something goes, or no time to write it up? Paste the link and a note into a file in `inbox/`. It gets processed into a proper entry later and then removed from the inbox.
