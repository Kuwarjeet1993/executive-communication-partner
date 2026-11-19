# Executive Communication & Critical Thinking Partner

A Claude skill that acts as an executive communication adviser, critical-thinking partner and strategic sounding board for a senior digital marketing and growth leader.

It doesn't just polish wording. It first works out the business situation, tests the reasoning, flags what's missing, and then helps produce the strongest message: clear, commercially aware, diplomatic when needed and firm when required.

## What it helps with

| Mode | Use it for |
|---|---|
| **A. Email / message drafting** | Writing, rewriting, shortening or replying to emails, WhatsApp, LinkedIn messages |
| **B. Difficult or sensitive replies** | Correcting the record, clarifying ownership, setting boundaries without escalating |
| **C. Executive / boardroom answers** | 60–90 second answers: position → reasons → business impact → execution |
| **D. Strategic decisions** | Problem → evidence → options and trade-offs → recommendation → owner and next step |
| **E. Negotiation and influence** | Interests vs positions, evidence, clear proposals, protecting relationships |
| **F. Meeting prep and follow-up** | Objectives, key messages, likely objections, decisions, action owners |

## Core principles

- Think before drafting. Find the real objective first.
- Protect credibility: never defensive, vague, junior or needlessly aggressive.
- Be commercially minded: revenue, margin, risk, ownership, customer/patient impact.
- Challenge weak logic respectfully.
- Plain, direct English. No jargon or corporate clichés.
- Never invent facts, metrics, approvals or commitments.
- Separate sourced, attributed, influenced and incremental revenue.

## Repository layout

```
executive-communication-partner/
├── README.md
└── executive-communication-partner/
    └── SKILL.md      # the skill itself (name + description in the frontmatter)
```

## Installing the skill

**Claude apps (claude.ai / desktop):** zip the inner `executive-communication-partner/` folder and upload it under **Settings → Capabilities → Skills**.

**Claude Code:** copy the inner folder into `~/.claude/skills/` (personal) or `.claude/skills/` in a project.

```bash
git clone https://github.com/<your-username>/executive-communication-partner.git
cp -r executive-communication-partner/executive-communication-partner ~/.claude/skills/
```

## Using it

Invoke it by name (`/executive-communication-partner`) or just ask for help with a work message, reply, meeting or decision. Examples:

- "Reply to this CFO email questioning our paid media spend. Keep it firm but not defensive."
- "I have 90 seconds with the CEO on why we should shift budget from Google Ads to CRM. Structure it."
- "The agency missed the deadline again. Draft a message that fixes ownership without burning the relationship."

## Privacy note

The skill's instructions contain a short professional profile of its owner. Review `SKILL.md` before making the repository public, and keep it private if you'd rather not share that context.
