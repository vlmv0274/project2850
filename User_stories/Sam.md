# User Story 1
As a student who commutes, 
I want to know about timetable changes quickly, 
so that I can plan my travels in time.

## Acceptance Criteria 
Given a lecture time is already set,
when the timetable is changed, 
then a notification is sent.

Given a timetable change, 
when a notification is sent, 
then it is received in <15 minutes.

Given a timetable change,
when a notification can't be sent,
then an email is sent in <30 minutes.


# User Story 2
As a student who commutes,
I want to be able to see my timetable easily,
so that I can easily plan my travels.

## Acceptance Criteria
Given the app is open,
when I open the timetable,
then a week of lectures is shown.

Given the timetable is open,
when I scroll/change dates,
then a single week is still shown.


# User Story 3
As a student who checks the timetable the night before,
I want the timetable to be available 24/7,
so that I'm not caught not knowing my schedule.

## Acceptance Criteria
Given it is any time of the day,
when I open the timetable,
then my week should be shown.

Given the timetable is unavailable,
when I open the timetable,
then the last known timetable should be shown.

# User Story 4
As a student who sometimes runs late,
I want the QR scanner to be available quickly,
so there is one less delay to stress about.

## Acceptance Criteria
Given the app has a check-in option,
when I open the app,
then I can access the QR scanner in <2 taps.

Given the check-in option is available,
when I open it,
then it should load in <2 seconds.
