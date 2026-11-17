# Horizon guide

Horizon is for planning projects: tasks with dates and dependencies on the Gantt chart, who does what, how loaded the team is and how the work goes compared with the plan. It runs in the browser, as a Windows app and as an Android app. The apps also work on their own and, if you want, connect to a server or to a team computer.

## Getting started

1. **Create an account:** open the server address and choose "Create an account". If the server is invitation-only, use the link you received by e-mail.
   - The password needs at least 10 characters: an easy-to-remember sentence is fine.
   - Very common passwords and passwords containing your name or e-mail are refused.
2. **Name your organization and first project.** The organization groups people and projects; you can have more than one and switch from the menu at the top left.
3. **Add tasks** with "New task", or type in the row at the bottom of the view.

To look around before you start, **Try a sample project** (at the start, or "Open a sample project" on Home) makes a project already filled in, with some tasks assigned to you. On Home the **First steps** list walks you through five steps (create a project, add three tasks, link two, assign one, invite a colleague) that tick themselves; **Hide** removes it.

**Home your way:** **Customize** chooses what Home shows and in which order: First steps, Numbers, Upcoming tasks, Upcoming milestones, My late tasks, Project status, Active projects. The choice applies on this device.

## Project views

| View | What it is for |
|---|---|
| **Gantt** | Bars on the calendar, dependencies, critical path, today line. Drag a bar to move it, its edge to change the duration, the handle to link it to another task |
| **Table** | Every column, editing several rows at once; you write in it as in a spreadsheet |
| **Kanban** | Columns by status: moving a card changes the status |
| **Calendar** | Month, week or agenda. Drag a task to another day (or Alt+arrows); a double click on a day creates one |
| **Overview** | The project at a glance: actual and planned progress over time, tasks done and late, hours, costs, a timeline by section and the people |
| **Map** | The project as a tree (sections, tasks, subtasks) to open, close, drag and zoom |
| **Progress** | Progress by section and comparison with a baseline |

When you move a task that others depend on, Horizon previews what would move and asks for confirmation. **Ctrl+Z** undoes.

**Keyboard on the Gantt:**

| Key | Action |
|---|---|
| Ctrl+C / Ctrl+V | Copy the task, paste it below the row |
| Alt+← / Alt+→ | Move the task by one day |
| Alt+Shift+← / → | Change the end |
| L | Link the task to the next one you pick |
| T | Go to today |
| M / Shift+M | Next / previous milestone |
| R / Shift+R | Next / previous late task |
| Delete | Delete the task (Ctrl+Z puts it back) |
| + / − | Zoom in or out |
| Enter | Open the details |
| Space | Complete the task, or untick it |
| F2 | Rename in place (Enter keeps, Esc goes back) |
| Ctrl+Enter | A new task below, written in place |
| Alt+↑ / Alt+↓ | Move the task up or down among those at its level |
| Ctrl+Shift+→ / ← | Indent or outdent (subtasks) |
| Shift+F10 or the Menu key | The task menu |
| Ctrl+click / Shift+click | Add to the selection / select up to here |
| Shift+↑ / Shift+↓ | Grow the selection |
| Ctrl+Space / Ctrl+A | Pick or drop the row / select all |

Anywhere, **Ctrl+K** opens the quick search for projects, tasks and commands, and **?** the list of every shortcut, with those of the open view first. Button tooltips show the key, for example "Go to today (T)".

**Overview timeline:** it shows the whole span of the project. **Layout** switches between Compact (one bar per section) and Extended (each section with its tasks); **Colours** picks by status, task colour or progress; the scale goes from weeks to years, the − + zoom widens the drawing and **Copy to clipboard** takes it to an e-mail or a presentation as an image.

**Columns:** on the Gantt and the Table, the **Columns** button chooses what you see: WBS (outline number, 1.2.3), dates, duration, status, %, people, hours, priority, risk, labels, dependencies, costs and custom fields. The choice applies to the project on this device and is kept in saved views too. On the Gantt you can change status and % by clicking them.

**Completion check (Gantt):** the circle before the name turns green when the task is at 100%. A click on the circle, or Space on the row, completes it: status "Done" and 100%. Unticking takes the task back to 0% and, if it was done, to "To do". Summary tasks have a dashed circle that turns green when all their subtasks are finished: you complete it by ticking those.

**Status and percentage go together:** on the Gantt, the Table, the Kanban and in the details, bringing the percentage to 100% makes the task "Done"; lowering it reopens a done task ("In progress", or "To do" at 0%). Changing the status from "Done" to another one starts the percentage again from 0%.

**Task numbers:** at the left of the name, on the Gantt and in the Table, each task has a running number (1, 2, 3…) through the whole plan, sections excluded. Closing a branch or filtering does not renumber: the hidden numbers are skipped. The Dependencies column uses the same numbers ("3", "5FS+2").

**Writing on the Gantt:**
- **F2**, or "Rename" in the task menu, turns the name into a field: Enter keeps it, Esc goes back.
- **Ctrl+Enter** on a row opens a new row below, at the same level: type the name and press Enter, and another one opens to go on; Esc stops.
- At the end of each open section there is **+ New task**.
- **Sections** have their own menu (right-click the section's row, or Shift+F10): new task in the section, **Rename** (F2 too) and **Delete the section**. Deleting it, Horizon asks first and says how many tasks it holds: they stay in the project, without a section. Deleting a section is for whoever can delete everyone's tasks (Owners, Admins, Project managers).
- After the name you can write a start and a duration, after a bar: "Testing | fri 5d".

**Reordering:** drag a row's **number** and drop it before or after another row (top or bottom of the row) or inside it (the middle), where it becomes its subtask. Where it cannot go, the line turns red and says why. With the keyboard **Alt+↑/↓**; in the task menu **Move up** and **Move down**. **Ctrl+Z** undoes it.

**Bar card:** hovering a bar, or reaching it with the keyboard, shows its dates and working days, status and %, people, predecessors, slack (how far it can slip without moving the project's end) and its variance from the compared baseline. Esc closes it.

**Gantt toolbar:** the buttons come in groups (Today and Fit; Expand and Collapse), with their names next to the icons when there is room. The critical path and the minimap are switched on from the **Show** menu. With the focus on a button, ←/→ move to the others.

**Dates in words:** in the details, in a new task and in the Table's cells you can write dates the way you would say them:
- dates: "15/12", "15 dec", "2026-12-15";
- words: "today", "tomorrow", "end of month";
- weekdays: "fri", "monday" (the next one);
- steps: "+3d", "+2w", "+1m", "in 2 weeks".

For an end, a duration works too, "5d" or "2w" (10 working days). Under the field you read what it understood; Esc goes back to the previous value, the calendar icon opens the picker. The **duration** in the details can be changed and moves the end.

**Details beside the view:** on screens 1200 px wide or more, a task's details open on the right and the view stays usable: clicking another task opens it instead. ‹ › or **Alt+↑/↓** go to the previous or next task, in the view's order; **Esc** closes them and takes you back; **F6** moves between the view and the details.

**Undo and Redo:** the two buttons at the top right of the project, or **Ctrl+Z** and **Ctrl+Y** (Ctrl+Shift+Z), go back and forth one change at a time: dates and moves (with the tasks that moved along), names, status and fields, people, links with their type and lag, repeats, sections (new, renamed, deleted) and changes to several tasks at once. The button tells you what the next step is about. The history belongs to the browser tab and the project; reloading the page starts it empty.

**Deleting can be undone:** after a delete the message has **Undo**, and **Ctrl+Z** too puts the task back with its subtasks, links and people. It works offline too, while the deletion is waiting to be sent. Horizon asks first only for large deletions: more than 10 tasks at once, or a task with more than 10 subtasks.

**Selecting several tasks:** on the Gantt and the Kanban, pick several tasks with Ctrl+click or Shift+click, with Shift+↑/↓, or by dragging a rectangle over the empty part of the chart. In the Table use the checkboxes. A bar shows up with status, people, priority, section, **Move…** (by N working days, forward or back), duplicate and delete, for all of them at once; **Clear selection** closes it. Dragging a selected bar moves the others too. Ctrl+Z undoes it in one step.

**Why this date?** In a task's details, and on the bar card in the "Why here" line, Horizon says what keeps it where it is: the task it waits for (with the lag and the days off in between), a constraint, the chosen date or the project's start. Next to it is the one-click fix: **Remove the link**, **Remove the date** or **Bring forward to…**. On the Gantt the chain holding it lights up.

**Paste a list:** copy a list from a document, an e-mail or a spreadsheet and press **Ctrl+V** on the Gantt or in the Table (or the project's ⋯ menu › **Paste a list…**). Each line becomes a task; indents and numbered lists become subtasks; a spreadsheet's columns with headers become the fields. @person, #label, !priority and, after a bar, a date and a duration work too ("Survey @Giulia | 16/11 3d"). You see a tree preview first; Ctrl+Z removes it all.

**Open as a project:** from the menu of a task with subtasks, **Open as a project** shows only that branch, as if it were a project of its own. A line on top reminds you; **The whole project** goes back.

**Back where you were:** reopening a project takes you to the view you last used on this device, and the Gantt to the same day and row. Links to a task (Inbox, e-mail) always go to the task.

**On a phone:** the header shrinks to the name while you scroll the plan and comes back whole at the top; "Planned finish" and slack are in the summary's "+". The view tabs show their names and scroll sideways. Search and filters fit on one line, with "Only mine", baselines and views in the "⋯" menu. A "+" at the bottom right creates a task, and menus come up from the bottom, with taller rows.

**List width:** drag the right edge of the task list. Narrower, the list scrolls sideways on its own (its bar, or the wheel over the list); wider, the hidden columns come back and then the name grows. Dragged all the way left, the list closes; the button on the edge opens it again. With the keyboard, focus on the edge: ←/→; Enter or a double click fit it to the columns.

**Dragging a bar:** while you move it, its new dates, working days and how many tasks move with it show next to it. **Lock the bars**, in the Gantt toolbar, stops drags (handy in a meeting or on a tablet): dates change in the details.

**Next to the bars:** from **Show**, choose what you read after each bar: people, progress, dates, slack. PDFs and images follow the same choice. **Copy image** puts the part of the Gantt you see, with the filters, on the clipboard, ready to paste in an e-mail or a chat.

**Reschedule:** from the project's ⋯ menu, or the button by the status when tasks are late. Late tasks start again from today (those under way keep their start and end after the work left), or every unfinished task moves by some working days. Before confirming you see the new dates, the tasks that move with them and the new end; Ctrl+Z undoes it all in one step.

**Since your last visit:** reopening a project, a line on top says how many changes the others made, who, and to how many tasks. Changed rows have a dot on their number; **Show only these** filters them, **Mark as seen** clears it all.

**Table as a spreadsheet:** the arrows move from cell to cell (where they do not change the value), Enter goes down a row and Shift+Enter up. In the **Predecessors** column write the numbers of the tasks to wait for, with type and lag if needed: "3, 5SS+2".

**Table:** each header has a menu to sort, show only some values (status, priority, section, people, labels; "Late only" on the end), fit the width or hide the column.

**Column widths (Gantt):** each column of the list has a handle on the right edge of its header. Drag it, or reach it with Tab and use ←/→. A double click, or Enter, fits the column to its content. Widths apply on this device; **Columns › Back to the defaults** brings them back.

**Long texts:** a name or value too long for its column ends with "…". Hover it, or reach it with the keyboard, to read it whole; Esc closes it.

**Closing the task list:** the round ‹ button on the list's edge closes it and gives the chart the whole width; › reopens it. It is also in quick search (Ctrl+K, "Gantt: close or open the task list") and Horizon remembers it. With the list closed the keyboard still works: the selected row's name shows over the chart.

**Minimap:** the map button in the Gantt toolbar shows the whole chart small, bottom right, with a frame on the part in view. Click or drag to move; with the focus on the minimap use the arrows, Home and End. × closes it, and it does not show when the whole chart is already in view.

**Today:** a red line marks today, with a "Today" label in the scale (Day and Week zoom). The crosshair button or the T key take the view there.

**Project summary:** under the project's name you find its state, start date, owner, priority and risk. The state comes from the plan:
- **Late:** the planned end is past the project's deadline;
- **At risk:** some unfinished tasks should already have ended;
- **On track:** otherwise;
- a project on hold, completed or archived shows that.

Priority and risk are chosen in the project settings: with the right to change the project, click any item of the summary.

**Export and share:** the button next to "New task" makes an image or a PDF, an Excel sheet or a CSV, or a read-only link.

**Seeing better:** in Settings › Appearance and language, **Text size** (Normal, Large, Larger) makes everything bigger; **Higher contrast** darkens secondary text and makes borders and the selection easier to see; **Patterns on the Gantt's bars** hatches late tasks and dots critical ones, so you do not need to tell colours apart.

**Density:** on computers Horizon uses a **compact** layout (smaller text, lower rows) to show more of the plan at once. If you prefer more room, choose **Comfortable** from the user menu, the quick search or Settings › Profile. On the Gantt, **Fit the project** picks the zoom that shows the whole project.

## Tasks

A task has:
- a section, dates, a duration in working days and a status;
- priority, progress and an estimate in hours;
- labels, assignees with a percentage, and constraints;
- for milestones, a single date.

The details panel shows first what changes most (status, priority, dates, progress, people, description); the rest is in groups you open and close, which stay as you leave them (Links and subtasks, Planning, Hours and costs, Labels and colour). Under the title you read how the last change went: "saved", "queued" without a network, or "not saved". Further down, comments, attachments and history.

**Task menu** (right click, Shift+F10, or a long press): Status, Assign (with "To me"), Priority, Duplicate, Copy link, Convert to milestone or task, Follow and Delete, besides levels and moves. **Delete** removes the selected task on the Gantt, in the Table, on the Kanban and on the Map; Ctrl+Z puts it back.

**Quick writing:** in a new task's name (a Gantt row, the Table's quick row, "New task") "@Giulia" assigns it, "#wiring" adds the label and "!high" the priority; suggestions show as you type. With filters on, the task takes their values, so it stays in view.

**Repeating tasks:** in the details, **Repeat** picks every day, every working day, every week, every 2 weeks, every month or every year, or a rule in words: "every 2 weeks mon and thu", "every month after completion". When you complete the task the next one is born, with the same people and labels; with "Count from the day it is finished" the date starts from there. Tasks without subtasks repeat.

**Approvals:** in the details, **Approvals › Ask to approve…** sends the request to a person of the project (a guest too), for the task or for an attachment, with a note. The person finds it in the Inbox and answers once, **Approve** or **Do not approve**, with a comment if they want; whoever asked gets the answer. While it is pending, the request can be withdrawn.

**Conflicts:** when a task has locked dates but its links would start it later, the details say so and offer to move it, unlock the dates or cut the link's lag.

- **Dependencies:** finish→start, start→start, finish→finish, start→finish, with lag or lead in days.
- **Calendars:** working days come from the project's calendar; people's time off (Settings › Time off) counts for the workload.

### Subtasks and levels

Under each section you can build a list with several levels: a task with subtasks, which have subtasks in turn, down to **10 levels**.

- **Task menu:** right-click the row (Gantt, Table) or the card (Map), the ⋯ or ⋮ button, or Shift+F10. It holds: open the details, new task at the same level, new subtask, indent, outdent. When an item cannot be used it stays greyed out and says why.
- **Indent** (Ctrl+Shift+→): the task goes under the one above it at the same level.
- **Outdent** (Ctrl+Shift+←): the task goes up a level, right after the task that held it.
- **Ctrl+Z** undoes these moves too.
- A task with subtasks is a **summary**: its dates, progress and hours worked come from the subtasks. Subtasks take the section of their top-level task.
- A milestone cannot have subtasks. In the Table, levels change only in plan order (with no column sorting).

### Copying and pasting tasks

From the task menu choose **Copy** (or **Ctrl+C**), then on another row **Paste below** (or **Ctrl+V**). In the Table, the rows selected with their checkboxes are copied.

- A copied row brings its subtasks; you can paste into another project of the same organization too.
- Copies keep dates, estimate, people, labels and the links among them, and start over at "To do" and 0 %, with no hours worked.
- **Ctrl+Z** removes everything you pasted.

### Custom fields

Each project can have fields of its own: **Columns › Manage custom fields** (or the project's ⋯ menu), for whoever manages the project.

| Type | Example |
|---|---|
| Dropdown list, with colours | Contractor |
| Text | Order number |
| Decimal or whole number | Square metres |
| Currency (the project's) | Budget |
| Percentage | Discount |
| Checkbox | Verified |

- Fill them in from the task panel, in the Table and, if you choose the column, on the Gantt. They end up in CSV and Excel files.
- Deleting a field or an option loses its values: Horizon first tells you how many tasks have one.
- **Copy the fields of another project** brings the definitions, not the values.
- Read-only links do not show them.

## Working together

- **Comments and mentions:** type `@` and the name. The person gets a notification in the **Inbox**, and by e-mail or push if they turned those on (Settings › Notifications). With `#` you cite another task, by number or name: in the comment it becomes a link.
- **Following a task:** comments reach who created it, who is assigned and who commented. With **Follow** (in the details or the task menu) you get them too; you can also stop. Next to it you see who follows it.
- **Grouped Inbox:** the notifications of the same day about the same task stay on one line; one click opens the others.
- **Quiet hours:** in Settings › Notifications choose the hours without e-mail or push notifications (for example from 8 pm to 8 am). Everything still arrives in the Inbox.
- **Muting a project:** the project's ⋯ menu › **Mute notifications**: from that project only mentions, assignments and approvals arrive, and only in the Inbox.
- **Inbox:** from each notification reply to the comment, complete the task, **snooze** it (it comes back unread later: in three hours, tomorrow morning, Monday, in a week) or mark it **Done**, which takes it out of the Inbox (it stays in the Done tab). J/K to move, E for Done; on a phone swipe right for Done, left for tomorrow.
- **Presence:** you see who is looking at the same project. Other people's changes appear without reloading.
- **Read-only links:** from the project's ⋯ menu, with expiry and revocation. Whoever opens one sees the project's latest status too.
- **Project status:** in the Overview, **Update the status** publishes a traffic light (On track, At risk, Off track) and a few lines on what is going on. Updates stay in the history and show on Home, on the read-only link and in the weekly report.
- **Weekly report:** in Settings › Notifications, **Weekly report** sends you an e-mail every Monday morning with your tasks of the week, the late ones, the next milestones and the status of the projects.
- **Favourites and recent:** the star next to the name of a project or a task puts it among the **Favourites**, in the sidebar. Below are the **Recent** ones. In Ctrl+K favourites and recent items come first. They apply on this device.
- **Search the whole organization:** **Search** in the sidebar, or "Across the organisation" in Ctrl+K, finds tasks, descriptions, comments, attachment names and projects. The beginnings of words are enough, and capitals and accents do not matter ("surv plan"). The filters choose what to look for, the project and "Open tasks only".
- **Request forms:** the project's ⋯ menu › **Request forms…** makes a public link anyone, even without an account, can use to ask for work: title, details, name, e-mail and maybe a date. Each request becomes a task in the section you choose, and the project's managers find it in the Inbox. Turn a form off or delete it whenever you want.
- **Guests:** for clients, suppliers and outside consultants, invite the person with the **Guest** role and add them to the projects they should see. They read and comment (if the project allows it) and answer approvals, but do not see the organization's other people or their workload, and cannot export.
- **Attachments:** drop files on a task's panel. They always download as files; if the server has an antivirus, an infected file is refused.

## Better planning

- **Workload:** hours assigned per person and per day against capacity; overloads are highlighted. Horizon never reassigns anything by itself, but from a cell's details you can give a task to someone else (see their load before and after) or move it by a few days, with Undo.
- **Baselines:** snapshots of the plan (⋯ menu › Baselines…), to compare on the Gantt, in the table and in Progress.
- **Templates:** save a project as a template and start again from it; built-in templates are there too.
- **Saved views:** filters, sorting and columns, for you or for everyone.
- **Import:** ⋯ menu › Import from CSV:
  1. upload the file and choose the columns;
  2. check the preview row by row;
  3. import.

  Every import can be undone from the History.
- **Export:** CSV, Excel, PDF or a PNG image of the Gantt, with the range and columns you choose. In the PDF and the image each task's name is next to its bar.
- **Hours worked and costs:** in a task's panel, enter the **hours worked** (in quarter hours). From the project's ⋯ menu › **Costs and rates**, choose the currency and each person's hourly rate. The Overview works out:
  - estimated cost = estimated hours × rate;
  - actual cost = hours worked × rate.

  The hours of a task with several assignees are split by each one's percentage; hours with no assignee, or of people without a rate, are shown apart. Only Owners, Admins and whoever manages the project see the rates, and they never end up in exports, files or shared links.
- **Overview:** the "Actual" line is recorded day by day from when the project runs on version 1.1; before that it is dashed.
- **Forecast:** in the Overview, **When it will end** runs the project many times, making each open task last a little less or a little more according to its risk. Three dates come out: **Likely (50%)**, **Safe (80%)** and **Almost certain (95%)**, with the chance of ending by the planned finish and by the deadline.
- **Earned value:** next to it, the schedule index (SPI) and the cost index (CPI, or an effort index in hours without rates) and the expected cost at the end. 1 means on track; below 1, behind or over budget.
- **"What if…" scenarios:** in the Gantt toolbar, **What if…** opens a scenario: you move bars and change dates, but nothing changes in the plan. The real bars stay as ghosts, and the scenario bar says how much the project's end changes. **Apply** saves every change in one step (Ctrl+Z undoes); **Discard** throws them away.
- **Level:** also in the Gantt toolbar, **Level** delays tasks not yet started until nobody is over 100% of their hours, and shows the result as a scenario to check before applying it. Tasks started, done or locked do not move.
- **Portfolio:** **Portfolio** in the sidebar shows every project you can see on one timeline, with progress, late tasks, milestones and links between projects.
- **Links between projects:** in a task's details, **Other projects › Wait for a task of another project…** makes it wait for a task of another project. When that one moves, the tasks waiting for it move too, from project to project. Loops between projects are refused. On the Gantt the bar card says what it waits for.
- **Project XML:** when exporting, choose **Project XML**, the interchange format other planning programs read: outline, dates, links with type and lag, people and calendar. **Import from CSV** takes a project XML file too and tells you first what does not come across.
- **Calendar in your apps:** in Settings › Notifications, **Calendar in your apps** makes an `.ics` address of your tasks or of a project. Add it to the calendar of your phone or computer ("Add calendar from URL") and the tasks update by themselves. Whoever has the address sees those tasks: if you lose it, revoke it.
- **Holidays from a file:** in Settings › Working calendars, **Import from .ics** adds the holidays of a downloaded calendar (for example the national one); then save.
- **Trash:** deleted projects and tasks stay for 30 days in Settings › **Trash**. **Restore** puts them back where they were, with everything deleted along with them. Whoever deletes many things in a row (more than 300 in ten minutes) is stopped for a few minutes.

## AI assistant

If your organization turned it on, choose **AI assistant…** from the project's ⋯ menu:
1. describe the work (a list of tasks, one per line, works best);
2. Horizon proposes sections, tasks, durations and dependencies;
3. correct them, remove rows, change the start date;
4. press **Apply**.

**Until you apply, nothing changes in the project.** An applied proposal can be undone like an import. The offline rules send no data anywhere; an external model (for example Claude) receives only the text you write.

## Automatic rules and other programs

- **Automatic rules:** the project's ⋯ menu › **Automatic rules…**. A rule has three parts:
  1. **When:** a task is created, its status changes (or becomes a given status), someone is assigned, a comment arrives, a task is late or its end is near;
  2. **If** (optional): it has a label, it is in a section, it has a priority, it is assigned to someone;
  3. **Then:** set the status or the priority, add a label, assign, notify the assignees or the managers, move to a section, call a webhook.

  For example: "when the status becomes Done, notify the project's managers". A rule acts as whoever saved it, and stops if that person can no longer change the project. **What it did** shows its runs. Rules that set each other off stop after three steps.
- **Outgoing webhooks** (Settings › Integrations, Owners and Admins): Horizon sends the chosen events (tasks created, changed, deleted, comments, assignments…) to another program, with a signed HTTPS request. If the program does not answer, it tries again for 12 hours. **Send a test** and **Deliveries** help you check.
- **API keys** (Settings › Security and devices): for scripts and other programs. A key acts as you, with your permissions, for the days you choose or until you revoke it; **Read only** changes nothing. Copy it at once: it will not be shown again. A key never changes the account, never does sensitive operations and does not use real time.

## Integrations

In Settings › Integrations (Owners and Admins) you connect a project to an issue tracker:
- new issues become tasks;
- title, status and labels stay aligned, both ways if you choose;
- if both sides change, Horizon records a conflict and asks which value to keep.

A "Sandbox Tracker" lets you try it without external accounts; GitHub Issues needs an OAuth App set up by whoever runs the server.

## Your account's security

**Settings › Security and devices:**
- **Change password:** your other devices are signed out.
- **Two-step verification:** recommended, and required if your organization or the server requires it.
  1. Install an authenticator app: Aegis or FreeOTP, free and open source, or Google or Microsoft Authenticator.
  2. Press **Turn on…**, confirm your password and scan the QR code.
  3. Type the 6-digit code.
  4. **Keep the 10 recovery codes**, for example in your password manager. Each one works once if you lose your phone.

  At sign-in, after the password, Horizon asks for the app's code.
- **Passkeys:** **Add a passkey** lets you sign in with your device's fingerprint, face or PIN, without a password: on the sign-in page choose **Sign in with a passkey**. A passkey cannot be stolen by a fake site and counts as two-step verification. It works when Horizon is opened by its name (not an IP address) in a browser that supports it; in the Windows and Android apps you sign in with the password.
- **Devices:** the browsers and apps you signed in with; sign them out one by one or all at once. When you sign in from a new device you get an e-mail: if it was not you, change your password and sign that device out.
- **Confirm it is you:** before sensitive operations (signing devices out, changing roles, deleting projects, making public links, keys, webhooks or forms) Horizon asks for your password, code or passkey again. The confirmation lasts 10 minutes.
- **Account activity:** sign-ins (failed ones too), new devices, password, two-step verification and passkeys, with date and device.
- **Security log** (Settings › Organization, Owners and Admins): roles, invitations, shared links, exports, deleted projects, integrations, keys and webhooks. Each entry is tied to the one before: **Check integrity** says whether any was removed or changed.
- **Inactivity:** if you do not use Horizon from a browser for 14 days, you will be asked to sign in again.

If you lost both your phone and your recovery codes, ask whoever runs the server: after checking who you are, they can turn off two-step verification so you can sign in.

## The Windows and Android apps

- **On their own:** at start you have a workspace on this computer or phone, without an account and encrypted, with the key kept by the system.
- **Connected:** in the browser of the server (or of the host computer) open Settings › Security and devices › **Connect a Horizon app**: a code and a QR code appear. In the app open **This computer** (or **This phone**) › **Connect to a host** and type the code, or scan the QR code with the phone.
- **Without a network:** changes wait in a queue and leave as soon as the connection is back. If someone changed the same field meanwhile, you choose which value to keep.
- **Host mode (Windows):** the computer acts as the server for the local network, for example in a small office without a server.

**Signing out in the browser** (user menu › Sign out): if some changes have not been sent yet, Horizon tells you before deleting them from that browser.

## Roles

| Role | What they can do |
|---|---|
| Owner | Everything, including the organization and its Owners |
| Admin | People, workspaces, integrations, organization settings |
| Project Manager | Their projects: settings, members, baselines, links, imports, rates and costs |
| Member | Tasks, dependencies, comments, exports |
| Viewer | Read only (comments if the project allows them) |
| Guest | Outside people: only the projects they are invited to; they read, comment if the project allows it and answer approvals; they do not see the other people and cannot export |
