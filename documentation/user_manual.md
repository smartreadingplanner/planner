# **What** is the SmartPlanner application
The `SmartPlanner` application is intended to help the user to organize and plan his learning or reading tasks.\
The user can elaborate a reading or learning schedule around a book or a reading support in general (book, reading paper...etc). He can then:
- Start the reading schedule, and follow the schedule progress and the expected schedule end date
- Add personal reading notes while reading
- At the end of the reading schedule, elaborate a schedule summary, by aggregating the notes or by writing a summary from scratch.
- Pause the schedule for a given period, and resume it later on
- Filter the list of displayed schedules, based on schedules tags and/or status

# **How** to use the SmartPlanner application
### Create the schedule or planning
To create a schedule (or planning), you should provide:
- The schedule title (e.g. simply the book title)
- The number of pages in the book (*)
- The average reading time for a single page (*)
- The desired start and end dates of the schedule
- At least a tag representing the general topic of the schedule (e.g. Economy, Literature...etc)
- And finally the dedicated weekly time slots for the schedule

_Schedule information:_\
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/2_schedule_properties_wizard.png" width="200">

_Schedule dedicated time slots:_\
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/3_schedule_availabilities_wizard.png" width="200">

(*) These data are used to have an approximation of the total reading time of the book.

> - After the schedule creation, and also all along the schedule progress, the application gives the user an approximation about the ***expected end date*** of the reading schedule.\
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/4_schedules_view.png" width="200">

> - The application will notify you before the schedule tasks. Please ensure that the **notifications are allowed** on your device for the `SmartPlanner` application.\
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/notification.png" width="200">

> - The application will ask you to allow notifications when needed.

### Run your schedule
1. Upon notification reception, or if you want to run the schedule outside the dedicated time slots, go to the schedule details view and click on the `Run Task` **before starting your reading**
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/6_schedule_details.png" width="200">
2. While running your reading task, you have the possibility to add your personal notes. You can share these notes with other people. (cf. screenshot in point 4.)<br>
3. You can also pause the task at any time to have a break, and resume it later on.<br>
4. Once you have finished your reading, please to click on the `End Task` button. This is mandatory so your reading time is taken into account in the schedule, and your notes are saved.
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/7_run_task.png" width="200">

When you end the task, if the schedule is finished, either <br>
i. the dedicated reading time is fully consumed\
ii. or the end date is passed\
iii. or if the schedule was previously extended and the extended date expires <br><br>
Then the application will suggest the user to :\
a) End the schedule. The schedule will then be finished and closed\
b) Extend the schedule to a future date. The expected end date will then always be the same as the extended date\
c) For recursive schedules, there will be as well the option to restart the schedule. When restarted, a new achievement record will be registered for the schedule. And its achieved time will be reset again to zero, for another reading iteration.

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/end_extend_restart_schedule.png" width="200">

# Further functionalities
### Timetable view
The timetable view shows a daily tasks based view, for all the active schedules. The user can then have a global view of the reading tasks he has for every weekday. Below is an illustration. <br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/5_timetable_view.png" width="200">

### Summaries
For each schedule, you can create a summary. You can build the summary by aggregating the schedule tasks notes, or you can create a summary from scratch.
These summaries can be shared by other people. cf. screenshots below: <br><br>
_Schedule menu_<br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/summary_menu_item.png" width="200">

_Create a summary_<br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/summary_create_dialog.png" width="200">

_View, edit or share summary_<br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/summary_view.png" width="200">

### Pausing schedules for a given period
You can pause the schedule for a given period. You can then resume it later on.<br>
Paused schedules will have their notifications suspended during the pause period.<br>

_Pausing schedule menu_<br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/pause_schedule_menu.png" width="200">

_Paused schedule below: Aristotle's Physics_<br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/paused_schedule.png" width="200">

### Terminating a schedule
The user can terminate a schedule, even if not yet completely finished.

### Reordering schedules
Long press on a schedule to move it to a different order in the schedules list.

### Deleting a schedule, a weekly task or a summary
In the schedules list, the summaries list, as well as in the time slots list, you can delete an element swiping it from the right to the left.

### Edit a schedule time slot
In the schedule details view, you can edit a time slot by long pressing on it. A dialog is then opened to choose a new time slot.

### Tags
Every schedule SHOULD have at least one associated tag (at most 3 tags). <br>
There is a list of provided tags (e.g. Economy, Arts...etc). You can also create your own custom tags. <br>
_The tags view_ <br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/tags.png" width="200">

_User can add custom tags_ <br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/tag_new.png" width="200">

### Filters
In the schedules list view, you can filter the list of displayed schedules. <br>
You can then display only the schedules that have at least one of the filter tags. Or display only the schedules having a given status.<br>
Only filtered schedules will be displayed in the schedules list, as well as in the timetable view. <br>
When no filter is activated, the filter icon is shown as below: <br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/filter_off.png" width="200">

_When the user clicks on the filter icon, a dialog appears to add the filter_ <br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/filter_add.png" width="200">

_The filter icon then indicates an active filter, as below_ <br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/filter_on.png" width="200">

# Settings
### Application settings
You can set some general settings for the application. For example:
- The average reading time per page (e.g. 2min)
- The min and max task durations (for time slots creation)

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/settings_app.png" width="200">

### Display settings
For example:
- The application language
- The system display theme

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/settings_display.png" width="200">

# Download
(Play Store) https://play.google.com/store/apps/details?id=ch.baker.planner
