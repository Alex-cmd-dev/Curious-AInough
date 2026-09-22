# 🤖 8. Coding With Agents (Optional)

[⬅ Back to overview](../README.md) · [⬅ Previous: Creating & Automation](../07-creating-and-automation/README.md) · [Next: Understanding AI Systems ➡](../09-understanding-ai-systems/README.md)

_Optional section for students who code._

## Core idea

A coding agent may inspect files, change code, run commands, and test a project. It can help plan and change software, but the developer remains responsible for permissions, review, testing, security, and maintainability.

## Safe workflow

1. Explain the goal and inspect the existing project.
2. Ask for a plan before asking for changes.
3. Give only the permissions and context needed.
4. Review the proposed diff before accepting it.
5. Run tests and inspect the behavior yourself.
6. Check dependencies, secrets, file access, and network access.
7. Keep the code understandable and maintainable.
8. Save or commit a working version before a substantial change so you can compare and recover.

## Questions to ask

- What files will change?
- What assumptions are being made?
- What could break?
- How will this be tested?
- Does the tool need this permission?
- Is any sensitive data exposed?

> [!IMPORTANT]
> **Remember:** An agent can write code. You still own the result.

## 📎 Examples

See the [examples](examples/) folder for a sample debugging prompt.
