# Playbook (one page)

Small routines. Each one takes a few minutes. Skip any that do not help.

## Daily (5 minutes, end of day)

1. Snap photos of today's receipts into `BOOKS/receipts/<this month>/`.
2. Say to one bot (voice is fine): "Today I did 6 jobs, sold 3 products, bought supplies for 40."
   Ask it to add a draft line to its `out` folder: `YYYY-MM-DD-day-log.md`.
3. Glance at `TASKS.md`. Pick tomorrow's **one** most important thing.

## Weekly (20 minutes, quiet day)

1. **Money check.** Ask Claude or ChatGPT:
   "Read this week's day logs and receipts. Draft the week's lines for BOOKS/BOOKKEEPING.md. Flag anything odd."
   You copy the lines in yourself after checking them.
2. **Clients.** Ask Gemini: "Who in CLIENTS.md is due for a visit soon?" Send reminders yourself.
3. **Tasks.** Move done items to the DONE section. Add new ones.
4. **One idea.** Ask Grok or Muse for 3 small ideas for next week (a promo, a post, a product).
5. **Loops.** If a bot runs a loop (see [LOOPS.md](LOOPS.md)), read its newest result. Say "go" or "stop".

## Monthly (45 minutes, first week of the month)

1. **Monthly close** (see [templates/BOOKKEEPING.md](templates/BOOKKEEPING.md)):
   - Total income, total expenses, profit.
   - Every expense has a receipt in `BOOKS/receipts/<month>/`.
   - Bank balance matches what the sheet says (roughly).
2. Ask one bot: "Compare this month to last month in 5 lines."
3. Tidy up: move last month's `out` files to `_old/<month>/`.
4. Ask yourself: which bot helped most? Which one can I drop?
5. Send the month's sheet and receipts to your accountant if you use one.

## Sayings that save time

| You say | The bot does |
|---|---|
| "go" | does the next item |
| "stop" | stops and writes where it got to |
| "explain" | gives the long version |
| "check this" | reviews another bot's file and lists problems |
| "short" | cuts its last answer in half |
