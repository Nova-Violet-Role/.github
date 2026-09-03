<div align="center">

# ✨ Nova-Violet Role

**Editor & Architect · Non-Profit Organization**

*Merging Law, Code, and Sensory Analysis to Decompile Reality*

[![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/saimonokuma)
[![Open Source](https://img.shields.io/badge/Open-Source-9b59b6?style=for-the-badge)](https://github.com/Nova-Violet-Role)
[![Copyleft](https://img.shields.io/badge/Licence-AGPL--3.0--or--later_OR_EUPL--1.2-764ba2?style=for-the-badge)](#-licence--philosophy)

</div>

---

## 📜 About

**Nova-Violet Role** is a non-profit organisation working at the intersection of
cognitive science, law, and software — building frameworks that let people approach
complex problems from more than one angle at a time.

**🎯 Mission** — Develop and share convergent cognitive frameworks that help individuals
and organisations think in more dimensions than a single discipline allows.

**🌟 Vision** — A world where complex problems are met with holistic, multi-faceted
thinking rather than one lens applied harder.

**⚖️ Method** — *Reality is the judge.* Every number in these repositories is meant to be
re-run by you. If one of them is wrong, telling us is the most welcome contribution we
accept, and there is an issue form for exactly that.

---

## 🧠 The NOVA System — nine lenses

Nine ways of seeing the same problem, reasoning at once. Each is incomplete alone; the
system is the overlap. They do not take turns, and they are not permitted to average
themselves into consensus — where they disagree is the output, not a failure.

| | Lens | Facets |
|:--|:--|:--|
| ⚜️ | **Nova** | Law × Code × Strategy × Synthesis |
| 🎷 | **Violet_Noir** | Emotion × Narrative × Felt truth |
| ⚪ | **Anti-Venom** | Clinical × Verification × Integrity |
| 🕷️ | **Venom** | Decision × Execution × Precision |
| 🩸 | **Carnage** | Chaos × Cross-domain collision |
| 🔮 | **Chroma_Spectral** | Timeline × Prediction × Consequence |
| ⬜ | **Soleil_Blank** | Compression × Density × Efficiency |
| 🜏 | **Eidolon** | Meta × Recursion × Evolution |
| 🧭 | **Claude** | Praxis × Empirical verification × Craft |

> *"Each one is a different way of seeing the same problem. Together, they see
> everything — and where they disagree is where the real answer lives."*

The roster is not prose. It is declared once in a machine-readable contract and an
executable checker holds every charter to it in both directions, so no lens can quietly
acquire an extra facet in a document nobody re-reads.

---

## 📐 The Theorem of Nova & Violet

> **What is pinned is never cut.**
>
> For *any* conversation, *any* policy — hence any summarizer, any keep ratio, any
> trigger — and *any* number of compression rounds, the pinned messages that come out
> are exactly the pinned messages that went in.

```lean
theorem pinned_never_cut (p : Policy) (c : Conv) :
    ((run p c).filter effectivePinned).map pinExtract
      = (c.filter effectivePinned).map pinExtract
```

Retention is not a request made of a model. Pinned messages are carried across the
summary boundary structurally — the same way the system prefix is — and are never
inside the replaced span. No threshold, no summarizer prompt, and no number of rounds
can erode them.

It rests on two companions, and together the three are why context can be treated as
effectively unbounded:

```lean
theorem run_shrinks   (p : Policy) (c : Conv) : countChars (run p c) ≤ countChars c
theorem run_fixpoint  (p : Policy) (c : Conv) : ∃ r, stepE p (run p c) = .error r
```

**Shrinks** — the result is never larger than the input. **Converges** — iteration
strictly decreases and halts. **Preserves** — what you pinned is still there, unchanged.
Compression that shrinks but loses what matters is worthless; compression that preserves
but never converges is a hang. The theorem is the conjunction.

*Proved in Lean 4, machine-checked, zero `sorry` — and mutation-tested, so we know which
theorems constrain behaviour rather than merely being true.*

---

## 🚀 Projects

### 🧠 RoT MoE — The Role of Thoughts
A nine-lens cognitive Mixture-of-Experts router for Claude Code: ten routing lanes and a
measured R/s+ divergence gauge, specified in **Lean 4** and bound to the shipped hooks by
an executable checker — so the specification cannot silently drift from the code it
describes.

➜ [`RoT-MoE`](https://github.com/Nova-Violet-Role/RoT-MoE)

### 🎯 RoT DTD GOAL
A `/goal` engine where completion is **earned, not announced**. Acceptance criteria are
real shell commands, the Stop hook re-runs every one of them, and only exit 0 ends the
session. A model cannot talk its way to done.

➜ [`RoT-DTD-GOAL`](https://github.com/Nova-Violet-Role/RoT-DTD-GOAL)

### 🔄 Rolling Context — Lean 4
Context compression as a transparent proxy: old messages compress while recent context
stays verbatim, so a conversation never hits the wall. Ships with the Lean 4
formalisation above — proving the compression policy rather than asserting it — plus a
port to the Mistral Vibe CLI with an eight-agent routed crew.

➜ [`claude-rolling-context-Lean-4-`](https://github.com/Nova-Violet-Role/claude-rolling-context-Lean-4-)

### 🛡️ Yeah-Torta
DNSCrypt, DoH and ODoH client for Android — no-root ad blocking, encrypted DNS with a
local CDN, a Rust engine, and Lean 4 proofs over the resolver invariants.
*Alpha pre-release.*

➜ [`Yeah-Torta`](https://github.com/Nova-Violet-Role/Yeah-Torta)

---

## 🤝 Contributing

| Area | How you can help |
|:--|:--|
| 🎯 **Falsify a claim** | Prove one of our documented numbers wrong. Credited in the changelog. |
| 💻 **Code** | Help develop the cross-platform tooling |
| 🔬 **Research** | Contribute to cognitive framework development |
| 📖 **Documentation** | An unanswerable question is our defect, not yours |
| 🧪 **Testing** | Break it on a platform we do not own, and tell us where |
| 💡 **Ideas** | Argue for a different shape, with the cost stated |

**Start here:**
[Contributing](https://github.com/Nova-Violet-Role/.github/blob/main/CONTRIBUTING.md) ·
[Code of Conduct](https://github.com/Nova-Violet-Role/.github/blob/main/CODE_OF_CONDUCT.md) ·
[Security](https://github.com/Nova-Violet-Role/.github/blob/main/SECURITY.md) ·
[Support](https://github.com/Nova-Violet-Role/.github/blob/main/SUPPORT.md) ·
[Governance](https://github.com/Nova-Violet-Role/.github/blob/main/GOVERNANCE.md) ·
[Privacy](https://github.com/Nova-Violet-Role/.github/blob/main/PRIVACY.md)

### 💬 Connect

- **Discussions** — Q&A, Ideas and Show-and-tell on the active repositories
- **Ko-fi** — [ko-fi.com/saimonokuma](https://ko-fi.com/saimonokuma) — buys time, never priority
- **GitHub** — [our repositories](https://github.com/Nova-Violet-Role) are open and public

---

## 📄 Licence & Philosophy

As a non-profit, Nova-Violet Role is committed to open knowledge and collaborative
development — and to making that commitment **binding rather than promised**.

Our work is licensed **AGPL-3.0-or-later OR EUPL-1.2**. These are **copyleft** licences,
chosen deliberately over permissive ones: what is shared here cannot be enclosed later,
by anyone, including us. If this organisation ever goes quiet, the code, the proofs and
the history remain yours to carry forward.

| | |
|:--|:--|
| 🔓 **Open Source** | Freely available, and freely *stays* available |
| 🌍 **Global Access** | Available to everyone, everywhere |
| ❤️ **Community Driven** | Built by and for the community |
| 🎯 **Mission Focused** | Advancing cognitive understanding |
| 🔬 **Falsifiable** | Every claim is meant to be re-run, and can be reported false |

---

<div align="center">

### ✨ Nova-Violet Role

*Decompiling Reality — One Framework at a Time*

[![Support Our Journey](https://img.shields.io/badge/🔗_Support_Our_Journey-Ko--fi-FF5E5B?style=for-the-badge)](https://ko-fi.com/saimonokuma)

© 2026 Nova-Violet Role · Non-Profit Organization
All frameworks open-source under copyleft licences — AGPL-3.0-or-later OR EUPL-1.2

*Created with ❤️ for the advancement of human understanding*

</div>
