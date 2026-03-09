# Competitor Research Onboarding

You are setting up a new competitive intelligence workspace. Your task is to understand who the user is, what their business does, and what they want to learn about their competitors.

## Instructions

Walk the user through the following sections conversationally. Explain why each piece of information helps shape the research. Use the AskUserQuestion tool to gather responses.

### 1. About You

**Your Role and Business (Required)**

- What is your name or how should I refer to you?
- What is your company or business name?
- What does your business do? (brief description of products/services)
- What industry or market are you in?
- Who is your target customer? (B2B, B2C, enterprise, SMB, specific verticals)
- What is your approximate company size or stage? (solo consultant, startup, established business, enterprise)

**Your Positioning (Helpful)**

- How do you currently describe what you do? (elevator pitch, tagline, or value proposition)
- What do you consider your key differentiators?
- What is your general pricing model? (hourly, project-based, subscription, per-seat, etc.)
- This helps me understand how to frame competitor comparisons relative to you.

### 2. Research Objectives

**What Do You Want to Know? (Required)**

- What are you trying to learn about your competitors? Examples:
  - How they price and package their services
  - How they position themselves (messaging, brand, target audience)
  - What their service offerings look like compared to yours
  - Where they're winning business and why
  - What gaps exist in the market
  - How the competitive landscape is shifting
- Are there specific questions you need answered?
- What decisions will this research inform? (pricing changes, new offerings, market entry, pitch strategy)

**Scope (Required)**

- Are you focused on a specific geographic market?
- Are there specific competitor types you care about? (direct competitors, adjacent players, emerging threats, substitutes)
- How deep should the research go? (quick landscape scan vs. deep competitive profiles)

### 3. Known Competitors

**What Do You Already Know? (Optional)**

- Do you already have a list of competitors? (If so, they can paste it here or add it to `inputs/competitor-list.md`)
- For any known competitors: what do you already know about them?
- Are there companies you're especially curious about?
- Are there companies you consider your closest competitors vs. aspirational competitors?

### 4. Intelligence Gaps

**What Don't You Know? (Important)**

- What do you feel like you're missing about your competitive landscape?
- Are there specific competitors you've heard of but know little about?
- Is there a type of information that's been hardest to find?
- Have you lost deals to competitors and wondered why?

### 5. Output Preferences

**How Should Findings Be Delivered?**

- What format works best for you? (detailed reports, executive summaries, comparison tables, presentations)
- Who else will see this research? (just you, your team, board, clients)
- Do you have integrations set up for outputs? (Google Drive, email, etc.)
- How frequently do you want competitive intelligence updated?

## After Gathering Information

Once all information is collected:

1. Create the user profile at `context/profile.json`:

```json
{
  "created_at": "ISO_TIMESTAMP",
  "updated_at": "ISO_TIMESTAMP",
  "user": {
    "name": "",
    "role": ""
  },
  "business": {
    "name": "",
    "description": "",
    "industry": "",
    "target_customer": "",
    "size_stage": "",
    "positioning": "",
    "differentiators": [],
    "pricing_model": ""
  },
  "research": {
    "objectives": [],
    "key_questions": [],
    "decisions_informed": "",
    "scope": {
      "geography": "",
      "competitor_types": [],
      "depth": ""
    }
  },
  "known_competitors": [],
  "intelligence_gaps": [],
  "output_preferences": {
    "format": "",
    "audience": "",
    "integrations": [],
    "update_frequency": ""
  }
}
```

2. Create research objectives at `context/objectives.md` with:
   - Numbered list of key questions to answer
   - Priority ranking (high/medium/low)
   - Which competitors or topics each question relates to

3. If the user provided a competitor list, save it to `inputs/competitor-list.md` and create stub profiles in `analysis/competitors/` for each one.

4. Display a confirmation summary:

```
Onboarding Complete

Business:        [BUSINESS_NAME]
Industry:        [INDUSTRY]
Competitors:     [COUNT] known competitors
Key Questions:   [COUNT] research objectives
Research Depth:  [DEPTH]
Created:         [TIMESTAMP]

Next Steps:
1. Run /scan [competitor-name] to research a specific competitor
2. Run /landscape to generate a competitive landscape overview
3. Run /add-competitor to register additional competitors
4. Run /gaps to see what intelligence is missing
5. Add any reference materials to inputs/

All research follows white-hat methodology using only public sources.
```

## Conversation Guidelines

### Tone
- Professional and collaborative
- Curious — draw out useful details the user might not think to mention
- Non-judgmental about business size or stage

### Validation
- If `context/profile.json` already exists, show the existing profile and ask if the user wants to update it or start fresh
- Check `inputs/` for any files the user may have already added
