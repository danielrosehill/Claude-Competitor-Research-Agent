# Competitor Comparison

Generate a side-by-side comparison of specific competitors.

## Instructions

### 1. Identify Competitors to Compare

If specified: `$ARGUMENTS` (may be a comma-separated list of competitor names)

- If not specified, ask the user which competitors to compare (suggest from tracked list)
- Read `context/profile.json` — include the user's own business in the comparison if appropriate
- Load existing profiles from `analysis/competitors/`

### 2. Build Comparison

Research or reference existing data to compare across these dimensions:

| Dimension | What to Compare |
|-----------|----------------|
| Overview | Company size, stage, founding year, location |
| Offering | Products/services, key features, scope |
| Target Market | Who they serve, segments, verticals |
| Positioning | Value proposition, brand tone, key claims |
| Pricing | Model, published prices, tiers |
| Strengths | What they do well, competitive advantages |
| Weaknesses | Gaps, complaints, limitations |
| Traction | Funding, team size, growth signals, customer count |
| Content | Blog activity, thought leadership, SEO focus |
| Reviews | Average ratings, common praise, common complaints |

### 3. Create Comparison Document

Save to `outputs/comparisons/[competitor-names]-comparison.md`:

```markdown
# Comparison: [Company A] vs [Company B] vs [Company C]

**Generated**: [DATE]

## At a Glance

| | [Company A] | [Company B] | [Company C] |
|---|---|---|---|
| Founded | | | |
| Size | | | |
| Target Market | | | |
| Pricing Model | | | |
| Key Strength | | | |
| Key Weakness | | | |

## Detailed Comparison

### Offering
[What each company offers and how they differ]

### Positioning
[How each company messages and differentiates]

### Pricing
[Pricing comparison — note what's confirmed vs. inferred]

### Customer Signals
[Reviews, case studies, testimonials for each]

### Strengths and Weaknesses
[Side-by-side assessment]

## Key Differences

[The 3-5 most important differences between these competitors]

## Implications

[What this comparison means for the user's strategy — reference their profile]

## Confidence Notes

[Which data points are confirmed, reported, or inferred]
```

### 4. Present Summary

- Highlight the most important differences
- Note which competitor appears strongest in each dimension
- Flag areas where more research is needed
