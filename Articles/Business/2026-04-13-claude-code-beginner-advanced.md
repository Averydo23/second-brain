---
title: "Claude Code (Beginner → Advanced)"
type: article
topic: Business
source: "https://charliehills.substack.com/p/claude-code-beginner-advanced"
date: 2026-04-13
---

Title: Claude Code (Beginner → Advanced)

URL Source: https://charliehills.substack.com/p/claude-code-beginner-advanced

Markdown Content:
# Claude Code (Beginner → Advanced)

[![Image 1: MarTech AI](https://substackcdn.com/image/fetch/$s_!ktX6!,w_40,h_40,c_fill,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4a5986fa-177f-49dd-8265-7ebb82f5ba36_800x800.png)](https://charliehills.substack.com/)

# [MarTech AI](https://charliehills.substack.com/)

Subscribe Sign in

# Claude Code (Beginner → Advanced)

### The non-developer's guide to Claude Code

[![Image 2: Charlie Hills's avatar](https://substackcdn.com/image/fetch/$s_!IZP3!,w_36,h_36,c_fill,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F39496630-b70a-49e7-a88a-db4d48810e00_1080x1078.jpeg)](https://substack.com/@charliehills)[![Image 3: Sabahudin Murtic 🎁's avatar](https://substackcdn.com/image/fetch/$s_!KR74!,w_36,h_36,c_fill,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F5237e3f0-71db-4106-9ead-1f5ec337844e_800x800.png)](https://substack.com/@sabahudinmurtic)[![Image 4: Walid Boulanouar's avatar](https://substackcdn.com/image/fetch/$s_!A617!,w_36,h_36,c_fill,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Faf506957-bad5-4cba-828c-4350cddf8ff5_1024x1024.png)](https://substack.com/@walidboulanouar)

[Charlie Hills](https://substack.com/@charliehills), [Sabahudin Murtic 🎁](https://substack.com/@sabahudinmurtic), and [Walid Boulanouar](https://substack.com/@walidboulanouar)

Mar 22, 2026

∙ Paid

222

21

33

Share

This is a collaborative issue. I cover the beginner setup. Sabahudin Murtic walks you through intermediate workflows with parallel agents for real client delivery. Walid Boulanouar shows what happens when Claude Code runs your entire agency. Three levels, one newsletter.

Everything in this newsletter is tested. I ran every workflow, hit every error, and documented what worked. If you are new here, welcome. If you have been reading for a while, thank you. Your subscription keeps this going.

MarTech AI is a reader-supported publication. To receive new posts and support my work, consider becoming a free or paid subscriber.

Subscribe

* * *

## Claude Code

Cowork is built on Claude Code. So is Claude’s coding environment. So are most of the serious AI automation workflows producing real business results.

I am not a Claude Code expert. I learnt most of what follows while researching and writing this newsletter. I came at it as a marketer, not a developer. The barrier around tools like this is largely gone. A few hours of learning-by-doing get you real results.

### What Claude Code actually is

[![Image 5: Enabling Claude Code to work more autonomously \ Anthropic](https://substackcdn.com/image/fetch/$s_!jZLO!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff8f5e62c-4401-4d73-915b-71e5ecaa8307_1920x1035.webp)](https://substackcdn.com/image/fetch/$s_!jZLO!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff8f5e62c-4401-4d73-915b-71e5ecaa8307_1920x1035.webp)

A command-line tool you install in your terminal. It runs locally on your machine. It reads, writes, creates, and modifies files directly. It calls APIs. It browses the web. It spawns sub-agents to run research in parallel. It executes Python scripts you have never written.

Think of it as an AI that lives inside your computer and works with your tools, not around them.

You do not have to be a developer to use it.

* * *

## How to Claude Code (Beginner)

### Getting set up

**Step 1.** Get a paid Claude plan. You need at least Pro at $20/month. Claude Max gives more usage for heavy workflows.

**Step 2.** Install Claude Code. Open your terminal. On Mac, open Spotlight and type “terminal.” On Windows, use CMD or PowerShell. Run the installation command from code.claude.com/docs. Takes about two minutes.

[![Image 6](https://substackcdn.com/image/fetch/$s_!CVWb!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc0b58649-63e5-47c9-9d43-cd6a77f05ca5_729x379.png)](https://substackcdn.com/image/fetch/$s_!CVWb!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc0b58649-63e5-47c9-9d43-cd6a77f05ca5_729x379.png)

**Step 3.** Authenticate. Type “claude” in your terminal. It will prompt you to log in with your Claude account. Follow the steps.

**Step 4.** Navigate to a project folder. In your terminal, go to whatever folder you want Claude Code to work in. Type “claude” again. You are running.

[![Image 7](https://substackcdn.com/image/fetch/$s_!UlE-!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F168fddc9-6dc3-4544-aa9e-65095578211c_740x377.png)](https://substackcdn.com/image/fetch/$s_!UlE-!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F168fddc9-6dc3-4544-aa9e-65095578211c_740x377.png)

If the terminal is new to you, use Claude Code through an IDE instead. The two recommended options are VS Code (free, from Microsoft, at code.visualstudio.com) and Windsurf (newer, more AI-native). Both let you run Claude Code through a graphical chat panel on the right while your files sit on the left. No raw terminal required.

To add Claude Code to VS Code: go to the Extensions tab, search “Claude Code,” install the one from Anthropic, and click the Claude icon that appears in your editor panel.

[![Image 8](https://substackcdn.com/image/fetch/$s_!Ys4z!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0d35e068-9dcf-4b4b-9335-dd1725f98aab_2958x1418.png)](https://substackcdn.com/image/fetch/$s_!Ys4z!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0d35e068-9dcf-4b4b-9335-dd1725f98aab_2958x1418.png)

### Free option (with tradeoffs):

You can run Claude Code with local open-source models through Ollama at zero cost.

Install Ollama, pull a model like qwen3-coder or gpt-oss:20b, and point Claude Code at your local endpoint.

No API fees or data leaving your machine.

You need at least 32GB of RAM for a usable experience. The output quality is noticeably lower than Claude’s own models.

Good for learning the interface. Not enough for the multi-step workflows later in this newsletter.

Set up guide at docs.ollama.com/integrations/claude-code.

* * *

### The CLAUDE.md file

**This is the single highest-leverage thing you can do in Claude Code.**

The CLAUDE.md file is a text file that sits in your project folder. Claude Code reads it automatically at the start of every session. It is injected into the context before you type a single message.

[![Image 9: Image](https://substackcdn.com/image/fetch/$s_!gglb!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F14c4b7e6-160d-4807-ad9c-285eaea884bf_1824x2830.jpeg)](https://substackcdn.com/image/fetch/$s_!gglb!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F14c4b7e6-160d-4807-ad9c-285eaea884bf_1824x2830.jpeg)

Think of it as the standing brief for this project. It tells Claude Code what the project is for, how you want it to behave, what it should never do, the tools and conventions you use, and any constraints specific to this work.

Every session with Claude Code starts cold. No memory of last time. The CLAUDE.md is what makes it feel like a tool that knows your work rather than a blank slate you brief every morning.

Your first CLAUDE.md does not need to be elaborate. Run `/init` in any project folder and Claude Code will read through your files and write one automatically. It analyses what is in the folder and produces a summary with working instructions. Then you refine it over time.

Rules for a good CLAUDE.md:

1.   Keep the most important constraints at the very top. Claude Code has primacy bias. The first things it reads stick hardest.

2.   Write in bullet points and short headings. High information density beats prose.

3.   200 to 500 lines maximum. Longer than that and you are paying token costs that reduce output quality.

4.   Never paste entire API documentation into it. Give Claude Code a summary and let it fetch the rest when required.

5.   Update it when Claude Code keeps making the same mistake. If it trips on the same issue twice, add a rule.

[![Image 10](https://substackcdn.com/image/fetch/$s_!KAko!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0510349d-5943-43c8-9fee-c43db60ad27e_2962x1500.png)](https://substackcdn.com/image/fetch/$s_!KAko!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F0510349d-5943-43c8-9fee-c43db60ad27e_2962x1500.png)

### Permission modes

Claude Code has four modes. Understanding them changes how you use it.

Ask Before Edits is the default. Claude Code asks permission before changing any file. Safe, but slow. If it is asking you to approve every individual edit during a complex build, switch modes.

Edit Automatically auto-accepts changes to existing files but still asks before creating new ones. A good middle ground for most work.

Bypass Permissions removes all prompts. Claude Code works without interruption. To enable it, add the flag `--dangerously-skip-permissions` when launching Claude Code from your terminal. Type `claude --dangerously-skip-permissions` instead of just `claude`.

[![Image 11](https://substackcdn.com/image/fetch/$s_!uL0o!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F264ca2ce-55ec-4663-abbe-30d12ad5de3f_694x290.png)](https://substackcdn.com/image/fetch/$s_!uL0o!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F264ca2ce-55ec-4663-abbe-30d12ad5de3f_694x290.png)

This is where most experienced users end up for knowledge work. The risk is real but low if you work in a non-critical folder. There was a widely shared incident where someone running bypass permissions on a Linux machine lost data. The command was valid. The context was wrong. Use with awareness.

Plan Mode is the one most beginners undervalue.

### Plan Mode

A minute of planning saves ten minutes of building. That is not motivational language. It is token economics.

Here is the actual maths. You build something without planning. It is wrong. You rebuild. Total cost: build time plus rebuild time plus the tokens consumed by both attempts. You plan first. Claude Code identifies the approach problem before touching a single file. Total cost: five minutes of planning plus one correct build.

Plan Mode is read-only. Claude Code researches your project, reads your files, checks documentation, and produces a plan before executing anything. **The plan is not cosmetic. It is load-bearing.** Every hour I have saved in complex builds came from spending five minutes in Plan Mode first.

How to use it: click “Plan Mode” in the permission toggle at the bottom of the chat panel. Describe what you want to build. Let Claude Code produce the plan. Read it. Push back if something looks off. Switch to Bypass Permissions when the plan looks right, and let it build.

[![Image 12](https://substackcdn.com/image/fetch/$s_!JqEr!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F816d7ba6-2715-4dac-a400-00072261c713_1128x722.png)](https://substackcdn.com/image/fetch/$s_!JqEr!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F816d7ba6-2715-4dac-a400-00072261c713_1128x722.png)

### Context management

**Context is the scarce resource in Claude Code.** Managing it well is the difference between a smooth build and a degraded one.

Slash commands worth knowing

You do not need to memorise all 62.

These are the most important ones to learn:

/plan — start Plan Mode before any complex task

/context — see exactly what is consuming your context window

/compact — free up context (do this at around 50%, not 95%)

/clear — reset context entirely when switching to a new task

/model — switch models or reasoning level mid-session

/init — generate your first CLAUDE.md automatically

/doctor — diagnose installation and authentication issues

/rewind — undo when Claude goes off track (or hit Esc twice)

/permissions — pre-allow safe commands instead of using bypass mode

/btw — ask a side question without interrupting the main task

Run `/context` in any session to see exactly what is consuming your context window. You will see your system prompt, tools, MCP tools, memory files, skills, and messages with their exact token counts. Most people are surprised. Before they type a single message, they are often 15-20% through their window from system-level overhead alone.

[![Image 13](https://substackcdn.com/image/fetch/$s_!Tadj!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F086ba38e-04d5-4b48-a9dc-463299cb4723_759x379.png)](https://substackcdn.com/image/fetch/$s_!Tadj!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F086ba38e-04d5-4b48-a9dc-463299cb4723_759x379.png)

### What you can actually build

This is where Claude Code stops being a productivity tool and starts being a business infrastructure layer.

Each use case below is built as a skill. A skill is a Markdown file that sits in your .claude/skills/ folder. Claude Code reads it on demand and follows it as a step-by-step workflow. You define it once. After that, one line runs the whole thing.

* * *

## The connector layer

Every skill above gets more useful the moment the right connector is active.

Connect Google Sheets and the lead scraping skill uploads results directly. Connect Gmail and the email classification skill reads and labels your real inbox. Connect Figma and your built interfaces land on the design canvas as editable frames.

The skill provides the workflow. The connector provides the live data and the destination. Without connectors you are working on local files. With them you are running operations inside the tools your business already depends on.

Go to Settings > Connectors in Claude Desktop. Over 50 integrations are listed. Authenticate once. Every future session picks them up automatically.

[![Image 14](https://substackcdn.com/image/fetch/$s_!R8yu!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb4dc7898-37ea-43b0-b8bf-cde020c59834_2210x1396.png)](https://substackcdn.com/image/fetch/$s_!R8yu!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb4dc7898-37ea-43b0-b8bf-cde020c59834_2210x1396.png)

### Four MCP servers worth installing first:

[Context7](https://context7.com/) fetches up-to-date library documentation into context. Stops Claude from hallucinating outdated APIs.

[Playwright](https://github.com/microsoft/playwright-mcp) gives Claude browser automation. It can implement, test, and verify UI features by navigating your app itself.

[Excalidraw](https://github.com/walidboulanouar/Ay-Skills/tree/main/skills/excalidraw-diagram) lets Claude generate architecture diagrams and flowcharts as hand-drawn sketches from a prompt.

[DeepWiki](https://docs.devin.ai/work-with-devin/deepwiki-mcp) pulls structured documentation for any GitHub repo. Point Claude at a repo and it gets the full picture without you pasting README files into the chat.

* * *

## Lead scraping

A skill that scrapes a target industry, classifies leads with AI, enriches contact emails, and uploads everything to a Google Sheet.

**Build the skill. Open Claude Code and paste:**

```
Create a Claude Code skill file called lead-scraping.md in a 
.claude/skills/ folder.

The skill should:
1. Scrape business leads for a target industry and location using web search
2. Classify each lead with AI (business name, website, phone, category)
3. Enrich a contact email for each lead where publicly available
4. Upload all results to a Google Sheet

Accept three inputs from the user:
- Industry (e.g. dentists, accountants, solicitors)
- Location (e.g. Manchester UK, United States)
- Number of leads required

Write it as a step-by-step Markdown checklist Claude Code follows 
when the skill is invoked.
```

[![Image 15](https://substackcdn.com/image/fetch/$s_!V1fN!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F380bbbbd-ac9c-4b65-850f-3be02b7bca8f_725x377.png)](https://substackcdn.com/image/fetch/$s_!V1fN!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F380bbbbd-ac9c-4b65-850f-3be02b7bca8f_725x377.png)

**Run it with one line:**

```
Use the lead-scraping skill. 
Industry: dentists
Location: Manchester, UK
Leads required: 20
Upload to this Google Sheet: [YOUR SHEET URL]
```

[![Image 16](https://substackcdn.com/image/fetch/$s_!0f1k!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6391e624-6067-4908-a2e8-770b5ddd7ecf_957x501.png)](https://substackcdn.com/image/fetch/$s_!0f1k!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6391e624-6067-4908-a2e8-770b5ddd7ecf_957x501.png)

* * *

## Proposal generation

A full proposal generator with a brief input form, AI-generated proposals in your voice, a client-facing view with an Accept button, and a payment link field. No PandaDoc subscription. No per-proposal cost.

**Build it using Plan Mode. Switch to Plan Mode first, then paste:**

```
/plan Build a proposal generator web app with the following:
- A brief input form (client name, industry, scope, budget)
- AI-generated proposal output written in my voice using my brand-voice.md file
- A client-facing view of the proposal with an Accept button
- A payment link field I can add manually before sending
- Each proposal saved as a Markdown file in a /proposals folder

Use plain HTML, CSS, and JavaScript. No frameworks.
Read all files in this folder before planning.
Ask me clarifying questions before you start building.
```

[![Image 17](https://substackcdn.com/image/fetch/$s_!jAH3!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fe895aa63-9158-40bd-b9f4-25ca5c8770d7_1450x1034.png)](https://substackcdn.com/image/fetch/$s_!jAH3!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fe895aa63-9158-40bd-b9f4-25ca5c8770d7_1450x1034.png)

This clears the context window before building so tokens used during planning do not eat into your build. Claude Code then executes every step without stopping to ask permission.

* * *

## Website generation

Screenshot a site you admire. Feed it to Claude Code alongside your content and brand guidelines. Get a complete, deployable website without touching a template or page builder.

**Build it. Drag your reference screenshot into the terminal, then paste:**

```
I am going to give you a screenshot of a website I like the design of 
and my own content. Build me a complete single-page website using my 
content but matching the visual style and layout of the reference.

My content:
Headline: [YOUR HEADLINE]
Subheadline: [YOUR SUBHEADLINE]  
Key points: [POINT 1], [POINT 2], [POINT 3]
CTA: [YOUR CTA TEXT]
Brand colour: [HEX CODE]

Build as a single HTML file with embedded CSS.
Produce three layout variants: version-a.html, version-b.html, version-c.html
Run them in parallel.
```

[![Image 18](https://substackcdn.com/image/fetch/$s_!PJW7!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8188677d-5849-4f04-965d-a95d668d13f8_3588x1856.png)](https://substackcdn.com/image/fetch/$s_!PJW7!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8188677d-5849-4f04-965d-a95d668d13f8_3588x1856.png)

**To push the finished build into Figma for design refinement, connect Figma MCP first:**

`claude mcp add --transport http figma https://mcp.figma.com/mcp`
**Then:**

`Start a local server for my app and capture the UI in a new Figma file.`
Claude Code opens a browser, captures the live interface, and sends it to Figma as editable design layers. Refine it on the canvas, push updates back. Design and code stay in sync without manual handoff.

[![Image 19](https://substackcdn.com/image/fetch/$s_!DGxC!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff2cdd7c6-11b8-4bd1-be2b-232302bb98a8_2494x1764.png)](https://substackcdn.com/image/fetch/$s_!DGxC!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff2cdd7c6-11b8-4bd1-be2b-232302bb98a8_2494x1764.png)

* * *

## Video generation

Remotion is an open-source framework that lets you create videos programmatically using React. Every frame is a component. Every animation is code. You describe what you want and Claude Code builds it.

This is not AI generating random video from a text prompt. Claude Code writes the React components that render your video. You get full control, full editability, and the ability to generate variations from a single template.

I used this to build a product launch video for [Vislo, my new AI infographic SaaS.](https://www.vislo.ai/)

Created entirely from the terminal. The first version was rough, and that was down to the quality of the screen recordings I gave it rather than anything Claude Code did wrong. Once I provided better source material and refined the prompts over a few iterations, the output got genuinely good. The fact that you can produce motion graphics from a terminal window is still slightly surreal.

Set it up in four steps.

Step 1. Create a new Remotion project:

`npx create-video@latest`
Select the Blank template, say yes to TailwindCSS, and say yes to install Skills when prompted.

Step 2. Navigate into the folder and start the preview server:

```
cd my-video
npm install
npm run dev
```

Step 3. Open a second terminal window and start Claude Code:

```
cd my-video
claude
```

Step 4. Describe the video you want. Claude Code reads your project, writes the components, and the preview at localhost:3000 updates in real time. When you are happy with the result, render your final MP4:

`npx remotion render`
The quality of your output depends almost entirely on the quality of your source material. Good screen recordings produce good videos. Blurry screenshots produce generic results. Give Claude Code sharp, high-resolution assets and it handles everything else.

One thing to check before using this commercially. Remotion is free for personal use and open source projects. Companies with three or more employees need a commercial licence to render videos for clients. Check remotion.dev/license before building client work on top of it.

Vislo, the tool I built the demo video for, is live. You describe what you want in plain text, Vislo generates share-ready infographics in seconds (no design skills needed). $19/month and the first 100 users lock in that price. Sign up at [https://www.vislo.ai/](https://www.vislo.ai/)

* * *

## How to Claude Code (Intermediate)

![Image 20: User's avatar](https://substackcdn.com/image/fetch/$s_!IZP3!,w_64,h_64,c_fill,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F39496630-b70a-49e7-a88a-db4d48810e00_1080x1078.jpeg)

## Continue reading this post for free, courtesy of Charlie Hills.

[Claim my free post](https://charliehills.substack.com/p/claude-code-beginner-advanced)

[Or purchase a paid subscription.](https://charliehills.substack.com/subscribe?simple=true&next=https%3A%2F%2Fcharliehills.substack.com%2Fp%2Fclaude-code-beginner-advanced&utm_source=paywall&utm_medium=web&utm_content=190182346&just_signed_up=falsesimple=true&utm_source=paywall&utm_medium=email&utm_content=190182346&next=https://charliehills.substack.com/p/claude-code-beginner-advanced)

© 2026 Charlie Hills · [Privacy](https://substack.com/privacy) ∙ [Terms](https://substack.com/tos) ∙ [Collection notice](https://substack.com/ccpa#personal-data-collected)

[Start your Substack](https://substack.com/signup?utm_source=substack&utm_medium=web&utm_content=footer)[Get the app](https://substack.com/app/app-store-redirect?utm_campaign=app-marketing&utm_content=web-footer-button)

[Substack](https://substack.com/) is the home for great culture
