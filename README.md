<div align="center">

# 🤖 Job Agent

**Your personal LinkedIn job-hunting agent.**
It scrapes fresh hiring posts, ranks the leads with AI, keeps everything in a
spreadsheet in **your own Google Drive**, and emails you the ones you can
actually apply to — on autopilot.

<br>

[![Download for Windows](https://img.shields.io/badge/⬇%20Download%20for%20Windows-JobAgent.exe-0077b5?style=for-the-badge)](https://github.com/KR-16/jobagent-app/releases/latest/download/JobAgent.exe)

**Also available:** [macOS — Apple Silicon](https://github.com/KR-16/jobagent-app/releases/latest/download/JobAgent-macos-arm64.zip) · [Linux](https://github.com/KR-16/jobagent-app/releases/latest/download/JobAgent-linux-x86_64.tar.gz)

[![Latest release](https://img.shields.io/github/v/release/KR-16/jobagent-app?style=flat-square&color=0077b5)](https://github.com/KR-16/jobagent-app/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/KR-16/jobagent-app/total?style=flat-square&color=00a0dc)](https://github.com/KR-16/jobagent-app/releases)

**[🌐 Website](https://kr-16.github.io/jobagent-app/)** · [What's new](https://github.com/KR-16/jobagent-app/releases) · [Report a problem](https://github.com/KR-16/jobagent-app/issues)

</div>

---

## ✨ What it does

- 🔍 **Scrapes LinkedIn hiring posts** for your target roles with human-like pacing — no manual browsing
- 🤖 **AI categorization** (Google Gemini, free tier) — extracts role, seniority, location, skills, and *how to apply* from every post
- 📬 **Finds the apply route** — pulls out application **emails** and **links**, so the best leads are one click from an application
- 📊 **Your own Google Sheet** — created automatically in *your* Drive on first run, with a live **Dashboard** (charts: leads per day, leads by role) and an **Activity log**
- 📧 **Email digests** — new actionable leads land in your inbox; nothing is ever sent twice
- ⚙️ **Setup wizard + settings page** — configure everything in a friendly first-run wizard, edit later in your browser
- 🔁 **Autopilot** — scrape → categorize → email on a ~3-hour cycle with randomized timing

## 🚀 Get started (3 steps)

1. **[Download for your platform](https://kr-16.github.io/jobagent-app/)** and run it.
   *Windows and macOS will warn because the app is unsigned — see the [FAQ](#-faq) for the one-click fix on each.*
2. **Answer the setup wizard** — your name, target roles, seniority, location, a free [Gemini API key](https://aistudio.google.com/apikey), and (optionally) your email for alerts. One Google consent click creates your personal job spreadsheet.
3. **Pick "Log in to LinkedIn"** (one time), then **"Autopilot"** — and watch leads fill your sheet.

📖 **New here? The [5-minute Getting Started guide](GETTING_STARTED.md) walks through every step with the exact clicks.**

### What you need

| | |
|---|---|
| 💻 | Windows, macOS, or Linux with **Google Chrome** installed |
| 🔗 | A **LinkedIn** account (the agent browses as you, at a human pace) |
| 📗 | A **Google** account (your spreadsheet lives in *your* Drive) |
| 🔑 | A free **Gemini API key** — [grab one here](https://aistudio.google.com/apikey) |

*No Python, no installs, no server — one download.*

## 🔒 Your data stays yours

Everything lives in **your** accounts and on **your** machine: the spreadsheet is created in your Google Drive (the app can only touch files it created — that's the only permission it asks for), your LinkedIn session and caches stay in the app's folder, and emails are sent from your own Gmail. Nothing is uploaded anywhere else, ever.

## ❓ FAQ

<details><summary><b>Windows says "Windows protected your PC"</b></summary>
That's SmartScreen flagging an unsigned app (code-signing certificates cost money — this is a free tool). Click <b>More info → Run anyway</b>. Every release is built and packaged automatically by GitHub Actions.
</details>

<details><summary><b>macOS says the app "cannot be verified"</b></summary>
Same story — the app isn't notarized with Apple. Unzip, then <b>right-click (Control-click) JobAgent → Open → Open</b>. On newer macOS you may also need <i>System Settings → Privacy &amp; Security → "Open Anyway"</i> after the first attempt. Run it from Terminal (<code>./JobAgent</code>) — it's a console app. Requires an Apple Silicon Mac (M1 or newer, i.e. any Mac from 2020 on).
</details>

<details><summary><b>How do I run it on Linux?</b></summary>
Download, then: <code>tar -xzf JobAgent-linux-x86_64.tar.gz && ./JobAgent</code>. You need Google Chrome installed (the agent drives your real Chrome). Built on Ubuntu 22.04, so it runs on most current distros.
</details>

<details><summary><b>Is it free?</b></summary>
Yes. The app is free, the Gemini free tier covers normal daily use, and Google Sheets is free. If a day's AI quota runs out mid-batch, the agent backs off and finishes automatically on a later cycle — nothing is lost.
</details>

<details><summary><b>Is scraping safe for my LinkedIn account?</b></summary>
The agent mimics a human: randomized scroll pauses, gaps between searches, a daily search cap, and a ~3-hour cycle. That said, it automates <i>your</i> account and LinkedIn's terms don't love automation — run it with the default pacing and use your own judgment.
</details>

<details><summary><b>Where do I change my roles/email/keys later?</b></summary>
Menu option <b>8 — Open settings page</b> (or <code>JobAgent.exe ui</code>) opens a local page in your browser. Option <b>7</b> re-runs the wizard. Preference edits never touch your spreadsheet.
</details>

<details><summary><b>How do I update?</b></summary>
Download the latest .exe from the same link — it always serves the newest release. Your profile, LinkedIn session, sheet, and caches are files next to the .exe, so replacing the .exe keeps everything.
</details>

---

<div align="center">

**[⬇ Download JobAgent.exe](https://github.com/KR-16/jobagent-app/releases/latest/download/JobAgent.exe)** — and let the agent hunt while you sleep.

Built by [KR-16](https://github.com/KR-16)

</div>
