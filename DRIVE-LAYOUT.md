# Drive layout

One folder. Everything lives in it. Bots read the shared files and write only in their own `out` folder.

```
WORK-HQ/
  START-HERE.md          <- copy of README.md, so any bot knows the rules
  TASKS.md               <- the task board (templates/TASKS.md)
  BOOKS/
    BOOKKEEPING.md       <- monthly money sheet (templates/BOOKKEEPING.md)
    receipts/
      2026-11/           <- photos or PDFs of receipts, one folder per month
  CLIENTS/
    CLIENTS.md           <- client + booking notes (templates/CLIENTS.md)
  IDEAS/
    interview-notes.md   <- what came out of the interview
  LOOPS/
    BACKLOG-claude.md    <- one backlog per bot that runs a loop (templates/BACKLOG.md)
  claude/out/            <- Claude writes here
  chatgpt/out/
  gemini/out/
  grok/out/
  manus/out/
  muse/out/
  vibe/out/
  _old/                  <- move old files here instead of deleting
```

Only make the `out` folders for apps you actually use.

## What goes where

| Folder | Who writes | What |
|---|---|---|
| `TASKS.md` | **you** (bots suggest) | the one list of things to do |
| `BOOKS/` | **you** (bots draft) | money in, money out, receipts |
| `CLIENTS/` | **you** | short client notes and booking habits |
| `IDEAS/` | you + bots | notes, the interview, wild ideas |
| `LOOPS/` | each bot its own file | to-do lists a bot works through (see [LOOPS.md](LOOPS.md)) |
| `<bot>/out/` | that bot only | answers, drafts, reports |
| `_old/` | anyone | old stuff. Nothing gets deleted. |

## File names

Bots name their files like this, so you can sort them by date:

```
2026-11-03-weekly-money-summary.md
2026-11-03-promo-ideas.md
```

Date first (year-month-day), then a few words. No spaces.

## How the bots "talk" to each other

1. Claude writes `claude/out/2026-11-03-promo-ideas.md`.
2. You tell Muse: "Read the newest file in claude/out and give me a second opinion."
3. Muse writes `muse/out/2026-11-03-promo-check.md`.
4. You read both, then add the winner to `TASKS.md`.

That is it. Files are the messages. You are the one who moves good work forward.

## Keep it light

- One task board, not one per bot.
- Short files. If a file gets longer than a page or two, ask a bot to summarize it and move the long one to `_old/`.
- Once a month, move old `out` files into `_old/2026-11/` and so on.
