<div align="center">

# AI Learning Resources

A curated learning path from zero to building your own AI-powered workflows, apps, and agents.

[![GitHub stars](https://img.shields.io/github/stars/conorbronsdon/ai-learning-resources?style=social)](https://github.com/conorbronsdon/ai-learning-resources/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![X](https://img.shields.io/badge/X-@ConorBronsdon-black?style=flat-square&logo=x)](https://x.com/ConorBronsdon)

</div>

---


This isn't a dump of links. It's a path. Start at Stage 1 and work forward, or jump to wherever you are.

*Last updated: March 2026*

## Contents

- [Prerequisites](#prerequisites)
- [Structured courses](#prefer-a-structured-course) (alternative to the staged path)
- [Stage 1: Understand How AI Works](#stage-1-understand-how-ai-works)
- [Stage 2: Start Using AI Effectively](#stage-2-start-using-ai-effectively)
- [Stage 3: Build with AI Coding Tools](#stage-3-build-with-ai-coding-tools)
- [Stage 4: Think Strategically About AI](#stage-4-think-strategically-about-ai)
- [Keep Learning](#keep-learning) (ongoing resources)

## Prerequisites

**Git:** Claude Code and many AI tools use Git for version control. If you're new to it, [GitHub's Git Handbook](https://guides.github.com/introduction/git-handbook/) will get you up to speed in 10 minutes. Prefer video? [Git Explained in 100 Seconds](https://www.youtube.com/watch?v=hwP7WQkmECE) (Fireship, 3 min) covers the essentials.

## Prefer a structured course?

If you'd rather follow a full curriculum than pick through curated links, start with one of these:

| Course | Provider | Format | Level |
|--------|----------|--------|-------|
| [Anthropic Academy](https://anthropic.skilljar.com/) | Anthropic | Self-paced, free | Beginner → Advanced |
| [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) | Microsoft | 21 lessons, Python/TS | Beginner → Intermediate |
| [AI for Beginners](https://github.com/microsoft/AI-For-Beginners) | Microsoft | 12-week curriculum | Beginner |
| [LLM Course](https://github.com/mlabonne/llm-course) | Maxime Labonne | Colab notebooks | Intermediate → Advanced |
| [Start Machine Learning](https://github.com/louisfb01/start-machine-learning) | Louis Bouchard | Reading list | Beginner |

Otherwise, follow the staged path below.

---

## Stage 1: Understand How AI Works

You don't need a CS degree. You need mental models for what's happening under the hood so you can reason about what AI can and can't do.

### Start here

- **[Deep Dive into LLMs like ChatGPT](https://www.youtube.com/watch?v=7xTGNNLPyMI)** — Andrej Karpathy (3.5 hrs)
  The single best general-audience walkthrough of how LLMs are built: pretraining, finetuning, RLHF. No technical background needed. If you watch one thing, make it this.
  *Shorter version: [Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) (1 hr)*

- **[Neural Networks](https://www.3blue1brown.com/topics/neural-networks)** — 3Blue1Brown (video series)
  The gold-standard visual explainer. Starts with "what is a neural network?" and builds through backpropagation to transformers and attention. Chapters 5-7 cover LLMs specifically.

- **[What Is ChatGPT Doing... and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)** — Stephen Wolfram
  Deep, readable explainer covering embeddings, tokens, transformers, and the philosophical "why" behind next-token prediction. Also [a book](https://www.amazon.com/What-ChatGPT-Doing-Does-Work/dp/1579550819).

### Go deeper

- **[The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)** — Jay Alammar
  The canonical visual blog post for understanding transformer architecture. More technical than the above, but still accessible with diagrams for every step.

- **[The AI Revolution: Road to Superintelligence](https://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html)** — Tim Urban (Wait But Why)
  Written in 2015, pre-LLM, but still the best accessible piece on why AI matters at civilizational scale. Good for the "why should I care" framing.

- **[GenAI Handbook](https://genai-handbook.github.io/)** — William Brown
  Curated roadmap organizing the best scattered resources into 9 structured sections. Good if you want a self-directed syllabus.

### Podcast episodes

Episodes from [Chain of Thought](https://chainofthought.show) that help build your mental model:

- **[Beyond Transformers](https://share.transistor.fm/s/645ba9fe)** — Maxime Labonne. Model architectures beyond the transformer — what comes next.

## Stage 2: Start Using AI Effectively

You understand the basics. Now make it useful.

### Choosing a tool

There are many AI tools, and more launching every week. The main ones worth knowing:
- **ChatGPT** (OpenAI) — the most widely used, good general-purpose starting point
- **Claude** (Anthropic) — strong at writing, analysis, and long documents (my personal favorite as of 2026)
- **Gemini** (Google) — integrated with Google Workspace
- **Perplexity** — AI-powered search with citations
- **Claude Code / Codex / Cursor / Windsurf** — AI coding tools (see Stage 3)

Don't overthink the choice. Pick one and start using it daily. You'll develop preferences fast.

### Start here

- **[The Practical Guide to Using AI to Do Stuff](https://www.oneusefulthing.org/p/the-practical-guide-to-using-ai-to)** — Ethan Mollick
  The canonical "OK I have ChatGPT, now what?" post. Covers writing, analysis, images, code, and when AI fails. Regularly updated.
  *Video alternative: [AI's Productivity Paradox — and What It Means for You](https://www.ted.com/talks/ethan_mollick_ai_s_productivity_paradox_and_what_it_means_for_you) (TED Talk, 12 min) — live demos of AI transforming productivity.*

- **[Co-Intelligence: Living and Working with AI](https://www.amazon.com/Co-Intelligence-Living-Working-Ethan-Mollick/dp/059371671X)** — Ethan Mollick (book)
  Best single book for non-technical professionals. Four principles: always invite AI, be the human in the loop, treat it as a smart-but-alien collaborator, assume it's the worst AI you'll ever use.

### Go deeper

- **[An Opinionated Guide to Using AI Right Now](https://www.oneusefulthing.org/p/an-opinionated-guide-to-using-ai)** — Ethan Mollick
  More recent, more opinionated. Recommends specific tools for specific tasks. Good for decision-makers.

- **Prompt engineering references** — Useful as reference material, but don't over-invest here. Modern tools handle most prompting complexity for you. If you want to go deep: [Anthropic's guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/claude-4-best-practices), [Anthropic's interactive tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial) (free, hands-on), or [DAIR.AI's Prompt Engineering Guide](https://www.promptingguide.ai/) (comprehensive reference).
  *Video alternative: [Prompt Engineering Tutorial](https://www.youtube.com/watch?v=_ZvnD73m40o) (freeCodeCamp, ~1 hr)*

### Know the limits

AI tools hallucinate, leak data to providers, and confidently produce wrong answers as they seek to predict the right response. Before relying on them:
- Never paste sensitive/proprietary data into a tool without understanding its data policy
- Always verify factual claims, especially numbers, citations, and dates
- AI is a collaborator, not an authority — you own the output

### Podcast episodes

- **[He Built an AI Coworker That Runs 90% of His Day](https://newsletter.chainofthought.show/p/he-named-his-ai-coworker-marvin-it)** — Sterling Chin. A practitioner who stopped treating AI as a tool and started treating it like a junior employee. The clearest example of what daily AI integration looks like.


## Stage 3: Build with AI Coding Tools

Hands-on. Install tools, build workflows, connect AI to your actual work. This section focuses on Claude Code and MCP, but the patterns apply to Cursor, Windsurf, Cline, and other AI coding tools too.

### Claude Code

- **[Claude Code Overview](https://code.claude.com/docs/en/overview)** — Anthropic (official docs)
  Start here. Installation (terminal, VS Code, JetBrains, desktop, web), core capabilities, and links to everything else.
  *Video alternative: [Claude Code Beginner's Tutorial](https://www.youtube.com/watch?v=GepHGs_CZdk) (Peter Yang, ~15 min) — hands-on walkthrough from install to building a working app.*

- **[Claude Code Quickstart](https://code.claude.com/docs/en/quickstart)** — Anthropic
  Walk through your first task: explore a codebase, make changes, commit.

- **[Claude Code Best Practices](https://code.claude.com/docs/en/best-practices)** — Anthropic
  Patterns for getting the most from Claude Code — CLAUDE.md setup, workflow patterns, sub-agents.

- **[Claude Code in Action](https://anthropic.skilljar.com/claude-code-in-action)** — Anthropic Academy
  Free official course with certificate. Teaches building, configuring, and sharing Skills.

- **[Anthropic Academy](https://anthropic.skilljar.com/)** — Anthropic
  13 free self-paced courses: Claude 101, AI Fluency, Claude Code, MCP, the API, and certification (Claude Certified Architect).

- **[How Anthropic Teams Use Claude Code](https://www-cdn.anthropic.com/58284b19e702b49db9302d5b6f135ad8871e7658.pdf)** — Anthropic (PDF)
  Internal practices showing how Anthropic's own teams use Claude Code. Good for advanced patterns.

- **[Claude Code GitHub repo](https://github.com/anthropics/claude-code)** — Anthropic
  Open source. Good for architecture understanding, CLAUDE.md examples, and filing issues.

- **[MARVIN template](https://github.com/SterlingChin/marvin-template)** — Sterling Chin
  Reference architecture for an autonomous background agent that runs on GitHub Actions + Claude Code. Good example of what's possible once you're comfortable with the basics.

### MCP (Model Context Protocol)

- **[What is MCP?](https://modelcontextprotocol.io/introduction)** — Anthropic / MCP team
  "USB-C port for AI." What MCP enables, why it matters, and who supports it (Claude, ChatGPT, VS Code, Cursor, Gemini).
  *Video alternative: [Model Context Protocol Explained](https://www.youtube.com/watch?v=HyzlYwjoXOQ) (Fireship, ~8 min) — fast-paced explainer of what MCP is and why it matters.*

- **[MCP Quickstart: Build a Server](https://modelcontextprotocol.io/docs/develop/build-server)** — MCP team
  Official tutorial: build a weather MCP server and connect it. Python and TypeScript.

- **[MCP Architecture & Concepts](https://modelcontextprotocol.io/docs/learn/architecture)** — MCP team
  Core concepts: resources, tools, prompts, transports, client-server architecture.

- **[Official MCP Servers](https://github.com/modelcontextprotocol/servers)** — MCP team
  Reference implementations and community servers. Browse to see what MCP servers look like in practice.

- **[awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)** — wong2
  Largest curated list of MCP servers by category. Good for discovering what's available.

### What to build first

Once you have Claude Code installed, try these as starter projects. Don't have a project? Create an empty folder with a README — that's enough to start.

1. **Add the [avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) skill** to a project and run it on something you've written. Seeing Claude audit your own text is the fastest way to understand how skills work.
2. **Write a CLAUDE.md file** for a project you're working on. Start with 3-5 instructions about how you want Claude to behave. Iterate from there.
3. **Install an MCP server** (start with one from the [official servers repo](https://github.com/modelcontextprotocol/servers)) and use it in Claude Code. The jump from "Claude can read files" to "Claude can access my calendar" is when it clicks.

### Skills & Tools

- **[agentskills.io](https://agentskills.io)** — Portable skill format that works across 40+ AI coding tools.
- **[AI Tools for Creators](https://github.com/conorbronsdon/ai-tools-for-creators)** — Curated collection of production-tested skills and MCP servers for content creators and knowledge workers.

### Podcast episodes

- **[The Critical Infrastructure Behind the AI Boom](https://share.transistor.fm/s/43ad9185)** — Jeetu Patel (Cisco). Big-picture infrastructure view — networking, compute, the plumbing behind AI.
- **[After Code Gen](https://share.transistor.fm/s/5fbf1f25)** — Greg Foster (Graphite). What the dev workflow looks like when AI writes the code.

## Stage 4: Think Strategically About AI

The hardest part isn't using AI — it's knowing what it changes about your work, your industry, and your decisions.

### Start here

- **[Situational Awareness: The Decade Ahead](https://situational-awareness.ai/)** — Leopold Aschenbrenner
  The most cited strategic analysis of where AI is heading. Dense but essential for anyone making bets on AI's trajectory.
  *Video alternative: [Leopold Aschenbrenner on Dwarkesh Podcast](https://youtu.be/zdbVtZIn9IM) (~4.5 hrs) — the full conversation covering AGI timelines, trillion-dollar clusters, and national security implications.*

- **[Co-Intelligence](https://www.amazon.com/Co-Intelligence-Living-Working-Ethan-Mollick/dp/059371671X)** — Ethan Mollick (book, also listed in Stage 2)
  The strategic framing chapters are as valuable as the practical ones. Read it twice — once for "how" and once for "what it means."

- **[Block Cut 4,000 Jobs and Blamed AI. The Truth is More Complicated.](https://newsletter.chainofthought.show/p/block-cut-4000-jobs-and-blamed-ai)** — Conor Bronsdon
  What actually happens when a company restructures around AI. The gap between the headline and the reality.

### Podcast episodes

- **[First Code, Then AGI](https://share.transistor.fm/s/17ac922c)** — Jason Warner & Eiso Kant (Poolside). Big-picture thinking on the path to AGI through software specialization.
- **[How AI Velocity is Rewriting the Rules for Engineering Leaders](https://share.transistor.fm/s/5178eb0a)** — Claire Vo (ChatPRD). Leadership accountability framework for AI adoption.
- **[From Demo to Defensibility](https://share.transistor.fm/s/fdb45b54)** — Aurimas Griciuanas. Why most AI demos don't become real businesses, and what separates the ones that do.
- **[How Block Deployed AI Agents to 12,000 Employees in 8 Weeks w/ MCP](https://share.transistor.fm/s/90efac38)** — Angie Jones. Concrete enterprise deployment with real numbers.
- **[Architecting AI Agents: The Shift from Models to Systems](https://share.transistor.fm/s/a22109d3)** — Aishwarya Srinivasan. How to think about agents as systems, not just models.

## Keep learning

Ongoing sources worth following once you've worked through the stages:

- **[One Useful Thing](https://www.oneusefulthing.org/)** — Ethan Mollick's Substack. The best ongoing writing about AI's practical impact on work. Updated regularly.
- **[Chain of Thought newsletter](https://newsletter.chainofthought.show)** — Weekly updates on AI tools, workflows, and what's working in production.
- **[How I AI](https://www.youtube.com/@howiaipodcast)** — Podcast focused on how people actually use AI in their daily work. Practical, not theoretical.
- **[Dwarkesh Podcast](https://www.youtube.com/@DwarkeshPatel)** — Long-form interviews with AI researchers, founders, and thinkers. The best deep-dive conversations on where AI is heading.
- **[Simon Willison's Weblog](https://simonwillison.net/)** — Deep, practical coverage of LLMs, tools, and the developer experience side of AI.

---

## About

Maintained by [Conor Bronsdon](https://github.com/conorbronsdon). I host [Chain of Thought](https://chainofthought.show), a podcast about AI infrastructure, developer tools, and how practitioners use AI in production. Many of these resources were discovered through conversations with guests on the show.

Subscribe to the [Chain of Thought newsletter](https://newsletter.chainofthought.show) for weekly updates on AI tools, workflows, and what's actually working in production.

## Contributing

PRs welcome. To suggest a resource, open an issue or submit a PR — include a sentence on why it's valuable and where it fits in the learning path. Quality bar: you've used it and it actually helped.
