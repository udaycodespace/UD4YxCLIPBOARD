# clipnest

### Your pocket board for everything worth keeping.

**Paste it. Tag it. Find it.**

Save notes, links, ideas, and snippets in one lightweight board.

No account. No sign-up. No backend.

<p align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge\&logo=github\&logoColor=white)](https://pages.github.com/)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-2fb26b?style=for-the-badge)](#tech)
[![Single File](https://img.shields.io/badge/Single--File-index.html-ff4f8b?style=for-the-badge)](#tech)
[![Local First](https://img.shields.io/badge/Data-Local--First-0b4f4a?style=for-the-badge)](#privacy)

</p>

<p align="center">

**Live Demo:** `https://YOUR-USERNAME.github.io/UD4YxCLIPBOARD/`

</p>

## Why?

Links get buried. Notes get scattered. Useful snippets disappear.

**UD4YxCLIPBOARD puts them all in one place.**

```text
CAPTURE  →  ORGANISE  →  SEARCH  →  FIND
```

## Features

|                   |                                                 |
| ----------------- | ----------------------------------------------- |
| **Quick Capture** | Notes, links, clipboard paste, multi-link paste |
| **Smart Links**   | Favicon, domain detection, duplicate handling   |
| **Organisation**  | Tags, search, filters, pins, card colours       |
| **Editing**       | Edit, copy, delete and undo                     |
| **Responsive**    | Desktop, mobile, light and dark themes          |
| **Local-First**   | localStorage + IndexedDB                        |
| **Backup**        | Export and restore as JSON                      |
| **Keyboard**      | Shortcuts for capture and search                |

## How It Works

```mermaid
flowchart LR
    A["Capture"] --> B["UD4YxCLIPBOARD"]
    B --> C["Local Storage"]
    B --> D["IndexedDB"]
    C --> E["Search & Organise"]
    D --> E
    E --> F["Backup / Restore"]
```

Everything is handled inside your browser.

## Privacy

* No account
* No backend
* No analytics
* No ads
* No server-side database
* Saved notes stay on your device

External services are used only for **Google Fonts** and **website favicons**.

> Clear your browser data or switch devices and your board won't come with you. **Use Backup for anything important.**

## Shortcuts

```text
Enter        Save
Shift + Enter New line
Ctrl + V     Save clipboard
n            New note
/ or Ctrl + K Search
Esc          Clear / Cancel
?            Shortcuts
```

Use `Cmd` instead of `Ctrl` on macOS.

## Tech

<p align="center">

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Dependencies](https://img.shields.io/badge/Dependencies-0-2fb26b?style=flat-square)](#tech)
[![Build](https://img.shields.io/badge/Build-None-555555?style=flat-square)](#tech)

</p>

* Plain HTML, CSS and JavaScript
* Single `index.html`
* Zero dependencies
* Zero build tools
* Responsive masonry layout
* GitHub Pages ready
* User text escaped before rendering

## Run Locally

```bash
git clone https://github.com/YOUR-USERNAME/UD4YxCLIPBOARD.git
```

Open `index.html` in your browser.

That's it.

## Deploy

1. Create a repository named `UD4YxCLIPBOARD`
2. Upload `index.html`
3. Open **Settings → Pages**
4. Select **Deploy from a branch → main → `/ (root)`**
5. Open your GitHub Pages URL

## Roadmap

* Folders / multiple boards
* Search match highlighting
* Markdown export
* Optional passcode lock

## Credits

**Built by UDAY**

> Small app. Zero backend. Surprisingly useful.

<p align="center">

**© 2026 UDAY**

</p>
