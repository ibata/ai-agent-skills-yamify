
# Escalation Skill

Escalate when:
- repeated 5xx errors persist over 10 minutes,
- deployment status is inconsistent with runtime state,
- user-facing impact affects multiple workspaces.

Escalation payload should include:
- incident summary,
- impact scope,
- affected URLs/workspaces,
- last known good timestamp,
- immediate mitigation steps.
