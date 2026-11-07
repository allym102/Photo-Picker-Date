# Photo Day Picker

A single-file, mobile-friendly GitHub Pages site that assigns a random date from 1 January 2017 through today, without repeating picked dates.

## Publish on GitHub Pages

1. Create a new **public** GitHub repository, for example `Photo-Picker-Date`.
2. Upload `index.html` to the repository root and commit it.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then **Save**.
5. Wait for GitHub to publish the site. Its address will normally be `https://YOUR-USERNAME.github.io/Photo-Picker-Date/`.

## How it works

- Each date is selected at most once, including skipped dates.
- A picked date stays visible until you complete or skip it.
- Completed days contribute to the progress bar.
- Progress is stored in your browser's `localStorage`, not in GitHub. It won't automatically sync across devices or browsers.
- Use **Progress & settings → Download progress backup** to save your progress, and **Restore progress backup** to move it to another browser.
- The available date range expands automatically as new days arrive.