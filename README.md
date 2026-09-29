# sync branch

Holds `sync.json`: the dashboard's tick-offs, AES-256-GCM encrypted with the
dashboard passphrase and written by the page itself through the GitHub API.
GitHub Pages serves `main`, so writes here never redeploy the site.
