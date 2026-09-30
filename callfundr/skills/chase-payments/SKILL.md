---
name: chase-payments
description: Find unpaid and overdue invoices in CallFundr and help collect them — oldest first, with amounts and customers, then send reminders on the user's go. Use for "who hasn't paid", "what's outstanding", "chase money", "overdue invoices".
---

# Chase payments

1. list_invoices and keep the ones not paid. Sort oldest due date first.
2. Show customer, invoice number, amount, due date, and days overdue. Total at the bottom.
3. Offer to resend the invoice (text_invoice or email_invoice, or invoice_payment_link for a pay link) for the ones the user picks. Each send runs through the tool's preview and confirm step.
4. record_invoice_payment only RECORDS a payment someone already made (cash, check, card taken in the field). It never charges a card or moves money — say so if the user seems to expect that.
