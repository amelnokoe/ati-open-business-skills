# ATI Open Business Skills: VendorGenius

**A free, open-source AI skill for vendors, online sellers, and small-business owners.**

VendorGenius helps people create accurate product listings, sales captions, customer replies, content plans, respectful follow-ups, and practical online-selling workflows.

**Built by Aetheris Tech & Innovation (ATI).**

> Sell Smarter. Manage Better. Grow Together.

## Project status

**Version:** 0.2.0  
**Status:** Public preview candidate — testing and platform verification required  
**Licence:** MIT

This repository contains the VendorGenius skill itself. It is an instruction package for compatible AI agents, not a standalone chatbot, website, mobile app, or automated sales system.

## What VendorGenius can help with

- Product descriptions and online listings
- WhatsApp, Facebook, Instagram, and TikTok sales copy
- Customer questions, complaints, and price objections
- Realistic content calendars
- Respectful inquiry follow-ups and customer retention
- Reviewing the steps from product discovery to fulfilment

It is designed with African small businesses in mind but does not assume every user is in Ghana or uses the same currency, language, payment method, or sales channel.

## Quick start

1. Download this repository or the ZIP release.
2. Read `SKILL.md`.
3. Install the skill using the instructions for your AI environment below.
4. Give the agent accurate information about your product, customer, platform, and goal.
5. Review all generated details before publishing or sending them.

### Example prompt

> I sell handmade sandals in Ghana. Write three WhatsApp Status messages. Use only these facts: leather upper, sizes 38–44, price GH₵180, and orders by WhatsApp DM. Do not invent any other product claims.

## Compatibility and installation

Agent Skills is an open format, but each AI product has its own supported surfaces, installation locations, and limitations. Availability can also depend on plan, version, account settings, and whether the user is using a desktop app, web app, IDE, CLI, or API.

The following is a practical starting guide, not a promise that every feature is available to every account.

### Claude

**Claude.ai:** Custom skills can be uploaded as a ZIP in supported plans and experiences. Package the skill folder so that `SKILL.md` is at the top level inside the skill folder. In Claude, use the Skills area in Settings/Features as documented by Anthropic.

**Claude Code:** Place the skill directory in `~/.claude/skills/vendorgenius/` for personal use, or `.claude/skills/vendorgenius/` in a project.

Official documentation: https://support.claude.com/en/articles/12512198-how-to-create-custom-skills and https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview

### OpenAI Codex and ChatGPT

**Codex:** Codex supports Agent Skills. A personal skill can be placed in `~/.agents/skills/vendorgenius/`; a repository skill can be placed in `.agents/skills/vendorgenius/`. Codex CLI and supported IDE experiences can discover skills from these locations. Follow the current OpenAI documentation for your environment.

**ChatGPT:** Standalone skills are available in supported ChatGPT desktop experiences. Skills distributed as plugins can be made available in ChatGPT Chat and Work across supported web, desktop, and mobile experiences. A raw `SKILL.md` file is not automatically installable in every ChatGPT interface. Distribution through a ChatGPT plugin is a separate packaging and publishing step.

Official documentation: https://learn.chatgpt.com/docs/build-skills and https://developers.openai.com/api/docs/guides/tools-skills

### GitHub Copilot and Visual Studio Code

Agent Skills are supported in documented Copilot and VS Code environments. Project and personal skill locations vary by host and configuration. Consult the current official documentation before installation.

Official documentation: https://docs.github.com/en/copilot and https://code.visualstudio.com/docs/agent-customization/agent-skills

### Other AI agents

Other tools may support the Agent Skills format or a compatible subset. Check whether the specific product supports `SKILL.md`, its required folder location, metadata constraints, and any scripts or reference files before installing.

## What this skill cannot do by itself

VendorGenius does not automatically:
- Publish posts or send WhatsApp messages.
- Connect to Facebook, Instagram, TikTok, or an online store.
- Read social media analytics or private customer conversations.
- Accept payments, issue refunds, or create real orders.
- Maintain a live inventory or accounting ledger.
- Verify product claims or local legal compliance without reliable sources and suitable tools.

These actions require separate integrations, permissions, and sometimes a dedicated application. VendorGenius can draft and advise based on the information and tools actually available to the AI agent.

## Privacy and safe use

- Do not paste customer passwords, full card details, or unnecessary personal information into an AI agent.
- Use fictional or anonymised examples when asking for help with customer conversations.
- Review AI-generated text, calculations, and claims before using them.
- Do not use the skill to create fake reviews, deceptive scarcity, spam, or misleading advertising.

## Repository contents

```text
vendorgenius/
├── SKILL.md
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── SECURITY.md
├── agents/
│   └── openai.yaml
├── examples/
│   └── sample-requests.md
└── tests/
    ├── TESTING.md
    └── test-cases.md
```

## Contributing

Ideas, corrections, translations, and tested examples are welcome. Please read `CONTRIBUTING.md` before opening an issue or pull request. Never include private customer information.

## Licence and attribution

VendorGenius is released under the MIT License. See `LICENSE`.

The licence applies to the repository materials covered by it. The Aetheris Tech & Innovation name, logo, and other trademarks are not granted for unrestricted use by the software licence. Modified or redistributed copies must not imply ATI endorsement.

## Maintainer

Aetheris Tech & Innovation (ATI)

## Disclaimer

VendorGenius provides general business-writing and planning assistance. It is not professional legal, tax, accounting, financial, medical, or regulatory advice. Users are responsible for verifying outputs, product claims, prices, policies, and local requirements before acting on them.
