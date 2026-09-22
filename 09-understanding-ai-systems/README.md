# 9. Understanding AI Systems (Optional)

[⬅ Back to overview](../README.md) · [⬅ Previous: Coding With Agents](../08-coding-with-agents/README.md) · [Next: Tool Directory ➡](../10-tool-directory/README.md)

_Optional deep dive — understand what the system can actually do._

## Learning path

**Model basics → Context & retrieval → Tools → MCP / skills → Agents → Build or automate something**

## The basics

A **large language model (LLM)** generates an answer using patterns learned during training and the information available in the current interaction. It can be fluent and wrong. Text is processed in pieces called **tokens**, and a system can only work with a limited amount of **context** at a time.

**Retrieval** brings in outside information, such as a document or a web page. **Tools** let an AI system do things beyond writing text, such as search, calculate, or inspect files. A **skill** can give it a repeatable set of instructions. **Model Context Protocol (MCP)** is a standard way for AI applications to connect to external tools and data. An **agent** can use these abilities over several steps to pursue a goal.

Product names and implementations differ, so check what a particular tool can actually see and do.

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

Treat third-party MCP servers and skills like software. They can contain malware, malicious instructions, or requests for more access than they need. Use trusted sources, review permissions and code when possible, use least privilege, and never give unknown tools credentials or sensitive data.

**Remember: Know what the system can see, what it can do, and where it can fail.**

## Learn more

- [Model Context Protocol: Introduction](https://modelcontextprotocol.io/docs/getting-started/intro) — the standard for connecting AI applications to external systems.
- [Anthropic: Introducing MCP](https://www.anthropic.com/news/model-context-protocol) — background on the protocol.
- [OpenAI: Why language models hallucinate](https://openai.com/index/why-language-models-hallucinate/) — an explanation of factual errors and uncertainty.
- [OpenAI: A practical guide to building agents](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/) — designing and evaluating agent workflows.

## Examples

See the [examples](examples/) folder for a sample permissions-check walkthrough.
