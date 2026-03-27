# 找助教 🙋🏻‍♀️
A simple web-based "raise hand" system using ntfy.sh. Deploy your own version in seconds

# How to use

1. **Fork** this repository.
2. **Set your Secret**:
   - Go to **Settings** > **Secrets and variables** > **Actions**.
   - Click **New repository secret**.
   - **Name:** `NTFY_TOPIC`
   - **Value:** Your private ntfy topic name (e.g., `candy-class-101`).
3. **Enable & Run**:
   - Go to the **Actions** tab and click **"Enable workflows"**.
   - Select **"Deploy to GitHub Pages"** on the left sidebar.
   - Click **Run workflow** > **Run workflow**.
4. **Final Step**: 
   - After the action finishes, go to **Settings** > **Pages**.
   - Ensure the "Branch" is set to `gh-pages` and folder to `/(root)`.
   - Your site is now live!
