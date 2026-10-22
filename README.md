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
- AI 10+ holds 10-19 points and AI 20+ holds 20+; a story moves up as it gains points.
- security (last button): 20+ point security stories; AI/LLM ones first, other security ones collapsed at the end.
- Stories under security don't appear under any other button.
- The same link posted more than once shows once: the post with the most points.
