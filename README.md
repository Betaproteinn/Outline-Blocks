![Version](https://img.shields.io/badge/version-1.1-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-experimental-lightgrey)


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

## How It Works

### Block-Based Outline Editor
Create, reorder, and structure ideas using hierarchical blocks.  
Blocks can be freely dragged, indented, and reorganized as the outline evolves.

<img src="screenshots/Main Editor.jpg" width="800" />

---

### Smart Batch Import (Forced Alignment)
Paste numbered or unordered text.  
The system maps lines to exact positions, sorts unordered entries, and can auto-fill gaps.

<img src="screenshots/batch-import.jpg" width="800" />

---

### Merge Review & Conflict Resolution
All changes are reviewed explicitly before being applied.  
Each conflict can be kept, overwritten, or appended.

<img src="screenshots/merge-review.jpg" width="500" />


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
