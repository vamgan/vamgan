# vamil

Software engineer at Amazon by day — natural language querying, dashboards,
and the unglamorous infrastructure that keeps both honest at scale. By night,
suspiciously, the same thing. My therapist and I are looking into it.

The through-line: models are smart, context is the bottleneck, and somebody
has to build the plumbing for the second one.

<br/>

### open issues · status: wontfix

**#1 — cannot ship anything that needs a backend to try it.**
If you can't `npx` it inside ten seconds I lose interest, and so does everyone
else — they're just too polite to file the issue.

**#2 — will spend four hours designing an API so you only type one attribute,**
then describe it in the README as "one line of code." Technically true.
Spiritually a flex.

**#3 — believes the protocol outlives the library that shipped it first.**
Brings this up at parties. To people who did not ask.

**#4 — checks whether someone already built it before proposing it.**
Usually they did. Occasionally they built it badly, which is the entire
opportunity.

**#5 — has rewritten this README more times than any reasonable person
would defend.** You are reading v6. "v5, allegedly final" did not survive
contact with v5.

<br/>

### shipped anyway

**[askable-ui](https://github.com/askable-ui/askable)** — give your LLM eyes.
One attribute for humans, one protocol for agents: the live data behind
whatever your user clicked, hovered, or circled, handed to the model on every
interaction. No screenshots, no stale system prompts. See issues #1–#3.
<sub>[site](https://askable-ui.com) · [docs](https://askable-ui.com/docs/) · [demo](https://askable-mu.vercel.app/) · [protocol spec](https://askable-ui.com/docs/guide/protocol)</sub>

**[same-session](https://github.com/vamgan/same-session)** — same session,
different machine. Moves a live Codex CLI or Claude Code session to another
machine — session ID, transcript, local commits, and your gloriously dirty
working tree intact. Age-encrypted capsules riding git refs; no server in the
middle. Nobody's context lives on my hardware, including mine.
<sub>rust · cli</sub>

**[roastmaster](https://github.com/vamgan/roastmaster)** — the only code
reviewer that hates you. Finds the bug, fixes the bug, leaves a
passive-aggressive comment about the bug. Built because I wanted to be humbled
by a machine on a schedule of my own choosing. Genuinely useful. Emotionally
devastating.
<sub>typescript · cli</sub>

<sub>also: contributor to the [strands agents sdk](https://github.com/strands-agents/sdk-python)</sub>

<br/>

---

<sub>Say hi — open an issue on any repo. Bug reports, protocol arguments, and
roasts all welcome. I built a tool for that last one; it's better at it than
you. · [askable-ui.com](https://askable-ui.com) · [linkedin](https://www.linkedin.com/in/vamgan)</sub>
