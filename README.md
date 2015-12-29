pimatic-calendar
================

Predicates for calendar events from ical calendars (e.g. Google Calendar)

```json
  {
    "plugin": "calendar",
    "calendars": [
      {
        "name": "Main Calendar",
        "ical": "https://calendar.google.com/calendar/ical/.../basic.ics"
      }
    ]
```

The following predicates are supported:

 * If calendar event with title|description contains|equals "some text" starts|ends|takes place

To get a ical url from your google calendar follow https://support.google.com/calendar/answer/37648 under "See your calendar (view only)"
