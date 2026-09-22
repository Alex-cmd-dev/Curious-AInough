# 🧠 9. Understanding AI Systems (Optional)

[⬅ Back to overview](../README.md) · [⬅ Previous: Coding With Agents](../08-coding-with-agents/README.md) · [Next: Tool Directory ➡](../10-tool-directory/README.md)

_Optional deep dive: understand what the system can actually do._

## Learning path

**Model basics → Context & retrieval → Tools → MCP / skills → Agents → Build or automate something**

## The basics

Here are the words you'll hear most often, explained in plain language with an everyday comparison for each.

### Large language model (LLM)

**What it is:** The "engine" behind tools like ChatGPT or Claude. It generates an answer by predicting the most likely next piece of text, based on patterns it learned from huge amounts of text during training, plus whatever you've told it in the current conversation.

**Like:** A friend who has read an enormous number of books and is great at finishing sentences in a way that *sounds* right, but they're going from memory and pattern, not looking anything up. They can be fluent and wrong at the same time, sounding just as confident either way.

**Why it matters:** Fluency is not evidence. This is exactly why [🔍 Research & Verification](../04-research-and-verification/README.md) matters: check the claims, don't just trust the confident tone.

### Tokens

**What it is:** The small chunks of text a model actually reads and writes: roughly pieces of words, not whole words or letters. A model processes your prompt as tokens and builds its reply one token at a time.

**Like:** Lego bricks for language. You don't hand a model a finished sentence: it's built (and read) piece by piece, and each piece costs a little time and money.

**Why it matters:** Costs, speed, and length limits are usually measured in tokens, not words: a shorter conversation or document leaves more "room" for the model to work with.

### Context window

**What it is:** How much text (measured in tokens) a model can "see" at once: your prompt, the conversation so far, and any files supplied to it.

**Like:** A whiteboard of a fixed size. You can keep writing on it, but once it's full, something has to be erased to make room for new notes: usually the oldest or least relevant material. That's why a model can "forget" something you said earlier in a very long conversation.

**Why it matters:** For long conversations or big documents, be ready to remind the model of anything important from earlier, rather than assuming it's still "on the whiteboard."

### Retrieval

**What it is:** Bringing outside information into the conversation instead of relying only on what the model memorized during training: for example, pulling in the text of a document you uploaded, search results from the web, or rows from a database before answering.

**Like:** The difference between a closed-book exam (answering from memory alone) and an open-book exam (allowed to check the actual source). Retrieval is what lets a tool discuss a specific PDF, a live webpage, or today's data, instead of only what it learned back when it was trained.

### Tools

**What it is:** Abilities that let an AI system *do* things beyond writing text: run a calculation, search the web, read or edit a file, query an API, or send a message.

**Like:** Giving someone hands and a phone instead of just a voice. Without tools, a model can only talk about doing something. With tools, it can actually go do it, which is exactly why the permissions it's granted matter so much.

### Skills

**What it is:** A packaged, reusable set of instructions (and sometimes reference files or scripts) that tells an AI system how to handle a particular kind of task: for example, formatting a spreadsheet a specific way, running a team's code-review checklist, or following a company's writing style.

**Like:** A recipe card or a training manual for a specific job. Instead of re-explaining the process from scratch every single time, someone writes it once, and the assistant follows those instructions whenever that kind of task comes up.

### Model Context Protocol (MCP)

**What it is:** An open standard that lets AI applications connect to external tools and data sources in a consistent way, instead of every app needing a custom-built connection to every service. An "MCP server" exposes a specific system (like GitHub, Slack, a database, or a filesystem) so an AI assistant can read from or act on it.

**Like:** A universal charging port (think USB-C) instead of every device needing its own proprietary cable. One standard plug that many different tools and services can connect through.

**Why it matters:** Because an MCP server is just software someone wrote, it deserves the same scrutiny as any other program you'd install on your computer. See the security warning below.

### Agents

**What it is:** An AI system that can use tools and skills across multiple steps (planning, taking an action, observing the result, and deciding what to do next) to pursue a goal with less step-by-step guidance than a single question-and-answer exchange.

**Like:** The difference between a vending machine (one input, one fixed output) and an intern you send on an errand ("book the venue for Friday") who figures out the sub-steps themselves (checking availability, comparing options, sending the email, confirming it worked) and comes back when it's done or stuck.

**Why it matters:** An agent can go further with less supervision, which is powerful but also means mistakes can compound across steps if no one checks in along the way. See [🤖 Coding With Agents](../08-coding-with-agents/README.md) for how to review its work.

Product names and implementations differ across companies, so always check what a particular tool can actually see and do rather than assuming based on these general definitions.

## Topics

- Prediction and tokens
- Context windows and retrieval
- Tool use and permissions
- Agents and delegated actions
- MCP and skills
- Evaluation and testing
- Safe use of third-party extensions

## Why this matters

Understanding the system helps you choose appropriate tasks, recognize limitations, inspect permissions, and decide where human review is necessary. More access means permissions matter more. Check the provider of an extension, MCP server, or skill; read what it can access; and grant only the access it needs. Do not paste passwords or private keys into an unfamiliar tool. Evaluate a workflow on several examples, including failure cases, before relying on it.

## Security warning

> [!WARNING]
> Treat third-party MCP servers and skills like software. They can contain malware, malicious instructions, or requests for more access than they need. Use trusted sources, review permissions and code when possible, use least privilege, and never give unknown tools credentials or sensitive data.

> [!IMPORTANT]
> **Remember:** Know what the system can see, what it can do, and where it can fail.

## Learn more

- 🔗 [Model Context Protocol: Introduction](https://modelcontextprotocol.io/docs/getting-started/intro): the standard for connecting AI applications to external systems.
- 🔗 [Anthropic: Introducing MCP](https://www.anthropic.com/news/model-context-protocol): background on the protocol.
- 🔗 [OpenAI: Why language models hallucinate](https://openai.com/index/why-language-models-hallucinate/): an explanation of factual errors and uncertainty.
- 🔗 [OpenAI: A practical guide to building agents](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/): designing and evaluating agent workflows.

## 📎 Examples

See the [examples](examples/) folder for what a permissions check looks like across different fields.
