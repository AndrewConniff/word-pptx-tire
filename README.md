# Copilot Winter Readiness Demo Package (Word + PowerPoint)

**Classification: Public**

This package is for a **live, demo-led Microsoft 365 Copilot training** tailored to a Canadian retail + auto service context inspired by public market patterns.

**Fictional Microsoft Fake Company:** MapleWheel Retail Group  
**Target audience context:** Canadian Tire store and head office teams (new or light Copilot users)  
**Locale standards used:** en-CA, CAD, metric units

This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this package.

## Scenario

Head office is preparing stores and Auto Service Centres for winter tire changeover season and the holiday rush. Learners see how to prompt Copilot in Chat, Word, and PowerPoint to create, rewrite, structure, summarize, and present operational content quickly.

## Timing (90 minutes)

1. **Opening in Copilot Chat (10 min)**: prompting basics (goal, context, source, expectations), weak vs stronger prompt, Prompt Coach, prompt gallery.
2. **Copilot in Word (35 min)**: drafting, rewriting for audience, turning checklist into table, summarization with follow-up.
3. **Copilot in PowerPoint (35 min)**: generating decks, leadership update, executive rewrite + slide ops, speaker notes.
4. **Close (10 min)**: one learner chat question per app + day-one habits.

## Repository contents

| Path | Purpose |
|---|---|
| [index.html](./index.html) | GitHub Pages quick-run demo guide with copy buttons |
| [demo/DEMO-INSTRUCTIONS.md](./demo/DEMO-INSTRUCTIONS.md) | Presenter script (markdown) |
| [demo/DEMO-INSTRUCTIONS.docx](./demo/DEMO-INSTRUCTIONS.docx) | Presenter script (Word) |
| [demo/sample-data/Winter-Season-Readiness-Procedure.docx](./demo/sample-data/Winter-Season-Readiness-Procedure.docx) | 6–8 page operating procedure |
| [demo/sample-data/Store-Auto-Service-Visit-Notes.docx](./demo/sample-data/Store-Auto-Service-Visit-Notes.docx) | ~3 page store visit notes |
| [demo/sample-data/Winter-Season-Plan-Leadership.docx](./demo/sample-data/Winter-Season-Plan-Leadership.docx) | 4–5 page leadership plan |
| [demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx](./demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx) | Branded title/section/content/closing template |
| [manifest.json](./manifest.json) | Demo metadata |
| [AI-CONTENT-DECLARATION.md](./AI-CONTENT-DECLARATION.md) | AI transparency statement |
| [LICENSE](./LICENSE) | MIT license |

## Published links

- **Repository:** https://github.com/AndrewConniff/word-pptx-tire
- **GitHub Pages:** https://andrewconniff.github.io/word-pptx-tire/
- **Demo guide page:** https://andrewconniff.github.io/word-pptx-tire/index.html

### Direct download links (raw)

- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/demo/sample-data/Winter-Season-Readiness-Procedure.docx
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/demo/sample-data/Store-Auto-Service-Visit-Notes.docx
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/demo/sample-data/Winter-Season-Plan-Leadership.docx
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/demo/DEMO-INSTRUCTIONS.md
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/demo/DEMO-INSTRUCTIONS.docx
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/manifest.json
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/AI-CONTENT-DECLARATION.md
- https://raw.githubusercontent.com/AndrewConniff/word-pptx-tire/main/LICENSE

## Setup steps

1. Open Microsoft 365 Copilot Chat, Word, and PowerPoint in the same tenant.
2. Download all files in `demo/sample-data/`.
3. Upload the sample files to a folder accessible in your Microsoft 365 account (OneDrive or SharePoint).
4. In Word and PowerPoint demos, attach or reference the specified files from that folder.
5. Open `index.html` (or GitHub Pages URL) for copy-ready prompts.

## Prompt sequence (exact order)

### Where to run each prompt (file + app)

| Step | Open app | Open file(s) | Alternative (Copilot Chat grounding) |
|---|---|---|---|
| Prompt 0.1, 0.2 | Copilot Chat | No file required | N/A |
| Prompt W1 | Word | Open `Winter-Season-Readiness-Procedure.docx` and `Store-Auto-Service-Visit-Notes.docx` | In Copilot Chat, attach both docs and run W1 there |
| Prompt W2 | Word | Stay in the bulletin doc created from W1 | In Chat, reference the W1 output you just generated |
| Prompt W3 | Word | Open `Winter-Season-Readiness-Procedure.docx` | In Chat, attach procedure doc and request table output |
| Prompt W4 | Word | Open `Winter-Season-Readiness-Procedure.docx` | In Chat, attach procedure doc and run summary prompt |
| Prompt P1 | PowerPoint | New blank deck or `MapleWheel-Branded-PowerPoint-Template.pptx` | In Chat, ask for slide outline text then paste into PPT |
| Prompt P2 | PowerPoint | Open `Winter-Season-Plan-Leadership.docx` as source in Copilot prompt | In Chat, attach leadership plan and ask for slide-by-slide draft |
| Prompt P3 | PowerPoint | Stay in deck generated in P2 | In Chat, paste slide list/headlines and request rewrite/reorder |
| Prompt P4 | PowerPoint | Stay in revised deck from P3 | In Chat, paste slide text and ask for notes/summary |

### Opening in Copilot Chat (10 min)

**Prompt 0.1 — Weak prompt (show limitations):**

```text
Write an update for stores about winter readiness.
```

**Prompt 0.2 — Strong prompt (goal + context + source + expectations):**

```text
You are helping a Canadian retail and auto-service organization prepare for winter tire season and holiday rush.
Goal: Draft a practical weekly update for store teams.
Context: mixed audience of service advisors, associates, and store managers. Keep Canadian tone and spelling.
Source: use realistic assumptions for scheduling, safety, staffing, and merchandising in winter.
Expectations: 250-300 words, clear headings, specific actions by role, include one customer-service reminder and one safety reminder.
```

### Copilot in Word (35 min)

**Prompt W1 — Draft weekly store bulletin from short prompt + references**

```text
Create a weekly store bulletin for Week -2 before winter tire peak.
Use these files as source context:
1) Winter-Season-Readiness-Procedure.docx
2) Store-Auto-Service-Visit-Notes.docx
Audience: stores and auto service teams.
Format: title, 5 short sections, and a “This week by role” list.
Keep it practical, specific, and in en-CA language.
```

**Prompt W2 — Rewrite for two audiences**

```text
Rewrite this bulletin in two versions:
Version A: plain, friendly language for store associates (about Grade 8 readability).
Version B: concise update for regional leadership (max 180 words, sharper executive tone).
Keep facts consistent between versions.
```

**Prompt W3 — Convert checklist to owned table**

```text
From the readiness checklist in Winter-Season-Readiness-Procedure.docx, create a table with these columns:
Checklist item | Owner | Due date | Status notes.
Infer realistic owners by role and assign due dates across Week -2 and Week -1.
Use concise action wording.
```

**Prompt W4 — Summarize and ask follow-up**

```text
Summarize Winter-Season-Readiness-Procedure.docx in 8 bullets for a new store manager.
Then ask two practical follow-up questions that clarify edge cases.
Include one about what happens when a customer misses a tire appointment.
```

### Copilot in PowerPoint (35 min)

**Prompt P1 — 5-slide store huddle deck from short prompt**

```text
Create a 5-slide store huddle deck for Week -2 winter readiness.
Audience: store associates and service advisors.
Include: priorities, booking reminders, safety reminders, merchandising actions, and today’s KPI focus.
Use concise slide headlines and 3-4 bullets per slide.
```

**Prompt P2 — Leadership update from source file**

```text
Create a leadership update deck using Winter-Season-Plan-Leadership.docx.
Build a concise update with goals, category priorities, KPI status, timeline, and top risks.
Keep an executive tone and use en-CA language.
```

**Prompt P3 — Executive rewrite + section + risks and asks + reorder**

```text
Revise the current deck:
1) Rewrite all slide headlines in an executive tone.
2) Add a section header slide before KPI content.
3) Add a final slide titled “Risks and asks”.
4) Reorder slides so the flow is: context, goals, KPI, risks, asks, timeline.
Keep slide text concise and presentation-ready.
```

**Prompt P4 — Summarize deck + speaker notes**

```text
Summarize this deck in 6 bullets for the presenter.
Then draft speaker notes for the “Risks and asks” slide (60-90 seconds spoken length).
Focus on trade-offs, decisions needed, and next-week actions.
```

## Learner chat question checkpoints

1. **After Word:** “Which prompt element improved output quality the most for you: goal, context, source, or expectations?”
2. **After PowerPoint:** “When would you ask Copilot to rewrite slide headlines vs. rewrite full slide body text?”

## Day-one habits (close)

1. Start every prompt with **goal + audience + source files + expected format**.
2. Ask Copilot to **rewrite for a specific audience** before sharing broadly.
3. End with **one validation prompt** (“What assumptions did you make?” or “What’s missing for operational use?”).

## Public research basis and assumptions

- Based on public, generic retail and auto-service seasonal operations practices in Canada (no customer-confidential inputs).
- All stores, people, records, metrics, and operational details in sample files are fictional.

## AI transparency

This repository contains AI-generated, human-reviewed demo materials. See [AI-CONTENT-DECLARATION.md](./AI-CONTENT-DECLARATION.md).

## License

MIT License. See [LICENSE](./LICENSE).
