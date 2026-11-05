# AcademiaFlow - Academic Work OS (React Frontend)

AcademiaFlow is a modern, high-focus student productivity workspace built with React, Vite, Tailwind CSS, and React Router. It converts the UI design generated using Google Stitch into a modular, production-ready frontend web application.

---

## 🚀 Features

- **Pixel-Accurate Fidelity**: Exact implementation of the Google Stitch Academic Work OS specifications, preserving layout geometry, Inter & JetBrains Mono typography, Material Symbols iconography, and the custom color palette (`#4d41df` primary, `#594cc3` secondary, `#006b2d` tertiary, etc.).
- **Client-Side Routing**: Multi-page navigation using `react-router-dom`:
  - `/`: **Dashboard** — Metric stats cards, today's priority task checklist, interactive weekly throughput chart, upcoming deadlines timeline, subject distribution bar, and study streak widget.
  - `/tasks`: **My Tasks** — Interactive list & Kanban board view (Pending, In Progress, Completed), multi-factor filtering by Subject, Priority, and Status.
  - `/calendar`: **Academic Calendar** — Monthly calendar overview with deadline markers and daily agenda schedule.
  - `/analytics`: **Progress & Analytics** — Velocity analytics, focus time counters, estimated standings, and optimal study window observations.
  - `/settings`: **Profile & Settings** — Student profile editor (Aarav Sharma), course subject management, notification toggles, and shortcut preferences.
- **Interactive State Management**: Global `TaskContext` with live addition of tasks, status transitions (`Pending` ↔ `In Progress` ↔ `Completed`), checkbox strikethrough animations, search bar (`⌘K`), and course filtering.
- **Keyboard Shortcuts**:
  - `N`: Quick-open Create Task modal from anywhere in the app.
  - `Escape`: Close modals and popups.
  - `Ctrl + Enter`: Submit and save task inside modal.
- **Focus Timer**: Built-in 25-minute Pomodoro study timer with play, pause, and reset controls.
- **Responsive Layout**: Desktop 260px collapsible sidebar, tablet fluid container, and mobile bottom navigation dock with floating quick-add button.

---

## 📁 Project Structure

```
stitch_student_task_manager/
├── code.html                  # Original Stitch HTML reference
├── DESIGN.md                  # Stitch design specifications & tokens
├── screen.png                 # Stitch visual screenshot
└── frontend/                  # React Application
    ├── index.html             # HTML entry point with Google Fonts
    ├── package.json           # Dependencies and scripts
    ├── tailwind.config.js     # Stitch design token colors, typography & spacing
    ├── postcss.config.js      # PostCSS configuration
    ├── vite.config.js         # Vite configuration (port 3000)
    └── src/
        ├── App.jsx            # Main app shell & router
        ├── main.jsx           # React DOM mount
        ├── index.css          # Tailwind base & custom scrollbars
        ├── context/
        │   └── TaskContext.jsx# Centralized task, course, and profile store
        ├── data/
        │   └── initialData.js # Preloaded mock dataset matching Stitch specs
        ├── components/
        │   ├── layout/
        │   │   ├── Sidebar.jsx   # Desktop sidebar navigation & course filter
        │   │   ├── TopHeader.jsx # Sticky search, date, notifications & actions
        │   │   └── BottomNav.jsx # Mobile navigation dock
        │   ├── tasks/
        │   │   ├── TaskItem.jsx  # Task row with checkbox, tags, priority & status
        │   │   ├── TaskList.jsx  # Today's priority interactive checklist
        │   │   └── TaskModal.jsx # Create task modal dialog
        │   └── dashboard/
        │       ├── HeroBanner.jsx      # Greeting & streak widget
        │       ├── MetricCards.jsx     # 4 statistical KPI cards
        │       ├── WeeklyChart.jsx     # Weekly productivity activity bar chart
        │       ├── DeadlinesList.jsx   # Upcoming deadlines timeline
        │       ├── SubjectBreakdown.jsx# Subject task breakdown progress bar
        │       └── StudyTipWidget.jsx  # Streak tip & Pomodoro focus timer
        └── pages/
            ├── DashboardPage.jsx # Main overview page
            ├── TasksPage.jsx     # Comprehensive task list & Kanban board
            ├── CalendarPage.jsx  # Monthly academic calendar & day agenda
            ├── AnalyticsPage.jsx # Progress and velocity analytics
            └── SettingsPage.jsx  # Student profile & workspace settings
```

---

## 🛠️ Installation & Run Commands

### Prerequisites
- Node.js (v18.0.0 or higher recommended; v26+ supported)
- npm (v9.0.0 or higher)

### 1. Navigate to the frontend directory:
```bash
cd frontend
```

### 2. Install dependencies:
```bash
npm install
```

### 3. Start the development server:
```bash
npm run dev
```
The application will launch at `http://localhost:3000/`.

### 4. Build for production:
```bash
npm run build
```

### 5. Preview the production build:
```bash
npm run preview
```
