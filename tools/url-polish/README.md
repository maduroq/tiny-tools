# URL Polish

A standalone URL workbench for SharePoint, Microsoft 365, and everyday development tasks.

[Open in your browser](https://htmlpreview.github.io/?https://github.com/maduroq/tiny-tools/blob/main/tools/url-polish/index.html) using third-party HTML Preview, or download [index.html](index.html) with **Download raw file** and open it locally.

## Encode and decode

Paste a URL or text, select a mode, and choose Encode or Decode. Each click processes one layer. Use result as input to work through another layer explicitly.

- Component: percent-encode a query value or path segment; decode percent escapes for readability.
- Whole URL: preserve URL separators. Decoding keeps reserved separators encoded.
- Form value: encode spaces as plus signs; decode plus signs as spaces.

Decoding a URL for readability can change its meaning if you navigate to that decoded version. Malformed input reports an error without replacing the input.

## Copy-ready links

Enter an HTTP(S) URL and optional label, then copy a plain URL, Markdown link, or HTML link source. Query parameters are retained. HTML output is source code rather than a rich-text clipboard item.

## Text-highlight links

Enter the page address and starting text. Optional ending text selects a range; optional preceding and following text distinguish repeated matches. The result updates as you type, like an equation.

Existing section anchors are preserved; existing fragment directives are replaced. Text values are percent-encoded, including hyphens and commas. Open to check highlight launches the result only when clicked.

Highlight support depends on the browser, matching text, and page behavior. Dynamic SharePoint pages may behave differently. The builder does not fetch or inspect the destination.

Syntax reference: [MDN text fragments](https://developer.mozilla.org/en-US/docs/Web/URI/Reference/Fragment/Text_fragments).

## Appearance and privacy

Uses the Maduroq palette and starts with the browser's preferred light/dark theme. A manual theme change applies for the current session.

No external dependencies, network requests, analytics, or persistent storage. Copy writes the selected result to the clipboard. Opening a generated link navigates to its destination.

## Validation

Logic checks cover Unicode, reserved characters, one-layer decoding, malformed input, fragment context and anchors, link escaping, and theme state. Visual browser review is pending.

## License

[MIT](../../LICENSE).
