# Positioning Analysis

Analyze how competitors position and differentiate themselves in the market.

## Instructions

### 1. Context

- Read `context/profile.json` for the user's own positioning
- If the user specified a competitor: `$ARGUMENTS` — focus on that competitor
- Otherwise, analyze all tracked competitors in `analysis/competitors/`

### 2. Research Positioning

For each competitor, analyze their **public-facing messaging**:

**Homepage and Core Pages**
- Headline / hero messaging — what's the first thing they say?
- Tagline or value proposition
- Primary call-to-action — what do they want visitors to do?
- Visual identity and brand tone (professional, casual, technical, creative)

**Who They're Targeting**
- Language that signals target audience (e.g., "for enterprises", "for freelancers")
- Case studies and customer logos — what segments?
- Pricing tiers that indicate market segments

**How They Differentiate**
- "Why us" or comparison pages
- Feature emphasis — what do they lead with?
- Claims about being the "first", "only", "fastest", "most affordable"
- Competitive positioning (do they name competitors? compare directly?)

**Content and Thought Leadership**
- Blog topics — what expertise do they claim?
- Whitepapers, guides, resources — what problems do they own?
- Social media voice and themes

**Brand Signals**
- Design quality and professionalism
- Trust signals (certifications, awards, media mentions, partner logos)
- Community engagement

### 3. Document Analysis

Create or update `analysis/landscape/positioning-analysis.md`:

```markdown
# Positioning Analysis

**Last Updated**: [DATE]

## Positioning Map

[Describe where each competitor sits — consider axes like:
  - Premium ←→ Budget
  - Specialist ←→ Generalist
  - Enterprise ←→ SMB
  - Technical ←→ Non-technical
  - Established ←→ Innovative]

## Competitor Positioning

### [Competitor Name]
**Tagline/Headline**: "[Their headline]"
**Value Proposition**: [What they promise]
**Target Audience**: [Who they're speaking to]
**Key Differentiators**: [How they stand out]
**Brand Tone**: [Professional / Casual / Technical / Bold / etc.]
**Competitive Stance**: [Do they compare themselves to others? How?]

---

[Repeat for each competitor]

## Messaging Patterns

[Common themes, overused claims, areas where everyone says the same thing]

## Positioning Gaps

[Positions no one is occupying, audiences no one is speaking to directly]

## Implications for [User's Business]

[How the user's positioning compares, where they stand out, where they blend in]
```

### 4. Present Findings

- Key positioning themes across the market
- Where the user stands relative to competitors
- Opportunities for differentiation
- Messaging suggestions based on gaps found
