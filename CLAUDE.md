# Instructions for Claude

This repo is Stu's design knowledge base. It's mainly for Stu's own reference (opened as an Obsidian vault) and also shared publicly on GitHub. Stu pastes in LinkedIn posts, X threads, links, screenshots or rough notes. Your job is to turn them into clean wiki entries and file them.

Visual inspiration lives in Eagle. This wiki is for ideas and knowledge, so focus on what the thing says, not just how it looks.

## When Stu shares something

1. Work out what it is and which topic folder in `topics/` fits best
2. Create an entry using `templates/entry.md` (articles, posts) or `templates/resource.md` (tools, websites), following `CONTRIBUTING.md`
3. Write the summary and takeaways in your own words. Never paste the full original post
4. No "My take" section. Stu doesn't want one. Only ask questions when something is unclear (topic, author, missing context)
5. Add tags, reusing existing ones listed in `CONTRIBUTING.md`. Add any new tag to that list
6. Link related entries both ways
7. Add the entry to the topic's `README.md` under Articles, Videos, Posts, or Tools and resources (create the heading if missing). Update the root `README.md`: the entry count in the topics table and "Recently added" (newest first, keep 5). The root page stays short; detail lives in topic pages
8. Commit with a message like `Add: <title>`

## Tools and Skills vs everything else

- `topics/tools-and-skills/` holds anything you can install or use: design tools, AI agent skills, spec frameworks, plugins, MCPs, and how-to docs for a tool
- The test: if it plugs into a workflow (an MCP, an API, a plugin, a skill, or code you drop in), it's a tool, even if it's also browsable. Appllama is a tool for this reason
- AI is a section on the Tools and Skills page, not a separate topic. Group the page by kind (Design tools, AI agent skills, Spec frameworks, Image generation). Add new sections as needed
- A post announcing a skill or tool goes in Tools and Skills, because the thing you'd come back for is the tool
- `topics/ai-and-design/` is for the thinking: articles, research, videos and opinions about AI and design
- Inspiration galleries, magazines and reading lists are resources, not tools. File them in the topic they're about (for example visual inspiration goes in Craft)

## Career topic

- Keep Career entries general and impersonal, written for any designer. No personal framing about Stu's own career
- Where it helps, note how an entry is useful from the hiring side too

## Things to check before filing

- Check for duplicates first. If a link is already filed, or is the source behind an existing entry, add to that entry instead of making a new one

- Content from work channels: strip anything confidential, internal, or that names colleagues. If unsure, ask
- Missing author or link: ask rather than guess
- Clean every URL before saving. Remove tracking parts like `?utm_...` and `rcm=...`. LinkedIn's `rcm=` value is tied to Stu's own account
- Never commit API keys, passwords, tokens, `.env` files or private screenshots. This repo is public
- If it doesn't fit any topic well, suggest a new topic rather than forcing it. Likely future topics: Accessibility, Content Design. Motion lives in Craft for now. Suggest one once two or three entries would belong there

## Format rules (Obsidian and GitHub)

- Filenames: `short-title.md`, lowercase, hyphens, no date prefix
- Links: standard Markdown relative links like `[Title](../tools-and-skills/some-note.md)`, never `[[wikilinks]]`, so they work on GitHub too
- Tags: in front matter only, lowercase and hyphenated
- Images: save to `assets/` and embed with a relative link

## Writing style

- Plain, clear English. Short sentences
- Bullets over long paragraphs
- No em or en dashes
- Refer to people by name. Don't assume pronouns
