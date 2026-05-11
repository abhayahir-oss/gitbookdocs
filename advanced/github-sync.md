# Syncing with GitHub

GitBook's GitHub Sync keeps your docs and repository in perfect alignment.

## How Sync Works

GitBook watches your connected branch (usually `main`). When you:
- Push a commit to GitHub → GitBook updates automatically
- Edit in GitBook editor → GitBook commits to GitHub automatically

## Setting Up Sync

1. Open your GitBook Space
2. Go to **Settings** (bottom-left gear icon)
3. Click **GitHub Sync**
4. Choose your repository and branch
5. Select sync direction:
   - **GitHub to GitBook** (recommended to start)
   - **GitBook to GitHub**
   - **Bidirectional**
6. Click **Sync**

## Troubleshooting Sync Issues

| Problem | Solution |
|---------|---------|
| Pages not showing | Check they are listed in `SUMMARY.md` |
| Old content showing | Trigger a manual sync in Settings |
| Auth error | Re-authorize GitBook in GitHub settings |
