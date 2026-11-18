# Engagemii AI Visibility for Claude

See how visible any company is to AI answer engines like ChatGPT, Claude, Perplexity and Gemini, right inside Claude.

This plugin connects Claude to the [Engagemii](https://engagemii.com) MCP server. Engagemii scores how well AI engines can find, read and name a company, across an index of more than 81 million companies.

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
| `dataset_sample` | 15 live rows with the 113 columns of a purchased data file (add-on cells empty) |
| `search_companies` | Searches the dataset by industry, state and score range (needs a data API key) |
| `data_signup` | Creates a free data account, or signs in to one, with just an email address |
| `data_records` | Pulls full company records, 113 columns, from your purchased quota (needs a data API key) |
| `data_orders` | Lists the data orders on your account, with download links for ready files |
| `kit_download` | Gets the files for a fix kit bought before October 2026 |

The free tools need no account or API key. Searching the dataset and pulling records need a free data account from [engagemii.com/aeo/data](https://engagemii.com/aeo/data), which `data_signup` can create.

Company records cost 10 cents each, 5 cents from 5,000; details at https://engagemii.com/aeo/data.

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
