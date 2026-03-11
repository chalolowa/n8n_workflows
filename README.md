## Workflow Features Summary

1. Rent Reminder (3 Days Before)

    - Runs daily at 8 AM

    - Fetches payments due in 3 days

    - Sends personalized SMS reminders

    - Logs all reminders in the database

2. Overdue Payment Escalation

    - Runs daily at 9 AM

    - Categorizes overdue payments by severity

    - Sends escalating reminders based on days overdue

    - Alerts landlord for high-priority cases

    - Supports legal escalation path

3. AI Assistant

    - Webhook-triggered for tenant queries

    - Checks landlord availability

    - Fetches tenant context (balance, property, lease)

    - Uses ollama chat model to generate helpful responses

    - Creates maintenance tickets automatically (INCOMPLETE)

    - Sends summary to landlord

4. Daily Summary (INCOMPLETE)

    - Runs daily at 6 PM

    - Compiles portfolio statistics

    - Lists today's payments

    - Summarizes open issues

    - Sends email report and SMS alert
