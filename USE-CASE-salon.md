# Use case: a one-person hair salon

One worked example of the kit. Made-up person, made-up numbers. Swap in your own trade.

**Who:** runs a small salon alone. Cuts, colour, some product sales. Likes to talk, does not like paperwork.
Books by text and a paper diary. Receipts live in a shoebox.

## Week 1: start with one app

1. Makes `WORK-HQ` in Google Drive with the folders from [DRIVE-LAYOUT.md](DRIVE-LAYOUT.md).
2. Signs up for ChatGPT on the phone ([SIGNUP.md](SIGNUP.md)). Pastes the talk-short rule.
3. Does the [interview](INTERVIEW.md) by voice between clients, over two days.
4. Top 3 from `interview-notes.md`, now in `TASKS.md` under NOW:
   - Know each month if I actually made money.
   - Stop losing regulars who forget to rebook.
   - Post on Instagram once a week without thinking about it.

## Week 2: money

- **Daily, 3 minutes:** photo of receipts into `BOOKS/receipts/2026-11/`. Then says to ChatGPT:
  "Today: 5 cuts, 2 colours, sold 3 shampoos, bought foils and developer, about 60."
  ChatGPT writes `chatgpt/out/2026-11-10-day-log.md`.
- **Sunday, 15 minutes:** adds Claude. Asks it to read the week's day logs and draft lines for
  `BOOKS/BOOKKEEPING.md`. Checks them with a calculator, copies them in.

Example lines in the sheet:

| Date | What | Paid by | Amount |
|---|---|---|---|
| 2026-11-10 | cut + colour | card | (your price) |
| 2026-11-10 | foils, developer (supplies) | card | (your cost) |

## Week 3: clients

- Fills in `CLIENTS/CLIENTS.md` for the 20 regulars: first name, how often they come, colour formula,
  allergies, "OK to text: yes/no".
- Adds Gemini, because it lives in Google. Asks: "Who in CLIENTS.md has not been in for 7 weeks?"
- Gemini lists 4 names. The owner texts them. 2 book.

## Week 4: posts and a loop

- Adds Grok: "3 post ideas this week using photos I already have. Sources for any trend you mention."
- Adds Muse as a checker: "Read grok/out newest file. Which idea fits a small local salon best?"
- Turns on a small loop for Claude ([LOOPS.md](LOOPS.md)), backlog `LOOPS/BACKLOG-claude.md`:
  1. Draft a friendly price list from my notes.
  2. Draft a no-show policy (2 lines).
  3. Draft a "welcome back" text for clients gone 3+ months.
- Searches Drive for `WORKLOOP` on Friday. Reads 3 results. Keeps 2. Says "stop".

## Month end

- Monthly close from [templates/BOOKKEEPING.md](templates/BOOKKEEPING.md): income, expenses, profit,
  every expense has a receipt. Asks Claude for a 5-line "this month vs last month".
- Moves old `out` files to `_old/2026-11/`.
- Decides: keep ChatGPT (voice), Claude (money), Gemini (clients). Drops Muse for now. Manus and Vibe: maybe later.

## What made it work

- One app at a time. A new one only when the last one was useful.
- The bots never touched the money sheet or client notes. They drafted; the owner copied.
- Short answers. When a bot rambled, the owner said "short".
