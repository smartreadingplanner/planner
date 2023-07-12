# **What** is the SmartPlanner application
The `SmartPlanner` application is intended to assist the user to organize and follow in an effective and `scientific` manner his learning or studying tasks, as well as his general or normal tasks.\
The user can elaborate a schedule (a studying schedule, or simply a normal schedule for general tasks). <br>
The user can :
- Create a schedule, and follow the schedule progress, statistics and other information
- Add personal notes while running tasks
- At the end of the schedule, elaborate a summary, by aggregating the notes or by writing a summary from scratch.
- Pause the schedule for a given period, and resume it later on
- Filter the list of displayed schedules, based on schedules tags and/or status

There are 2 types of schedules:
- Study schedules: for study, learning or reading tasks
- Agenda schedules: general or normal schedules (e.g. sport workout, personal tasks...etc)

# **How** to use the SmartPlanner application
### Create the schedule or planning
To create a schedule (or planning), you should provide:
- The schedule title (e.g. for study or reading schedules, the book title for example)
- The desired start date of the schedule
- The schedule time slots and their repeat mode
- At least a tag representing the general topic of the schedule (e.g. Economy, Literature, Arts...etc)

And for study or reading schedules, the following info:
- The number of pages of the book or the reading support (*)
- The average reading time for a single page (*)

(*) These parameters are used to have an approximation of the total study or reading time of the book.

Below is an illustration of the schedule creation form:

_Schedule information wizard:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/2_schedule_form_study.png" width="200">

> - To get notified about the coming tasks:
-  Please add notifications to the schedule.
-  Please also ensure that the **notifications are allowed** on your device for the `SmartPlanner` application. <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/5_schedule_notification.png" width="200">
> - The application will ask you to allow notifications when needed.

### Schedules view
The schedules view contains the list of created schedules. The study schedules are separated from the normal agenda schedules.
The list contains schedules headers with brief important information about the schedule (title, start date, repeat mode, tags...etc). 

> - For study schedules, the application gives the user an approximation about the ***expected study end date*** of the schedule.
> - For study schedules also, the study progress is indicated in the schedule header.

_Schedules list:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/3_schedules_list_study.png" width="200">

#### Additional custom tasks

For both study and agenda schedules, The user can add additional tasks, as illustrated below: <br><br>

_Adding custom time slots:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/4.1_add_custom_tasks.png" width="200">

_Display of custom time slots:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/4.1_custom_tasks_display.png" width="200">

For weekly schedules:
_Adding weekly custom time slots:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/4.2_add_custom_tasks_weekly.png" width="200">

_Display of weekly custom time slots:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/4.2_custom_tasks_display_weekly.png" width="200">

### Archived schedules:
When the end time (schedule limit or the number of occurrences) of a schedule is expired, then the schedule is marked as expired.

Then the schedule is archived as follow:
- For non repeat schedules, the schedule is archived after 1 day
- For daily schedules, the schedule is archived after 3 days
- For weekly schedules, the schedule is archived after 7 days
- For monthly and yearly schedules, the schedule is archived after 30 days

_Archived schedules:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/6.1_expired_then_archived_schedule.png" width="200">

Finished schedule are also archived as well.

### Schedule details and statistics
The schedule details view contains the following statistics :
- `Accomplished time`: the time that was consumed during the schedule runs. For study schedules, if the schedule is restarted, ths achieved time is reset to `0` and a new achievement is added.
- `Runs`: The number of times the schedule was run (a run is triggered using the `Run Task` in the schedule details view.
- `Notes`: How many notes were creaated in the schedule

For study schedules, the statistics contains also the following data:
- `Progress`: The study progress, or percentage of the study accomplishment (based on the achieved time and the calculated reading time)
- `Accomplishments`: How many times the schedule was finished and restarted.

> - Schedule statistics <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/7_schedule_details_study.png" width="200">

The details view contains also the timeslots, repeat mode details and notifications...etc

### Timetable view
The timetable view shows the daily tasks (each day with its scheduled tasks), for all the active schedules. Below is an illustration. <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/8_timetable.png" width="200">

### Run the schedule
1. Upon notification reception, or if you want to run the schedule outside the dedicated time slots, go to the schedule details view and click on the `Run Task` **when starting your task**
2. While running your task, you have the possibility to add your personal notes. You can share these notes with other people. <br>
3. You can also pause the task at any time to have a break, and resume it later on. <br>
4. When you have finished your task, please click on the `End Task` button. This is **mandatory** so your accomplished time is taken into account in the schedule, and your notes are saved. <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/9.0__task_run.png" width="200">

While the task is running, or paused, a notification is shown indicating the running (or paused task), with its details (schedule name, start time, accomplished time, the task note). Below is an illustration:
_Running task notification:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/9.1_notification_running.png" width="200">

_Paused task notification:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/9.2_notification_paused_with_notes.png" width="200">

For study schedules, when the user ends the task, if the dedicated study time is fully consumed, then a dialog is displayed to the user to choose one of the following actions:
i. Finish and archive the studz schedule <br>
ii. Continue the study schedule <br>
iii. Restart the schedule. The accomplished time and the schedule progress is reset to `0`, and the schedule can be started from the beginning. <br><br>

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/10_reading_time_consumed_dialog.png" width="200">

# Further functionalities

### Summaries and notes
For each schedule, you can create a summary. You can build the summary by aggregating the schedule tasks notes, or you can create a summary from scratch.
These summaries can be shared to other people. cf. screenshots below: <br><br>
You can also consult your notes in the schedule details view menu (cf below)

There is a size limit for summaries and notes created by users:<br>
- For notes: `10.000` characters
- For summaries: `100.000` characters

_Schedule menu_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/11_schedule_details_menu.png" width="200">

_View, edit and share notes_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/13_notes.png" width="200">

_View, edit and share summaries_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/12.1__init_summary.png" width="200">

### Other operations on schedules
#### Pausing schedules for a given period
You can pause a schedule for a given period. You can then resume it later on.<br>
Paused schedules will have their notifications suspended during the pause period.<br>

_Paused schedule example below: Aristotle's Physics_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/14_paused_schedule.png" width="200">

#### Terminating a schedule
You can terminate a schedule, even if not yet completely finished.

#### Reordering schedules
Long press on a schedule to move it to up or down in the schedules list order.

#### Deleting a schedule, a weekly task, a summary or a tag
In the schedules list, the summaries list, the tags list, you can delete an element swiping it from the right to the left (for Arabic language display, swipe from left to right).

> Deleting a schedule will not delete its associated summary. However, the schedule associated notes will be deleted.

#### Restarting a study schedule
For study schedules, when the progress is >= 75%, then the user has the possibility to restart the schedule and restart the study or book reading from the beginning.

#### Editing a schedule time slot
In the schedule details view, you can edit a time slot by long pressing on it. A dialog is then opened to choose a new time slot.

### Filters
In the schedules list view, you can filter the list of displayed schedules. <br>
You can then display only the schedules that have at least one of the filter tags. Or display only the schedules having a given status.<br>
Only filtered schedules will be displayed in the schedules list. And only the filtered schedules tasks will be displayed in the timetable view. <br>

_When no filter is activated, the filter icon is shown as below:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/15.1_filter_off.png" width="200">

_When you clicks on the filter icon, a dialog appears to add the filter_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/15_filter_inprogress_history_or_sport.png" width="200">

In the filter above, only the schedules with the following properties are displayed:
- In progress (started and not yet terminated)
  AND
- Have one of the following tags: "History", or "Sport and Health Care".

_The filter icon then indicates an active filter, as below_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/15.2_filter_on.png" width="200">

### Tags
Every schedule SHOULD have at least one associated tag (at most 3 tags). <br>
There is a list of provided tags (e.g. Economy, Arts...etc). You can also create your own custom tags. <br>

_The tags view_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/16.1_tags.png" width="200">

_User can add custom tags_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/16.2_add_tag.png" width="200">

The new tag "Algebra" is added as below, and can be associated to schedules: <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/16.4_added_custom_tag.png" width="200">

# Settings
### Application settings
You can set some general settings for the application. For example:
- The average reading time per page (e.g. 2min)
- The min and max task durations (for time slots creation)

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/blob/featre/schedule_agenda/documentation/display/17.2_settings_app.png" width="200">

### Display settings
For example:
- The application language
- The system display theme

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/17.1_settings_display.png" width="200">

### Application menu
You can check the application menu for more functionnalities.<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/18_app_menu.png" width="200">

# Download
(Play Store) https://play.google.com/store/apps/details?id=ch.baker.planner
