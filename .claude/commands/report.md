# Competitive Intelligence Report

Generate a formal competitive intelligence report combining all research findings.

## Instructions

### 1. Gather All Intelligence

- Read `context/profile.json` for user context and objectives
- Read `context/objectives.md` for key questions
- Load all competitor profiles from `analysis/competitors/`
- Load landscape analysis from `analysis/landscape/`
- Load pricing research from `analysis/pricing/`
- Check `outputs/` for previous reports

### 2. Determine Report Scope

If the user specified a focus: `$ARGUMENTS`

Options:
- **Full report**: Comprehensive competitive intelligence covering all tracked competitors
- **Competitor-specific**: Deep report on one competitor
- **Topic-specific**: Report focused on pricing, positioning, or a specific question

Check the user's output preferences in `profile.json` for format and audience guidance.

### 3. Generate Report

Save to `outputs/reports/competitive-intel-[DATE].md`:

```markdown
# Competitive Intelligence Report

**Prepared for**: [User/Business Name]
**Date**: [DATE]
**Scope**: [What this report covers]

---

## Executive Summary

[3-5 key takeaways. What does the user most need to know? Lead with insights, not data.]

## Your Competitive Position

[Brief assessment of where the user stands in the market, based on their profile and the research]

## Competitive Landscape

[Overview of the market, key players, and dynamics]

### Market Map

[Categorized view of competitors — direct, adjacent, emerging, substitutes]

## Competitor Profiles

### [Competitor 1 — Highest Priority]
**Overview**: [1-2 sentences]
**Positioning**: [How they present themselves]
**Strengths**: [Key advantages]
**Weaknesses**: [Vulnerabilities or gaps]
**Pricing**: [What's known]
**Threat Level**: [High / Medium / Low — with reasoning]

[Repeat for each tracked competitor]

## Pricing Landscape

[Summary of pricing patterns, the user's position, opportunities]

## Positioning Analysis

[How competitors differentiate, messaging patterns, gaps]

## Key Insights

1. [Actionable insight with supporting evidence]
2. [Actionable insight with supporting evidence]
3. [Actionable insight with supporting evidence]

## Opportunities

[Strategic opportunities identified from the research]

## Risks and Threats

[Competitive threats the user should monitor]

## Recommendations

[Specific, actionable recommendations based on the research]

## Intelligence Gaps

[What remains unknown and how it could be researched]

## Methodology

This report was compiled using publicly available information including company websites, review platforms, job postings, press releases, social media, and public filings. All research follows white-hat competitive intelligence methodology. Confidence levels are noted where claims are inferred rather than confirmed.

## Sources

[List of key sources referenced]
```

### 4. Save and Present

- Save the report to `outputs/reports/`
- Provide a concise summary to the user
- Note any caveats or limitations
- Ask if they want any section expanded or adjusted
- Remind them about output integrations if configured
