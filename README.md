# files.xmenu.dev

A simple website that automatically downloads files and redirects to xmenu.dev.

## How It Works

When you visit this website, it will:
1. Automatically prompt to download all files from the `files/` folder
2. Immediately redirect you to https://xmenu.dev

## Adding Files

To add files for download:
1. Place your files in the `files/` directory
2. Update the `filesToDownload` array in `index.html` to include the new file paths

## Files Structure

```
.
├── index.html          # Main HTML page with download and redirect logic
├── files/              # Directory containing files to be downloaded
│   ├── example.txt     # Example file
│   ├── sample.txt      # Sample file
│   └── README.md       # Instructions for adding files
└── README.md           # This file
```

## Usage

Simply open `index.html` in a web browser or host it on a web server. The files will be downloaded and the redirect will happen automatically.
