# Privacy Policy — Nebsty Planner

**English** · [한국어](ko/privacy.md)

Effective: October 11, 2026

Nebsty Planner ("the app") **does not collect personal data.** There are no accounts, servers, ads or analytics.

## 1. What the app stores, and where
- What you write in the planner (tasks, events, memos, project documents, images) is saved as Markdown and image files in **the data folder you choose**. The default is `~/Documents/Nebsty Planner`.
- App settings (data folder location, sync settings, subscribed calendar addresses, the last launch date and so on) are saved in `~/Library/Application Support/Nebsty Planner/`.
- These files exist only on your Mac, and the app never sends them anywhere. If you put your data folder in a synced folder such as iCloud Drive or Nextcloud, that service syncs it under its own policy.

## 2. Reminders and Calendar (optional)
- Only if you turn it on in ⚙ Settings › External sync, and only after macOS asks for your permission, does the app access Apple Reminders and Calendar.
- It matches today's due to-dos and the events in calendars you choose against your planner files, on your Mac. This information never leaves the app.
- You can revoke access at any time in **System Settings › Privacy & Security**.

## 3. Internet use
The app goes online in only two cases. Neither sends your planner content or any personal data.
- **Subscribed calendars (ICS):** it downloads the calendar files from the addresses you enter.
- **Update check:** once a day (or when you ask), it reads a public file in this repository (`latest.json`) to see whether a new version is out. The request carries nothing beyond the app version. Like any web server, GitHub may keep access logs such as IP addresses — see the [GitHub General Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 4. Sharing or selling data
None.

## 5. Contact
Please get in touch through [GitHub Issues](https://github.com/yang83/nebsty-planner/issues).

## 6. Changes
If this policy changes, this page will show the change with a new effective date.
