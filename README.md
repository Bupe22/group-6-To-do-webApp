# Todo List (Group 6)

A simple web app project that helps users organize and manage daily tasks.

## About

The Todo List system is designed to make it easier to keep track of daily activities. Users can create an account, sign in, and manage tasks from a dashboard. The current version is a frontend-only prototype built with plain HTML and CSS.

## Main Features

### Available now

- Landing page with links to sign in and create an account
- Sign-in page and create-account page
- "My tasks" dashboard with one simple task list and overview cards
- Add-task popup opened from the dashboard (works without JavaScript)
- Separate add-task page (`addTask.html`)
- Responsive layout for desktop, tablet, and mobile

### Planned

- Saving tasks and showing them on the dashboard
- Editing, completing, and deleting tasks
- User accounts and authentication with a backend
- Database storage for tasks and users

## Tech Stack

| Technology | Purpose |
| --- | --- |
| HTML | Page structure and content |
| CSS | Styling, layout, responsive design, and the CSS-only add-task popup |
| JavaScript | Planned for client-side interaction and validation |
| PHP | Planned for server-side logic, authentication, and form processing |
| MySQL | Planned for database storage and data management |
| Git & GitHub | Version control and team collaboration |

## Project Structure

```text
frontend/
  index.html          # Landing page
  css/
    index.css         # Landing page styles
    login.css         # Sign in page styles
    signUp.css        # Create account page styles
    dashboard.css     # Dashboard layout and task list styles
    addTask.css       # Add-task popup and add-task page styles
  pages/
    login.html        # Sign in page
    signUp.html       # Create account page
    dashboard.html    # "My tasks" dashboard with the add-task popup
    addTask.html      # Standalone add-task page
```

## How the Add Task Popup Works

The popup is opened with a normal link to `#add-task` and closed with a link to `#close`. CSS `:target` shows and hides it, so the dashboard needs no JavaScript. The same styles are reused by the standalone add-task page.

## Current Status

All frontend pages are in place and responsive. The add-task form is not connected to a backend yet, so submitted tasks are not saved. JavaScript, PHP, and MySQL functionality can be added as the project progresses.

## Running the Project

Open `frontend/index.html` in a web browser. There is no build step and no server required for the current frontend.
