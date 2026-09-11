# Private Image Resizer

Resize and compress images directly in your browser, without uploading them.

## Run it

1. Download the repository using **Code → Download ZIP** and extract it.
2. Open `tools/private-image-resizer/index.html` in a modern browser.
3. Choose an image or drag and drop one onto the preview area.
4. Select a size preset or enter dimensions, choose an output format and quality, then select **Resize and download**.

Alternatively, download [index.html](index.html) with GitHub's **Download raw file** button and open it locally. No installation or internet connection is needed once downloaded.

## Features

- Presets for a longest side of 480, 720, 1080, 1600, or 2048 pixels, plus original dimensions.
- Custom dimensions with an optional aspect-ratio lock.
- JPG, WebP, and PNG output, subject to browser support.
- Adjustable compression quality for JPG and WebP; PNG preserves transparency.
- Image preview and downloaded dimensions and file size.
- Light and dark themes: each open follows your browser's preference. The **Dark theme** toggle overrides it for the current session.

JPG output fills transparent areas with white. Large images may exceed your device's available memory.

## Privacy

Image processing uses the browser Canvas API locally. The tool makes no uploads or network requests and uses no analytics, cookies, or persistent application storage. Theme overrides reset when you reopen or refresh the page.

## License

Covered by the repository's [MIT license](../../LICENSE).
