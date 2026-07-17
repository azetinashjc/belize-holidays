# Belize Holidays 📅

A simple, subscribable calendar feed of official Belize public and bank holidays — built for iPhone (and any other app that supports iCalendar subscriptions).

Source: [Belize Press Office](https://www.pressoffice.gov.bz) official press releases, published under the *Holidays Act, Chapter 289 of the Laws of Belize*.

## Subscribe

Add this feed to your calendar app so it updates automatically whenever this file is changed:

```
webcal://azetinashjc.github.io/belize-holidays/Belize-Holidays.ics
```

### iPhone / iPad
1. **Settings → Calendar → Accounts → Add Account → Other → Add Subscribed Calendar**
2. Paste the `webcal://` link above
3. Tap **Next**, then **Save**

### Mac (Calendar app)
1. **File → New Calendar Subscription**
2. Paste the link above (use `https://` instead of `webcal://` if prompted)
3. Set refresh frequency, then **Subscribe**

### Google Calendar
1. **Other calendars → + → From URL**
2. Paste the `https://` version of the link above

## What's included

All public and bank holidays observed in Belize, including fixed-date holidays (e.g. New Year's Day, Independence Day) and movable religious holidays (Good Friday, Holy Saturday, Easter Monday).

## Updating this calendar

Belize's official holiday list is announced yearly by the Belize Press Office, usually a few months before each new year, and can change occasionally (e.g. new holidays added, dates shifted per the Act's Sunday/Friday/Tuesday–Thursday rules).

To update:
1. Get the latest official press release from the Belize Press Office
2. Edit `Belize-Holidays.ics` in this repo — add or update the relevant `VEVENT` blocks
3. Commit the change

Once committed, subscribed calendars will pick up the update automatically on their next refresh (typically within a day).

## Disclaimer

This is an unofficial, community-maintained calendar file. Always confirm holiday dates against the official [Belize Press Office](https://www.pressoffice.gov.bz) release for anything time-sensitive (banking, government offices, legal deadlines).
