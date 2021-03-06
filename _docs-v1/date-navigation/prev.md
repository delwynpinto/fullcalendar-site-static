---
title: prev
type: method
since_version: 1.3
---

Moves the calendar one step back (either by a month, week, or day).

<div class='spec' markdown='1'>
.fullCalendar( 'prev' )
</div>

If the calendar is in `month` view, will move the calendar back one month.

If the calendar is in `basicWeek` or `agendaWeek`, will move the calendar back one week.

If the calendar is in `basicDay` or `agendaDay`, will move the calendar back one day.

Example using `prev` with an external button:

```js
$('#my-prev-button').click(function() {
  $('#calendar').fullCalendar('prev');
});
```

<div class='version-info' markdown='1'>
In versions 1.0 through 1.2.1, this option was known as *prevMonth*.
</div>
