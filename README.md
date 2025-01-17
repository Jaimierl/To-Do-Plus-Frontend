# Team: ToDoPlusUltra

# App: Calendar Carousel - [Link!](https://calendar-carousel.netlify.app/)

## Members

- Anthony Turinski
- Jae Loney
- Chris Rarig

## To Do Plus

- The problem solved by this app is having a calendar oriented to-do list. So many times calendars are strictly for events with to-do lists that are strictly for tasks. With this app, the user will be able to assign times to tasks (as well as delete or set up recurring tasks) and integrate this list with their Google calendars. Some additional features would even include linking the tasks with a messaging platform or allowing users to share to-do tasks.

## MVP

- The minimum viable product would let the user input and delete tasks to be done as well as times the tasks would take individually and link this with a calendar for accountability.

## Wireframe

![Wireframe](/wireframe.png)

## Domain Model

![Domain Model](/domain_model.png)

## Project Management and User Stories

[Trello](https://trello.com/b/4ndc5YjL/todoplus)

## Database Schema

```json
Event:
{
  "summary": "Appointment",
  "location": "Somewhere",
  "start": {
    "dateTime": "2011-06-03T10:00:00.000-07:00",
    "timeZone": "America/Los_Angeles"
  },
  "end": {
    "dateTime": "2011-06-03T10:25:00.000-07:00",
    "timeZone": "America/Los_Angeles"
  },
  "recurrence": [
    "RRULE:FREQ=WEEKLY;UNTIL=20110701T170000Z",
  ],
  "attendees": [
    {
      "email": "attendeeEmail",
      # Other attendee's data...
    },
    # ...
  ],
}
```

## Credits:
- Landing Photo by <a href="https://unsplash.com/@serge_k?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Serge Kutuzov</a> on <a href="https://unsplash.com/s/photos/carousel?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

