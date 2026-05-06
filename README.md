## 👋 Hi, I'm hidetzu

Building **Prism** — a review context compiler for AI.

> AI review quality does not start with the model.  
> It starts with review design.

---

## 🔷 What is Prism?

**Prism** decomposes pull requests into structured context so that AI can review them consistently and reliably.

Pull Request → Structured Context → Stable AI Review

Instead of asking:
- Why is AI review inconsistent?

Prism focuses on:
- What should we feed into AI to make reviews stable?

---

## 🧠 Philosophy

Most tools try to make AI smarter.

Prism takes a different approach:

Make the input better, not the model.

- Define what to review  
- Define how deep to review  
- Define what context to include  

Prism turns these into a reproducible system.

---

## ⚙️ Core Projects

### 🔹 Prism (Main)
- Review Context Compiler
- PR → structured JSON / prompt
- Change type / risk / review axes analysis
- Multi-mode review (light / detailed / cross)

👉 https://github.com/hidetzu/prism

---

### 🔸 ccpr (Adapter)
- AWS CodeCommit PR fetcher
- Used as a provider for Prism

👉 https://github.com/hidetzu/ccpr

### 🔹 zemo (Personal Knowledge)
- Minimalist Git-based notebook for developers
- Single binary (Zig) with auto-sync and AI-friendly dump command
- Turn your daily journals into structured context for AI
👉 https://github.com/hidetzu/zemo

---

## 🚀 Vision

AI-native development needs a missing layer:

Code → PR → ❌ (missing layer) → AI → Review

Prism fills that gap:

Code → PR → Prism → AI → Stable Review

---

## 🧩 What I'm building

- CLI for developers  
- API (Fly.io / Cloudflare)  
- GitHub Actions integration  
- Review Policy as Code  
- AI review evaluation pipeline  

---

## 📌 Focus Areas

- AI-assisted development workflows  
- Review system design  
- Context engineering for LLMs  
- Developer tooling (CLI-first)  

---

## 📝 Writing

- https://zenn.dev/hidetzu

---

## 🤝 Let's connect

Interested in:
- AI + Dev workflows  
- OSS collaboration  
- Review automation systems  

---

## ⚡ Tagline

Stop prompting. Start structuring.
