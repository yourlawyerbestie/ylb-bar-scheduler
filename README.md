# ylb-bar-prep-scheduler
A free bar prep scheduling tool — built for your actual life

# ⚖️ YLB Bar Prep Scheduler
### A free bar prep scheduling tool — built for your actual life

**Built by [Your Lawyer Bestie](https://yourlawyerbestie.substack.com)**

---

## What this is

A free, browser-based scheduling tool for bar exam takers — especially retakers and working adults who can't just clear their calendar for two months.

You answer 6 questions about your actual life (work hours, caretaking responsibilities, non-negotiables, study preferences, and the tools you're using). The tool builds a complete, personalized study arc — every week from today to your exam date.

It is not a product. It is not a startup. It is not collecting your data. It is a single HTML file that runs in your browser — the same way a calculator works.

---

## Who it's for

- Bar exam takers (first attempt or retakers) who are also working, caregiving, or otherwise not studying full time
- Anyone who wants a structured week built around their actual schedule and bar prep tools
- People who have tried commercial schedules and found them unrealistic for their actual life

---

## How to use it

**Option 1 — Use it in your browser (easiest)**

Visit: https://yourlawyerbestie.github.io/goat-bar-scheduler/

No download, no account, no install.

**Option 2 — Save it to your computer (works offline)**

Right-click the page → Save As → open `index.html` in any browser. Works completely offline. Good for library sessions with spotty wifi.

---

## The 6 steps

| Step | What it asks |
|------|-------------|
| 01 · Exam Setup | Jurisdiction (UBE, CA, + more coming), exam date, attempt number. The exam date is what the entire schedule builds around. |
| 02 · Work & Caretaker | Your actual work schedule, commute (AM + PM), caregiving and household hours |
| 03 · Non-Negotiables | Wellness and life activities that go in *first* — gym, spirituality, family, therapy, meal prep, TikTok (yes really) |
| 04 · Subject Strategy | NCBE outline order, or weakest subject first with confidence ratings. Mark subjects you've already covered to skip them from your schedule. |
| 05 · Study Settings | Weekday study start time, MCQ targets, essay frequency, Book of Shame toggle |
| 06 · Your Tools | Which bar prep tools you're actually using — layer them into your schedule as you go |

Hit **Continue →** through all six and a full multi-week schedule generates from today to your exam.

---

## How the schedule generates

The tool reads your exam date and today's date, calculates the real number of weeks you have, and distributes your active MBE subjects across that arc — reserving the final 2 weeks for MEE/MPT final push. Every week gets:

- Work blocks at your actual hours
- Study blocks at your study start time, with MCQ targets from Step 5
- Saturday Library Day with rolling review of all subjects covered so far
- Sunday preview of next week's subject
- Wellness blocks from your Step 3 selections, distributed across the week
- AM + PM commute blocks if enabled in Step 2

Subjects you've marked as "Already covered" in Step 4 are skipped. The remaining subjects are redistributed across your actual available weeks.

---

## What you can do with the schedule

- **Double-click any block** to edit it — time, duration, day, MCQ count, supplements
- **Switch between Week / Day / Month views** — Month view shows your full arc; click any week row to jump to it
- **"I'm behind" button** — three real options: compress this week (adds MCQs to remaining days), redistribute to Library Day, or skip and log to Book of Shame
- **Export** — download a `.ics` for Google Calendar, print to PDF, copy to Notion, or save to browser

---

## About the data (important to read)

**Nothing you enter goes anywhere.**

There is no backend. No server. No database. No account. Everything runs in your browser tab.

- **While the tab is open:** your schedule lives in memory. Edit blocks freely.
- **To save across sessions:** hit **💾 Save My Settings** — saves to browser local storage on your device.
- **To keep a permanent copy:** export buttons — `.ics` for Google Calendar, PDF print, or Notion copy.

Closing the tab without saving or exporting loses your changes. That is the trade-off for zero sign-up.

---

## Jurisdictions

| Jurisdiction | Status |
|---|---|
| Standard UBE | ✅ Fully supported |
| California Bar | ✅ Fully supported (different essay subjects + PT format) |
| Louisiana Bar | 🚧 Coming soon |
| Florida Bar | 🚧 Coming soon |
| Georgia, Texas, Nevada + others | 🚧 Queued |

---

## Technical notes

Single self-contained HTML file. No framework, no build step, no backend, no dependencies except Google Fonts. Approximately 2,200 lines of HTML, CSS, and vanilla JavaScript.

Open in any modern browser. That's it.

---

## Credits

Built by **Reni Rhodes / Your Lawyer Bestie**

- YLB on [Substack](https://yourlawyerbestie.substack.com) · [TikTok](https://www.tiktok.com/@yourlawyerbestie) · [YouTube](https://www.youtube.com/@Your-Lawyer-Bestie)

---

*Free. No login. No data collected. Built because the standard bar prep schedule assumes you have no life — and most of us do.*
