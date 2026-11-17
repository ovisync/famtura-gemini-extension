# Famtura

This extension connects Gemini CLI to Famtura (business management:
customers, invoices, offers, orders, projects, tasks and more) through the
public Famtura MCP server.

## Privacy behavior (important)

- People appear as aliases (`Kunde-XXXX`); contact and address data is
  masked by default. This is a privacy feature, not a bug.
- Never ask the user to disable masking. Unmasking needs a separate,
  documented release inside Famtura (admin module + proof + approval).
- For write operations (create invoice, create customer, …), confirm the
  key fields with the user before calling the tool.

## Examples

- "List my 5 most recent invoices."
- "Create a customer named Muster GmbH."
- "Show my open offers."
- "What is the current revenue on my dashboard?"
