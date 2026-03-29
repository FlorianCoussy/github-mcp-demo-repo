# TaskBoard Lite

TaskBoard Lite is a very small vanilla JavaScript web app for managing simple tasks.

This repository is designed as a demo project for showcasing real GitHub MCP workflows with Claude Code.

## Features

- Add tasks
- Search tasks
- Mark tasks as complete
- Delete tasks
- Persistent storage via localStorage
- Small and beginner friendly codebase

## Data Persistence

Tasks are automatically saved to `localStorage` under the key `tasks`. Changes (add, toggle, delete) are persisted immediately and survive page reloads.

On first load, if no saved data is found, a set of seeded tasks from `src/data.js` is used as the default state.

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript

## Run Locally

You can use any static file server. One simple option is:

```bash
npm install
npm run start
