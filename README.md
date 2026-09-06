# vamil

<sub>software engineer at amazon · building [askable-ui](https://github.com/askable-ui/askable) · teaching machines what you actually meant</sub>

Natural language querying, dashboards, and the unglamorous infrastructure that
keeps both honest at scale. Nights and weekends, suspiciously, the same thing.
My therapist and I are looking into it.

Models are smart. Context is the bottleneck. Somebody has to build the plumbing
for the second one.

<br/>

## 🟢 open issues

| | | |
|:-:|:--|--:|
| 🟢 | **#1 · ships nothing that requires a backend to try it**<br><sub>if you can't `npx` it inside ten seconds i lose interest — and so does everyone else, they're just too polite to file the issue.</sub> | `wontfix` |
| 🟢 | **#2 · spends four hours designing an API so you only type one attribute**<br><sub>then describes it in the README as "one line of code." technically true. spiritually a flex.</sub> | `by design` |
| 🟢 | **#3 · believes the protocol outlives the library that shipped it first**<br><sub>brings this up at parties. to people who did not ask.</sub> | `wontfix` |
| 🟢 | **#4 · checks whether someone already built it before proposing it**<br><sub>usually they did. occasionally they built it badly, which is the entire opportunity.</sub> | `works as intended` |
| 🟢 | **#5 · has rewritten this README more times than any reasonable person would defend**<br><sub>you are reading v8. "v5, allegedly final" did not survive contact with v5.</sub> | `wontfix` |
| 🟢 | **#6 · starts the next repo before the last one has a single star**<br><sub>four of them in five days, once. the ideas do not queue politely and i have never learned to make them.</sub> | `wontfix` |

<br/>

## 🟣 merged anyway

<sub>the first three are one obsession from three angles: getting context into a model that does not have it.</sub>

**[askable-ui](https://github.com/askable-ui/askable)** — give your LLM eyes.
One attribute for humans, one protocol for agents: the live data behind whatever
your user clicked, hovered, or circled, handed to the model on every
interaction. No screenshots. No stale system prompts. Nine framework adapters,
an MCP bridge, an open wire format.
<sub>[site](https://askable-ui.com) · [docs](https://askable-ui.com/docs/) · [demo](https://askable-mu.vercel.app/) · [protocol spec](https://askable-ui.com/docs/guide/protocol) · [npm](https://www.npmjs.com/package/@askable-ui/core)</sub>

**[same-session](https://github.com/vamgan/same-session)** — same session,
different machine. Moves a live Codex CLI or Claude Code session to another
machine: session ID, transcript, local commits, and your gloriously dirty
working tree intact. Age-encrypted capsules riding git refs, no server in the
middle. Nobody's context lives on my hardware, including mine.
<sub>rust · cli · pre-release</sub>

**[review-to-rule](https://github.com/vamgan/review-to-rule)** — a reviewer
catches it once, every future coding agent remembers. Turns accepted review
feedback into scoped rules that live in the repo, so the same note doesn't get
written by hand on four more pull requests. Reads GitHub, GitLab, Bitbucket,
Gerrit and Azure Repos; dry-runs everything and writes nothing without you
saying so.
<sub>typescript · claude code plugin · codex skill · new</sub>

**[roastmaster](https://github.com/vamgan/roastmaster)** — the only code
reviewer that hates you. Finds the bug. Fixes the bug. Leaves a
passive-aggressive comment about the bug. Genuinely useful. Emotionally
devastating.
<sub>typescript · cli</sub>

<sub>also shipped: **[openpresent](https://github.com/vamgan/openpresent)** — local-first presentation runtime for agents; real React slides edited in place, not regenerated · **[declutter](https://github.com/vamgan/declutter)** — your computer is a mess, teach your agent to clean it · contributor to the [strands agents sdk](https://github.com/strands-agents/sdk-python)</sub>

<br/>

## 🔵 file a new one

These open a real, pre-filled issue on this repo. No signup, no form, no
backend — see #1.

**[🐛 report a bug in me](https://github.com/vamgan/vamgan/issues/new?title=bug%3A%20&body=expected%3A%0A%0Aactual%3A%0A%0Asteps%20to%20reproduce%3A)** · **[📜 argue about the protocol](https://github.com/vamgan/vamgan/issues/new?title=protocol%20argument%3A%20&body=askable.context%20should%20...%0A%0Areasoning%3A)** · **[🔥 roast me](https://github.com/vamgan/vamgan/issues/new?title=roast&body=pick%20a%20repo.%20be%20specific.)**

<sub>fair warning on that last one: i built a tool for it, and it's better at this than you are.</sub>

<br/>

---

<sub>[askable-ui.com](https://askable-ui.com) · [linkedin](https://www.linkedin.com/in/vamgan)</sub>
