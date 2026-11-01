# Sign up and connect each app

Do these one at a time, and only for the apps you want. Use the **same Google account** that owns your `WORK-HQ` folder.
Start free. Check each app's current plan before you pay. Free limits for each app: [FREE-MODELS.md](FREE-MODELS.md).

## Why connect an app to your Drive folder at all?

Without the folder, every chat starts from zero: you explain your business again, and the answer stays stuck in that one app.
With the folder, the app can **read your notes first** (prices, clients, to-do list) and **save its work where you and
the other apps can find it**. That is what turns a few separate chat apps into a small team.
If an app cannot connect, it still helps: you copy its answer into its folder yourself. It takes ten seconds.

**Before you start, for every app:**
1. Make sure you are on the real site or the real app in the app store (check the maker's name).
2. Turn on two-step login if the app offers it.
3. Paste the TALK-SHORT RULE from [README.md](README.md) into its custom instructions.

**Connecting to Drive, in general:** look in the app's **Settings** for *Connectors*, *Apps*, *Integrations* or *Extensions*.
Pick **Google Drive** and sign in. If it asks what to share, pick the `WORK-HQ` folder only, when it lets you.

---

## Claude
- **Sign up:** claude.ai (web) or the Claude app on your phone.
- **Drive:** Settings, then Connectors, then Google Drive.
- **Why connect it:** Claude is good at reading long files. Connected, it can read your price list or a month of receipts and write you a short summary file.
- **Tip:** make a **Project** called "Work HQ". Put the talk-short rule and [prompts/claude.md](prompts/claude.md) in the project instructions. Every chat in it remembers them.

## ChatGPT
- **Sign up:** chatgpt.com or the ChatGPT app.
- **Drive:** Settings, then Apps / Connectors. Drive may need a paid plan (see FREE-MODELS.md). Free way: upload a file from Drive into the chat.
- **Why connect it:** so a voice chat on your phone can end with a note saved in the folder, not lost in the app.
- **First prompt:** [prompts/chatgpt.md](prompts/chatgpt.md).

## Gemini
- **Sign up:** gemini.google.com or the Gemini app. It uses your Google account already.
- **Drive:** look in Settings for Google Workspace / Drive. Whether the free plan can read your Drive files changes often: check current plan.
- **Why connect it:** it is made by Google, so your Drive, Gmail and Calendar are close by when the plan allows it.
- **First prompt:** [prompts/gemini.md](prompts/gemini.md).

## Grok
- **Sign up:** grok.com or the Grok app.
- **Drive:** check Settings. If there is no Drive option, copy its answer into `grok/out/` yourself.
- **Why connect it (or not):** Grok is for looking outward (trends, reviews), so it needs your files least. Copy and paste is fine.
- **First prompt:** [prompts/grok.md](prompts/grok.md).

## Manus
- **Sign up:** manus.im.
- **Drive:** it has connectors (Google Drive, Gmail and more). Give it the `WORK-HQ` folder only, **not** your whole Gmail.
- **Why connect it:** Manus does longer jobs on its own. Connected, it can drop the finished report straight into `manus/out/`.
- **Watch out:** Manus spends "credits" per job, and big jobs can use a lot. Start with one small job and see what it cost.
- **First prompt:** [prompts/manus.md](prompts/manus.md).

## Muse (Meta AI)
- **Sign up:** the Meta AI app or meta.ai. Meta AI runs on Meta's "Muse Spark" model. If you meant a different Muse, check its maker first.
- **Drive:** no Drive option found. Copy its answers into `muse/out/` by hand.
- **Why use it anyway:** fast caption and idea lists, and it lives next to Instagram and Facebook.
- **First prompt:** [prompts/muse.md](prompts/muse.md).

## Vibe (by Mistral)
- **Sign up:** mistral.ai, or the Vibe app (it used to be called Le Chat). Check the maker is Mistral.
- **Drive:** its free plan lists many connectors, but does not name Google Drive. Check Settings. Some connectors can read but not edit files: that is OK, it only writes new files in `vibe/out/`.
- **Why connect it:** so it can answer questions about your own policy or price files, in any language you need.
- **First prompt:** [prompts/vibe.md](prompts/vibe.md).

---

## Two things that trip people up

1. **"I can't edit that file."** Many Drive connectors can only edit files **the app made itself**.
   So in this kit each app writes **new files in its own `out` folder** and never edits your files.
2. **Google Docs vs plain files.** Ask every app to save as a plain `.md` or `.txt` file, not a Google Doc.
   Plain files are easier for the other apps to read.
