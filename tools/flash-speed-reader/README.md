# Flash Speed Reader

A small, offline reader that displays your text one word at a time, with a highlighted focus letter.

## Run it

1. Download the repository using **Code → Download ZIP** and extract it.
2. Open `tools/flash-speed-reader/index.html` in a modern web browser.
3. Paste text, load a `.txt`, `.md`, or `.markdown` file, or choose **Load sample text**.
4. Select **Start reading**. Use the gear button to adjust the reading settings.

You can also download just [index.html](index.html) using GitHub's **Download raw file** button and open the downloaded file. GitHub's source preview does not run the tool.

## Features

- Adjustable speed from 100 to 1,200 words per minute; default 350.
- Word sizes from 24 to 160 pixels, with sans, serif, and monospace fonts.
- Five colour themes: Black, Dark, Warm, Sepia, and Light.
- Play, pause, restart, step controls, and a clickable progress bar.
- Basic Markdown cleanup before reading.
- Longer pauses for punctuation, long words, numbers, and paragraph breaks.

The selected speed is a base pace; added pauses mean elapsed reading time can exceed the displayed estimate. Markdown cleanup is intentionally basic and skips fenced code blocks and images.

## Keyboard controls

While in the reader:

| Key | Action |
| --- | --- |
| Space | Play or pause |
| Left / Right arrow | Step backward / forward |
| Up / Down arrow | Change speed by 25 wpm |
| R | Restart |
| Esc | Return to text editing |
| S | Toggle settings (also available outside the reader when not typing) |

## Privacy

Text and loaded files are processed in the browser. This version contains no network requests, analytics, external dependencies, or application storage. The app does not save your text or settings between sessions.

## Status

Initial import of the existing Flash tool, with its visuals and behavior preserved. Browser interaction and visual review are still pending. The sample text contains reading-speed claims that have not been independently validated; it is demonstration content, not a performance guarantee.

## License

Covered by the repository's [MIT license](../../LICENSE).
