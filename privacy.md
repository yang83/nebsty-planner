# Privacy Policy — Nebsty Planner

**English** · [한국어](ko/privacy.md)

Effective: October 11, 2026

Nebsty Planner ("the app") **does not collect personal data.** There are no accounts, servers, ads or analytics.

## 1. What the app stores, and where
- What you write in the planner (tasks, events, memos, project documents, images) is saved as Markdown and image files in **the data folder you choose**. The default is `~/Documents/Nebsty Planner`.
- App settings (data folder location, sync settings, subscribed calendar addresses, the last launch date and so on) are saved in `~/Library/Application Support/Nebsty Planner/`.
- These files exist only on your computer, and the app never sends them anywhere. If you put your data folder in a synced folder such as iCloud Drive or Nextcloud, that service syncs it under its own policy.

## 2. Reminders and Calendar (optional)
- Only if you turn it on in ⚙ Settings › External sync, and only after macOS asks for your permission, does the app access Apple Reminders and Calendar.
- It matches today's due to-dos and the events in calendars you choose against your planner files, on your Mac. This information never leaves the app.
- You can revoke access at any time in **System Settings › Privacy & Security**.

## 3. Google Tasks and Google Calendar (optional)
- Only if you click **Connect Google account** in ⚙ Settings › External sync and approve access on Google's sign-in page does the app access your Google account.
- Scopes requested: Google Tasks (read and write your tasks), Google Calendar events (read and write events in calendars you choose) and your calendar list (read-only, to show which calendars you can pick).
- The app talks **directly** from your computer to Google's servers. There is no Nebsty server in between, and the developer never sees your Google data or your sign-in.
- The sign-in token is stored only on your computer, in `google_token.json` inside the app settings folder, readable only by your user account.
- Google data is used only to sync today's to-dos and events with your planner files. It is not used for advertising, not sold, not transferred to anyone, and no human reads it. Nebsty Planner's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
- To stop access, click **Disconnect** in the app (this also revokes the token at Google), or remove Nebsty Planner at [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

## 4. Internet use
Apart from Google sync (section 3), which you turn on yourself, the app goes online in only two cases. Neither sends your planner content or any personal data.
- **Subscribed calendars (ICS):** it downloads the calendar files from the addresses you enter.
- **Update check:** once a day (or when you ask), it reads a public file in this repository (`latest.json`) to see whether a new version is out. The request carries nothing beyond the app version. Like any web server, GitHub may keep access logs such as IP addresses — see the [GitHub General Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## 5. Sharing or selling data
None.

## 6. Contact
Please get in touch through [GitHub Issues](https://github.com/yang83/nebsty-planner/issues).

## 7. Changes
If this policy changes, this page will show the change with a new effective date.
