# C2LY Help Center

Static help center intended for Cloudflare Pages.

Recommended deployment:

1. Create a separate public GitHub repository, for example `c2ly-help`.
2. Copy the contents of this `help-site/` directory into that repository.
3. In Cloudflare Pages, create a project from the repository.
4. Build command: leave empty.
5. Output directory: `/`.
6. Bind the custom domain `help.c2ly.com`.

Do not put application source code, customer data, credentials, backups, or private deployment files in the public help repository.
