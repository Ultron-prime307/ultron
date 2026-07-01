# 🚀 Ultron — Command Center

> A brutalist-style task management dashboard with cutting-edge 3D visuals and operational clarity.

---

## ✨ Features

- **Brutalist Design System** — Bold typography, geometric precision, and industrial aesthetics
- **3D Interactive Elements** — Depth effects and smooth animations for immersive experience
- **Command Center Dashboard** — Real-time task tracking with multiple views
- **Multi-View Support** — Board and table views for flexible task management
- **Responsive Layout** — Optimized for desktop and mobile devices
- **Zero Dependencies** — Pure HTML, CSS, and vanilla JavaScript

---

## 📊 Dashboard Overview

### Core Sections
- **Workspace Pulse** — Live metrics of active projects and pending tasks
- **Delivery Board** — Kanban-style workflow with 5 columns (Backlog → Done)
- **Task Analytics** — Open tasks, overdue, completed, and blocked items
- **Detail Panel** — Contextual task information with metadata

### Color Palette
| Element | Color | Usage |
|---------|-------|-------|
| Alert | `#ff4d2e` | Urgent tasks |
| Success | `#2eff7b` | Completed items |
| Info | `#3d5afe` | Active tasks |
| Warning | `#ffd600` | Due soon alerts |

---

## 🎮 Quick Start

### Option 1: Direct Browser
Simply open `index.html` in your browser.

### Option 2: Local Server
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000

# Node.js
npx http-server
```

Then navigate to: **http://127.0.0.1:8000**

---

## 🛠️ Customization

### Modify Theme Colors
Edit the CSS variables in the `<style>` section:

```css
:root {
  --bg: #f5f3ee;           /* Background */
  --ink: #0d0d0d;          /* Text/Borders */
  --surface: #ffffff;      /* Card backgrounds */
  --accent-alert: #ff4d2e; /* Error/Urgent */
  --accent-go: #2eff7b;    /* Success */
  --accent-info: #3d5afe;  /* Info */
  --accent-warn: #ffd600;  /* Warnings */
}
```

### Add New Tasks
Update the `taskMap` object in the script section with new task objects following this structure:

```javascript
{
  title: 'Task Name',
  priority: 'Priority: Level',
  description: 'Task description text'
}
```

---

## 🎨 Design Philosophy

Ultron embraces **brutalism** in web design:
- ✓ Heavy borders and shadows for tactile depth
- ✓ Bold, uppercase typography
- ✓ Geometric grids and structured layouts
- ✓ High contrast and legibility
- ✓ No unnecessary ornamentation

---

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

---

## 📄 License

Created as a design concept for modern task management interfaces.

---

## 🚀 Try It Now

**[Open Dashboard](index.html)** — Start managing tasks with industrial precision.

---

*Built with precision. Designed for clarity. Engineered for results.*

=======
# Ultron
>>>>>>> a1de93bf222503a28f509b1f95165d84c2a99469
