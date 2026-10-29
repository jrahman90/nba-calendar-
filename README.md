# Knicks & 76ers Calendar

Auto-updating subscription calendars for New York Knicks and Philadelphia 76ers games, using ESPN schedule data. Regular season and postseason games are included as published. Head-to-head games appear once in the combined feed.

## Subscribe

Copy the URL into your calendar app's **Add subscription calendar** or **From URL** option. Subscribe instead of importing a downloaded file, so schedule changes can sync.

**Both teams:**

https://raw.githubusercontent.com/jrahman90/nba-calendar-/main/calendars/knicks-76ers.ics

**Knicks only:**

https://raw.githubusercontent.com/jrahman90/nba-calendar-/main/calendars/knicks.ics

**76ers only:**

https://raw.githubusercontent.com/jrahman90/nba-calendar-/main/calendars/76ers.ics

On iPhone, open Calendar, choose Calendars > Add Calendar > Add Subscription Calendar, then paste the URL. In Google Calendar on the web, choose Other calendars + > From URL.

The feed refreshes daily at 10:17 UTC via GitHub Actions; your calendar app controls how quickly changes appear. Times display in your calendar's local time zone. Games last an estimated 2.5 hours. Unknown tipoffs appear as all-day events marked time TBD. No reminders are forced.

## Maintenance

See the Actions tab for refresh status or run **Refresh NBA calendars** manually. Failed downloads preserve the previous published feed. No API keys or paid services are required. GitHub may disable scheduled runs in public repositories after 60 days without activity; re-enable the workflow in Actions if that happens.
