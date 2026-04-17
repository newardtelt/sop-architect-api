# SOP Architect GPT — Reference API

Static JSON reference files for the **SOP Architect GPT** — City of Rockville Department of Recreation and Parks.

These files are consumed by the ChatGPT Custom GPT via Actions. Each file contains reference content that was too large to fit in the GPT's 8,000-character instructions field.

## File Structure

```
divisions/
  recreation-services.json          — Recreation Services Division context
  recreation-facilities.json        — Recreation Facilities Division context
  parks-facilities-maintenance.json — Parks and Facilities Maintenance Division context
  senior-citizen-services.json      — Senior Citizen Services Division context
  administration.json               — Administration Division context
  cross-divisional.json             — Cross-divisional operational areas

templates/
  sop-framework.json                — Full 10-section SOP template (Format Type 1)

checklists/
  quality-check.json                — Complete quality check checklist + What Changed table

intake-questions/
  mode-a.json                       — Intake questions for Mode A (Create)
  mode-b.json                       — Intake questions for Mode B (Revise)
  mode-f.json                       — Intake questions for Mode F (Split and Restructure)

format-types/
  all-types.json                    — All five document format type definitions

numbering/
  codes.json                        — Complete SOP numbering convention and area codes

addons/
  list.json                         — Six optional add-on descriptions
```

## Base URL

`https://newardtelt.github.io/sop-architect-api/`

## Maintenance

Update the relevant JSON file when:
- Division names, roles, or cost centers change
- New facilities open or close
- Software systems change (CivicRec, ClearGov, etc.)
- New output modes or format types are added
- SOP numbering convention is expanded

Do **not** update for annual budget figures, FTE counts, staff promotions, or fiscal-year-specific data.

## Version

This reference API corresponds to **SOP Architect GPT v2.4**.
