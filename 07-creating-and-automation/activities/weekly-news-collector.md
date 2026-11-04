# Activity: Design a Weekly News-Collection Workflow

[⬅ Back to Activities](README.md)

## The scenario

You want a short weekly briefing about a topic you care about. Design a workflow that gathers recent stories, organizes them, and prepares a draft for review. The goal is to understand what can be repeated, what can fail, and where a person needs to check the result.

## Copy this into your AI assistant

Copy the whole activity prompt below and paste it into the AI provider you already use. Stay in that chat to complete the activity and reflection.

```text
Help me design and test a human-reviewed workflow I could repeat each week to collect news about [choose a topic, such as local public transit]. If I have not provided a topic, ask me to choose one. This is a workflow design exercise; do not access tools, send, or publish anything.

First, ask me to identify the topic and date range I would use. Then map the steps from choosing the topic and date range to preparing a briefing for human review. For each step, say what information or tool access it needs, what could be automated, what could go wrong, and where a person should make a decision or check the result.

Then make a sample briefing from these fictional story records:
- Monday: “City proposes new bus routes” — Source: City News — link: https://example.com/routes
- Wednesday: “Transit agency delays route decision” — Source: Metro Desk — link: https://example.com/delay
- No publication date: “Five ways to improve buses” — Source: Travel Blog — link not provided

Group related stories and summarize what each record says without adding facts that are not in it. Include each provided source and link. Flag the record with no date and link as needing review; do not treat it as confirmed current news. Point out that two stories may describe different stages of the same issue. Do not send or publish the briefing. End with a checklist for a person to review. Then ask me which steps could repeat each week, what might go wrong if an error repeats, what must be verified before sharing, and how the workflow should respond if a link is missing or dates conflict. Help me add a rule for any failure I identify. Once we have finished the activity and reflection, ask me: “Would you like me to create a similar exercise?” If I say yes, create a new workflow-design exercise that keeps human review, flags uncertainty and missing data, and does not access tools, send, or publish anything.
```

## Do the activity

1. **Map the process:** Identify the inputs needed each week, such as topic, date range, and sources. Which steps repeat?
2. **Find the human decisions:** Decide who chooses the topic, what counts as relevant, and who checks the briefing before sharing.
3. **Review the sample:** Check that the undated story is flagged and that the assistant does not invent details or treat the two dated stories as contradictory without checking.
4. **Test an edge case:** Remove a link or add two records with conflicting dates. Does the workflow flag the problem and pause for review?
5. **Improve the workflow:** Add a rule for any failure you found. Consider what source access or scheduling feature a real tool would need to collect stories every week.

## Check your understanding

Which steps could run the same way every week? What could go wrong if the workflow repeated an error? What must a person verify before sharing the briefing?

## 💬 Share feedback

Help improve this activity by [sharing feedback](https://docs.google.com/forms/d/e/1FAIpQLSer6w236SEhMt18CPA8vo5dsLnYd5WV6G5jy1irgFv9Osq_lg/viewform?usp=sharing&ouid=111326601163922216667).
