# DEMO-INSTRUCTIONS — Follow-Along (Word + PowerPoint)

**Classification: Public**  
**Fictional Company:** MapleWheel Retail Group

## Demo goal

Show a follow-along workflow where participants:
1. generate chart visuals from the shared Excel file,
2. edit provided Word docs in-file and via Chat,
3. create a PowerPoint from Chat,
4. refine slides inside the branded PPTX template.

## Files to open

1. `demo/sample-data/shared/Canada-Wide-Winter-Tire-Sales-Weather-2023-2026.xlsx`
2. `demo/sample-data/Winter-Season-Readiness-Procedure.docx`
3. `demo/sample-data/Store-Auto-Service-Visit-Notes.docx`
4. `demo/sample-data/Winter-Season-Plan-Leadership.docx`
5. `demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx`

## Follow-along run order

### A) Build visuals from Excel (Analyst/Copilot in Excel)

**Where this happens:** Excel, workbook `Canada-Wide-Winter-Tire-Sales-Weather-2023-2026.xlsx`.

Prompt A1:
```text
Create a chart comparing weekly Winter Tire Sales (CAD) and Snowfall (cm) by region.
Use a layout that is easy to explain in 60 seconds.
```

Prompt A2:
```text
Summarize 3 insights from this chart that matter for store and auto service readiness.
```

Save or copy one chart image for Word/PPT use.

### B) Edit in Word (in-file path)

**Where this happens:** Word, file `Winter-Season-Readiness-Procedure.docx`.

Prompt W1:
```text
Rewrite the opening section in plain, friendly language for store associates.
Keep all actions and dates intact.
```

**Where this happens:** Word, file `Store-Auto-Service-Visit-Notes.docx`.

Prompt W2:
```text
Convert key follow-ups into a table with:
Store | Issue | Owner role | Due date | Escalation needed.
```

### C) Edit using Copilot Chat (doc-grounded alternative)

**Where this happens:** Copilot Chat with docx files attached.

Prompt C1:
```text
Using Winter-Season-Readiness-Procedure.docx and Store-Auto-Service-Visit-Notes.docx,
draft a one-page weekly operations bulletin for stores and service teams.
Include 5 priority actions and 3 risks.
```

Prompt C2:
```text
Rewrite this bulletin for regional leadership in 6 concise bullets with owner/date actions.
```

### D) Create PowerPoint from Chat

**Where this happens:** Copilot Chat with these files attached:
`Winter-Season-Plan-Leadership.docx` + your chart insight text from section A.

Prompt D1:
```text
Create a 7-slide leadership deck outline with:
Context, trend insight, readiness actions, risks, asks, and next-week timeline.
Use executive tone and concise slide headlines.
```

### E) Build/refine slides inside PPT template

**Where this happens:** PowerPoint with `MapleWheel-Branded-PowerPoint-Template.pptx` open.

Prompt P1:
```text
Using this outline, create slides in this deck using the current template style.
Keep each slide to one headline and 3-4 bullets.
```

Prompt P2:
```text
Add one slide titled "Risks and asks" and one slide titled "Decisions needed this week".
Then reorder slides for this flow:
Context -> Trends -> Actions -> Risks -> Decisions -> Timeline.
```

Prompt P3:
```text
Draft speaker notes for the "Trends" slide and "Risks and asks" slide (60-90 seconds each).
```

## Close (learner follow-along)

1. Ask learners to run one in-file Word prompt and one Chat-grounded prompt.
2. Ask learners to choose template-first vs Chat-first PPT creation for their own use case.
