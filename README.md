# Outline Blocks

Outline Blocks is a block-based outlining tool designed for structured thinking and long-form writing.

It treats an outline as a set of movable, hierarchical blocks rather than a linear document, allowing ideas to be freely reorganized, merged, and refined.

The project runs entirely in the browser as a single HTML file.

No installation. No backend. No build step.

---

## Why Outline Blocks

Traditional editors are linear.  
Mind maps are often too scattered.

Outline Blocks sits in between.

It is designed for situations where structure matters, but flexibility is essential:
- Novel planning
- Article outlining
- Course or project structure design
- Any form of hierarchical thinking

---

## Core Design Principles

### 1. Everything is a Block
Each idea is an independent block that can be reordered, nested, or removed without breaking the overall structure.

### 2. Structure First, Text Second
Outline Blocks focuses on *where* ideas belong before *how* they are written.

### 3. Explicit Conflict Handling
When importing or merging content, conflicts are never hidden.
Every overwrite, insertion, or filler block is visible and controllable.

---

## Screenshots

### Smart Batch Import (Forced Alignment)
Paste numbered or unordered text.  
The system maps lines to exact positions, automatically sorting and filling gaps.

![Smart Batch Import](./screenshots/batch-import.png)

---

### Merge Review & Conflict Resolution
Before applying changes, all conflicts are presented explicitly.
Each block can be kept, overwritten, or appended.

![Confirm Merge](.merge-review.jpg)

---

### Block-Based Outline Editor
Drag, indent, and reorganize blocks freely.
Outlines remain readable and editable even as they grow.

![Main Editor](./screenshots/editor.png)

---

## Features

- Block-based outline editing
- Hierarchical indentation and reordering
- Native drag-and-drop
- Smart batch import with forced alignment
- Explicit merge review and conflict control
- Local autosave via browser storage
- Export to text / markdown formats
- Multilingual interface (Chinese / English)

All data stays local in the browser.

---

## Usage

Open the HTML file directly in a modern browser.

Chromium-based browsers such as Chrome or Edge are recommended.

---

## Notes

- All logic runs entirely on the front end
- Data is stored locally using `localStorage`
- No network requests are made after initial load
- Original files are never modified

---

## License

MIT
