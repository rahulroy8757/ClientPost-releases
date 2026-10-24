# ClientPost Privacy Policy

_Last updated: 24 October 2026_

ClientPost is a Windows desktop app that lets a professional send personalized emails to their own clients from
their own Gmail account. This policy explains what ClientPost does with your data.

## Data stays on your computer

- Your client list, templates, campaigns, send history, settings and backups are stored only on your computer
  (in `%LOCALAPPDATA%\ClientPost` and in the backup folder you choose).
- ClientPost has no server. The developer does not receive, collect or see your client data, your emails or your
  Gmail account.
- ClientPost does not use analytics, advertising or tracking.

## Google account and Gmail data

When you click **Connect Gmail**, you sign in on Google's own page in your browser. ClientPost never sees your
Google password. ClientPost asks Google for these permissions only:

| Permission | Why ClientPost needs it |
|---|---|
| `gmail.send` (Send email on your behalf) | To send the emails you create and confirm in ClientPost. ClientPost cannot read, search, change or delete any email in your mailbox. |
| `openid`, `email` | To show which Gmail address is connected, so you know which account your emails go from. |

- The permission Google gives is stored on your computer, encrypted with Windows (DPAPI) for your Windows user
  only. It is not included in backups and is never sent to the developer.
- Emails are sent only when you confirm a campaign or press **Send test to me**, and only to the clients you chose.
- ClientPost does not use Google user data for advertising, does not sell it, does not transfer it to anyone,
  and does not use it to train AI or machine-learning models.
- ClientPost's use and transfer of information received from Google APIs adheres to the
  [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
  including the Limited Use requirements.

## Removing access and deleting data

- **Settings → Disconnect** in ClientPost removes the saved permission and asks Google to revoke it.
- You can also remove access at any time at <https://myaccount.google.com/connections>.
- To delete all ClientPost data, delete the folder `%LOCALAPPDATA%\ClientPost` and your backup files.
  Uninstalling ClientPost keeps this folder so your data is not lost by accident.

## Updates

ClientPost checks the public release page on GitHub for new versions. This check sends no client data or
personal information; GitHub may log the request like any website visit.

## Contact

Questions about this policy: **rahulroy8757@gmail.com**
