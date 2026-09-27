# ISIT 300 Docker lab

**Style A for the server, Style C for the resume mount.** Nginx is already defined and publishes port 8080. The resume bind mount is a TODO you complete in Week 3.

## Start

On GitHub, choose **Use this template** (or fork), then clone **your** copy.

```sh
docker compose up -d
```

Open http://localhost:8080 — you should see the placeholder in `site/index.html`, not your resume.

## Dev Container

Open this folder in VS Code or Cursor and choose **Reopen in Container**.

## Your work

- Week 2: Read `compose.yml` and `.devcontainer/devcontainer.json`. Change the published port if 8080 is taken, restart, and document the new URL in this README. Confirm image vs container in two sentences.
- Week 3: TODO(student): bind-mount `./site` so edits on your computer show up in the container. Copy `resume.html` from your resume repo into `site/` and open it through the published port. Document host path vs container path.

Do not replace this file with a WordPress stack. That is a different template.
