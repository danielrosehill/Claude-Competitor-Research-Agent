# Pricing Research

Research competitor pricing, packaging, and monetization strategies using only publicly available information.

## Instructions

### 1. Context

- Read `context/profile.json` for the user's own pricing model
- Check `analysis/competitors/` for existing competitor profiles
- If the user specified a competitor: `$ARGUMENTS` — focus on that competitor

### 2. Research Pricing

For each competitor (or the specified one), research **only publicly available** pricing information:

**Direct Sources**
- Public pricing pages on their website
- Published rate cards or media kits
- Pricing mentioned in press releases or announcements
- App store listings with pricing

**Indirect Sources**
- Review sites that mention pricing (G2, Capterra)
- Comparison articles that include pricing data
- Job postings mentioning budget ranges or deal sizes (signals ACV)
- Customer reviews mentioning cost or value
- Conference talks or podcasts where pricing is discussed

**Inferred Signals**
- Pricing model type (freemium, subscription, usage-based, project-based, hourly)
- Enterprise vs. SMB focus (signals price range)
- "Contact us for pricing" vs. transparent pricing (signals positioning)
- Number of tiers and feature differentiation
- Free trial or demo availability

### 3. Document Findings

Create or update `analysis/pricing/pricing-research.md`:

```markdown
# Pricing Research

**Last Updated**: [DATE]

## Summary

[Overview of pricing patterns in this market — common models, price ranges, trends]

## Competitor Pricing

### [Competitor Name]
**Source**: [URL or "Not publicly available"]
**Confidence**: [Confirmed / Reported / Inferred]
**Model**: [Subscription / Usage / Project / Hourly / etc.]

| Tier | Price | Includes |
|------|-------|----------|

**Notes**: [Any additional context — discounts, enterprise pricing, free tier, etc.]

---

[Repeat for each competitor]

## Pricing Landscape

| Competitor | Model | Entry Price | Mid-Tier | Enterprise | Transparent? |
|-----------|-------|------------|----------|------------|--------------|

## Patterns and Insights

- [What pricing models dominate this market?]
- [Where does the user's pricing sit relative to competitors?]
- [Are there pricing opportunities or risks?]

## What We Couldn't Find

[Competitors with no public pricing and what that might signal]
```

### 4. Present Findings

Summarize:
- Which competitors have transparent pricing vs. "contact us"
- Price range in the market
- How the user's pricing compares (if they shared it during onboarding)
- Pricing strategies that seem to be working (based on review sentiment, growth signals)
- Recommendations or observations

### Important

**White Hat Reminder**: Do not submit fake quote requests, RFQs, demo requests, or contact forms to obtain pricing. If pricing is not publicly available, note that fact and document what can be inferred from indirect sources. The absence of public pricing is itself useful competitive intelligence.
