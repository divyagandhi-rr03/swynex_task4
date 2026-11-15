# StudySync — Task 02: Information Architecture & Low-Fidelity Wireframes

## Product concept
StudySync is a student study planner and productivity tracker for college students and competitive-exam aspirants. It helps learners organise tasks, plan study sessions, focus during work, and review progress.

## Information architecture
- **Home:** Today overview, upcoming deadlines, quick actions, daily goal.
- **Tasks:** All tasks, filters, task details, add/edit task, completion state.
- **Planner:** Calendar, day/week view, scheduled study blocks, reminders.
- **Focus:** Focus timer, session goal, pause/resume, session summary.
- **Progress:** Weekly study time, completed tasks, streak, subject breakdown.
- **Profile / Settings:** Personal details, subjects, notification preferences, help.

Main navigation: Home | Tasks | Planner | Focus | Progress. Profile/Settings is accessed from the profile icon.

## Intended user flow
Sign in → optional first-use onboarding → Home → Tasks or Planner → Task details → Focus session → Mark complete → Progress.
Quick path: Home → Add Task → Save → Home.

The core cycle is plan → prioritise → focus → complete → review.

## Major screens
1. Welcome / Sign in: product introduction, email, password, sign-in, create account, forgot password.
2. Home Dashboard: greeting, daily goal/progress, upcoming deadline, today's tasks, quick Add Task action.
3. Tasks: search, All/Today/Upcoming/Completed filters, task rows, completion controls.
4. Add/Edit Task: title, subject/category, due date/time, priority, reminder, Save and Cancel.
5. Planner: calendar, selected-day agenda, scheduled study blocks, add schedule action.
6. Focus Timer: selected task, timer, session progress, Start/Pause, End session.
7. Progress: weekly study time, study time by day, tasks completed, streak, subject breakdown.

## Important design decisions
- Five-item bottom navigation keeps frequent destinations visible.
- Home is the default landing screen so users immediately see priorities and deadlines.
- Quick-add reduces the effort of capturing a task.
- Tasks and Planner are separate: tasks represent what to do; Planner represents when to do it.
- The Focus screen is minimal to reduce distraction.
- Progress highlights a few understandable metrics rather than dense analytics.
- Clear labels, feedback, and empty/overdue/completed states support usability.

## Usability considerations
- Keep primary actions visually distinct and consistently placed.
- Provide feedback after saving, completing, or ending a session.
- Provide confirmation or undo for destructive actions.
- Use helpful empty states such as “Add your first task”.
- Keep text and touch targets usable on small mobile screens.

## Conclusion
This IA and wireframe set defines the core StudySync experience from account entry through daily planning, focused study, task completion, and progress review. It is a foundation for interactive Figma wireframes and later high-fidelity UI design.
