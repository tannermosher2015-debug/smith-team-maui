# Sync workflow (laptop <-> upstairs PC)

This repo is the source of truth for The Smith Team (Coldwell Banker Maui) redesign,
shared across two machines.

- **Before working:**  `git pull --rebase`
- **When done:**       `git add -A && git commit -m "msg" && git push`

Always `pull --rebase` first — there are usually upstream commits from the other machine.

The site is the single self-contained `smith-team-maui.html` (no build step).

## Important
This repo lives OUTSIDE OneDrive on purpose. Do NOT move it into a OneDrive-synced
folder — OneDrive syncing the hidden .git folder can corrupt the repository.
