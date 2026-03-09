# Research Status

Review the current state of competitive intelligence research.

## Instructions

### 1. Gather State

- Read `context/profile.json` for user context
- Read `context/objectives.md` for research objectives
- List all files in `analysis/competitors/` — count and read each
- Check `analysis/landscape/` for landscape and positioning analyses
- Check `analysis/pricing/` for pricing research
- Check `outputs/` for generated reports and comparisons
- Check `inputs/` for user-provided materials

### 2. Assess Research Status

For each competitor profile, check the Research Status checklist and determine:
- How many items are completed vs. outstanding
- When the profile was last updated

For objectives, check which key questions have been addressed in the analysis files.

### 3. Present Status Dashboard

```
Competitor Research Status
══════════════════════════

Business:       [NAME]
Industry:       [INDUSTRY]
Onboarded:      [DATE]

Competitors Tracked: [X]
  ✓ Fully profiled:  [X]
  ◐ Partially:       [X]
  ○ Not started:     [X]

Research Objectives: [X] of [Y] addressed

Analyses:
  Landscape:    [Complete / Partial / Not started]
  Pricing:      [Complete / Partial / Not started]
  Positioning:  [Complete / Partial / Not started]

Reports Generated: [X]
Last Report:       [DATE or "None yet"]

Competitor Summary:
  [Name]          [██████░░░░] 60%  Priority: High
  [Name]          [████████░░] 80%  Priority: Medium
  [Name]          [██░░░░░░░░] 20%  Priority: Low

Suggested Next Actions:
1. [Most impactful action based on gaps and priorities]
2. [Second action]
3. [Third action]
```

### 4. Recommendations

Based on the current state, suggest the most impactful next steps:
- If competitor profiles are sparse → suggest `/scan`
- If no landscape analysis → suggest `/landscape`
- If pricing is missing → suggest `/pricing`
- If objectives are unaddressed → suggest specific research
- If research is comprehensive → suggest `/report`
