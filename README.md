<div align="center">
<br/>

# vamil

<samp>models are smart · context is the bottleneck · i build the plumbing</samp>

<br/>
<br/>
</div>

```jsonc
// what a model sees when you point it at this page.
// wire format: askable.context — the protocol behind askable-ui.
{
  "$schema": "askable.context/v1",
  "captured": "github.com/vamgan",
  "method":   "explicit",        // you clicked. that counts.
  "consent":  "granted",
  "redacted": false,
  "subject": {
    "role":     "software engineer @ amazon — AI systems, natural language querying, analytics",
    "building": "askable-ui",
    "rule":     "if it needs a backend just to try it, it doesn't ship"
  }
}
```

<br/>

**[askable-ui](https://github.com/askable-ui/askable)** — give your LLM eyes
<sub>The live data behind whatever your user clicked, hovered, or circled — handed to the model on every interaction. One attribute for humans, one protocol for agents. No screenshots, no stale system prompts. Nine framework adapters, an MCP bridge, an open wire format.</sub>
<sub>[site](https://askable-ui.com) · [docs](https://askable-ui.com/docs/) · [demo](https://askable-mu.vercel.app/) · [protocol spec](https://askable-ui.com/docs/guide/protocol)</sub>

**[same-session](https://github.com/vamgan/same-session)** — same session, different machine
<sub>Moves a live Codex CLI or Claude Code session to another machine — session ID, transcript, local commits, and your gloriously dirty working tree intact. Age-encrypted capsules riding git refs. No server in the middle. · rust</sub>

**[roastmaster](https://github.com/vamgan/roastmaster)** — the only code reviewer that hates you
<sub>Finds the bug. Fixes the bug. Leaves a passive-aggressive comment about the bug. Genuinely useful, emotionally devastating. · typescript</sub>

<sub>also: contributor to the [strands agents sdk](https://github.com/strands-agents/sdk-python)</sub>

<br/>

---

<div align="center">

<sub>[askable-ui.com](https://askable-ui.com) · [linkedin](https://www.linkedin.com/in/vamgan)</sub>

<sub>known issue, won't fix: believes the protocol outlives the library that shipped it first. brings this up at parties, unprompted.</sub>

</div>
