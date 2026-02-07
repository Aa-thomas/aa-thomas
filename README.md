# I build the tools that make AI agents work.

Full-stack developer · TypeScript · Rust · Python · React  
Building open-source AI developer tools — CLIs, dashboards, and agent extensions.

> I spent 7 years in operations designing SOPs and training systems before moving into software.  
> When AI coding agents shipped, I noticed they fail the same way new hires do — they skip docs, ignore process, and don't know when to ask for help. So I started building the missing layer.

---

## What I'm shipping

<table>
<tr>
<td width="50%" valign="top">

### [Conduit](https://github.com/aaron/conduit)
**MCP protocol toolkit** · `TypeScript`

Every tool call in Claude Code, Codex, and Cursor runs over MCP. Conduit lets you discover any MCP server's tools, invoke them from the command line, and generate fully-typed TypeScript clients from their schemas.

Postman for the agent era.

</td>
<td width="50%" valign="top">

### [Pulse](https://github.com/aaron/pulse)
**AI usage dashboard** · `Rust` `Tauri` `React`

Tracks rate limits, session windows, and costs across Claude, Codex, Cursor, and Gemini in one system tray app. Rust backend with async polling and platform-native keychains. React frontend. ~5MB binary on macOS, Windows, and Linux.

Cross-platform rebuild of [CodexBar](https://github.com/steipete/CodexBar) (5K+ ⭐).

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Echo](https://github.com/aaron/echo)
**Second-opinion skill for AI agents** · `Python`

Your AI coding agent is stuck. Echo bundles the current context and asks a different model — GPT, Gemini, or Claude — for a fresh perspective. Built as a native [Agent Skill](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills), works across every major coding agent.

</td>
<td width="50%" valign="top">

### [Signal](https://github.com/aaron/signal)
**Process guardrails for AI agents** · `Python` `Shell`

Five skills that teach AI agents to follow professional standards: generate SOPs, enforce commit conventions, onboard before coding, create training docs, and log every architectural decision.

The ops background meets the AI stack.

</td>
</tr>
</table>

<details>
<summary><b>How they connect →</b></summary>
<br>

```
Conduit  (protocol)    →  how agents discover and call tools
Pulse    (monitoring)  →  how you track what they consume
Echo     (intelligence)→  how they recover when stuck
Signal   (knowledge)   →  how they follow your standards
```

Signal's skills invoke tools through Conduit. Echo logs decisions through Signal. Pulse monitors the providers Echo calls. One system, not four repos.

</details>

---

### Tech

| | |
|:--|:--|
| **Languages** | TypeScript · Rust · Python · JavaScript · Shell |
| **Frontend** | React · Tailwind CSS · HTML/CSS |
| **Backend** | Node.js · Express · tokio (Rust async) |
| **AI / Agent** | MCP protocol · Agent Skills · Claude Code · Codex · Vercel AI SDK |
| **Desktop** | Tauri v2 · System tray APIs · Platform keychains |
| **Tools** | Git · GitHub Actions · Docker · Linux · VS Code |

---

All four projects are in active development. I build in public and I'm always up for a conversation about AI tooling.

<p align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aaronthomas-dev)
&nbsp;
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/the_aaronthomas)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=black)](https://aaronthomas.dev)

</p>
