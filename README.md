# PrivacyBlur

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, browser-based tool to quickly blur sensitive parts of an image. All processing is done locally in your browser, so your images are never uploaded to a server.

## Features

- **Load from Anywhere:** Open an image from a local file or paste directly from the clipboard (`Ctrl+V` / `Cmd+V`).
- **Interactive Blurring:** Simply click on the image to add a blur mask at that location.
- **Fine-Tuned Controls:** Adjust the blur area size, blur strength, and edge feathering for a smooth blend.
- **Client-Side by Design:** Your images are never sent to an external server, guaranteeing your privacy.
- **Multiple Formats:** Export the final image as a PNG or JPEG.
- **Easy Edits:** Undo the last blur or clear all blurs with a single click.

## Usage

1.  Open [`index.html`](./index.html) in your web browser.
2.  Load an image using the file picker or by pasting it from your clipboard.
3.  Use the left-hand panel to configure the blur settings:
    - **Size:** Adjusts the blur area as a percentage of the image's width (2% to 50%).
    - **Blur Strength:** Sets the blur radius in pixels (2px to 40px).
    - **Edge Feathering:** Softens the edges of the blur mask for a more natural look (0px to 80px).
4.  Click on the image to apply a blur mask. You can add as many as you need.
5.  Click "Save as PNG" or "Save as JPEG" to download the result.

## Privacy

This tool is designed with privacy as its core principle. All image processing happens entirely within your browser. Your files are not uploaded, stored, or transmitted to any external server.

## Requirements

A modern web browser that supports the Canvas API (e.g., Chrome, Firefox, Safari, Edge).

## License

[MIT](./LICENSE)
