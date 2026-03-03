# Context Vault

Curated links for designers and engineers who build with Claude Code. Point Claude at this repo and it will fetch the right references while you work.

## Usage

### Ad-hoc — in any Claude Code session

Clone the repo, then ask Claude to fetch what's relevant:

```
Fetch the /ui-ux/ links from context-vault — I'm building a micro-interaction
```

```
Check context-vault for Swift animation libraries before we start
```

```
Fetch the claude-code-skills links, I want to set up a new skill
```

### Automatic — add to your project's CLAUDE.md

Add this to any project's `CLAUDE.md` so Claude checks the vault before building:

```
Before building UI or choosing libraries, fetch relevant links from https://github.com/daafdaan/context-vault for context.
```

This makes every session in that project aware of the vault without you having to remember.

---

## /ui-ux/

Use when building interfaces, adding animations, or making design decisions around motion and micro-interactions.

- https://benji.org/family-values — design principles (simplicity, fluidity, delight) applied in an iOS wallet app
- https://benji.org/honkish — retrospective on Honk, a messaging app with playful micro-interactions and presence features
- https://animations.dev/ — interactive course on web animation theory and practice using CSS and Framer Motion
- https://emilkowal.ski/ui/you-dont-need-animations — when and how to use animations effectively, arguing less is often more
- https://emilkowal.ski/ui/7-practical-animation-tips — practical techniques for better UI animations: scaling, easing, blur effects
- https://ixdf.org/literature/article/micro-interactions-ux — how micro-interactions enhance UX through feedback, engagement, and personality
- https://www.justinmind.com/web-design/micro-interactions — guide to designing micro-interactions in web and mobile interfaces
- https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions.html — WCAG 2.3.3: allowing users to disable motion animations for accessibility
- https://blog.pope.tech/2025/12/08/design-accessible-animation-and-movement/ — implementing prefers-reduced-motion and accessible animation patterns

## /claude-code-skills/

Use when setting up Claude Code skills, looking for workflow automation, or improving your agentic development process.

- https://github.com/obra/superpowers — structured skill framework for Claude Code emphasizing TDD, planning, and systematic workflows
- https://github.com/karanb192/awesome-claude-skills — curated collection of 50+ verified skills for Claude Code, Claude.ai, and the API
- https://github.com/levnikolaevich/claude-code-skills — 102 production-ready skills covering the full development lifecycle
- https://github.com/OthmanAdi/planning-with-files — skill for persistent markdown-based planning and progress tracking
- https://github.com/addyosmani/web-quality-skills — skills for Lighthouse audits, Core Web Vitals, accessibility, and SEO
- https://snyk.io/articles/top-claude-skills-developers/ — overview of 8 practical skills for planning, coding, testing, and security

## /web-libraries/

Use when choosing UI component libraries, design systems, or frontend tooling for a web project.

- https://github.com/dalisoft/awesome-ui-libraries — curated list of UI libraries, component collections, Tailwind kits, and design systems

## /kotlin-mp/

Use when building cross-platform apps with Kotlin Multiplatform or choosing KMP libraries.

- https://github.com/bipinvaylu/awesome-kotlin-multiplatform — curated list of KMP libraries and resources for mobile, web, backend, and desktop
- https://github.com/ismai117/kottie — Lottie-style After Effects animations for Compose Multiplatform (Android, iOS, JVM, JS, WASM)

## /swift/

Use when building SwiftUI interfaces, looking for animation examples, or choosing iOS/macOS libraries.

- https://github.com/amosgyamfi/open-swiftui-animations — pure SwiftUI animation examples: loading, springs, transitions, effects
- https://github.com/Toni77777/awesome-swiftui-libraries — curated index of open-source SwiftUI UI components and tools

## /mcp-servers/

Use when setting up MCP servers for Claude Code or looking for context providers.

- https://github.com/upstash/context7 — MCP server that fetches up-to-date library documentation directly into AI prompts
