# DEMO-INSTRUCTIONS — Winter Readiness (Word + PowerPoint)

**Classification: Public**  
**Fictional Company:** MapleWheel Retail Group  
**Tool focus:** Microsoft 365 Copilot Chat, Copilot in Word, Copilot in PowerPoint (no agents)

This demo uses a fictional Microsoft Fake Company created for demonstration purposes. Any resemblance to real organizations, people, products, services, or data is coincidental. Do not use customer confidential information in this package.

## 1) Demo title

90-minute Microsoft 365 Copilot demo: winter tire changeover + holiday readiness for stores and Auto Service Centres.

## 2) Scenario

Head office is coordinating stores and Auto Service Centres for winter demand peaks and holiday traffic. You will show how Copilot helps draft operations content quickly, adapt tone for different audiences, and turn planning material into briefing slides.

## 3) Demo tool and mode

- **Opening (10 min):** Copilot Chat prompting basics.
- **Word segment (35 min):** drafting, rewrite, table creation, summarization.
- **PowerPoint segment (35 min):** deck generation, executive rewrite, slide management, speaker notes.
- **Close (10 min):** learner Q&A checkpoint + day-one habits.

## 4) Files to attach (execution order)

1. `demo/sample-data/Winter-Season-Readiness-Procedure.docx`
2. `demo/sample-data/Store-Auto-Service-Visit-Notes.docx`
3. `demo/sample-data/Winter-Season-Plan-Leadership.docx`
4. `demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx`

## 5) Prompts

### Opening in Copilot Chat (10 min)

#### Prompt 0.1 (weak)

**Exact prompt text:**

```text
Write an update for stores about winter readiness.
```

**Sources/files used:** none  
**Required result format:** short update  
**Acceptance criteria:** output is generic enough to discuss weaknesses  
**Next handoff:** compare with stronger prompt  
**Expected output:** broad update with missing specificity

#### Prompt 0.2 (strong)

**Exact prompt text:**

```text
You are helping a Canadian retail and auto-service organization prepare for winter tire season and holiday rush.
Goal: Draft a practical weekly update for store teams.
Context: mixed audience of service advisors, associates, and store managers. Keep Canadian tone and spelling.
Source: use realistic assumptions for scheduling, safety, staffing, and merchandising in winter.
Expectations: 250-300 words, clear headings, specific actions by role, include one customer-service reminder and one safety reminder.
```

**Sources/files used:** realistic assumptions only  
**Required result format:** 250-300 words with headings and role actions  
**Acceptance criteria:** clear, role-based, action-ready, Canadian spelling  
**Next handoff:** point to Prompt Coach + prompt gallery  
**Expected output:** structured operational update ready for editing

---

### Word demos (35 min)

#### Prompt W1 — Weekly bulletin from short prompt + file references

**Exact prompt text:**

```text
Create a weekly store bulletin for Week -2 before winter tire peak.
Use these files as source context:
1) Winter-Season-Readiness-Procedure.docx
2) Store-Auto-Service-Visit-Notes.docx
Audience: stores and auto service teams.
Format: title, 5 short sections, and a “This week by role” list.
Keep it practical, specific, and in en-CA language.
```

**Sources/files used:** Procedure + Visit notes  
**Required result format:** title + 5 sections + role list  
**Acceptance criteria:** references both files; practical weekly actions; en-CA language  
**Next handoff:** rewrite for two audience levels  
**Expected output:** operational bulletin draft suitable for store communications

#### Prompt W2 — Rewrite by audience

**Exact prompt text:**

```text
Rewrite this bulletin in two versions:
Version A: plain, friendly language for store associates (about Grade 8 readability).
Version B: concise update for regional leadership (max 180 words, sharper executive tone).
Keep facts consistent between versions.
```

**Sources/files used:** W1 output  
**Required result format:** two clearly labelled versions  
**Acceptance criteria:** simpler associate version + concise executive version; facts unchanged  
**Next handoff:** convert checklist to table  
**Expected output:** audience-tailored variants

#### Prompt W3 — Readiness checklist table

**Exact prompt text:**

```text
From the readiness checklist in Winter-Season-Readiness-Procedure.docx, create a table with these columns:
Checklist item | Owner | Due date | Status notes.
Infer realistic owners by role and assign due dates across Week -2 and Week -1.
Use concise action wording.
```

**Sources/files used:** Procedure checklist section  
**Required result format:** table with four required columns  
**Acceptance criteria:** all checklist rows mapped to owner + due date; concise action text  
**Next handoff:** summarize and ask follow-up questions  
**Expected output:** ownership-ready tracking table

#### Prompt W4 — Summary and follow-up questions

**Exact prompt text:**

```text
Summarize Winter-Season-Readiness-Procedure.docx in 8 bullets for a new store manager.
Then ask two practical follow-up questions that clarify edge cases.
Include one about what happens when a customer misses a tire appointment.
```

**Sources/files used:** Procedure  
**Required result format:** 8 bullets + 2 follow-up questions  
**Acceptance criteria:** practical manager summary; includes missed-appointment edge case question  
**Next handoff:** move to PowerPoint creation  
**Expected output:** concise brief with open decision points

---

### PowerPoint demos (35 min)

#### Prompt P1 — 5-slide store huddle deck

**Exact prompt text:**

```text
Create a 5-slide store huddle deck for Week -2 winter readiness.
Audience: store associates and service advisors.
Include: priorities, booking reminders, safety reminders, merchandising actions, and today’s KPI focus.
Use concise slide headlines and 3-4 bullets per slide.
```

**Sources/files used:** existing operational context  
**Required result format:** 5-slide huddle deck  
**Acceptance criteria:** all five content requirements included; concise slide structure  
**Next handoff:** leadership update from plan file  
**Expected output:** practical huddle presentation

#### Prompt P2 — Leadership update from source file

**Exact prompt text:**

```text
Create a leadership update deck using Winter-Season-Plan-Leadership.docx.
Build a concise update with goals, category priorities, KPI status, timeline, and top risks.
Keep an executive tone and use en-CA language.
```

**Sources/files used:** Leadership plan docx  
**Required result format:** concise executive update deck  
**Acceptance criteria:** includes goals, priorities, KPIs, timeline, risks; executive tone  
**Next handoff:** rewrite headlines and adjust structure  
**Expected output:** leadership brief draft deck

#### Prompt P3 — Executive rewrite + structural edits

**Exact prompt text:**

```text
Revise the current deck:
1) Rewrite all slide headlines in an executive tone.
2) Add a section header slide before KPI content.
3) Add a final slide titled “Risks and asks”.
4) Reorder slides so the flow is: context, goals, KPI, risks, asks, timeline.
Keep slide text concise and presentation-ready.
```

**Sources/files used:** P2 deck  
**Required result format:** revised and reordered deck  
**Acceptance criteria:** all four operations completed in-order  
**Next handoff:** summarize + speaker notes  
**Expected output:** polished leadership flow

#### Prompt P4 — Deck summary + speaker notes

**Exact prompt text:**

```text
Summarize this deck in 6 bullets for the presenter.
Then draft speaker notes for the “Risks and asks” slide (60-90 seconds spoken length).
Focus on trade-offs, decisions needed, and next-week actions.
```

**Sources/files used:** revised deck from P3  
**Required result format:** 6 bullets + one set of speaker notes  
**Acceptance criteria:** decision-focused summary; clear 60-90 second talk track  
**Next handoff:** close + habits  
**Expected output:** presenter-ready speaking support

## 6) Build/configure notes

- Optional: open `MapleWheel-Branded-PowerPoint-Template.pptx` and apply its visual style as a baseline.
- Keep locale conventions to Canadian spelling, CAD, and metric values.

## 7) Test and validate

- Ensure each output references the requested source files.
- Ensure audience rewrite clearly changes tone while preserving facts.
- Ensure PowerPoint structural operations (insert slide + reorder) are explicitly visible.

## 8) Cleanup

- Remove any accidental real customer references from prompts or outputs before sharing.

## Learner check questions

- After Word: “Which part of prompt framing changed quality most: goal, context, source, or expectations?”
- After PowerPoint: “When is headline rewrite enough, and when should you regenerate full slides?”

## Day-one habits (close)

1. Lead with goal + audience + files + format.
2. Use audience rewrites before distribution.
3. End with a validation question to expose assumptions.
