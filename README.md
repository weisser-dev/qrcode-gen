# QR Code Generator

A tiny, dependency-light QR code generator that runs entirely in your browser — nothing you type is sent to a server.

**Live:** https://qrcode-gen.weisser.dev

## Features

- Any text or URL as content
- Sizes 100×100 to 400×400 px
- Custom foreground and background colors, optional transparent background
- Highest error correction level (H), so codes stay readable with logos or damage
- Download as **PNG** or **SVG**

## Usage

Open the live page, enter your text or URL, pick size and colors, press the generate button, then download PNG or SVG.

## Run locally

It is a single static page. Open `index.html` in a browser, or serve the folder with any static file server, e.g.:

```
python3 -m http.server 8080
```

The page loads [QRious](https://github.com/neocotton/qrious) from cdnjs.

## Tech

Plain HTML, CSS and JavaScript, Bootstrap for layout, QRious for rendering.
