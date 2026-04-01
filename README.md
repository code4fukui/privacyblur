# PrivacyBlur

[日本語版はこちら](./README.ja.md)

PrivacyBlur is a small browser-based tool for blurring sensitive parts of an image locally.

## Features

- Load an image from a file or paste it from the clipboard.
- Click anywhere on the image to add a blur mask centered at that point.
- Adjust blur area size, blur strength, and edge feathering.
- Undo the last blur, clear all blur masks, and export as PNG or JPEG.
- Process everything in the browser without uploading the image anywhere.

## Usage

1. Open [`index.html`](./index.html) in a browser.
2. Load an image with the file picker, or paste one with `Ctrl+V` / `Cmd+V`.
3. Adjust the blur settings on the left panel.
4. Click the image where you want to hide private information.
5. Save the result as PNG or JPEG.

## Privacy

This tool is designed for local-only processing. Images stay in the browser and are not sent to any external server.

## License

[MIT](./LICENSE)

