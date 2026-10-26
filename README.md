# Cat-Note — A Simple Notes App

A minimal, cat-themed note-taking application built with React, Vite, and Tailwind CSS. Create, edit, search, and delete notes through a simple interface, with your notes saved locally in your browser.

**Live Demo:** [Cat-Note](https://cat-note-ten.vercel.app/)

**Source Code:** [GitHub Repository](https://github.com/adita097/NotesApp)

## Features

- **Create Notes** — Add notes with a title and description.
- **Edit Notes** — Update existing notes whenever you need to.
- **Delete Notes** — Remove unwanted notes with a confirmation prompt.
- **Search Notes** — Find notes by searching their titles or descriptions.
- **Persistent Storage** — Notes are saved in browser `localStorage` and remain available across page reloads in the same browser.
- **Responsive Layout** — A two-section layout that adapts to different screen sizes.
- **Cat-Themed UI** — A playful visual design featuring cat illustrations and notepad-inspired note cards.
- **Input Validation** — Prevents saving notes without both a title and description.

## Tech Stack

| Technology | Purpose |
|---|---|
| React 19 | UI components and state management |
| Vite | Development server and production build |
| Tailwind CSS 4 | Styling and responsive layouts |
| JavaScript (ES6+) | Application logic |
| Browser localStorage | Client-side note persistence |
| ESLint | Code linting |
| Vercel | Deployment and hosting |

## Getting Started

Follow these steps to run Cat-Note locally.

### Prerequisites

- Node.js compatible with Vite 7
- npm
- Git

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/adita097/NotesApp.git
```

**2. Navigate to the project directory**

```bash
cd NotesApp
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

**5. Open the application**

Visit the local URL displayed in your terminal, usually:

```text
http://localhost:5173
```

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the Vite development server |
| `npm run build` | Creates an optimized production build |
| `npm run preview` | Previews the production build locally |
| `npm run lint` | Runs ESLint to check for code issues |

## How to Use

1. Enter a title and description in the note creation form.
2. Click **Add Note** to save your note.
3. Browse your notes in the Recent Notes section.
4. Use the search field to filter notes by title or description.
5. Select the blue action button on a note to edit it.
6. Select the red action button to delete it after confirmation.

Your notes are automatically saved in the browser's local storage whenever the notes list changes.

## Project Structure

```text
NotesApp/
├── public/              # Public static assets
├── src/
│   ├── assets/          # Images and visual assets
│   ├── App.jsx          # Main application and notes logic
│   ├── App.css          # Application-specific styles
│   ├── index.css        # Global styles and Tailwind import
│   └── main.jsx         # React application entry point
├── index.html           # HTML entry point
├── package.json         # Dependencies and npm scripts
├── package-lock.json    # Dependency lockfile
├── vite.config.js       # Vite configuration
├── eslint.config.js     # ESLint configuration
└── README.md
```

## Data Storage and Privacy

Cat-Note uses browser `localStorage` to persist notes. It does not require a backend server or database for its current note-taking functionality.

- Notes are stored locally in the browser that you use.
- Notes are not automatically synchronized between different browsers or devices.
- Clearing the website's local storage or browser site data may permanently delete saved notes.
- Using a different browser or device will not automatically transfer your notes.

**Tip:** Export or back up important notes separately if you need to preserve them.

## Future Improvements

Potential enhancements for future versions include:

- Dark and light themes
- Note categories and tags
- Creation and modification timestamps
- Pinning and sorting notes
- Export and import functionality
- Cloud synchronization and user authentication

## Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request describing your improvements.

## Author

**Adita Singh**

- GitHub: [@adita097](https://github.com/adita097)

---

Built as a hands-on project to practice React, component-based UI development, state management, browser storage, and modern frontend tooling.
