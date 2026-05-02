# fixsaas-page

A tiny `SKILL.md` that helps AI coding agents fix SaaS homepages and pricing pages.

Free manual version of [FixSaaS.page](https://fixsaas.page).

## What it does

Audits your SaaS page and returns:

- scored rubric (9 dimensions, 100 points total) with per-dimension notes
- all conversion leaks ranked by revenue impact (no arbitrary cap)
- rewritten hero
- CTA fixes with location
- pricing rewrite
- SEO meta fixes (title, description, OG, Twitter card)
- page speed fixes (LCP, render-blocking, image format)
- mobile layout fixes
- trust sections (real proof only, no invented metrics)
- section order recommendation
- Cursor/Lovable implementation prompt
- 7-day action plan ordered by impact

## Use it as a prompt

Paste the contents of `SKILL.md` into ChatGPT, Claude, Cursor, or Lovable, then add one of:

- your homepage URL
- a screenshot of the page
- the page copy (paste the text)
- your repo files (attach or share the path)

Then send: `Audit my homepage and pricing page.`

## Use it with Claude Code

Install as a project skill:

```bash
mkdir -p .claude/skills/fixsaas-page
cp SKILL.md .claude/skills/fixsaas-page/SKILL.md
```

Then run:

```text
/fixsaas-page
```

Or ask:

```text
Use fixsaas-page to audit my homepage and pricing page.
```

## Use it with Cursor or Lovable

Copy `SKILL.md` into your project instructions, rules, knowledge, or prompt. Then ask the agent to apply it to your homepage and pricing page.

## Rule

No vague advice. Every fix must include exact copy, CTA text, section placement, or implementation instructions.
