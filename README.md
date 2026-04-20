# LnGRocks

## Steps Followed

1. Created a repository named `LnGRocks` on GitHub.

2. Initialized Git locally and connected it to GitHub:

   ```
   git init
   git remote add origin <repo-url>
   ```

3. Added README file and pushed it to `main` branch:

   ```
   git add .
   git commit -m "Added Readme.md"
   git push -u origin main
   ```

4. Created a feature branch for values:

   ```
   git checkout -b feat/LnGValues
   ```

   * Created `values.txt`
   * Added some values
   * Committed and pushed

5. Created another feature branch for culture:

   ```
   git checkout -b feat/LnGCulture
   ```

   * Created `culture.txt` and `fun.txt`
   * Committed and pushed

6. Updated `values.txt`:

   * Added initial values
   * Later added **Innovation**
   * Committed and pushed changes

7. Created pull requests:

   * Merged `feat/LnGValues` into `main`
   * Merged `feat/LnGCulture` into `main`

8. Created and resolved a merge conflict:

   * Made changes to the same line in `values.txt` in two branches
   * Pulled latest changes and got a conflict
   * Resolved it using VS Code (accepted current change)
   * Committed and pushed the fix

---
