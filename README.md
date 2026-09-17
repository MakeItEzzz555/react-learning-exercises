# React Learning Exercises

> This coursework has been consolidated into [MakeItEzzz555/frederick-university-coursework](https://github.com/MakeItEzzz555/frederick-university-coursework). This repository is archived to preserve its history and URLs.

Vite React practice projects exploring routing, context, theme switching and persistent todos.

## Contents

| Folder / file | Topic | Technologies |
| --- | --- | --- |
| `Router-Practice` | Home/About/Contact route demo with basic navigation and styled components. | JavaScript / React / Vite |
| `ContextThemeSwitcher` | Light/dark UI toggle distributed through React context. | JavaScript / React / Vite |
| `TODOlist` | Adds, edits, deletes and completes todos and persists them in localStorage. | JavaScript / React / Vite |
| `User-Context` | Stores form-entered user state in context and shows a greeting/profile. | JavaScript / React / Vite |

Each folder is an independent exercise or project. Original folder organization, dependency versions and required project configuration are preserved.

## Getting Started

Each subfolder has its own Vite package and lockfile. With Node.js and npm installed, enter one subfolder, run `npm ci`, then `npm run dev`. Keep the historical dependency versions. TODOlist stores data in browser localStorage; User-Context is a state-sharing demo and does not authenticate users. The theme import now matches `Theme.js` exactly; the TODO update callback uses its requested ID. The routing exercise uses a neutral example contact address.

## Validation

Lightweight local checks: Vite production build using copied installed dependencies. Compilation and syntax checks do not verify application behavior. Source is preserved; interactive application behavior was not executed during archival.

## Notes

Original implementation is preserved. Build outputs, dependencies, machine-specific IDE state, backups, submission documents and private runtime data are excluded. No license has been inferred for the original work.
