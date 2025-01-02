# File Organizer by Creation Date

This repository contains a Python script to automatically organize files (e.g., photos, videos) into year/month subfolders based on their creation date extracted from metadata.

## Features
- **Metadata Extraction**: Uses file metadata (e.g., EXIF tags, QuickTime metadata) to determine creation dates.
- **Folder Organization**: Moves files into `year/month` subfolders within a specified output directory.
- **Error Handling**: Handles missing metadata gracefully and logs errors when a file cannot be processed or moved.

## Dependencies
The script requires the following Python libraries:
- `os` (built-in)
- `shutil` (built-in)
- `pathlib` (built-in)
- `datetime` (built-in)
- `Pillow` (`PIL`)
- `mimetypes` (built-in)
- `subprocess` (built-in)

Install external dependencies with:
```bash
pip install Pillow

