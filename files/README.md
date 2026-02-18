# Files Directory

This directory contains files that will be automatically downloaded when users visit the website.

## How to Add Files

1. Place any files you want to be downloaded in this directory
2. Update the `filesToDownload` array in `index.html` to include the new file paths

Example:
```javascript
const filesToDownload = [
    'files/example.txt',
    'files/sample.txt',
    'files/your-new-file.pdf'  // Add new files here
];
```

## Current Files

- example.txt - Example file demonstrating the functionality
- sample.txt - Another sample file for testing
