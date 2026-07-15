# 🛑 How to Stop GitHub Actions Email Alerts

**Problem:** You are receiving email notifications for every Actions run.

**Solution (Do this once in GitHub UI):**

1. Go to your **GitHub Notification Settings**: https://github.com/settings/notifications
2. Scroll to **"Automatically watching repositories"**.
3. **Uncheck** the option: *"Automatically watch all repositories I visit"* (if checked).
4. **Crucially**: Go to **Repository Settings** > **Actions** (for each repo) or use the Global setting.
   - **Global Fix**: In Notification Settings, under "Automated emails", select **"Don't send exponential emails"** or **"Only for manual runs"** if available.
   - **Per-Repo Fix**: In each repo go to **Settings > Actions > General** and uncheck **"Workflow run notifications"**.

**Alternative (Mute via Email):**
- Click "Mute" in the email you just received. This will stop alerts for that specific workflow.

✅ **Once done:** You will only get notifications for bugs, security alerts, or if you manually subscribe.
