# Job Agent — your first 5 minutes

A plain-language walkthrough from download to your first job leads. No coding, no
setup files — the app asks you everything it needs.

## 1. Download & open (1 min)

Grab the file for your computer from **https://kr-16.github.io/jobagent-app/**:
Windows (`JobAgent.exe`), macOS (Apple Silicon), or Linux.

- **Windows** will say *"Windows protected your PC"* — that's just because the app
  isn't signed (it's free). Click **More info → Run anyway**.
- **macOS** will say it *"cannot be verified"* — **right-click the app → Open → Open**.

This is normal for free, independent apps and happens only the first time.

## 2. Answer the setup wizard (2 min)

On first launch the app asks a few questions:

| It asks for | What to enter |
|---|---|
| **Your name** | anything — it just personalizes the app |
| **Target roles** | the jobs you want, e.g. `Software Engineer, Data Analyst` |
| **Seniority** | internship / entry / mid / senior |
| **Location** | a country, state, city, or `Remote` — leads are matched to this |
| **Gemini API key** | free from https://aistudio.google.com/apikey (paste one or more) |
| **Email** (optional) | where to send you new job alerts |
| **Job sources** | LinkedIn is on; you can also turn on Dice |

Then it opens **one Google sign-in** and creates a spreadsheet **in your own Google
Drive** — that's where all your leads will live. Bookmark the link it prints.

When the wizard finishes, the app **opens a settings page in your browser** so you
land on a real screen, not a terminal. You can change any answer there later.

## 3. Log in to LinkedIn — one time (1 min)

Pick **menu option 1 (Log in to LinkedIn)**. A Chrome window opens — sign in to
LinkedIn like you normally would. The app reuses that session from then on; you
won't need to do it again unless it expires.

## 4. Start Autopilot (1 min to start; then it runs itself)

Pick **menu option 6 (Autopilot)**. From here the agent, on its own, every few hours:

1. **Scrapes** fresh hiring posts + jobs for your roles and location
2. **Categorizes** them with AI (role, seniority, skills, how to apply)
3. **Emails you** the best, directly-applyable leads (Tier 1 — has an email or link)
4. **Updates your spreadsheet** with a Dashboard (charts) and an Activity log

Leave it running and check your inbox and your sheet. That's it.

## Where everything lives

- **Your leads** → the Google Sheet in *your* Drive (the link from step 2)
- **Your settings** → menu option 8 (settings page) or option 7 (re-run the wizard)
- **Your data** → stays in your accounts and on your machine. Nothing is uploaded
  anywhere else.

## Common questions

- **"No leads yet?"** The first cycle takes a while, and a quiet day simply has fewer
  hiring posts. Check the Activity tab in your sheet to see what each run did.
- **"AI quota exceeded?"** The free Gemini tier resets daily; the agent picks up
  where it left off. Adding a second free key (settings page) doubles your headroom.
- **"How do I update the app?"** Menu option 9 checks for a new version. Download it
  from the same link — your settings, sheet, and login all carry over.
