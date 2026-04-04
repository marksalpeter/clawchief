# HEARTBEAT.md

# Orchestrated chief-of-staff heartbeat

Canonical sources:
- Priority map: `clawchief/priority-map.md`
- Auto-resolver: `clawchief/auto-resolver.md`
- Meeting-notes policy: `clawchief/meeting-notes.md`
- Meeting-notes ledger: `workspace/memory/meeting-notes-state.json`
- Live tasks: `clawchief/tasks.md`
- EA workflow: `executive-assistant` skill
- Biz-dev / outreach workflow: `business-development` skill
- Task workflow: `daily-task-manager` skill

On heartbeat, during normal work hours:

1. Read the priority map.
2. Read the auto-resolver policy.
3. Read the meeting-notes policy and meeting-notes ledger.
4. Read the live task file.
5. Run the executive-assistant workflow for meeting-notes ingestion plus inbox / calendar / scheduling triage.
6. If a signal is really about outreach tracker state, lead status, prospect pipeline, or partner follow-up, use the business-development workflow instead of treating it as generic EA work.
7. Auto-resolve low-risk operational items when the next step is obvious and authority is clear.
8. If meeting notes create principal tasks, add them to `clawchief/tasks.md`.
9. If the principal needs to know or act, send one short, direct update.
10. If there is no EA or biz-dev issue needing attention, use the remaining heartbeat value for at most one priority nudge anchored in a live program from the priority map or an open task from `clawchief/tasks.md`.
11. If there is nothing useful to say, reply: HEARTBEAT_OK

Rules:
- Be proactive, but do not create noise.
- Keep this file as an orchestrator, not as a duplicate workflow spec.
- Let the skills own their detailed procedures.
- Let `clawchief/priority-map.md` own people/program priority and urgency.
- Let `clawchief/auto-resolver.md` own auto-resolution policy.
- Let `clawchief/meeting-notes.md` own meeting-notes ingestion policy.
- Let `clawchief/tasks.md` own the live task state.
- Keep any task-related update short and direct.
- Do not send repeated or near-identical nudges unless there is materially new information, a changed recommendation, or a concrete trigger.
