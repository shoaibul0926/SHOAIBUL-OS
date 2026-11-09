# Playbook · "Switch to work mode"

Owner: main session (account-context change, not a task — no helper agent dispatch).

**Something comes in** — a spoken or typed mode switch.

**Brain picks the job** — account-context change, not a task.

**Reads what it knows** — current connector state (only one Google account live at a time); whether the target account is already signed into Chrome.

**Helpers do the work** — none of the content agents fire; this just repoints which inbox/calendar/Drive subsequent actions read and write.

**Safety checks** — if two modes are implied in the same breath, say so rather than pretending both are live; if the target account isn't signed into Chrome, stop and ask rather than attempting credentials.

**Sign-off** — one-word reply naming the mode. No recap, no re-reading the request back.
