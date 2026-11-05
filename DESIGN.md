---
name: Academic Work OS
colors:
  surface: '#fbf8ff'
  surface-dim: '#d5d8f6'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f2ff'
  surface-container: '#ececff'
  surface-container-high: '#e5e6ff'
  surface-container-highest: '#dee1fe'
  on-surface: '#161a30'
  on-surface-variant: '#464555'
  inverse-surface: '#2b2f46'
  inverse-on-surface: '#f0efff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4f44e2'
  primary: '#4d41df'
  on-primary: '#ffffff'
  primary-container: '#675df9'
  on-primary-container: '#fffbff'
  inverse-primary: '#c4c0ff'
  secondary: '#594cc3'
  on-secondary: '#ffffff'
  secondary-container: '#9186ff'
  on-secondary-container: '#270c92'
  tertiary: '#006b2d'
  on-tertiary: '#ffffff'
  tertiary-container: '#00873b'
  on-tertiary-container: '#f7fff3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c4c0ff'
  on-primary-fixed: '#100069'
  on-primary-fixed-variant: '#3622ca'
  secondary-fixed: '#e4dfff'
  secondary-fixed-dim: '#c6c0ff'
  on-secondary-fixed: '#150066'
  on-secondary-fixed-variant: '#4031aa'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#fbf8ff'
  on-background: '#161a30'
  surface-variant: '#dee1fe'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 3rem
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  title-sm:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.01em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system targets high-achieving university and postgraduate students who need to organize complex coursework, research deadlines, and everyday academic obligations. The product merges the structural flexibility of Notion, the precision and keyboard-driven efficiency of Linear, and the effortless capture and task triage of Todoist.

### Visual Aesthetic & Philosophy
- **Modern Minimalist Utility**: Clutter-free workspaces where academic content leads. Chrome and structural chrome remain subdued until engaged.
- **Calm, High-Focus Ambiance**: Ultra-soft background hues diminish eye strain during extended study sessions.
- **Architectural Rhythm**: Crisp borders, deliberate typographic hierarchy, and generous container framing provide a sense of control and clarity.
- **Delight through Precision**: Micro-interactions, soft status glows, and fluid layout state transitions celebrate task completions and milestone achievements.

## Colors

The palette establishes an energetic yet focused academic atmosphere. Vibrant indigos provide momentum for actions, deep slate ensures legibility, and refined status hues clearly distinguish priorities.

### Application Roles
- **Primary (`#6C63FF`)**: Brand anchor, primary call-to-actions, active navigation markers, keyboard shortcuts indicator, and primary progress indicators.
- **Secondary (`#8B80F9`)**: Sub-brand accents, active hover states on interactive controls, highlighted tags, and focus ring outlines.
- **Tertiary / Success (`#22C55E`)**: Task completion ticks, submission confirmations, positive grade progress markers, and healthy study metrics.
- **Warning (`#F59E0B`)**: Looming syllabus deadlines (< 24 hours), unconfirmed exam slots, and schedule conflicts.
- **Danger (`#EF4444`)**: Overdue assignments, critical grade alerts, and destructive actions.
- **Neutral Main (`#20243A`)**: High-contrast typography, primary iconography, and structural active states.
- **Neutral Muted (`#777B90`)**: Secondary metadata, timestamps, subtle breadcrumbs, and placeholder copy.
- **Surface Canvas (`#F7F8FC`)**: Ambient canvas backdrop, nested table background wrappers, and empty track bars.
- **Surface Card (`#FFFFFF`)**: Floating workspace boards, modal containers, and dashboard widget modules.
- **Border Default (`#E5E7EB`)**: Structural dividers, card edges, and table grid borders.

## Typography

The typography relies on Inter to deliver clinical legibility, tight horizontal flow, and clear numeric differentiation for dates, scores, and task counts.

### Usage Standards
- **Optical Density**: Headings use slight negative letter-spacing (`-0.01em` to `-0.03em`) to mimic high-end editorial and modern SaaS engineering standards (Linear/Notion).
- **Tabular Numerals**: Apply `font-feature-settings: 'tnum' 1` to table cells, countdown timers, and grade averages to eliminate jitter when data updates.
- **Monospace Insets**: JetBrains Mono serves metadata pills, course catalog codes (e.g., `CS-401`), and keyboard navigation tokens (e.g., `Cmd + K`).

## Layout & Spacing

The layout model implements a structured, desktop-first productivity canvas with dynamic responsive reflow.

### Structural Architecture
- **Sidebar-Canvas Model**: Desktop experiences feature a collapsible 260px navigation pane, leaving the primary workspace dynamic and fluid.
- **Main View Area**: Restrained with a max content width of `1440px` on wide screens to maintain scanning comfort, centering within the viewport.
- **Grid Layout**: 
  - **Desktop (1024px+)**: 12-column grid with `1.5rem` (24px) gutters and `2rem` (32px) margins.
  - **Tablet (768px - 1023px)**: 8-column layout with `1rem` (16px) gutters; board views convert to horizontal swiping panes.
  - **Mobile (< 768px)**: 4-column layout with `1rem` margins; sidebars collapse into a bottom navigation bar or sheet drawer.
- **Vertical Spacing Rhythm**: All layout offsets and component gaps conform strictly to an 8px base rhythm (`4px`, `8px`, `16px`, `24px`, `32px`, `48px`).

## Elevation & Depth

Visual hierarchy uses layered surfaces coupled with soft, tinted drop shadows to create clean, paper-like depth without visual weight.

### Surface Tiers
- **Tier 0 (Canvas Base)**: `#F7F8FC`. The non-interactive background surface.
- **Tier 1 (Surface Cards & Widgets)**: `#FFFFFF`. The primary interactive surface for content blocks, tasks, and list containers.
- **Tier 2 (Popovers, Flyouts, Menus)**: `#FFFFFF`. Used for contextual dropdowns, date pickers, and filter panels.
- **Tier 3 (Modals & Overlays)**: `#FFFFFF`. Heavy modal interfaces with backdrop blur (`backdrop-filter: blur(8px); background: rgba(32, 36, 58, 0.2)`).

### Shadows & Borders
- **Subtle Card Border**: Every elevated card combines a soft shadow with an ultra-thin border: `border: 1px solid rgba(32, 36, 58, 0.06)`.
- **Card Shadow (Level 1)**: `0 1px 3px 0 rgba(32, 36, 58, 0.04), 0 4px 12px 0 rgba(32, 36, 58, 0.03)`.
- **Raised/Hover Shadow (Level 2)**: `0 4px 6px -1px rgba(108, 99, 255, 0.06), 0 10px 20px -2px rgba(32, 36, 58, 0.05)`.
- **Floating Shadow (Level 3)**: `0 12px 32px -4px rgba(32, 36, 58, 0.12), 0 4px 8px -2px rgba(32, 36, 58, 0.04)`.

## Shapes

The interface balances precision and warmth through generous, modern curvature.

### Geometry Hierarchy
- **Standard Radius (`0.5rem` / 8px)**: Inputs, buttons, list item highlights, badges, and inline status tags.
- **Card & Widget Radius (`rounded-lg` - `1rem` / 16px)**: Canvas content cards, syllabus items, Kanban columns, and floating calendar panels.
- **Modal & Container Radius (`rounded-xl` - `1.5rem` / 24px)**: Global modals, slide-out document sidecars, command palettes, and primary dashboard metric cards.
- **Full Radius (Pill / 9999px)**: Avatars, circular icon buttons, task completion checkboxes, and quick-filter pills.

## Components

### Buttons
- **Primary**: Solid `#6C63FF` fill, `#FFFFFF` text, `0.5rem` border-radius. On hover, background deepens to `#5B52E0` with a smooth 150ms ease. Focus uses a 2px offset ring with `#8B80F9`.
- **Secondary**: `#FFFFFF` background, `1px solid rgba(32, 36, 58, 0.1)` border, `#20243A` text. Hover adds a `#F7F8FC` surface fill.
- **Ghost/Tertiary**: Transparent background, `#777B90` text. Hover yields `#20243A` text and `#F0F2F9` background.
- **Command / Shortcut Indicator**: Right-aligned pill within buttons containing keyboard keys (e.g., `Ctrl + Enter`), styled with JetBrains Mono, `#777B90` text, and soft grey background.

### Cards & Dashboard Widgets
- **Structure**: `#FFFFFF` fill, `1px solid rgba(32, 36, 58, 0.06)` border, `1rem` or `1.5rem` radius, and Level 1 elevation.
- **Header Slot**: Clear title pairing (`title-sm`), trailing action menu (three dots icon), and optional category badge.
- **Widget Behavior**: Subtle card scale (`transform: translateY(-2px)`) on cursor hover with transition to Level 2 elevation.

### Task List & Table Rows
- **List Items**: Clean horizontal rows with `0.5rem` border-radius when hovered. 
- **States**:
  - *Default*: Transparent container, visible bottom separator (`1px solid #F0F2F9`).
  - *Hover*: Transitions to `#F7F8FC` background, revealing right-aligned contextual quick actions (Move, Reschedule, Delete).
  - *Active / Selected*: Subtle tinted background `rgba(108, 99, 255, 0.05)` with `#6C63FF` accent border on the left edge (3px solid).
- **Strike-through Transitions**: Completed tasks display strikethrough styling with `#777B90` muted text, while the tertiary emerald check triggers a subtle celebration micro-bounce.

### Checkboxes & Radios
- **Checkboxes**: 18px × 18px, `0.375rem` radius, `#E5E7EB` border. Checked state transitions to `#22C55E` fill with a crisp white tick mark.
- **Priority Radios**: Custom ring selectors indicating task urgency (P1 Red `#EF4444`, P2 Amber `#F59E0B`, P3 Indigo `#6C63FF`, P4 Slate `#777B90`).

### Chips, Badges & Tags
- **Status Badges**: Pill-shaped with `0.75rem` text and `0.25rem` vertical, `0.625rem` horizontal padding.
  - *In Progress*: `rgba(108, 99, 255, 0.1)` background with `#6C63FF` text.
  - *Completed*: `rgba(34, 197, 94, 0.1)` background with `#22C55E` text.
  - *Due Soon*: `rgba(245, 158, 11, 0.1)` background with `#F59E0B` text.
  - *Overdue*: `rgba(239, 68, 68, 0.1)` background with `#EF4444` text.
- **Course Tag**: Subtle grey capsule with a distinct 6px colored dot denoting the individual course or subject.

### Input Fields & Search Bars
- **Form Controls**: Height 40px, `0.5rem` radius, `1px solid #E5E7EB`, `#20243A` text, `#777B90` placeholder.
- **Focus State**: `1px solid #6C63FF` border accompanied by an ambient focus ring: `0 0 0 3px rgba(108, 99, 255, 0.15)`.
- **Command Palette (`Cmd + K`)**: Modal card floating in the upper third of the screen, housing a clean search bar with real-time fuzzy filtering of assignments, flashcards, notes, and schedules.