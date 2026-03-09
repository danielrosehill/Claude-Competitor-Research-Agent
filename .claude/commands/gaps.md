# Intelligence Gaps

Identify what's missing from the competitive research and suggest how to fill the gaps.

## Instructions

### 1. Audit Current Intelligence

- Read `context/profile.json` and `context/objectives.md`
- Review all profiles in `analysis/competitors/`
- Check research status checklists in each competitor profile
- Review `analysis/pricing/` and `analysis/landscape/`
- Cross-reference against the user's stated objectives and key questions

### 2. Identify Gaps

Analyze across several dimensions:

**Coverage Gaps**
- Are there competitors the user mentioned but haven't been researched?
- Are there competitor types (direct, adjacent, emerging, substitutes) with no entries?
- Has the landscape analysis been done?

**Depth Gaps**
- Which competitor profiles have incomplete sections?
- Is pricing data missing for key competitors?
- Are there competitors with only surface-level research?

**Objective Gaps**
- Which of the user's key questions (from objectives.md) remain unanswered?
- Are there research objectives that no current analysis addresses?

**Freshness Gaps**
- Which profiles haven't been updated recently?
- Is the landscape overview outdated?

**Blind Spots**
- Are there categories of information not being tracked at all?
- Are there market dynamics not captured in any analysis?

### 3. Create Gaps Report

Save to `analysis/landscape/intelligence-gaps.md`:

```markdown
# Intelligence Gaps Report

**Generated**: [DATE]

## Summary

[X] of [Y] research objectives addressed
[X] of [Y] competitors fully profiled
[Key gaps in 1-2 sentences]

## Coverage Gaps

| Gap | Impact | Suggested Action |
|-----|--------|-----------------|

## Depth Gaps

| Competitor | Missing Sections | Priority |
|-----------|-----------------|----------|

## Unanswered Questions

| Question (from objectives) | Status | Blocker |
|---------------------------|--------|---------|

## Freshness Issues

| Item | Last Updated | Recommended |
|------|-------------|-------------|

## Recommended Research Plan

1. [Highest priority action]
2. [Next priority]
3. [...]

## Ethical Boundaries

[Note any gaps that cannot be filled via white-hat methods, and explain why. Suggest the closest ethical alternative where possible.]
```

### 4. Present to User

- Summarize the most critical gaps
- Propose a prioritized research plan
- Ask if priorities should be adjusted
