# Larapaper Home Assistant Add-on
Minimal Home Assistant add-on to run Larapaper. This add-on simply runs the upstream Larapaper application.

Repository
- Upstream Larapaper: https://github.com/usetrmnl/larapaper

What this add-on does
- Runs Larapaper inside the add-on container.
- Persists application files in the add-on data folder.

Installation
1. Add this add-on repository to Home Assistant (Supervisor → Add-on Store → ⋮ → Repositories).
2. Install and start the add-on.

Data
- Persistent data is stored in the add-on data directory; do not delete it unless you want to reset Larapaper.

Logs & troubleshooting
- View logs from the add-on page in Supervisor.
- For Larapaper-specific issues or configuration, consult the upstream repo.