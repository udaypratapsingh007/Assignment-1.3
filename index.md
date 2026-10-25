# Assignment 1.3 - Terminal & Developer Workflow

## Task

Create and manage a project folder structure using the terminal.

## Terminal Commands

```bash
mkdir web-development-practice
cd web-development-practice
mkdir week-1 week-2 week-3
type nul > week-1\index.html
type nul > week-2\index.html
type nul > week-3\index.html
dir
cd week-1
cd ..
ren week-1 week-1-renamed
ren week-1-renamed week-1
rmdir /s /q week-3
mkdir week-3
type nul > week-3\index.html
tree /F
code .
```

## Explanation

- `mkdir` creates a new folder.
- `cd` moves into a folder, and `cd ..` goes back one level.
- `type nul > file` creates an empty file.
- `dir` lists the files and folders in the current location.
- `ren` renames a file or folder.
- `rmdir /s /q` deletes a folder along with everything inside it.
- `tree /F` shows the folder structure with files.
- `code .` opens the current folder in VS Code.

## Final Folder Structure

```
web-development-practice
├── week-1
│   └── index.html
├── week-2
│   └── index.html
└── week-3
    └── index.html
```