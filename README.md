# Engagemii AI Visibility for Claude

See how visible any company is to AI answer engines like ChatGPT, Claude, Perplexity and Gemini, right inside Claude.

This plugin connects Claude to the [Engagemii](https://engagemii.com) MCP server. Engagemii scores how well AI engines can find, read and cite a company, across an index of about 70 million companies.

## What you can ask

- "What is the AI visibility score for hubspot.com?"
- "Run a live AI visibility audit of my site, example.com."
- "Which brands is ChatGPT recommending for CRM software right now?"
- "Why doesn't AI recommend my bakery, and what should I fix first?"
- "Send me the free fix kit for my site."

## Tools

| Tool | What it does |
|---|---|
| `aeo_score` | A company's stored AI visibility score (0 to 10) with its breakdown |
| `aeo_audit` | A live audit of a site as it is right now (5 per hour) |
| `brand_profile` | A company's public profile, category and AI crawler reads |
| `citation_watch` | Which brands ChatGPT is recommending right now |
| `ai_readstream` | Which AI engines are reading company pages right now |
| `free_kit` | Requests the free fix kit for your own site, emailed after confirmation |
| `connect_tracker` | Sets up free AI crawler monitoring for your own site |
| `dataset_sample` | 15 live rows in the shape of the Engagemii dataset |

The free tools need no account or API key. Searching the full dataset needs a free data account from [engagemii.com/aeo/data](https://engagemii.com/aeo/data).

## Install

In Claude Code:

```
claude mcp add --transport http engagemii https://api.engagemii.com/api/mcp
```

Or install this plugin from the Claude directory.

## Links

- Docs: https://engagemii.com/aeo/mcp
- Support: https://engagemii.com/contact
- Privacy: https://engagemii.com/privacy
- Terms: https://engagemii.com/terms

## License

MIT
