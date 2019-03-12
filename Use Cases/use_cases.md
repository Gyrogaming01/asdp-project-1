# ITLC Timetable System

## Use Cases

### Add Lesson
Preconditions:
- Signed in as mentor

Normal Sequence of Steps:
1. Get lesson info
2. Add to schedule

Postconditions:
- Updated timetable
- Time-slot cannot be booked again

### Remove Lesson
Preconditions:
- Signed in as mentor

Normal Sequence of Steps:
1. Select lesson to Remove
2. Update schedule
3. Inform involved users (mentor, students who booked)

Postconditions:
- Updated timetable
- Time-slot can be booked again

### Change Lesson
Preconditions:
- Signed in as mentor

Normal Sequence of Steps:
1. Select lesson to change
2. Get new information
3. Update schedule
4. Inform involved users (mentor, students who booked)

Postconditions:
- Updated timetable
- New time-slot cannot be booked again
- Old time-slot can be booked again

### Show Timetable
Preconditions:

Normal Sequence of Steps:
1. Select timetable to show
2. Display timetable

Postconditions:

### Search Lessons
Preconditions:

Normal Sequence of Steps:
1. Get search terms (lesson type, time, etc.)
2. Search schedule for matching classes
3. Display matching classes

Postconditions:

### Book Class
Preconditions:

Normal Sequence of Steps:
1. Get information (topic, preferred time, etc.)
2. Add to request list
3. Mentor contacts student if additional info needed (e.g. different time)
4. Class added to schedule

Postconditions:
- New class booked
- Time-slot cannot be booked again

### Check against DkIT Timetable
Preconditions:

Normal Sequence of Steps:
1. Select DkIT classes to search
2. Display common free slots
3. Display links to individual class timetables

Postconditions:

### Contact Mentor
Preconditions:

Normal Sequence of Steps:
1. Select mentor to message
2. Get message to send
3. Send message to chosen mentor
4. Mentor may reply

Postconditions:

### Update Class attendance
Preconditions:
- Signed in as mentor

Normal Sequence of Steps:
1. Get class to update
2. Get class attendance info
3. Update database with info

Postconditions:

### Monitor Class Attendance
Preconditions:
- Signed in as mentor
- Class attendance has been uploaded

Normal Sequence of Steps:
1. Select class to check
2. Display attendance for class

Postconditions:

### Update Student Progress
Preconditions:

Normal Sequence of Steps:
1. Select student and class
2. Get student progress (grades etc.)
3. Update database

Postconditions:

### Track Student Progress
Preconditions:
- Student has progress data available

Normal Sequence of Steps:
1. Select student
2. Display student progress

Postconditions:

### Provide Online Resources
Preconditions:
- Signed in as mentor

Normal Sequence of Steps:
1. Select topic
2. Get resource (text, link, pdf, etc.)
3. Add to resource list for that topic

Postconditions:

### Access Online Resources
Preconditions:

Normal Sequence of Steps:
1. Get topic to search for
2. Display resources for selected topic

Postconditions:
