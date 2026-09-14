# mhosFIT

Form-ready image tools that run entirely in the browser. Crop, resize, position, rotate, compress, and download photos or signatures without uploading them to a server.

## Features

- Photo tool: exports a 300 x 300 JPG under 100 KB.
- Signature tool: exports a 300 x 80 JPG under 60 KB.
- Custom tool: choose your own width, height, and maximum file size.
- Drag-and-drop or file picker image input.
- Position, zoom, and rotation controls.
- Automatic JPG compression.
- Bengali / English language toggle.
- Animated tutorial video button.
- All image processing happens locally on the user's device.

## Getting started

This is a dependency-free static site. Open [index.html](./index.html) directly in a browser, or serve the folder with any static web server.

Example with a local static server:

```bash
npx serve .
```

Then open the local URL shown in the terminal.

## Tutorial

Use the floating **Watch video** button in the bottom-right corner to open the tutorial:

https://youtu.be/cUXcqkXN83Q

## Project structure

```text
.
├── index.html
├── assets/
└── README.md
```

## Privacy

Images are processed with the browser File, Canvas, and Blob APIs. They are not uploaded to a backend or stored remotely.
