# Accounting: Give Good Directions

[Back to prompting examples](../README.md)

**Remember:** You decide where you're going. A good prompt gives AI better directions.

## Before
```text
Why is my bank balance wrong?
```
**Why this falls short:** It gives no details, so AI has to guess. You will get a generic list that may not fit your situation.

## After
```text
My goal is: Find possible reasons my bank balance is $40 lower than my own spending notes.
Context you need: I track purchases in a notes app and pay with a debit card. Here are my 8 purchases from this week with dates and amounts: [paste list]. Account numbers removed.
Constraints: Explain it for a beginner. Do not ask for account numbers or passwords.
Please produce: A checklist of possible reasons, most likely first, and how to confirm each one on my statement.
Help me check it by: Tell me what you are assuming and which reasons you are less sure about.
```

| Part | What this prompt does |
|---|---|
| 🎯 Goal | Find possible reasons my bank balance is $40 lower than my own spending notes. |
| 📚 Context | I track purchases in a notes app and pay with a debit card. Here are my 8 purchases from this week with dates and amounts: [paste list]. Account numbers removed. |
| 🚧 Constraints | Explain it for a beginner. Do not ask for account numbers or passwords. |
| 📦 Output | A checklist of possible reasons, most likely first, and how to confirm each one on my statement. |
| ✅ Check | Tell me what you are assuming and which reasons you are less sure about. |

## Read and follow up
Read the answer first. What is unclear or missing? Then keep the conversation going, for example:
- "Which of these could I rule out using just my statement?"
- "Show me how to add up the pending charges."

## Why it fits accounting
Accounting depends on exact records. A prompt with real details gets a checklist you can verify against the statement.

## Try it yourself
Take a vague prompt you have used before. Rewrite it with the five parts above, then compare the answers.
