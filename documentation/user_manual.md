# **What** is the SmartPlanner application
The `SmartPlanner` application is intended to assist the user to organize and follow in an effective and scientific manner his learning or studying tasks, as well as his general or daily life tasks.\
The user can elaborate a schedule (a studying schedule, or simply a normal schedule for general tasks). <br>
The user can :
- Create a schedule, and follow the schedule progress, statistics and other information
- Add personal notes while running tasks
- At the end of the schedule, elaborate a summary, by aggregating the notes or by writing a summary from scratch.
- Pause the schedule for a given period, and resume it later on
- Filter the list of displayed schedules, based on schedules tags and/or status
- Share notes, summaries or schedule statistics online with other users

There are 2 types of schedules:
- Study schedules: for study, learning or reading tasks
- Agenda schedules: general or daily life schedules (e.g. sport workout, personal tasks...etc)

The main functions are illustrated below:
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/smartplanner-intro.gif" width="200">

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

(*) These parameters are used to have an approximation of the total required study or reading time of the book.

Below is an illustration of the schedule creation form:

_Schedule information wizard:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/new_schedule.png" width="200">

> To get notified about the schedule coming tasks:
> -  Please add notifications to the schedule.
> -  Please also ensure that the **notifications are allowed** on your device for the `SmartPlanner` application.

_Schedule task notification_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/schedule_notification.png" width="200">

> The application will ask you to allow notifications when needed.

### Schedules view
The schedules view contains the list of created schedules (Study and agenda (normal) schedules)
The list contains schedules headers with brief important information about the schedule (title, start date, repeat mode, tags...etc). 

> For study schedules, the application gives the user an approximation about the ***expected study end date*** of the schedule.<br>
> For study schedules also, the study progress is indicated in the schedule header.

_Schedules list:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/schedules_list.png" width="200">

#### Additional custom tasks

For both study and agenda schedules, The user can add additional tasks, as illustrated below: <br><br>

_Adding custom time slots:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/add_custom_slots.png" width="200">

##### For weekly schedules:

_Adding weekly custom time slots:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/add_custom_weekly_time_slots.png" width="200">

### Archived schedules:
When the end time (schedule limit or the number of occurrences) of a schedule is expired, then the schedule is marked as expired.

Then the schedule is archived as follow:
- For non repeat schedules, the schedule is archived after 1 day
- For daily schedules, the schedule is archived after 3 days
- For weekly schedules, the schedule is archived after 7 days
- For monthly and yearly schedules, the schedule is archived after 30 days

Finished schedule are also archived as well.

### Schedule details and statistics
The schedule details view contains the following information :
- `Accomplished time`: the time that was consumed during the schedule runs. For study schedules, if the schedule is restarted, ths achieved time is reset to `0` and a new achievement is added.
- `Runs`: The number of times the schedule was run (a run is triggered using the `Run Task` in the schedule details view.
- `Notes`: How many notes were creaated in the schedule

For study schedules, the statistics contains also the following data:
- `Progress`: The study progress, or percentage of the study accomplishment (based on the achieved time and the calculated reading time)
- `Accomplishments`: How many times the schedule was finished and restarted.

The schedule details contains also the schedule run statistics, the schedule notes, and eventual achievements. As well as schedule timeslots, repeat mode details and notifications

_Schedule details:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/schedule_details_study_1.png" width="200">
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/schedule_details_study_2.png" width="200">
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/schedule_details_study_3.png" width="200">
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/schedule_details_study_4.png" width="200">

The task runs with notes are indicated with the symbol 🗒. <br><br>

### Timetable view
The timetable view shows the daily tasks (each day with its scheduled tasks), for all the active schedules. Below is an illustration. <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/timetable.png" width="200">

> You can run a task directly via the task header play button.

#### Creating a summary
For each schedule, you can create a summary. You can build the summary by aggregating the schedule tasks notes, or you can create a summary from scratch.
These summaries can be shared with other people. cf. screenshots below: <br><br>
You can consult your notes in the schedule details view menu (cf below)

There is a size limit for summaries and notes created by users:<br>
- For notes: `10.000` characters
- For summaries: `100.000` characters

_View, edit and share notes_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/notes.png" width="200">

_View, edit and share summaries_<br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/summary.png" width="200">

### Run the schedule
1. Upon notification reception, or if you want to run the schedule outside the dedicated time slots, go to the schedule details view and click on the `Run Task` **when starting your task**
2. While running your task, you have the possibility to add your personal notes. <br>
3. You can also pause the task at any time to have a break, and resume it later on. <br>
4. When you have finished your task, please click on the `End Task` button. This is **mandatory** so your accomplished time is taken into account in the schedule, your notes are saved, and statistics are updated. <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/run_mode_normal.png" width="200">

> You can update the task duration at any time.
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/task_note_edit_duration.png" width="200">

While the task is running, or paused, a notification is shown indicating the running (or paused task), with its details (schedule name, start time, accomplished time, the task note). Below is an illustration: <br><br>
_Running task notification:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/notification_running.png" width="200">

_Paused task notification:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/notification_paused_with_notes.png" width="200">

For study schedules, when the user ends the task, if the dedicated study time is fully consumed, then a dialog is displayed to the user to choose one of the following actions: <br>
i. Finish and archive the study schedule <br>
ii. Continue the study schedule <br>
iii. Restart the schedule. The accomplished time and the schedule progress is reset to `0`, and the schedule can be started from the beginning. <br><br>

_Reading schedule end dialog:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/reading_time_consumed_dialog.png" width="200">

#### Audio listening to files and web pages
You can listen  (audio reading) to files (pdf, microsoft docx, md or text files),
You can also listen to web pages content via the integrated browser.

_Audio listening to a local file:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/run_mode_file.png" width="200">

_Audio listening to an internet web page:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/run_mode_browser.png" width="200">

You have the possibility to adapt the audio settings (TTS engine, language...etc) for the read fil or web page.

> For webpages, the audio controls are available only after the page html content is loaded.

### Notes and Summaries view
In this view, you can consult, search, edit, or organize in folders your notes and summaries.
To move a note or summary into a folder, simply drag and drop the note (or summary), or the whole schedule notes inside the desired folder.

_Moving a note into a specific folder:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/moving_note_into_folder.png" width="200">

To create a folder, use the floating button.

### Statistics view
Contains all the statistics about the schedules and their runned tasks (tasks run time per day, per tag, task run modes...etc).

_User schedules statistics:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/statistics_1.png" width="200">
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/statistics_2.png" width="200">
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/statistics_3.jpg" width="200" height="355">
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/statistics_4.jpg" width="200" height="355">

# Cloud content

You can share your content (notes, summaries and statistics) with other users online. You can get also content matching your respective schedules (match by tags ou keywords).

<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud_workflow.png" width="200">

### How content is shared
When you share a content (note, summary or schedule status) online, it is shared with the following metadata:
- The tags of the schedule to wich the content belongs
- The keywords of the schedule to wich the content belongs
- The sharing context, which is the groups with which to share privately the content with.
  No groups means that the content is shared publicly with all users. If some groups are specified, only these groups members can access the shared content.

Once, you can update or delete the content on the cloud.

#### Sharing notes and summaries
In the notes view, and summary view, you have the menu to share the content on the cloud. Below an illustration example for sharing a note online.

_Task note menu:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/task_view_menu.png" width="200">

_Sharing a note privately within a group:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/cloud_sharing_status_private.png" width="200">

#### Sharing schedule's status
The schedule's status can only shared within groups. It can not be shared publicly with all users.

### Real time fetched content for schedules
For each schedule, cloud content is fetched automatically on real time. The content is fetched based on the schedule tags and keywords.

_Notifications about new cloud content:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/schedules_list_with_cloud_notifs.png" width="200">

_Cloud matching content for a given schedule:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/schedules_new_cloud_content.png" width="200">

### Cloud groups
Every user can create a group on the cloud. Other users online can then join this group.
The group members can then share content privately (content accessible only for group members) within the group.

_Cloud groups:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/cloud_groups.png" width="200">

_Cloud group content:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/cloud_group_content.png" width="200">

The group owner can manage the group settings. Accept or decline users requests to join the group. Or delete members from the group.

_Cloud group settings:_ <br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/cloud/cloud_group_settings.png" width="200">

### Cloud search
You can search for specific content (notes and summaries) on the cloud, based on some criterias. You can also search for specific groups, and then send joining requests to join them.
You become a member of a specific group only when the group owner accepts your joining request.

## Application Backup
You can upload a backup of your schedules and application data on your Google Drive account.
You can later download this backup on the same device (be aware this will erase the actual application data). Or download this backup on another device.

<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/application_backup.png" width="200">

## Upload content to Google Drive
You can upload your content (summaries, folders with various notes & summaries) to your Google Drive.

<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/google_drive_upload.png" width="200">

## Save content localy in the device
You can save your content (summaries, folders with various notes & summaries) in your local device.

<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/content_local_save.png" width="200">

## Advanced themes
Upgraded users have access to advanced application themes.

## Further functionalities

### Global search
You have the possibility to search your schedules, notes, summaries and their content.

_Searching in schedules:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/search_notes.png" width="200">

_Searching in summaries and notes contents:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/search_schedules.png" width="200">

### Other operations on schedules
#### Pausing schedules for a given period
You can pause a schedule for a given period. You can then resume it later on.<br>
Paused schedules will have their notifications suspended during the pause period.<br>

#### Terminating a schedule
You can terminate a schedule, even if not yet completely finished.

#### Reordering schedules
Long press on a schedule to move it to up or down in the schedules list order.

#### Deleting a schedule, a summary or a tag
In the schedules list, the summaries list, the tags list, you can delete an element swiping it from the right to the left (for Arabic language display, swipe from left to right).

> Deleting a schedule will not delete its associated summary. However, the schedule associated notes will be deleted.

#### Restarting a study schedule
For study schedules, when the progress is >= 75%, then the user has the possibility to restart the schedule and restart the study or book reading from the beginning. <br><br>

#### Editing a schedule time slot
In the schedule details view, you can edit a time slot by long pressing on it. A dialog is then opened to choose a new time slot.

#### Copying a schedule
You can copy a schedule. Note that only the schedule properties are copied. The run history, notes and statistics are not copied.

### Filters
In the schedules list view, you can filter the list of displayed schedules. <br>
You can then display only the schedules that have at least one of the filter tags. Or display only the schedules having a given status.<br>
Only filtered schedules will be displayed in the schedules list. And only the filtered schedules tasks will be displayed in the time.<br>

_When you clicks on the filter icon, a dialog appears to add the filter_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/schedules_filter.png" width="200">

In the filter above, only the schedules with ,history' tag are displayed.

For statistics, an additional (and exclusif) filter parameter is the tasks runs period (tasks that were run in a given period of time).
This way only the statistics of this period of time are shown.

### Tags
Every schedule SHOULD have at least one associated tag (at most 3 tags). <br>
There is a list of provided tags (e.g. Economy, Arts...etc). You can also create your own custom tags. <br>

_The tags view_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/tags.png" width="200">

# Settings
### Application settings
You can set some general settings for the application. For example:
- The average reading time per page (e.g. 2min)
- The min and max task durations (for time slots creation)

You can also set the global audio parameters (The TTS speech engine parameters). cf screenshot below.

_Application settings:_ <br><br>
<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/settings_app.png" width="200">

### Display settings
For example:
- The application language
- The system display theme

<img src="https://raw.githubusercontent.com/smartreadingplanner/smartplanner/main/documentation/display/settings_display.png" width="200">

### Application menu
You can check the application menu for more functionnalities.<br><br>
<img src="https://github.com/smartreadingplanner/smartplanner/blob/release/cloud/documentation/display/app_menu.png" width="200">

# Download
(Play Store) https://play.google.com/store/apps/details?id=ch.baker.planner

(App Store) https://itunes.apple.com/app/id6470530541
