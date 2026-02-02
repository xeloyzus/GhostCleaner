# GhostCleaner

A powerful macOS disk cleanup utility with advanced scanning capabilities and safe file management.

## Features

### Core Functionality
- **12 Scan Categories**: User caches, logs, downloads, iOS backups, Xcode artifacts, SwiftPM caches, Homebrew caches, browser caches, mail attachments, and more
- **Deep Scan Mode**: Toggle to scan hidden files and package contents
- **Large Files Scanner**: Find and manage large files with custom size threshold
- **Smart Risk Assessment**: Three-tier risk system (Safe, Review, Danger) to prevent accidental deletion
- **Quarantine System**: Safe deletion with restore capability for 30 days

### Safety Features
- **User-Selected Access**: Only accesses folders explicitly granted by user
- **Security-Scoped Bookmarks**: Persistent access across app launches
- **Protected Paths**: Built-in protection for critical system directories
- **Undo Support**: Restore deleted items from quarantine within retention period

### Advanced Features
- **Scheduled Scans**: Automatic daily/weekly/monthly scanning
- **Scan History**: Track all scans and cleanup operations
- **Export Reports**: Generate PDF or HTML reports
- **Dark Theme**: Beautiful pitch-black UI optimized for dark mode
- **Insights**: Smart recommendations based on scan results

## System Requirements

- macOS 14.0 (Sonoma) or later
- Apple Silicon (M1/M2/M3/M4) or Intel processor
- Compatible with all Macs running macOS 14+

## Installation

1. Download GhostCleaner.app
2. Move to Applications folder
3. Launch and grant folder access when prompted

## Usage

### First Time Setup
1. Complete the onboarding wizard
2. Grant folder access permissions for directories you want to scan
3. Configure your preferences in Settings

### Running a Scan
1. Click "Start Scan" or press ⌘⇧S
2. Wait for scan to complete
3. Review found items by category and risk level
4. Select items to delete (or use "Select Safe Items")
5. Click "Delete Selected Items"

### Large Files
1. Navigate to Large Files panel
2. Click "Choose Folder" to select directory
3. Adjust minimum file size threshold
4. Select files to delete or reveal in Finder

### Deep Scan
- Enable in Settings → Scanning → Deep Scan
- Includes hidden files and package contents
- May take longer but finds more items

### Restoring Deleted Items
1. Go to Management tab
2. Select item from deletion history
3. Click "Restore" to recover the file

## Permissions

GhostCleaner requests access only to folders you explicitly grant:
- User caches, logs, and temporary files
- Downloads folder
- Developer tools (Xcode, Homebrew, SwiftPM)
- Browser caches and mail attachments

All access is managed through security-scoped bookmarks with your consent.

## Support

For issues or feature requests, please contact the developer or submit feedback through the app.

## Version

**1.0** - Initial Release
- 12 scan categories
- Deep scan capability
- Large files management
- Scheduled scanning
- Full sandbox support

## License

Copyright © 2026 GhostCleaner. All rights reserved.
