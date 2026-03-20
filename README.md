# PDF Editor

A lightweight, single-file PDF editor that runs entirely in your browser. No installs, no uploads, no accounts — your files never leave your device.

## How to use

1. Open `pdf-editor.html` in any modern browser (Chrome, Safari, Edge, Firefox)
2. Drop your PDF onto the page or click **Browse file**
3. Add text or images, position them, download

That's it.

## Features

- **Add Text** — click the button, then click anywhere on the PDF to place it. Double-click to edit. Drag to move, corner handles to resize. Change font size and color from the toolbar.
- **Add Image** — click the button, pick an image file, then click anywhere on the PDF to place it. Drag to move, corner handles to resize.
- **Multi-page** — edits are saved per page as you navigate
- **High quality export** — overlays are rendered at ~288 DPI before embedding
- **Open another PDF** — load a fresh PDF without refreshing the page

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| `Escape` | Cancel place mode |
| `Delete` / `Backspace` | Remove selected object |
| Double-click text | Edit text content |

## Privacy

Everything runs locally in your browser. No data is sent anywhere.

## Requirements

Internet connection on first open (loads PDF.js, Fabric.js, pdf-lib from CDN). After that, works offline too if your browser has cached the scripts.
