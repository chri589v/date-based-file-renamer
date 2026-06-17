# File Date Renamer

A simple Python tool to rename files based on their last modification date.

## Features
- Rename files to the format: `YYYY-MM-DD.ext`
- Automatically avoids overwriting files by adding a counter
- Supports any file extension (e.g. `.png`, `.jpg`, `.pdf`)
- Includes a preview mode to see changes before applying them

## Scripts

### 1. Rename files
`date-based-filename-renamer.py`  
Renames files based on their modification date.

### 2. Preview renaming
`preview-file-renaming.py`  
Shows how files would be renamed without making any changes.

## How to use

Run **one of the following**:

### Rename files (applies changes)
```bash
python date-based-filename-renamer.py
```

### Preview only (no changes made)
```bash
python preview-file-renaming.py
```
