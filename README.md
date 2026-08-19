
# The AI Blueprint

An AI literacy hub and resource center for enterprise teams to discover, learn, and apply AI tools effectively and responsibly.

## Overview

The AI Blueprint is a centralized knowledge platform designed to help employees across all departments discover and leverage AI tools, agents, and prompt templates. It provides curated recommendations, ready-to-use prompts, and best practices for responsible AI adoption in the enterprise.

**Live:** https://ailiteracyy.netlify.app/

## Features

### 🤖 AI Agents Directory
A curated selection of 10+ recommended AI tools organized by use case:
- **Research & Analysis:** Perplexity AI, Claude by Anthropic
- **Content Creation:** Gamma App (presentations), HeyGen (video)
- **Code & Engineering:** GitHub Copilot
- **Automation:** Zapier AI, Otter.ai (meeting transcription)
- **Design:** Canva AI, Runway
- **Legal & Compliance:** Harvey AI
- Plus tool introductions, direct links, and feature highlights

### 📋 Prompt Library
50+ production-ready prompt templates organized by function:
- **QA:** Test matrices, bug reports, release test plans, RCA
- **HR:** Onboarding plans, feedback, interviews, recruitment
- **Operations:** Meeting minutes, SOPs, escalation responses, email drafts
- **Finance & Reporting:** Dashboards, executive summaries, data insights
- **Engineering:** Technical specs, release notes, code reviews
- **Communications:** Professional emails, business cases, client diplomacy
- **Presentations & Content:** Slide planning, branded decks, marketing copy

Each prompt includes:
- Templated input fields (customizable for your use case)
- Copy-to-clipboard functionality
- Links to recommended AI tools
- Usage tips and best practices

### 🎨 Featured Use Case: Branded Presentations
Full Gamma AI prompt with Intertek brand guidelines built in:
- Color palette (charcoal, yellow, teal)
- Typography standards (Calibri, sizing)
- Logo placement and styling
- Slide layout variety
- One-click generation

### ⚠️ Enterprise Security
Built-in security warnings emphasizing responsible AI usage:
- Never share confidential data, source code, or proprietary specifications with public AI tools
- Always verify technical results independently
- Guidance for compliance and risk management

## Use Cases

- **Onboarding:** Help new employees discover enterprise-approved AI tools
- **Training:** AI literacy workshops and educational resources
- **Workflow Acceleration:** Copy-paste prompts for common business tasks
- **Standardization:** Enterprise-branded templates and branding guidelines
- **Governance:** Recommended tools with transparency on capabilities and limitations

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Deployment:** Netlify
- **CMS:** Static site (editable via version control)

## Getting Started

### Local Development

```bash
git clone https://github.com/your-org/ai-blueprint.git
cd ai-blueprint
# Open index.html in your browser or run a local server:
python -m http.server 8000
```

### Deployment

The site is deployed on Netlify. To deploy changes:
1. Push to the main branch
2. Netlify automatically rebuilds and deploys

## Project Structure

```
/
├── index.html          # Main application
├── styles/             # CSS stylesheets
├── scripts/            # JavaScript logic (search, filtering)
├── assets/             # Images, logos, branding
└── README.md          # This file
```

## Contributing

Contributions welcome! To add a new prompt or AI agent:
1. Create a feature branch: `git checkout -b add-new-prompt`
2. Update the relevant section in `index.html` or data file
3. Test locally
4. Submit a pull request with a brief description

### Adding a Prompt
Include:
- Prompt title and category
- Template with `[==Your Input Here==]` placeholders
- Copy button functionality
- Link to recommended tool(s)

### Adding an AI Agent
Include:
- Tool name and icon
- One-sentence description
- Use-case tags
- Direct link to tool
- Intro video (if available)

## Security & Compliance

This tool emphasizes responsible AI adoption:
- ⚠️ **No confidential data sharing** with external AI services
- ✓ **Independent verification** of AI outputs
- ✓ **Enterprise compliance** in prompt templates
- ✓ **Approved tool recommendations** only

## Roadmap

- [ ] Role-based prompt recommendations
- [ ] Team-specific branding templates
- [ ] Prompt effectiveness ratings and feedback
- [ ] Integration with internal knowledge base
- [ ] Mobile-optimized design
- [ ] Dark mode
- [ ] Multi-language support



**Version:** 1.0  
**Last Updated:** August 2026  
**Maintained by:** Intertek Digital Innovation
