# LnGRocks

## Steps Followed

1. Created a new repository `LnGRocks` on GitHub.

2. Initialized Git locally and connected to GitHub:

   ```
   git init
   git remote add origin <repo-url>
   ```

3. Created `main` branch and pushed initial commit:

   ```
   git add .
   git commit -m "Added Readme.md"
   git push -u origin main
   ```

4. Created feature branch **LnGValues**:

   ```
   git checkout -b feat/LnGValues
   ```

   * Added `values.txt`
   * Committed and pushed changes

5. Created feature branch **LnGCulture**:

   ```
   git checkout -b feat/LnGCulture
   ```

   * Added `culture.txt` and `fun.txt`
   * Committed and pushed changes

6. Updated `values.txt` in feat/LnGValues:
   * Added initial values
   * Committed and pushed changes, Then
   * Added new value: **Innovation**
   * Committed and pushed changes

7. Created Pull Requests:

   * `feature/LnGValues` → `main`
   * `feature/LnGCulture` → `main`
   * Merged both PRs

---

## Final Files

* values.txt
* culture.txt
* fun.txt
* README.md
