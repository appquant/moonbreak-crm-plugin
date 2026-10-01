# Moonbreak CRM

Skills that teach Claude how to work with your Moonbreak CRM workspace through the Moonbreak connector: quote from a call, follow up on overdue invoices, review collections and the pipeline, check the health of a deal, and prepare for a meeting. Claude reads your records, drafts the work and shows it to you. Nothing is sent or duplicated without your clear yes.

## What is in it

- `moonbreak-crm`: the ground rules for every request (find records by search, ask before creating a missing buyer, never guess an id, never add amounts in different currencies).
- `moonbreak-quote-from-call`: turn a call transcript or notes into a draft quotation.
- `moonbreak-overdue-followup`: draft one payment reminder per customer with overdue invoices.
- `moonbreak-collections`: what customers owe, aged, and who to chase first.
- `moonbreak-pipeline-review`: open quotations by stage and value, what is expiring or stuck.
- `moonbreak-deal-health`: rate one deal, or all open deals, as healthy, watch or at risk.
- `moonbreak-meeting-prep`: a one-page briefing before a call or meeting with a contact or company.

## Use it

Connect Moonbreak from this plugin's Connectors tab and sign in. The consent screen names the workspace and the permissions you approve (read, write, send email). Then ask in plain words: "Turn this call into a quote for Acme", "Who owes us money and who should I chase first?", "Give me this week's pipeline review", "Prep me for my meeting with Juan Dela Cruz".

Only workspace owners, admins and approvers can connect, and the workspace needs a Growth, Pro or Scale plan.

## Data

The skills are plain Markdown instructions: they run no code and send nothing themselves. The Moonbreak connector, once you connect it, lets the AI app you use read that workspace's CRM records (contacts, companies, quotations, invoices, calls and activity), and, only when you ask and approve, create or update records, save email drafts and send email. What the connector reads is passed to the AI provider you use. Moonbreak keeps an audit log of each request, and you can disconnect at any time under Account settings, Connected apps.