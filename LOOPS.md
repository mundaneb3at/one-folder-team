# Loops: let a bot work through a list on its own

A **loop** means: the bot reads its to-do file, does one item, writes the result, adds the next items it thinks of, and repeats.
You check in once in a while and say "go" or "stop".

## The marker word: `WORKLOOP`

Every loop file starts with one line that has the word `WORKLOOP` in it.
That way you (or any bot) can search the Drive for `WORKLOOP` and see all loop work in one go.

The first line of every result file looks like this:

```
WORKLOOP bot=claude status=RESULT item=7
```

`status` is one of:
- `RESULT` - I finished an item, result is below.
- `BACKLOG` - I added new items to my list.
- `BLOCKED` - I need you. The question is on line 2.
- `DRY` - my list is empty and I could not find good new items. I stopped.

## The loop, step by step

Each bot that loops has **its own backlog file it created itself**, like `LOOPS/BACKLOG-claude.md`
(start it from [templates/BACKLOG.md](templates/BACKLOG.md)). Bots often can't edit files they didn't create, so let each bot make its own.

1. Read `START-HERE.md` and your backlog file.
2. Take the top `OPEN` item.
3. Do it. Write the result as a **new file** in your `out` folder, first line `WORKLOOP ... status=RESULT`.
4. Mark the item `DONE` in your backlog and add the file name.
5. If the list has fewer than 3 open items, **refill**: add up to 10 new useful items (see the caps).
6. Go back to step 2, or stop if a cap says stop.

## Caps (so it never runs away)

| Cap | Number |
|---|---|
| New items per refill | **10 at most** |
| Refills per day | **3 at most** |
| Empty refills in a row before stopping | **2** (then write `status=DRY` and stop) |
| Money, sending, booking, deleting | **never** without asking you first |

Refill ideas must come from what is already in the folder: `TASKS.md`, `IDEAS/`, the interview notes, or open questions in the bot's own results.
No made-up busy work.

## Starting and stopping

- **Start:** paste the LOOP RULES block below after the app's prompt from [prompts/](prompts/), then say "start your loop".
- **Check in:** search Drive for `WORKLOOP`. Read anything with `BLOCKED` first.
- **Stop:** say "stop". The bot writes where it got to as its last result.
- **Run by itself on a schedule:** some apps (for example Manus, and some others) can run a saved task on a timer. Check current plan. Start by hand for the first week anyway, so you see what it does.

## Paste-in loop block

Add this to the end of any bot's prompt to turn the loop on:

```
LOOP RULES
- Your backlog is LOOPS/BACKLOG-<your name>.md in my WORK-HQ Drive folder. Create it if missing; only you edit it.
- Do the top OPEN item. Save the result as a new plain .md file in <your name>/out/, named YYYY-MM-DD-<short-name>.md.
- First line of every file you write: WORKLOOP bot=<your name> status=RESULT|BACKLOG|BLOCKED|DRY item=<number>
- Refill when fewer than 3 items are open: add at most 10, at most 3 refills a day, only from what is in the folder.
- After 2 empty refills in a row, write status=DRY and stop.
- Never spend money, send messages, book, or delete. Ask me with status=BLOCKED instead.
- Write one reply file per run, not several copies.
```
