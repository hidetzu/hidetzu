### Hi, I'm hidetzu

**Building software that shows its evidence — and says what it could not verify.**

Software engineer in Tokyo. I write CLIs, small web services and systems experiments in Go, TypeScript, Zig and C.
Much of my recent work asks where an AI should hand a decision back to a human, and how a tool can show
what its answer is based on.

## Questions I'm working on

- **Delegation** — What can an AI coding agent do alone, and when should it stop and ask?
- **Evidence** — Can a tool cite the source of every claim, and keep "not found" apart from "could not check"?
- **Products & systems** — Can those ideas hold up in software people actually run, from web apps to a TCP/IP stack?

## Selected projects

| Project | What it is for | Status |
| --- | --- | --- |
| [flagman](https://github.com/hidetzu/flagman) | Called by an AI coding agent before commit / push / merge. Answers *continue*, *review* or *defer* from repository evidence, logs why, and replays the log to measure whether a rule change reduced "false autonomy". | in development · no release yet |
| [decide-first](https://github.com/hidetzu/decide-first) | Is this GitHub issue ready to hand to an AI agent? Lists what a human has to decide first, using named checks instead of a score. | v0.1.0 · [web](https://decide-first.hidetzu.work) |
| [vulnograph](https://github.com/hidetzu/vulnograph) | Turns a CVE ID into a report and Mermaid diagrams where every claim cites a collected source. Not a scanner. | pre-release v0.1.0-dev.1 |
| [tenken](https://github.com/hidetzu/tenken) | Checks a web site in one run (TLS, redirects, links, security headers, sitemap) and fails CI on problems — and reports what it did not check. | in development · v0.1.0-dev.1 tag |
| [konjaku](https://github.com/hidetzu/konjaku) | What was this place before? Answers from open data published by Japan's GSI, shows the sources it read, and separates "no data" from "could not read". (Japanese) | live · [web](https://konjaku.hidetzu.work) |
| [zemo](https://github.com/hidetzu/zemo) | A terminal memo tool that keeps markdown notes in a git repository, pulling before you write and pushing after. One static binary. | v0.4.1 |

## Also

- [connect-doctor](https://github.com/hidetzu/connect-doctor) — Why does this URL not connect? Checks DNS → TCP → TLS → HTTP and names the first layer that failed. [web](https://connect-doctor.hidetzu.work)
- [claude-dev-template](https://github.com/hidetzu/claude-dev-template) — A Claude Code workflow with human decisions, verification and review, keeping only what reproduced in two projects.
- [prism](https://github.com/hidetzu/prism) / [ccpr](https://github.com/hidetzu/ccpr) — Turn pull requests (GitHub / CodeCommit) into structured context for AI code review.
- [backlog-fzf](https://github.com/hidetzu/backlog-fzf) — Fuzzy and Japanese full-text search across Nulab Backlog issues and documents.
- [dotfiles](https://github.com/hidetzu/dotfiles) — A macOS client and an Arch Linux dev host (WezTerm, fish, Neovim).

## Experiments

Open questions more than finished tools.

- [tcpip-stack](https://github.com/hidetzu/tcpip-stack) — A user-space TCP/IP core in C, interoperated with the Linux kernel over a TAP device. It has no application-facing TCP API yet.
- [verigen](https://github.com/hidetzu/verigen) — Generate, then let a strict verifier throw away almost everything. What a generate → verify loop looks like when generation guarantees nothing. (Japanese)
- [vrestore](https://github.com/hidetzu/vrestore) — Restore a fixed region of a video from pixels visible in other frames, and report which pixels could not be restored. Zig. (Japanese)

## Writing

- [Zenn](https://zenn.dev/hidetzu) — in Japanese
- [DEV Community](https://dev.to/hidetzu) — in English

More context, and why these projects exist: **[hidetzu.work](https://hidetzu.work)**
