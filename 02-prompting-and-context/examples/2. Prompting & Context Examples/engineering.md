# Engineering: Give Good Directions

[Back to prompting examples](README.md)

**Remember:** You decide where you're going. A good prompt gives AI better directions.

## Before
```text
How do I build a strong bridge?
```
**Why this falls short:** There is no span, material, or rule set. AI will give a textbook answer that may break your contest rules.

## After
```text
My goal is: Design a popsicle-stick bridge that holds the most weight.
Context you need: The span is 12 inches. I have 100 sticks and wood glue. It must be built in 2 hours.
Constraints: Follow the contest rules: no extra materials. Keep the design simple enough for a beginner.
Please produce: Three designs with a quick sketch description and a likely weak point for each.
Help me check it by: Tell me which claims about strength I should test or look up before I trust them.
```

| Part | What this prompt does |
|---|---|
| 🎯 Goal | Design a popsicle-stick bridge that holds the most weight. |
| 📚 Context | The span is 12 inches. I have 100 sticks and wood glue. It must be built in 2 hours. |
| 🚧 Constraints | Follow the contest rules: no extra materials. Keep the design simple enough for a beginner. |
| 📦 Output | Three designs with a quick sketch description and a likely weak point for each. |
| ✅ Check | Tell me which claims about strength I should test or look up before I trust them. |

## Read and follow up
Read the answer first. What is unclear or missing? Then keep the conversation going, for example:
- "Where will design 2 most likely break?"
- "How can I test a small version first?"

## Why it fits engineering
Engineers write down requirements before they design. A prompt with requirements is the same skill.

## Try it yourself
Take a vague prompt you have used before. Rewrite it with the five parts above, then compare the answers.
