# Copilot Follow-Along Lab (Word + PowerPoint)

**Classification: Public**

This package is now a **follow-along** demo flow that works in standard commercial Microsoft 365 Copilot environments.

## What changed

1. Instructions now focus on **in-file follow-along actions** first.
2. Every prompt has a clear execution location (Word/PPT/Chat + file).
3. Added shared Excel file for **Analyst chart creation** and downstream Word/PPT use.
4. Kept the **template-based PowerPoint path** with `MapleWheel-Branded-PowerPoint-Template.pptx`.

## Core files

| Path | Purpose |
|---|---|
| [index.html](./index.html) | Single-page runbook with all prompts and prep |
| [demo/DEMO-INSTRUCTIONS.md](./demo/DEMO-INSTRUCTIONS.md) | Presenter script in markdown |
| [demo/sample-data/Winter-Season-Readiness-Procedure.docx](./demo/sample-data/Winter-Season-Readiness-Procedure.docx) | Word source doc |
| [demo/sample-data/Store-Auto-Service-Visit-Notes.docx](./demo/sample-data/Store-Auto-Service-Visit-Notes.docx) | Word source doc |
| [demo/sample-data/Winter-Season-Plan-Leadership.docx](./demo/sample-data/Winter-Season-Plan-Leadership.docx) | Word source doc for leadership narrative |
| [demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx](./demo/sample-data/MapleWheel-Branded-PowerPoint-Template.pptx) | Branded PPT template (keep/use) |
| [demo/sample-data/shared/Canada-Wide-Winter-Tire-Sales-Weather-2023-2026.xlsx](./demo/sample-data/shared/Canada-Wide-Winter-Tire-Sales-Weather-2023-2026.xlsx) | Analyst/Copilot chart source |
| [demo/sample-data/shared/Analyst-to-Outlook-Teams-Workflow.md](./demo/sample-data/shared/Analyst-to-Outlook-Teams-Workflow.md) | Analyst chart workflow reference |

## Follow-along flow (high level)

1. Build one or two chart visuals from the shared Excel file.
2. Edit Word docs directly in file with Copilot in Word.
3. Run equivalent doc-grounded prompts in Copilot Chat (alternative path).
4. Create a PowerPoint outline from Chat.
5. Open the branded PPTX template and build/refine slides inside PowerPoint.

## Published links

- Repository: https://github.com/AndrewConniff/word-pptx-tire
- GitHub Pages: https://andrewconniff.github.io/word-pptx-tire/
- Runbook page: https://andrewconniff.github.io/word-pptx-tire/index.html

This demo uses fictional sample content only. Do not add customer-confidential content.
