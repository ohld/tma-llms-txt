# Contributing

Improvements to the TMA developer guide are welcome.

## How to Contribute

1. Fork this repository
2. Create a branch: `git checkout -b improve-auth-section`
3. Edit `llms-full.txt` (the main guide) or `llms.txt` (the index)
4. Commit and push
5. Open a Pull Request with a description of what you changed and why

## Guidelines

- **Keep it concise.** No filler text. Developers (and LLMs) want facts, code, and links.
- **Total size under 30K words.** If a section grows too long, link to external docs instead.
- **Code snippets must work.** Test any code you add. Broken examples waste developer time.
- **English only.** The guide is in English for maximum reach.
- **Link to official docs.** Don't duplicate entire documentation — summarize and link.
- **Test with an LLM.** Feed the modified `llms-full.txt` to Claude Code or ChatGPT and ask it to build a TMA. Verify it produces working code.

## What to Contribute

- Fix outdated SDK versions or API changes
- Add missing patterns (e.g., new Telegram features)
- Improve code examples
- Fix broken links
- Add links to useful resources

## What NOT to Contribute

- Full application code (the guide is text + snippets, not a codebase)
- Marketing language or verbose explanations
- Duplicate information already in official docs
- Non-English content
