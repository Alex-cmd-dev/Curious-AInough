# Challenge: Automate a Weekly Campus Events Digest

[⬅ Back to Examples](README.md)

## The scenario

Students often hear about campus events too late to attend. Create a short digest every Monday that lists interesting events happening at your college that week. Use public event listings as the source, and have AI organize the information into a consistent draft for you to review.

## Try the challenge

1. **Choose a delivery method.** Run the prompt below manually on Monday, or use an AI tool that supports scheduled tasks. If you schedule it, have it prepare a draft for review rather than publish or send it.
2. **Use public information.** Find your college's public events calendar or use these fictional listings to try the workflow:
   - Tuesday, 4:00 p.m.: Biology Club talk, “Pollinators on Campus,” Science Building, Room 120.
   - Wednesday, 6:30 p.m.: Student Film Night, Student Union Theater.
   - Friday, time not listed: Volunteer Garden Cleanup, location not listed.
3. **Try this prompt:**

   > Every Monday, prepare a concise campus events digest for the current week. Include the event name, day and date, start time, location, and a one-sentence description when the source provides one. Use public college event listings and link each event to its source. If the time, location, or another detail is missing or unclear, label it “Check details” instead of guessing. Do not include events from outside the requested week. Organize the result as an easy-to-scan list and return a draft for my review.

4. **Review the draft.** Check each event on its source page. Confirm it is happening this week and that its time and location match. The Friday garden cleanup should be flagged as missing details, not completed with invented information.
5. **Test an edge case.** Change one listing so its event date is from last week, or so two pages show different start times. Check that the workflow leaves out the past event or flags the conflict for you to resolve.
6. **Improve the workflow.** If the digest is too long or hard to scan, adjust the prompt and run it again. Keep the format consistent so it is easy to use every week.

## Check the result

The digest should be short, cover only the requested week, link to public sources, and clearly flag missing or conflicting details. A person checks the draft before sharing it. No coding or connection to a real campus account is needed.
