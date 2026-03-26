# AI Learning Resources

A curated learning path from "what even is AI?" to building your own AI-powered workflows. Quality over quantity — every resource here is the best of its kind.

This isn't a dump of links. It's a path. Start at Stage 1 and work forward, or jump to wherever you are.

## Prerequisites

**Git:** Claude Code and many AI tools use Git for version control. If you're new to it, [GitHub's Git Handbook](https://guides.github.com/introduction/git-handbook/) will get you up to speed in 10 minutes. Prefer video? [Git Explained in 100 Seconds](https://www.youtube.com/watch?v=hwP7WQkmECE) (Fireship, 3 min) covers the essentials.

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

- **[Transformer Explainer](https://poloclub.github.io/transformer-explainer/)** — Georgia Tech / Polo Club
  Interactive browser tool — type text and watch the model process it through attention and prediction in real time.

- **[The AI Revolution: Road to Superintelligence](https://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html)** — Tim Urban (Wait But Why)
  Written in 2015, pre-LLM, but still the best accessible piece on why AI matters at civilizational scale. Good for the "why should I care" framing.

- **[GenAI Handbook](https://genai-handbook.github.io/)** — William Brown
  Curated roadmap organizing the best scattered resources into 9 structured sections. Good if you want a self-directed syllabus.

### Podcast episodes

Episodes from [Chain of Thought](https://chainofthought.show) that help build your mental model:

- **[The State of AI: Open-Source Models & Enterprise Trust](https://share.transistor.fm/s/345672b7)** — May Habib & Galileo co-founders. Foundational overview of where AI stands — open vs. closed models, enterprise trust gaps.
- **[GenAI Predictions for 2025](https://share.transistor.fm/s/0f0efc07)** — Sara Hooker (Cohere), Craig Wiley (Databricks), Vikram Chatterji (Galileo). Three AI company leaders map the landscape and where it's heading.
- **[How DeepSeek Changed the AI Race Overnight](https://share.transistor.fm/s/4bf30e72)** — How a single model release shifted global AI competition. Good entry point for understanding model economics.
- **[Beyond Transformers](https://share.transistor.fm/s/645ba9fe)** — Maxime Labonne. Model architectures beyond the transformer — what comes next.

---

## Stage 2: Start Using AI Effectively

You understand the basics. Now make it useful.

### Start here

- **[The Practical Guide to Using AI to Do Stuff](https://www.oneusefulthing.org/p/the-practical-guide-to-using-ai-to)** — Ethan Mollick
  The canonical "OK I have ChatGPT, now what?" post. Covers writing, analysis, images, code, and when AI fails. Regularly updated.
  *Video alternative: [AI's Productivity Paradox — and What It Means for You](https://www.ted.com/talks/ethan_mollick_ai_s_productivity_paradox_and_what_it_means_for_you) (TED Talk, 12 min) — live demos of AI transforming productivity.*

- **[Co-Intelligence: Living and Working with AI](https://www.amazon.com/Co-Intelligence-Living-Working-Ethan-Mollick/dp/059371671X)** — Ethan Mollick (book)
  Best single book for non-technical professionals. Four principles: always invite AI, be the human in the loop, treat it as a smart-but-alien collaborator, assume it's the worst AI you'll ever use.

- **[Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/claude-4-best-practices)** — Anthropic
  Official Claude prompting best practices. Covers clarity, XML tags, chain-of-thought, and Claude-specific behavior.
  *Video alternative: [Prompt Engineering Tutorial](https://www.youtube.com/watch?v=_ZvnD73m40o) (freeCodeCamp, ~1 hr) — comprehensive walkthrough with hands-on examples.*

### Go deeper

- **[An Opinionated Guide to Using AI Right Now](https://www.oneusefulthing.org/p/an-opinionated-guide-to-using-ai)** — Ethan Mollick
  More recent, more opinionated. Recommends specific tools for specific tasks. Good for decision-makers.

- **[Prompt Engineering Guide](https://www.promptingguide.ai/)** — DAIR.AI
  Comprehensive reference for prompting techniques (few-shot, chain-of-thought, tree-of-thought, RAG). More technical — use as a reference manual.

- **[Anthropic Interactive Prompt Engineering Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)** — Anthropic
  9-chapter hands-on course with Jupyter notebooks. Each lesson has a playground. Free.

- **[OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)** — OpenAI
  Official best practices. Concise, actionable, model-specific. Industry standard for GPT prompting.

### Podcast episodes

- **[How Block Deployed AI Agents to 12,000 Employees in 8 Weeks w/ MCP](https://share.transistor.fm/s/90efac38)** — Angie Jones. Concrete enterprise deployment with real numbers — the "how we actually did it" episode.
- **[Architecting AI Agents: The Shift from Models to Systems](https://share.transistor.fm/s/a22109d3)** — Aishwarya Srinivasan. How to think about agents as systems, not just models.
- **[Practical Lessons for GenAI Evals](https://share.transistor.fm/s/c5db81b4)** — Chip Huyen & Vivienne Zhang. Hands-on guide to evaluating AI outputs — essential for anyone building with LLMs.
- **[Low-Code AI: From Requirements to Enterprise Apps in Minutes](https://share.transistor.fm/s/4dd2a8ce)** — Rodrigo Coutinho. Accessible for non-developers — shows AI tool usage without deep technical skill.

---

## Stage 3: Build with Claude Code & MCP

Hands-on. Install tools, build workflows, connect AI to your actual work.

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

Once you have Claude Code installed, try these as starter projects:

1. **Add the [avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) skill** to a project and run it on something you've written. Seeing Claude audit your own text is the fastest way to understand how skills work.
2. **Write a CLAUDE.md file** for a project you're working on. Start with 3-5 instructions about how you want Claude to behave. Iterate from there.
3. **Install an MCP server** (start with one from the [official servers repo](https://github.com/modelcontextprotocol/servers)) and use it in Claude Code. The jump from "Claude can read files" to "Claude can access my calendar" is when it clicks.

### Skills & Tools

- **[agentskills.io](https://agentskills.io)** — Portable skill format that works across 40+ AI coding tools.
- **[AI Tools for Creators](https://github.com/conorbronsdon/ai-tools-for-creators)** — Curated collection of production-tested skills and MCP servers for content creators and knowledge workers.

### Podcast episodes

- **[The Critical Infrastructure Behind the AI Boom](https://share.transistor.fm/s/43ad9185)** — Jeetu Patel (Cisco). Big-picture infrastructure view — networking, compute, the plumbing behind AI.
- **[Got Agents? Agentic Workflows & Architecture](https://share.transistor.fm/s/d35a1ff1)** — Bob van Luijt (Weaviate), Brian Raymond (Unstructured), Joao Moura (crewAI). Three infrastructure builders explain the agent stack.
- **[Defining the AI Agent Stack](https://share.transistor.fm/s/6d776ed2)** — Joao Moura (CrewAI). The layers of the agent toolchain — what sits where and why.
- **[After Code Gen](https://share.transistor.fm/s/5fbf1f25)** — Greg Foster (Graphite). What the dev workflow looks like when AI writes the code.

---

## Stage 4: Think Strategically About AI

The hardest part isn't using AI — it's knowing what it changes about your work, your industry, and your decisions.

### Start here

- **[Situational Awareness: The Decade Ahead](https://situational-awareness.ai/)** — Leopold Aschenbrenner
  The most cited strategic analysis of where AI is heading. Dense but essential for anyone making bets on AI's trajectory.
  *Video alternative: [Leopold Aschenbrenner on Dwarkesh Podcast](https://youtu.be/zdbVtZIn9IM) (~4.5 hrs) — the full conversation covering AGI timelines, trillion-dollar clusters, and national security implications.*

- **[Co-Intelligence](https://www.amazon.com/Co-Intelligence-Living-Working-Ethan-Mollick/dp/059371671X)** — Ethan Mollick (book, also listed in Stage 2)
  The strategic framing chapters are as valuable as the practical ones. Read it twice — once for "how" and once for "what it means."

### Podcast episodes

- **[First Code, Then AGI](https://share.transistor.fm/s/17ac922c)** — Jason Warner & Eiso Kant (Poolside). Big-picture thinking on the path to AGI through software specialization.
- **[How AI Velocity is Rewriting the Rules for Engineering Leaders](https://share.transistor.fm/s/5178eb0a)** — Claire Vo (ChatPRD). Leadership accountability framework for AI adoption.
- **[Why Most Enterprise AI Projects Fail to Show ROI](https://share.transistor.fm/s/dd11211d)** — HP, ServiceNow, Accenture panel. The reality check on enterprise AI.
- **[The Agent Bubble Debate](https://share.transistor.fm/s/3a5c548d)** — Kelly Vaughn. Healthy skepticism about agent hype — an important counterpoint.
- **[From Demo to Defensibility](https://share.transistor.fm/s/fdb45b54)** — Aurimas Griciuanas. Why most AI demos don't become real businesses, and what separates the ones that do.
- **[The 2025 AI Shift: From Chat to Task Completion](https://share.transistor.fm/s/3577fd8c)** — Vikram Chatterji & Atindriyo Sanyal (Galileo). Trust, not technology, is the bottleneck for AI agent adoption.

---

## Structured courses

If you prefer a full curriculum over curated links:

| Course | Provider | Format | Level |
|--------|----------|--------|-------|
| [Anthropic Academy](https://anthropic.skilljar.com/) | Anthropic | Self-paced, free | Beginner → Advanced |
| [LLM Course](https://github.com/mlabonne/llm-course) | Maxime Labonne | Colab notebooks | Intermediate → Advanced |
| [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) | Microsoft | 21 lessons, Python/TS | Beginner → Intermediate |
| [AI for Beginners](https://github.com/microsoft/AI-For-Beginners) | Microsoft | 12-week curriculum | Beginner |
| [Start Machine Learning](https://github.com/louisfb01/start-machine-learning) | Louis Bouchard | Reading list | Beginner |

---

## About

Maintained by [Conor Bronsdon](https://github.com/conorbronsdon). I host [Chain of Thought](https://chainofthought.show), a podcast about AI infrastructure, developer tools, and how practitioners use AI in production. Many of these resources were discovered through conversations with guests on the show.

Subscribe to the [Chain of Thought newsletter](https://newsletter.chainofthought.show) for weekly updates on AI tools, workflows, and what's actually working in production.

Suggestions? Open an issue. Quality bar: you've used it and it actually helped.
