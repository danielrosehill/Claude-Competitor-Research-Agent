# Add Competitor

Register a new competitor for tracking and research.

## Instructions

### 1. Gather Competitor Details

Ask the user for the following (only the name and website are required):

- **Company name** (required)
- **Website URL** (required)
- **What they do** — brief description of their product/service
- **Why they're a competitor** — direct competitor, adjacent player, emerging threat, or substitute
- **What the user already knows** about them
- **Priority** — how important is it to research this competitor? (high/medium/low)

### 2. Create Competitor Profile

Create a file at `analysis/competitors/[company-name-slugified].md`:

```markdown
# [Company Name]

**Website**: [URL]
**Type**: [direct / adjacent / emerging / substitute]
**Priority**: [high / medium / low]
**Added**: [DATE]
**Last Updated**: [DATE]

## Overview

[Brief description of what they do]

## What We Know

[User-provided information]

## Research Status

- [ ] Website reviewed
- [ ] Pricing researched
- [ ] Positioning analyzed
- [ ] Customer signals collected
- [ ] Team/size assessed
- [ ] Strengths identified
- [ ] Weaknesses identified
- [ ] Content/SEO reviewed

## Offering

_Not yet researched_

## Positioning

_Not yet researched_

## Pricing

_Not yet researched_

## Customers

_Not yet researched_

## Strengths

_Not yet researched_

## Weaknesses

_Not yet researched_

## Notes

[Any additional user-provided context]
```

### 3. Update Competitor List

Append the competitor to `inputs/competitor-list.md`. Create the file if it doesn't exist, using this format:

```markdown
# Competitor List

| Company | Website | Type | Priority | Profile |
|---------|---------|------|----------|---------|
| [Name] | [URL] | [Type] | [Priority] | [analysis/competitors/slug.md] |
```

### 4. Confirm

After creating the profile:
- Show a summary of what was added
- Suggest running `/scan [company-name]` to begin research
- Ask if there are more competitors to add
