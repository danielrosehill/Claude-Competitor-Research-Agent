# Competitor Scan

Conduct deep-dive research on a specific competitor using only publicly available sources.

## Instructions

### 1. Identify the Target

If the user specified a competitor: `$ARGUMENTS`

- Check `analysis/competitors/` for an existing profile
- Check `context/profile.json` to understand the user's business and what comparisons matter
- If no profile exists, ask for the company name and website, then create one via the add-competitor workflow

### 2. Conduct Research

Use WebSearch and WebFetch to research the competitor across these dimensions. **Respect Guideline One: White Hat** — only access publicly available information.

**Website Analysis**
- Visit the company website and analyze:
  - Homepage messaging and value proposition
  - Product/service pages — what do they offer?
  - Pricing page (if public) — tiers, models, specific numbers
  - About page — team size, founding story, mission
  - Case studies or testimonials — who are their customers?
  - Blog/content — what topics do they write about?

**Public Profiles and Directories**
- Search for the company on:
  - LinkedIn (company page, employee count, recent hires)
  - Crunchbase (funding, investors, revenue estimates)
  - G2, Capterra, or relevant review platforms
  - Glassdoor (employee count, culture signals)
  - Industry directories

**Media and Community**
- Search for:
  - News articles and press releases
  - Podcast appearances or conference talks
  - Social media presence and engagement
  - Forum discussions or Reddit mentions
  - Industry analyst mentions

**Competitive Signals**
- Look for:
  - Job postings (what roles are they hiring for? signals growth areas)
  - Partnership announcements
  - Product launches or feature updates
  - Customer wins or losses mentioned publicly

### 3. Update the Competitor Profile

Update the profile in `analysis/competitors/[company-name].md` with all findings:

- Fill in each section with researched data
- Mark confidence levels for each claim (Confirmed / Reported / Inferred / Unverified)
- Cite sources with URLs
- Check off completed research items in the Research Status checklist
- Note the date of the scan

### 4. Identify Gaps

After completing the scan, note:
- What information was not publicly available (e.g., pricing not listed)
- What areas need further research
- Any surprising or notable findings

### 5. Present Summary

Provide the user with a concise summary:
- Key findings (3-5 bullet points)
- How this competitor compares to the user's business (reference `context/profile.json`)
- Notable strengths and weaknesses
- Intelligence gaps that remain
- Suggested next steps

### Research Guidelines

- **Do**: Visit public websites, read reviews, check job boards, read press releases
- **Do**: Draw inferences from public data (e.g., "10 job postings for engineers suggests product investment")
- **Don't**: Submit fake demo requests, impersonate anyone, scrape behind login walls
- **Don't**: Present inferences as confirmed facts — always label confidence level
- **Do**: Note when information may be outdated and suggest re-scanning
