# 🕹️ Damien's Arcade

A password-gated landing page that links Damien's web games together as tiles.

**[Open the arcade](https://aapearce.github.io/damiens-arcade/)** (GitHub Pages)

## Games

| Game | What it is |
| --- | --- |
| 👹 **[Damien's Maze Runner](https://aapearce.github.io/damiens-maze-runner/)** | First-person 3D maze — escape across three levels while masked monsters roam. |
| 🚇 **[Damien's Underground Match](https://aapearce.github.io/TUBEMATCH/)** | London Underground memory/matching game. |

## How it works

- A single self-contained `index.html` (inline CSS + JS), so it deploys instantly on GitHub Pages with no build step.
- Entering the password reveals the game tiles. The unlock is remembered for the browser session (closes when the tab does); a **🔒 Lock arcade** button re-locks it.

## ⚠️ A note on the password

The password gate is **client-side only** — it's enough to keep casual visitors out, but it is **not real security**. Anyone who views the page source can read the password. Don't use this to protect anything sensitive. For genuine protection you'd need a server-side login (happy to add one later).

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
