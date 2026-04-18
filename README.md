# dreytools-tasks

Kanban task board for drey tools.

**Live:** https://tasks.dreytools.com
**CF project:** `dreytools-tasks`

## Features

- 4-column Kanban: Backlog / Todo / In Progress / Done
- Drag and drop cards between columns
- 3 boards: Personal / 1BB / VE (toggle from header)
- Card details: title, description, priority (P1/P2/P3), tags (Work/Client/Ship/Research/Bug), owner avatar, due date
- Due-date badges: overdue (red), today/tomorrow (amber), future (muted)
- Create / edit / delete tasks via modal
- Search across title + description
- Live open/done counter
- localStorage persistence (dreytools-tasks-v1)
- Seeded with realistic tasks on first load (Drey ship queue + Kevin 1BB + VE clients)
- Mobile: horizontal-scroll board, touch-friendly cards
- Safe-area insets, iOS zoom-blocker

## Can fold into 1BB Community Platform

Designed to become a feature inside the white-label 1BB community (Skool-killer). Pattern: each community has shared boards, users assign tasks, owners filter by their avatar.

## Stack

Pure HTML + CSS + vanilla JS. Single file. HTML5 drag-drop API. Zero dependencies.

## Deploy

```bash
wrangler pages deploy . --project-name dreytools-tasks --branch main
```
