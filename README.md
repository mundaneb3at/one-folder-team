# Drive Starter Kit: AI helpers for people who work on their own

A small, free kit for any independent person or small business: a trade, a shop, a studio, a freelancer.
It shows how to let several AI chat apps work as a little team, using **one Google Drive folder** as the shared office.

Want to see it in a real-looking day? Read [USE-CASE-salon.md](USE-CASE-salon.md): one worked example, a one-person hair salon.

The bots never talk to each other directly. They read and write plain files in the same folder.
You stay the boss: you read what they wrote, keep what is good, and say "go" for the next step.

This is a **mini version to explore**, not a set of rules. Take what helps. Skip the rest.

## The one rule: talk to me short

Every bot in this kit must talk to you short and plain. Paste this block into each app
(in its custom instructions, project instructions, or the first message of a chat):

```
TALK-SHORT RULE
- Answer in 5 lines or less unless I say "explain".
- Plain words. No jargon. If you must use a word I may not know, explain it in brackets.
- Lead with the answer or the next step. No warm-up, no summary at the end.
- One question at a time. Give me 2-3 choices when you can.
- If you are not sure, say "not sure" and how to check.
- Never sign me up, pay, send, or delete anything without asking first.
```

## 10-minute start

1. Make a Google Drive folder called `WORK-HQ`. Copy the folders from [DRIVE-LAYOUT.md](DRIVE-LAYOUT.md).
2. Copy the files from [templates/](templates/) into it.
3. Pick **one** app to start (Claude, ChatGPT, or Gemini is easiest). Follow its part of [SIGNUP.md](SIGNUP.md).
4. Paste the talk-short rule, then paste that app's prompt from [prompts/](prompts/).
5. Run [INTERVIEW.md](INTERVIEW.md). Talk as long as you like. The bot turns it into a task list.

Add a second app only after the first one feels useful. One good helper beats seven noisy ones.

## Which app is good for what

| App | Good for | Try it for |
|---|---|---|
| **Claude** | careful writing, reading long files, organizing | the weekly money summary, polishing client messages |
| **ChatGPT** | all-rounder, voice chat on your phone | the interview (talk out loud), quick drafts |
| **Gemini** | lives inside Google (Drive, Gmail, Calendar) | finding files, reading your Drive, calendar ideas |
| **Grok** | fast web lookups, what people say online | trends, local competitor prices, product reviews |
| **Manus** | longer "go do this" jobs that run on their own | a weekly report, research that takes many steps |
| **Muse** | a second opinion, idea lists | promo ideas, checking another bot's work |
| **Vibe** | explainers with sources, step-by-step guides | "how do I...?" answers you can trust and check |

Features and prices change often. **Check each app's current plan** before you pay for anything.
Start with the free tier.

## Which free tools exist and what each is good for

See [FREE-MODELS.md](FREE-MODELS.md): every free or free-tier AI app we know of (the seven above plus others like Meta AI, Copilot, DeepSeek),
what each is good for, its limits, and where the facts came from.

## What is in this kit

| File | What it is |
|---|---|
| [FREE-MODELS.md](FREE-MODELS.md) | which free AI apps exist, what each is good for, limits |
| [SIGNUP.md](SIGNUP.md) | how to sign up for each app and connect it to your Drive folder |
| [DRIVE-LAYOUT.md](DRIVE-LAYOUT.md) | the folder tree and what goes where |
| [PLAYBOOK.md](PLAYBOOK.md) | daily, weekly, and monthly routines on one page |
| [LOOPS.md](LOOPS.md) | how a bot can work through a to-do file on its own, safely |
| [INTERVIEW.md](INTERVIEW.md) | a prompt that has a bot interview you, then makes your task list |
| [EXPLORE.md](EXPLORE.md) | ideas to try, no orders |
| [USE-CASE-salon.md](USE-CASE-salon.md) | worked example: a one-person hair salon |
| [prompts/](prompts/) | one short starter prompt per app |
| [templates/](templates/) | task board, bookkeeping sheet, client notes, loop backlog |

## Safety in plain words

- Connect each bot to the `WORK-HQ` folder only, never your whole Drive or whole Gmail, if the app lets you choose.
- Do not put card numbers, passwords, or bank logins in any file.
- Client notes: keep only what you need to do a good job (first name, what they like, allergies). Ask clients before you store anything personal.
- Bots make mistakes, especially with numbers. You check the money files yourself.
- This kit is not tax, legal, or money advice. Ask your accountant about taxes.

## License

MIT. See [LICENSE](LICENSE). Use it, change it, share it.
