# Sign up and connect each app

Do these one at a time. Use the **same Google account** that owns your `WORK-HQ` folder.
Start free. Check each app's current plan before you pay.
Not sure which apps to try? [FREE-MODELS.md](FREE-MODELS.md) lists the free ones and what each is good for.

**Before you start, for every app:**
1. Make sure you are on the real site or the real app in the app store (check the maker's name).
2. Turn on two-step login if the app offers it.
3. Paste the TALK-SHORT RULE from [README.md](README.md) into its custom instructions.

**Connecting to Drive, in general:** look in the app's **Settings** for a section called
*Connectors*, *Apps*, *Integrations*, or *Extensions*. Pick **Google Drive** and sign in.
If it asks what to share, pick the `WORK-HQ` folder only when it lets you.
If an app has no Drive option, that is fine: download its answer and drop the file in its `out` folder yourself.

---

## Claude
- **Sign up:** claude.ai (web) or the Claude app on your phone.
- **Drive:** Settings, then Connectors, then Google Drive. Check current plan for which plans have it.
- **Tip:** make a **Project** called "Work HQ". Put the talk-short rule and [prompts/claude.md](prompts/claude.md) in the project instructions. Every chat in it remembers them.
- **First prompt:** paste [prompts/claude.md](prompts/claude.md).

## ChatGPT
- **Sign up:** chatgpt.com or the ChatGPT app.
- **Drive:** Settings, then Apps / Connectors, then Google Drive. Check current plan.
- **Tip:** the phone app has voice chat. Good for the interview while you work with your hands.
- **First prompt:** paste [prompts/chatgpt.md](prompts/chatgpt.md).

## Gemini
- **Sign up:** gemini.google.com or the Gemini app. It uses your Google account already.
- **Drive:** in Settings, turn on the Google Workspace / Drive extension. Then you can say "look in my WORK-HQ folder".
- **First prompt:** paste [prompts/gemini.md](prompts/gemini.md).

## Grok
- **Sign up:** grok.com or the Grok app.
- **Drive:** check Settings for a Google Drive connector. If there is none, copy its answer into `grok/out/` yourself.
- **First prompt:** paste [prompts/grok.md](prompts/grok.md).

## Manus
- **Sign up:** manus.im.
- **Drive:** it has connectors (Google Drive, Gmail and more). Give it the `WORK-HQ` folder only, **not** your whole Gmail.
- **Watch out:** Manus spends "credits" per job, and big jobs can use a lot. Start with one small job and see what it cost.
- **First prompt:** paste [prompts/manus.md](prompts/manus.md).

## Muse
- **Sign up:** find the official Muse app or site in your app store. Check the maker's name before you sign up.
- **Drive:** check its Settings for Google Drive. If none, copy answers into `muse/out/` by hand.
- **First prompt:** paste [prompts/muse.md](prompts/muse.md).

## Vibe
- **Sign up:** find the official Vibe app or site. Check the maker's name before you sign up.
- **Drive:** check its Settings for Google Drive. Some connectors can read but not edit files. That is OK: it only writes new files in `vibe/out/`.
- **First prompt:** paste [prompts/vibe.md](prompts/vibe.md).

---

## Two things that trip people up

1. **"I can't edit that file."** Many Drive connectors can only edit files **the bot made itself**.
   So in this kit each bot writes **new files in its own `out` folder** and never edits your files.
2. **Google Docs vs plain files.** Ask every bot to save as a plain `.md` or `.txt` file, not a Google Doc.
   Plain files are easier for the other bots to read.
