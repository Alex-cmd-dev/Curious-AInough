# 🤖 9. Coding With Agents


For anyone working with coding agents on a personal, school, or work project.

## Core idea

A coding agent may inspect files, change code, run commands, and test a project. It can help plan and change software, but the developer remains responsible for permissions, review, testing, security, and maintainability.

> [!WARNING]
> Codex, Claude Code, and similar tools can read or change files and run commands on the computer or environment you give them access to. A mistaken action could delete work, break a project, or expose private data. Work in a dedicated project folder, keep a recoverable copy, review permission requests, and inspect changes before accepting them.

## Vibe coding: fast exploration, with tradeoffs

**Vibe coding** is an informal way to build software by describing what you want in natural language, letting an AI generate or change code, and iterating by looking at the result. It can be a useful way to explore an idea, make a prototype, or learn by experimenting.

### Advantages

- You can get from an idea to a visible prototype quickly, even without knowing every detail of the programming language.
- Conversational iteration makes it easy to try alternatives and refine a rough concept.
- The agent can explain unfamiliar code and take on repetitive setup or implementation work.

### Risks and limits

- Code that appears to work can still have hidden bugs, security problems, accessibility gaps, or poor performance.
- You may end up with code you cannot explain or safely change, especially when accepting large changes without review.
- Quick patches can create tangled structure, duplicate logic, or unnecessary dependencies that make future work harder.
- A demo passing one happy-path check does not prove the software is reliable for real users or sensitive data.

Vibe coding is best treated as an exploration method, not a substitute for engineering judgment. As a project becomes important or is used by others, shift from improvising to a deliberate process: clarify requirements, understand the design, review small changes, test expected and failure cases, and maintain the system.

## Safe workflow

1. Explain the goal and inspect the existing project.
2. Ask for a plan before asking for changes.
3. Give only the permissions and context needed.
4. Review the proposed diff before accepting it.
5. Run tests and inspect the behavior yourself.
6. Check dependencies, secrets, file access, and network access.
7. Keep the code understandable and maintainable.
8. Save or commit a working version before a substantial change so you can compare and recover.

For consequential changes, add explicit acceptance criteria, ask the agent to explain the approach and tradeoffs, and review the diff in small pieces. Run the relevant automated checks, then manually exercise the feature. Before release, also consider accessibility, error handling, dependency health, data handling, and deployment or rollback. Do not put credentials or private data into prompts or project files unless the environment and handling are appropriate.

## Questions to ask

- What files will change?
- What assumptions are being made?
- What could break?
- How will this be tested?
- Does the tool need this permission?
- Is any sensitive data exposed?

> [!IMPORTANT]
> **Remember:** An agent can write code. You still own the result.

## 💬 Share feedback

Help improve this guide by [sharing feedback](https://docs.google.com/forms/d/e/1FAIpQLSer6w236SEhMt18CPA8vo5dsLnYd5WV6G5jy1irgFv9Osq_lg/viewform?usp=sharing&ouid=111326601163922216667).

<nav class="page-navigation" aria-label="Page navigation"><div class="page-navigation-overview"><a href="#/README.md">⬅ Back to overview</a></div><div class="page-navigation-neighbors"><a class="previous-page" href="#/08-ai-automation/README.md">⬅ Previous: AI Automation</a><a class="next-page" href="#/10-understanding-ai-systems/README.md">Next: Understanding AI Systems ➡</a></div></nav>
