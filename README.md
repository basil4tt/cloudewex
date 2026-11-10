# CloudEwex website

A starter brochure website built with Django and Docker.

## Run locally

1. Open Docker Desktop and wait until it says it is running.
2. In VS Code, open this project folder and open **Terminal → New Terminal**.
3. Run:

   ```sh
   docker compose up --build
   ```

4. Visit <http://localhost:8000>. Stop the local server with **Ctrl+C**.

## Git and GitHub

Install Apple's Command Line Tools if `git` is unavailable, then in this folder run:

```sh
git init
git add .
git commit -m "Create CloudEwex website starter"
git branch -M main
```

Create an empty GitHub repository named `cloudewex`, then connect and push it:

```sh
git remote add origin https://github.com/YOUR-USERNAME/cloudewex.git
git push -u origin main
```

Git stores project history. GitHub hosts a copy online. The workflow in `.github/workflows/ci.yml` runs Django checks when you push or open a pull request.

## Next step: deployment

This starter includes continuous integration (CI). Continuous deployment (CD) to AWS needs an AWS account and a hosting target. Choose that once the site content is ready; keep AWS credentials in GitHub Actions secrets or use AWS OIDC, never in source files.
# cloudewex
# cloudewex
# cloudewex
# cloudewex
