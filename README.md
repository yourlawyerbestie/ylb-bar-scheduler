# goat-bar-scheduler
free scheduling tool for the busy goat bar exam taker
# 🐐 The Busy GOAT Scheduler
### A free bar prep scheduling tool — built for your actual life

**A collaboration between [Your Lawyer Bestie](https://yourlawyerbestie.substack.com) × [GOAT Bar Prep](https://www.instagram.com/goatbarprep)**

---

## What this is

A free, browser-based scheduling tool for bar exam takers — especially retakers and working adults who can't just clear their calendar for two months.

You answer 6 questions about your actual life (work hours, caretaking responsibilities, non-negotiables, study preferences, and the tools you're using). The tool builds a personalized weekly schedule around all of it, with GOAT Bar Prep as the study backbone.

It is not a product. It is not a startup. It is not collecting your data. It is a single HTML file that runs in your browser — the same way a calculator works.

---

## Who it's for

- Bar exam takers (first attempt or retakers) who are also working, caregiving, or otherwise not studying full time
- Anyone using GOAT Bar Prep who wants a structured week around those modules
- People who have tried commercial schedules and found them unrealistic

---

## How to use it

**Option 1 — Use it in your browser (easiest)**

Visit: `[your GitHub Pages URL here]`

No download, no account, no install.

**Option 2 — Save it to your computer (works offline)**

Right-click the page → Save As → open `index.html` in any browser. Works completely offline, no internet needed. Good for library study sessions with bad wifi.

---

## The 6 steps

| Step | What it asks |
|------|-------------|
| 01 · Exam Setup | Jurisdiction, exam date, attempt number |
| 02 · Work & Caretaker | Your actual work schedule, commute, caregiving hours |
| 03 · Non-Negotiables | Wellness and life activities that go in *first* — gym, spirituality, family, therapy, TikTok (yes really) |
| 04 · Subject Strategy | NCBE outline order, or weakest subject first with confidence ratings |
| 05 · Study Settings | Heavy study days, start times, MCQ targets, essay frequency |
| 06 · Your Tools | Which bar prep tools you're actually using — GOAT is the backbone, everything else layers on top |

Hit **Continue →** through all six and your schedule populates on the output screen.

---

## About the data (important to read)

**Nothing you enter goes anywhere.**

There is no backend. No server. No database. No account. Everything runs entirely in your browser tab.

- **While the tab is open:** your schedule lives in memory. Edit blocks by double-clicking them.
- **To save it across sessions:** hit **💾 Save My Settings** — this saves to your browser's local storage. It stays until you clear your browser data or switch devices.
- **To keep a permanent copy:** use the export buttons — download a `.ics` file for Google Calendar, print to PDF, or copy a Notion-formatted version to your clipboard.

If you close the tab without saving or exporting, your changes are gone. That is the intentional trade-off for a tool that requires zero sign-up.

---

## Jurisdictions

| Jurisdiction | Status |
|---|---|
| Standard UBE | ✅ Fully supported |
| California Bar | ✅ Fully supported |
| Louisiana Bar | 🚧 Coming soon |
| Florida Bar | 🚧 Coming soon |
| Georgia, Texas, Nevada + others | 🚧 Queued |

---

## Features

- Week, Day, and Month views of your schedule
- Color-coded block categories (study, wellness, work, commute, protected, library day)
- Double-click any block to edit it (time, duration, day, MCQ count, supplements)
- Conflict warnings in GOAT voice when you overload a day
- Rolling Review auto-populates on Library Day (Saturday) as subjects accumulate
- Commute blocks (AM + PM) auto-generated from your work schedule
- Wellness blocks auto-generated from your Step 3 selections — gym, walks, meal prep, TikTok, all of it
- Export to Google Calendar (.ics), Print to PDF, Copy to Notion, Save to browser

---

## Technical notes (for anyone curious)

This is a single self-contained HTML file — no framework, no build step, no dependencies except Google Fonts. It is approximately 1,900 lines of HTML, CSS, and vanilla JavaScript.

If you want to run it locally, open the file in any modern browser. That's it.

If you want to contribute, fork this repo, make your changes, and open a pull request. All welcome.

---

## Credits

Built by **Reni Rhodes / Your Lawyer Bestie**
Study methodology and content backbone by **GOAT Bar Prep**

- YLB on [Substack](https://yourlawyerbestie.substack.com) · [TikTok](https://www.tiktok.com/@yourlawyerbestie) · [YouTube](https://www.youtube.com/@Your-Lawyer-Bestie)
- GOAT on [TikTok](https://www.tiktok.com/@goatbarprep) · [Instagram](https://www.instagram.com/goatbarprep)

---

*Free. No login. No data collected. Built because the standard bar prep schedule assumes you have no life — and most of us do.*
