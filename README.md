# RelayHQ — Work stays in sync

RelayHQ is a lightweight project dashboard concept for small and remote teams that need task ownership, deadline visibility, and a readable activity feed without the setup overhead of a heavyweight project-management suite.

## Run locally

No build step or dependencies are required. Open `index.html` in a modern browser, or serve the folder with any static file server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## What works in this prototype

- Dashboard summary for open, due-soon, completed, and overdue tasks
- Three-column task board: To do, In progress, and Done
- Drag and drop between columns, plus one-click status changes
- Create tasks with description, priority, owner, status, and due date
- Search tasks and filter by high priority or tasks assigned to the current user
- Deadline radar and an activity feed updated by task actions
- Browser-local persistence using `localStorage`
- Responsive layout for desktop and mobile screens

## Honest limitations

This is a frontend MVP. Task and activity data are stored in the current browser only. It does **not** currently implement authentication, shared multi-user persistence, real-time collaboration, email/push notifications, or a server API. Deadline alerts are visible in the dashboard; they are not sent externally.

## Stack and AI assistance

- HTML5, CSS3, vanilla JavaScript
- Browser `localStorage` for persistence
- AI-assisted coding was used to accelerate scaffolding and implementation; the builder remains responsible for reviewing, testing, and explaining the result.

## Adaptation log

Record the actual text of Challenge Card #1 and Challenge Card #2 here, then document the implementation decisions made in response. Do not claim a card was addressed unless the resulting change is visible and testable.
