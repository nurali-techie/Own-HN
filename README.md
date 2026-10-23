# Own-HN

A personal Hacker News reader for iPhone: one `index.html`, served by GitHub Pages at https://nurali-techie.github.io/Own-HN/.

## Summary breakup

| Section | Words |
|---|---|
| TL;DR | 1 sentence, <= 20 |
| Bullets | 3 x <= 12 |
| Why it matters | 1 sentence, <= 15 |
| HN says | 1 sentence, <= 20, last line, only when comment rules below allow |
| Total | <= 75, or <= 95 with HN says |

## Comments in summaries

- Uses the top 15 top-level comments, in HN's own ranking order.
- HN says appears only with 10+ total comments and 5+ top-level comments.
- If the article can't be read, the whole summary comes from comments, marked as such.
- Too little discussion to summarize shows an error, nothing is saved.

## How stories are listed

- A new edition loads at 7 AM IST: stories posted in the 24 hrs up to 1 AM IST.
- Points and comment counts refresh during the day; the story set stays fixed.
- Sorted by points, highest first; unread stories first, read ones last.
- 100+ to 500+ show tech stories only; non-tech ones are collapsed at the end.
- Stories move between 100+ to 500+ as points grow; read marks go with them.
- AI 20+ holds 20-49 points, AI 50+ holds 50-99, AI 100+ holds 100+; a story moves up as it gains points.
- An AI story has an AI term in its title or link: AI, LLM, GPT, Claude, OpenAI, Anthropic, Gemini, MCP, AI/coding agents, Llama, Qwen, inference, ...
- The same link posted more than once shows once: the post with the most points.
- Each story shows under one button only, by priority: watch, then security, then AI 20+ / 50+ / 100+, then 100+ to 500+.

## Security button

The last button, for security news worth reading every day.

| Rule | Value |
|---|---|
| Points | 20+, from the same daily edition |
| Security story | title has a security term (CVE, RCE, exploit, backdoor, malware, compromised, credential, leak, supply chain, zero-day, prompt injection, ...) or links to a security site (safedep.io, krebsonsecurity, bleepingcomputer, socket.dev, wiz.io, ...) |
| Shown first | all AI/LLM security stories (AI words in title or link: AI, LLM, agents, Claude, GPT, OpenAI, MCP, prompt, ...) |
| Collapsed | top 5 other security stories by points; the rest go back to their points buttons |
| Unread count | AI/LLM security stories only |
| Other buttons | stories listed under security don't appear under AI or points buttons; watch stories stay under watch |
