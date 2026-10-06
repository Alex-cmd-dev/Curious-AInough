# Computer Science: Give Good Directions

[Back to prompting examples](../README.md)

**Remember:** You decide where you're going. A good prompt gives AI better directions.

## Before
```text
My code does not work.
```
**Why this falls short:** AI cannot see your code or the error, so it can only guess.

## After
```text
My goal is: Find out why my program crashes when the input box is empty.
Context you need: I am using Python in an intro class. Here is the error message: [paste]. Here are the 10 lines involved: [paste]. Passwords and keys removed.
Constraints: Do not rewrite the whole program. Only use what we have learned in class (no extra libraries).
Please produce: Explain the cause in 2 to 3 sentences, then show the smallest fix.
Help me check it by: Tell me how to test the fix, and which functions I should confirm in the official docs.
```

| Part | What this prompt does |
|---|---|
| 🎯 Goal | Find out why my program crashes when the input box is empty. |
| 📚 Context | I am using Python in an intro class. Here is the error message: [paste]. Here are the 10 lines involved: [paste]. Passwords and keys removed. |
| 🚧 Constraints | Do not rewrite the whole program. Only use what we have learned in class (no extra libraries). |
| 📦 Output | Explain the cause in 2 to 3 sentences, then show the smallest fix. |
| ✅ Check | Tell me how to test the fix, and which functions I should confirm in the official docs. |

## Read and follow up
Read the answer first. What is unclear or missing? Then keep the conversation going, for example:
- "Why does that line cause the crash?"
- "Give me a second way to fix it and compare the two."

## Why it fits computer science
Programmers share the error, the code, and the limits. The same habit makes AI far more useful, and you still run the tests.

## Try it yourself
Take a vague prompt you have used before. Rewrite it with the five parts above, then compare the answers.
