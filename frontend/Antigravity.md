# Noteify Tech Stack & Conventions

A simple guide to the tech stack and coding practices used in this project.

## Tech Stack
- **React (v19)**: For creating the user interface using reusable components.
- **Vite**: Used as the build tool and development server for fast builds.
- **Vanilla CSS**: Standard CSS used for dark theme styles, responsive layout, and transitions.

## Conventions & Rules
- **State Management**: Uses React's `useState` for UI changes and `useEffect` to save notes to the browser's `localStorage`.
- **Navigation (Multi-Page)**: Uses simple state-based routing (`currentView` state) to toggle between pages (Notes list vs. Note creator) instead of heavy external routing libraries.
- **Styling**: Standard custom CSS variables defined in `:root` of `App.css` for consistent colors, shadows, and rounding values.
