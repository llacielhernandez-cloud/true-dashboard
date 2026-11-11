# T.R.U.E. Technician Overview

The MAS technician dashboard, hosted on GitHub Pages.

- `index.html` is the page. It is built from the Management Master's `MM_WebApp.html` by `github-pages/build.py`.
- The data lives on the `data` branch as `overview.json`. The Management Master publishes it after each import.
  It is encrypted with the dashboard password, so the file is unreadable without it.
- Open the page, enter the dashboard password, and pick a technician and reporting period.
