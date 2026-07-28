<div align="center">

# ✨ Nova-Violet Role

**Editor & Architect · Non-Profit Organization**

*Merging Law, Code, and Sensory Analysis to Decompile Reality*

[![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/saimonokuma)
[![Open Source](https://img.shields.io/badge/Open-Source-9b59b6?style=for-the-badge)](https://github.com/Nova-Violet-Role)
[![Non-Profit](https://img.shields.io/badge/Non--Profit-Community%20Driven-764ba2?style=for-the-badge)](https://github.com/Nova-Violet-Role)

</div>

---

## 📜 About

**Nova-Violet Role** is a non-profit organization working at the intersection of cognitive
science, law, and software — building frameworks that let people approach complex problems
from more than one angle at a time.

**🎯 Mission** — Develop and share convergent cognitive frameworks that help individuals and
organizations think in more dimensions than a single discipline allows.

**🌟 Vision** — A world where complex problems are met with holistic, multi-faceted thinking
rather than one lens applied harder.

---

## 🧠 The NOVA System

Five lenses on the same problem. Each is incomplete alone; the system is the overlap.

| Lens | What it does |
|:--|:--|
| 🔮 **Emotional Resonance** | Reads the problem through emotional intelligence and empathy — the human element others miss |
| 🛡️ **Immunological Purification** | Filters noise from signal; the defensive layer against cognitive contamination |
| 👑 **Sovereign Execution** | Autonomous decision-making and implementation — the arm that actually ships |
| 🌪️ **Chaos Weaving** | Treats chaos as a creative force, finding pattern in the apparently random |
| 🌌 **Omniscient Coalescence** | The convergence point where the other four unite into synthesis |

> *"Each one is a different way of seeing the same problem. Together, they see everything."*

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

## 🚀 Projects & Initiatives

### 🔄 Rolling Context — Lean 4
Context compression as a transparent proxy: old messages compress while recent context stays
verbatim, so a conversation never hits the wall. Ships with a **Lean 4 formalization** —
157 theorems, zero `sorry` — proving the compression policy rather than asserting it, plus a
port to the Mistral Vibe CLI with an eight-agent routed crew.

➜ [`claude-rolling-context-Lean-4-`](https://github.com/Nova-Violet-Role/claude-rolling-context-Lean-4-)

### 💻 GHC Compiler Python
⚡ *The bridge between Haskell and Python.* The first pip-installable Glasgow Haskell
Compiler — one command, three platforms, the full toolchain.

- ✅ `pip install ghc-python`
- ✅ Windows, macOS, Linux
- ✅ Full GHC compiler included
- ✅ Complete Cabal support
- ✅ Any AI with Python execution can now compile Haskell

### 🔧 Tetra's Echo Location
A sensory analysis framework mapping cognitive landscapes through echo-based feedback systems.

### 🌿 Project Symbiose
An ecosystem of interconnected cognitive tools built to form symbiotic relationships between
the people using them and the problems they face.

---

## 🤝 Contributing

| Area | How you can help |
|:--|:--|
| 💻 **Code** | Help develop our cross-platform applications |
| 🔬 **Research** | Contribute to cognitive framework development |
| 📖 **Documentation** | Improve our guides and tutorials |
| 🧪 **Testing** | Provide feedback on beta releases |
| 💡 **Ideas** | Share your vision for the future of cognitive tools |

### 💬 Connect

- **Ko-fi** — [ko-fi.com/saimonokuma](https://ko-fi.com/saimonokuma)
- **GitHub** — [our repositories](https://github.com/Nova-Violet-Role) are open and public
- **Community** — join a growing network of thinkers and builders

---

## 📄 License & Philosophy

As a non-profit, Nova-Violet Role is committed to open knowledge and collaborative development.

| | |
|:--|:--|
| 🔓 **Open Source** | Our tools are freely available |
| 🌍 **Global Access** | Available to everyone, everywhere |
| ❤️ **Community Driven** | Built by and for the community |
| 🎯 **Mission Focused** | Advancing cognitive understanding |

---

<div align="center">

### ✨ Nova-Violet Role

*Decompiling Reality — One Framework at a Time*

[![Support Our Journey](https://img.shields.io/badge/🔗_Support_Our_Journey-Ko--fi-FF5E5B?style=for-the-badge)](https://ko-fi.com/saimonokuma)

© 2026 Nova-Violet Role · Non-Profit Organization
All frameworks open-source under permissive licences

*Created with ❤️ for the advancement of human understanding*

</div>
