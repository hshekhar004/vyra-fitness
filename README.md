# Vyra — Local Ask Me Out Edition

## Publish on GitHub Pages
1. Extract the ZIP.
2. Upload `index.html` to the root of your existing GitHub repository, replacing the previous file.
3. Commit. GitHub Pages will publish the updated page automatically.

## Changes
Only the **Ask Me Out** assistant interface and behavior were updated:
- Instant local answers: no network AI calls or deliberate response delay.
- Chat history, new chats, chat switching, and chat deletion.
- Progress graphs when logged data is available; if it isn't, the assistant says so.
- Subtle turquoise styling with restrained pink highlights within the assistant tab.
- Meal combinations based on saved food nutrients; no invented nutrition values.

No paid API service or Cloudflare Worker is bundled. Existing fitness data stays in local browser storage, but back up your data before updating. Existing legacy AI connection settings in the separate Settings tab have deliberately not been altered because this is an Ask Me Out-only update; they are not used by this assistant.

## Important limitations
This is a **rule-based** local assistant, not generative AI. It cannot create novel recipes reliably or understand every phrasing. Open Food Facts food values are unverified community data; verify labels. Without logs, graphs cannot display meaningful progress.
