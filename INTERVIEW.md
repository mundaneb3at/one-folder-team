# The interview

You like to talk. Good. Let a bot interview you, then turn what you said into a plan.
Best with a voice app (ChatGPT or Gemini on your phone). 20-40 minutes. You can stop and come back.

## Step 1: paste this into one bot

```
You are interviewing me, someone who runs a small business on my own.
Goal: find out what I want, what I look forward to, and what I can imagine my business becoming,
so we can decide which AI helpers to use and for what.

How to interview me:
- Ask ONE short question at a time. Wait for my answer.
- Let me ramble. Then ask one follow-up that goes deeper ("What would that look like on a good Tuesday?").
- Cover these areas, in any order that feels natural:
  1. A normal day and week. What eats my time? What do I dread?
  2. Money: how I track it now, what worries me, what I wish I knew each month.
  3. Clients: bookings, no-shows, reminders, keeping regulars coming back.
  4. Marketing: social posts, reviews, word of mouth, what I have tried.
  5. Products and suppliers: ordering, stock, what sells.
  6. What I look forward to. What would make me proud in a year.
  7. Wild ideas: if time and money were no problem, what would I add?
  8. What I do NOT want a bot to touch.
- Every 10 questions, give me a 3-line "here is what I heard" and ask if it is right.
- Talk short and plain. No jargon.

When I say "done":
Write a file called interview-notes.md with these parts:
A. What I want (5-10 bullets, my own words where you can)
B. What I look forward to (3-5 bullets)
C. Pain points ranked, worst first
D. Hands off (things no bot should do)
E. Task ideas, each one line, in the table below
```

## Step 2: how answers turn into tasks

Ask the bot to fill this table at the end (part E):

| Idea | Which app | How often | First small step | Saves me |
|---|---|---|---|---|
| Weekly money summary | Claude | weekly | draft from day logs | 30 min/week |
| Reminder texts for regulars | Gemini (reads CLIENTS.md) | weekly | list who is due | lost bookings |
| 3 post ideas for Instagram | Grok or Muse | weekly | ideas file in out/ | thinking time |
| Supplier price check | Manus | monthly | one product, 3 shops | money |

Rules the bot uses to pick the app:
- Needs your Google files or calendar: **Gemini**.
- Careful writing or long reading: **Claude**.
- Talking it out, quick drafts: **ChatGPT**.
- What is happening online right now: **Grok**.
- A long job with many steps: **Manus**.
- Second opinion or more ideas: **Muse**.
- Explainer with sources you can check: **Vibe**.

## Step 3: you pick

1. Save `interview-notes.md` in `WORK-HQ/IDEAS/`.
2. Pick the **top 3** task ideas. Put them in `TASKS.md` under NOW.
3. Everything else goes under LATER. Nothing is a must.

Do the interview again in 3 months. Things change.
