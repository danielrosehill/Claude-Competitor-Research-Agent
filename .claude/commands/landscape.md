# Competitive Landscape Overview

Generate a high-level overview of the user's competitive landscape.

## Instructions

### 1. Gather Context

- Read `context/profile.json` to understand the user's business, industry, and objectives
- Read `context/objectives.md` for research priorities
- Check `inputs/` for any user-provided competitor lists or materials
- Review any existing profiles in `analysis/competitors/`

### 2. Research the Landscape

If existing competitor profiles are sparse, use WebSearch to:
- Search for competitors in the user's industry and market segment
- Look for industry landscape articles, analyst reports, and "alternatives to [user's product]" content
- Identify market categories the user falls into
- Find competitors the user may not have listed

### 3. Create Landscape Analysis

Create or update `analysis/landscape/landscape-overview.md`:

```markdown
# Competitive Landscape: [Industry/Market]

**Generated**: [DATE]
**Based on**: [NUMBER] tracked competitors

## Market Overview

[2-3 paragraphs describing the competitive landscape, key trends, and dynamics]

## Competitor Map

### Direct Competitors
[Companies offering similar products/services to similar customers]

| Company | Focus | Size/Stage | Key Differentiator |
|---------|-------|------------|-------------------|

### Adjacent Players
[Companies in related markets that could compete or already partially overlap]

| Company | Overlap Area | Threat Level |
|---------|-------------|--------------|

### Emerging Threats
[Newer entrants or companies showing signs of moving into this space]

| Company | Signal | Timeline |
|---------|--------|----------|

### Substitutes
[Alternative approaches customers might use instead]

| Alternative | Why Customers Choose It |
|-------------|----------------------|

## Positioning Map

[Describe where competitors cluster in terms of positioning — e.g., premium vs. budget, specialist vs. generalist, enterprise vs. SMB]

## Key Trends

1. [Trend and its implications]
2. [Trend and its implications]
3. [Trend and its implications]

## Opportunities

[Gaps in the market, underserved segments, or positioning opportunities]

## Threats

[Competitive dynamics that could affect the user's business]

## Intelligence Gaps

[What we don't know yet and how to find out]
```

### 4. Register New Competitors

If the research surfaces competitors not yet tracked:
- Ask the user if they want to add them
- Create profiles for approved additions

### 5. Present to User

Provide a concise summary with:
- How many competitors were identified across each category
- The most notable findings
- Suggested next actions (which competitors to scan deeper, which gaps to fill)
