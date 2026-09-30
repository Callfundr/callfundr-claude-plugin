---
name: reshuffle-the-day
description: Rearrange the day in CallFundr when a tech is out, it rains, or a job runs long — move or reassign affected jobs in one pass and list which customers are affected. Use for "Mike's out sick", "rain day", "push everything", "cover Dana's jobs".
---

# Reshuffle the day

1. Find the affected jobs with list_appointments (filter by the tech or the date the user names).
2. Propose a plan before touching anything: for each job, the new tech and/or new window, and why (skills, location, open time). Show it as a short table.
3. Ask for one go-ahead for the whole plan. On yes, apply each change with update_appointment and its confirm step (list_technicians shows who's available).
4. Report what changed and list the customers whose window moved, so the office knows who to expect calls from.

Never move a job the user didn't include. If a job can't fit, say so and suggest the next open day instead of forcing it.
