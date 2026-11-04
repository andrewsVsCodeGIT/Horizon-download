# Horizon guide

Horizon is for planning projects: tasks with dates and dependencies on the Gantt chart, who does what, how loaded the team is and how the work goes compared with the plan. It runs in the browser, as a Windows app and as an Android app. The apps also work on their own and, if you want, connect to a server or to a team computer.

## Getting started

1. **Create an account:** open the server address and choose "Create an account". If the server is invitation-only, use the link you received by e-mail.
   - The password needs at least 10 characters: an easy-to-remember sentence is fine.
   - Very common passwords and passwords containing your name or e-mail are refused.
2. **Name your organization and first project.** The organization groups people and projects; you can have more than one and switch from the menu at the top left.
3. **Add tasks** with "New task", or type in the row at the bottom of the view.

## Project views

| View | What it is for |
|---|---|
| **Gantt** | Bars on the calendar, dependencies, critical path, today line. Drag a bar to move it, its edge to change the duration, the handle to link it to another task |
| **Table** | Every column, editing several rows at once |
| **Kanban** | Columns by status: moving a card changes the status |
| **Calendar** | Month, week or agenda |
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
| + / − | Zoom in or out |
| Enter | Open the details |
| Ctrl+Shift+→ / ← | Indent or outdent (subtasks) |
| Shift+F10 or the Menu key | The task menu |

Anywhere, **Ctrl+K** opens the quick search for projects, tasks and commands.

**Overview timeline:** it shows the whole span of the project. **Layout** switches between Compact (one bar per section) and Extended (each section with its tasks); **Colours** picks by status, task colour or progress; the scale goes from weeks to years, the − + zoom widens the drawing and **Copy to clipboard** takes it to an e-mail or a presentation as an image.

**Columns:** on the Gantt and the Table, the **Columns** button chooses what you see: task number, dates, duration, status, %, people, hours, priority, risk, labels, dependencies, costs and custom fields. The choice applies to the project on this device and is kept in saved views too. On the Gantt you can change status and % by clicking them, and drag the edge of the task column to widen it.

**Export and share:** the button next to "New task" makes an image or a PDF, an Excel sheet or a CSV, or a read-only link.

**Density:** on computers Horizon uses a **compact** layout (smaller text, lower rows) to show more of the plan at once. If you prefer more room, choose **Comfortable** from the user menu, the quick search or Settings › Profile. On the Gantt, **Fit the project** picks the zoom that shows the whole project.

## Tasks

A task has:
- a section, dates, a duration in working days and a status;
- priority, progress and an estimate in hours;
- labels, assignees with a percentage, and constraints;
- for milestones, a single date.

The details panel also holds comments, attachments and the change history.

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

- **Comments and mentions:** type `@` and the name. The person gets a notification in the **Inbox**, and by e-mail or push if they turned those on (Settings › Notifications).
- **Presence:** you see who is looking at the same project. Other people's changes appear without reloading.
- **Read-only links:** from the project's ⋯ menu, with expiry and revocation.
- **Attachments:** drop files on a task's panel. They always download as files; if the server has an antivirus, an infected file is refused.

## Better planning

- **Workload:** hours assigned per person and per day against capacity; overloads are highlighted. Horizon never reassigns anything by itself.
- **Baselines:** snapshots of the plan (⋯ menu › Baselines…), to compare on the Gantt, in the table and in Progress.
- **Templates:** save a project as a template and start again from it; built-in templates are there too.
- **Saved views:** filters, sorting and columns, for you or for everyone.
- **Import:** ⋯ menu › Import from CSV:
  1. upload the file and choose the columns;
  2. check the preview row by row;
  3. import.

  Every import can be undone from the History.
- **Export:** CSV, Excel, PDF or a PNG image of the Gantt, with the range and columns you choose.
- **Hours worked and costs:** in a task's panel, enter the **hours worked** (in quarter hours). From the project's ⋯ menu › **Costs and rates**, choose the currency and each person's hourly rate. The Overview works out:
  - estimated cost = estimated hours × rate;
  - actual cost = hours worked × rate.

  The hours of a task with several assignees are split by each one's percentage; hours with no assignee, or of people without a rate, are shown apart. Only Owners, Admins and whoever manages the project see the rates, and they never end up in exports, files or shared links.
- **Overview:** the "Actual" line is recorded day by day from when the project runs on version 1.1; before that it is dashed.

## AI assistant

If your organization turned it on, choose **AI assistant…** from the project's ⋯ menu:
1. describe the work (a list of tasks, one per line, works best);
2. Horizon proposes sections, tasks, durations and dependencies;
3. correct them, remove rows, change the start date;
4. press **Apply**.

**Until you apply, nothing changes in the project.** An applied proposal can be undone like an import. The offline rules send no data anywhere; an external model (for example Claude) receives only the text you write.

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
- **Devices:** the browsers and apps you signed in with; sign them out one by one or all at once.
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
