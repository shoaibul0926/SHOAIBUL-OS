# Playbook · Meeting gets confirmed on the calendar

Owner agent: `calendar-meetings`.

**Something comes in** — a calendar invite (e.g. the Indic EMS Monday 10:30–11:30 IST session) lands on whichever account it belongs to.

**Brain picks the job** — *meeting lifecycle*: accept → agenda → nudge → recap.

**Reads what it knows** — Memory for who's on the thread (e.g. Shirin Khanna / Indic EMS engagement scope), the account-to-company map, default call length (1hr unless told otherwise).

**Helpers do the work** — Calendar & Meetings auto-accepts (no confirmation asked), flags it instead of silently double-booking if it collides with something else; 24h out it sends a confirmation/agenda email; 1h out, a short nudge if unconfirmed; within hours after, a recap with decisions/owners/next steps.

**Safety checks** — send from the account matching the *meeting's* company, not whichever is currently connected; agenda/nudge/recap are the only auto-sends, everything else stays draft; flag rather than guess if the right account isn't the one currently authenticated.

**Sign-off** — recap lands in the matching inbox; conflicts and account mismatches surface to Shoaibul as one line, not silently resolved.
