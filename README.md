# Competitor Research Agent

A Claude Code space for systematic competitive intelligence research using white-hat methodology.

## What This Is

A ready-to-use Claude Code workspace for researching your competitive landscape. It helps consultants, startups, and businesses understand how competitors position themselves, what they charge, and where opportunities exist — using only publicly available information.

## Quick Start

1. Clone this repo
2. Open with Claude Code: `claude` in the project directory
3. Run `/onboard` to set up your profile and research objectives
4. Add competitors with `/add-competitor` or drop a list into `inputs/`
5. Run `/scan`, `/pricing`, `/positioning` to research
6. Run `/report` to generate a competitive intelligence report

## Commands

| Command | Purpose |
|---------|---------|
| `/onboard` | Set up your profile, business context, and research objectives |
| `/add-competitor` | Register a new competitor for tracking |
| `/scan` | Deep-dive research on a specific competitor |
| `/landscape` | Generate competitive landscape overview |
| `/pricing` | Research competitor pricing and packaging |
| `/positioning` | Analyze how competitors position and differentiate |
| `/compare` | Side-by-side comparison of specific competitors |
| `/gaps` | Identify intelligence gaps and suggest research directions |
| `/report` | Generate formal competitive intelligence report |
| `/status` | Review current state of research |

## White-Hat Methodology

All research uses only publicly available sources: company websites, review platforms, job postings, press releases, social media, and public filings. This agent will never submit fake requests, impersonate anyone, or access non-public information.

## Structure

```
context/          Your profile and research configuration
inputs/           Competitor lists and reference materials you provide
analysis/         Working research (competitor profiles, pricing, landscape)
outputs/          Finished reports, comparisons, and summaries
.claude/commands/ Slash commands powering the workflow
```

## Who It's For

- **Consultants** researching how peers present and price services
- **Startups** mapping the competitive landscape before market entry
- **Businesses** monitoring competitor positioning and strategy
- **Agencies** conducting competitive research for clients
