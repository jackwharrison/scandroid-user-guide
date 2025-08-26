# Scandroid — System Administration

This page covers the **app internals and operations** for system administrators and engineers. It’s separate from user-facing guidance.

---

## Architecture Overview

- **Framework:** Flask (single entrypoint `app.py`)
- **Views:** Jinja2 HTML templates (`templates/`) with static assets (`static/`)
- **Config Storage:** JSON files (e.g., `system_config.json`, `display_config.json`)
- **Offline Support:** `service-worker.js` caches selected routes/assets for PWA/offline use
- **Data Sources:** Kobo (registration form) and 121 Platform (programme + payment)
- **Hosting:** Azure App Service (Linux), source in GitHub  
  - Repo: <https://github.com/jackwharrison/scandroid>
  - Azure App: (App Service) scandroid-app
  - Resource Group: scandroid-app_group
  - Subscription: 510 - Cash and Voucher Assistance
  - Directory: Rode Kruis
 
For any additional questions or support, please contact jharrison@redcross.nl or support@121.global
