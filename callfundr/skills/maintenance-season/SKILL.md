---
name: maintenance-season
description: Line up maintenance and return visits in CallFundr — find customers who are due, then book them into open windows on the user's go. Use for "who's due for maintenance", "tune-up season", "fill next week", "book the returns".
---

# Maintenance season

1. Find customers due for a visit: list_maintenance_eligible and list_maintenance_plans, plus customers the user names (customer_history shows past work).
2. Show a short list: customer, last visit, what was done, city.
3. Suggest windows from the open slots on the board, grouped by area so techs aren't driving across town.
4. Book only the ones the user approves with book_appointment, each through its preview and confirm step.

Don't contact customers unless the user asks. Booking and messaging are separate steps.
