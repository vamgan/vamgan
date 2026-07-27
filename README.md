<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4f46e5,100:06b6d4&height=180&section=header&text=Vamil&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Teaching%20machines%20what%20you%20actually%20meant&descAlignY=55&descSize=16" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=800&color=4F46E5&center=true&vCenter=true&width=680&lines=Models+are+smart.+Context+is+the+bottleneck.;I+build+the+plumbing+for+the+second+one.;Zero+backend.+One+attribute.+No+screenshots." alt="Typing SVG" />
</a>

[![Website](https://img.shields.io/badge/askable--ui.com-4f46e5?style=for-the-badge&logo=googlechrome&logoColor=white)](https://askable-ui.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vamgan)
[![Docs](https://img.shields.io/badge/Read_the_docs-06b6d4?style=for-the-badge&logo=readthedocs&logoColor=white)](https://askable-ui.com/docs/)

</div>

<br/>

```console
$ whoami
vamil

$ cat ~/.config/vamil/manifest.toml
```
```toml
[identity]
role        = "software engineer"
obsession   = "context — the thing models never have enough of"
hot_take    = "your AI feature isn't underpowered, it's underinformed"

[currently]
building    = "askable-ui"
maintaining = "two CLIs and one grudge against stale system prompts"
rewriting   = "this README (v5, allegedly final)"

[will_not]
ship_if     = "it needs a backend just to try it"
```

<br/>

---

<div align="center">

# 👁️ askable-ui

### **Give your LLM eyes.**
#### One attribute for humans. One protocol for agents.

[![npm](https://img.shields.io/npm/v/@askable-ui/core?color=4f46e5&label=npm&style=flat-square)](https://www.npmjs.com/package/@askable-ui/core)
[![downloads](https://img.shields.io/npm/dw/@askable-ui/core?color=4f46e5&label=downloads&style=flat-square)](https://www.npmjs.com/package/@askable-ui/core)
[![stars](https://img.shields.io/github/stars/askable-ui/askable?color=4f46e5&style=flat-square)](https://github.com/askable-ui/askable)
[![license](https://img.shields.io/npm/l/@askable-ui/core?color=4f46e5&style=flat-square)](https://github.com/askable-ui/askable/blob/main/LICENSE)

</div>

We've all shipped this conversation:

> **User:** *"explain this"*
> **Your $20/million-token frontier model:** *"Could you clarify which metric you're referring to?"*

The model isn't the problem. It's sitting in the dark. Your options were a hand-written system prompt that goes stale the second someone moves a card, or a screenshot that costs a fortune and throws away the actual data.

There's a third option, and it's one attribute:

```jsx
<Askable meta={{ metric: 'net revenue retention', value: '118%', delta: '+6pp' }}>
  <NRRCard data={data} />
</Askable>
```

That's the whole integration. The model now sees the real, live data behind whatever the user clicked, hovered, or scrolled to — refreshed on every interaction. No screenshots. No stale prompts. No clarifying questions.

<details>
<summary><b>🔬 What's actually in the box</b> — click, it's good</summary>

<br/>

| | |
|:--|:--|
| 📦 **An open wire format** | Everything serializes to the `askable.context` Context Packet — a versioned JSON envelope carrying what was captured, how, and whether it was redacted under what consent. Privacy is a first-class field, not a retrofit bolted on after the incident review. askable-ui is the reference implementation; anyone can speak the protocol. |
| 🔌 **An MCP bridge** | One command and Claude Desktop or Cursor can call `get_current_context` against your running app. It sees what your user sees. Slightly unsettling. Very useful. |
| 🎯 **Explicit capture** | Region, circle, lasso, and text-selection tools — because sometimes the user just wants to draw a circle around the weird number and say "this one." |
| 🧠 **30+ context sources** | Forms, tables, errors, cart, wizard progress, routes, Core Web Vitals. All the app state a model cannot possibly infer from the DOM, no matter how confidently it tries. |
| ⚛️ **Nine framework adapters** | React · Vue · Svelte 4 & 5 · Solid · Angular · Qwik · React Native · Web Components · zero-dependency vanilla JS. Yes, Angular too. I did it so you wouldn't have to. |

</details>

<div align="center">

[**📖 Docs**](https://askable-ui.com/docs/) · [**🚀 Live Demo**](https://askable-mu.vercel.app/) · [**📜 Protocol Spec**](https://askable-ui.com/docs/guide/protocol) · [**⭐ Repo**](https://github.com/askable-ui/askable)

</div>

<br/>

---

## 🛠️ Also in the workshop

<table>
<tr>
<td width="50%" valign="top">

### 🔄 [SameSession](https://github.com/vamgan/same-session)
**Same session. Different machine.**

Your agent has three hours of context and you have a train to catch. SameSession moves a live Codex CLI or Claude Code session to another machine — or hands it to a teammate — with the session ID, transcript bytes, local commits, and your gloriously dirty working tree intact.

Age-encrypted capsules riding append-only Git refs. **No server in the middle.** Nobody's context lives on my hardware, including mine.

`Rust` · `CLI` · pre-release

</td>
<td width="50%" valign="top">

### 🔥 [roastmaster](https://github.com/vamgan/roastmaster)
**The only code reviewer that hates you.**

Finds the bug. Fixes the bug. Leaves a passive-aggressive comment about the bug.

Built because code review was boring and I wanted to be humbled by a machine on a schedule of my own choosing.

Genuinely useful. Emotionally devastating.

`TypeScript` · `CLI`

</td>
</tr>
</table>

<div align="center">

Contributor to the [**Strands Agents SDK**](https://github.com/strands-agents/sdk-python)

</div>

<br/>

---

## 💼 By day

Software engineer at **Amazon**, building AI systems and the analytics tooling that sits on top of them — natural language querying, dashboards, and the unglamorous infrastructure that keeps both honest at scale. The bar is that someone asks a question the way a human would ask it and gets an answer they can trust, without first learning SQL, a schema, and four internal acronyms.

Which is, suspiciously, the same thing I do on nights and weekends. My therapist and I are looking into it.

<br/>

---

## 🐛 Known issues · won't fix

- **Cannot ship anything that requires a backend to try it.** If you can't `npx` it inside ten seconds, I lose interest, and so does everyone else — they're just too polite to file the issue.
- **Will spend four hours designing an API so you only have to type one attribute**, then describe it in the README as "one line of code," which is technically true and spiritually a flex.
- **Believes the protocol outlives the library that implemented it first.** Will bring this up unprompted. At parties. To people who did not ask.
- **Checks whether someone already built it before proposing it.** Usually they did. Occasionally they built it badly, which is the entire opportunity.
- **Has rewritten this README more times than any reasonable person would defend.** See `[currently].rewriting` above. The number is not accurate. It is a floor.

<br/>

<div align="center">

### 🤝 Say hi

Open an issue on any repo — bug reports, protocol arguments, and roasts all welcome.
(I built a tool for that last one. It's right up there. It's better at it than you.)

[**LinkedIn**](https://www.linkedin.com/in/vamgan) · [**askable-ui.com**](https://askable-ui.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,100:4f46e5&height=120&section=footer" width="100%" />

</div>
