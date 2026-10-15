# Federico Delrio — personal website

Static personal portfolio. No build step or external dependencies are required.

To preview locally from the repository root:

```powershell
python -m http.server 8000 --directory personal-website
```

Then open `http://localhost:8000`.

## GitHub Pages

This folder is intentionally an isolated Git repository: it contains only the
public website, never the surrounding job-search workspace, CVs, applications or
theses. The included GitHub Actions workflow deploys the site automatically after
each push to the `main` branch.

After the repository is connected to GitHub:

1. Create a **public** repository, preferably named `<github-username>.github.io`.
2. Add it as `origin`, then push the local `main` branch.
3. In the repository's **Settings → Pages**, select **GitHub Actions** as the
   publishing source.

GitHub will provide the public URL. A custom domain can be configured later in
the same Pages settings.

