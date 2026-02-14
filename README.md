# Solo Builder Playbook

A personalized growth advisor for solo builders, powered by real strategies from **19 founders** who built apps to **$10K-$200K+ MRR**. Extracted from [Starter Story](https://www.youtube.com/@starterstory) interviews (2025-2026).

This is a [Claude Code](https://claude.ai/code) skill. Install it and get founder-tested growth strategies tailored to your specific project — Claude reads your repo, understands what you're building, and delivers actionable advice with real founder citations.

## Install

**All projects (global):**

```bash
git clone https://github.com/drewautomates/solo-builder-playbook-skill.git ~/.claude/skills/solo-builder-playbook
```

**Single project only:**

```bash
cd your-project
git clone https://github.com/drewautomates/solo-builder-playbook-skill.git .claude/skills/solo-builder-playbook
```

Then restart Claude Code. The skill will be available as `/solo-builder-playbook`.

## What Makes This Different

Most growth advice is generic. This skill is contextual.

**Without context** (typical chatbot):
> "Consider using social media marketing. Create content that resonates with your target audience. Try multiple channels and see what works."

**With Solo Builder Playbook** (inside your project):
> It looks like you're building a B2B SaaS with Next.js and Stripe. Based on your stack and stage, here's what worked for **Roman** — he grew his SaaS to **$22K MRR through Reddit alone** by posting genuine how-to content in subreddits where his target users hung out. Here's your 30-day plan...

The skill reads your `README.md`, `package.json`, and other project files to auto-detect your product type, tech stack, and stage — then routes you to the right playbooks with personalized action items.

## How It Works

1. **Detects your project** — Scans your repo to understand what you're building, your tech stack, and your stage
2. **Asks smart questions** — Only asks what it can't figure out from your code (stage, MRR, what you've tried)
3. **Routes to the right playbooks** — A B2B SaaS gets different advice than a mobile app or dev tool
4. **Delivers actionable outputs** — Not summaries, but draft posts, growth plans, email sequences, and pricing copy for *your* product

## What's Inside

17 playbooks covering every stage from idea to $100K+ MRR:

| Playbook                  | What You'll Learn                                            |
| ------------------------- | ------------------------------------------------------------ |
| **Idea Selection**        | 4-filter test for picking ideas that can reach $10K MRR      |
| **Distribution Strategy** | Which growth channel fits your product type                  |
| **Reddit Marketing**      | Roman's system: $2K to $22K MRR through Reddit alone         |
| **TikTok-First Apps**     | Louis's framework: $0 to $800K/year via organic TikTok       |
| **Discord Communities**   | Sam's screen-share selling trick for niche tools             |
| **Twitter/X**             | Build in public + DM support hack for SaaS growth            |
| **Influencer Marketing**  | George's 100-DMs-per-day outreach system                     |
| **Partnerships**          | Hassam's equity-for-distribution model (0 to $25K in 48hrs)  |
| **SEO & Content**         | Bhanu's free-tools strategy: 50K monthly clicks, $0 ad spend |
| **Lifetime Deals**        | Mike's 3-phase LTD hack to bootstrap $100K in runway         |
| **Pricing & Revenue**     | Pricing models and milestones from $0 to $200K MRR           |
| **Onboarding**            | George & Connor's conversion formula for free-to-paid        |
| **Vibe Coding**           | Building production apps with Cursor, Bolt, Replit in days   |
| **B2B SaaS Playbook**     | Full playbook: idea to $100K MRR (Mike + Tibo combined)      |
| **Mobile App Playbook**   | Content-first strategy for iOS/Android apps                  |
| **Open Source**           | Nevo's launch-week plan: 5M downloads, $17K MRR              |
| **When to Pivot**         | Signal detection and Eyal's rebuild framework                |

## Usage Examples

### Broad question — Claude diagnoses first

> **You**: `/solo-builder-playbook` How do I get users?
>
> **Claude**: *reads your repo, detects a Next.js SaaS with Stripe* — "It looks like you're building a B2B SaaS. Here's what I'd recommend based on your stage..."

### Specific question — Claude goes straight to the playbook

> **You**: `/solo-builder-playbook` Should I do a lifetime deal?
>
> **Claude**: *pulls from the LTD playbook* — "Mike used a 3-phase LTD strategy to bootstrap $100K in runway. Here's when it makes sense and when it backfires..."

### Deliverable request — Claude generates real outputs

> **You**: `/solo-builder-playbook` Write me some Reddit posts to promote my app
>
> **Claude**: *reads your product details, drafts 3 Reddit posts tailored to relevant subreddits with the right tone*

### Growth plan — Claude builds a roadmap

> **You**: `/solo-builder-playbook` Give me a 30-day growth plan
>
> **Claude**: *diagnoses your stage and product type, creates a week-by-week action plan with specific milestones*

## The Founders

Data from founders making $10K-$200K+/month MRR:

| Founder      | Product              | MRR              | Key Channel       |
| ------------ | -------------------- | ---------------- | ----------------- |
| Tibo         | Tweethunter/Taplio   | $700K/mo         | Twitter + Content |
| Mike         | 5 SaaS apps          | $200K/mo         | SEO + LTDs        |
| Roman        | QuillBot alternative | $22K/mo          | Reddit            |
| Louis        | GlowUp AI            | $67K/mo          | TikTok            |
| George       | Wrestle AI           | $17K/mo          | Influencers       |
| Connor       | Payout               | $20K/mo          | Onboarding        |
| Nevo         | Postiz               | $17K/mo          | Open Source       |
| Bhanu        | SiteGPT              | $13K/mo          | SEO/Free Tools    |
| Hassam       | WhatsBot             | $25K first 48hrs | Partnerships      |
| + 10 more... |                      |                  |                   |

## How This Was Made

These playbooks were compiled by watching, transcribing, and cross-referencing 19 founder interviews from [Starter Story](https://www.youtube.com/@starterstory). Content analysis was powered by [Noverload](https://noverload.com) — AI-powered knowledge management that turns saved content into actionable insights.

## License

MIT
