# Playbook · Known file/link opens ("open the deck", "open Azlan's project")

Owner: main session (direct open, no helper agent dispatch).

**Something comes in** — a short trigger phrase, possibly voice-transcribed with typos.

**Brain picks the job** — direct open, no research.

**Reads what it knows** — fixed phrase→target map: "AI enablement deck" → `C:\Users\OWNER\OneDrive\Desktop\ai-enablement-every-age.pdf`; "Azlan's project" → the GitHub Pages URL. Each trigger is independent — they don't share a window.

**Helpers do the work** — opens it immediately via Chrome (`Start-Process chrome.exe <target>`), skipping Read/search/explanation entirely.

**Safety checks** — none needed; this is a pure local/navigation action, not a send or an edit.

**Sign-off** — the file/page is just open; no report beyond that.
