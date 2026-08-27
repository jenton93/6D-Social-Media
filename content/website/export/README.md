# Export

**`6D-website-copy.pdf`** , the full site copy as a document, for sending to
Christian or anyone else who needs to read it away from a browser.

17 pages. Title, then one section per site page, in the brand with Audiowide
and Arimo embedded. Gap blocks are hidden in the PDF, so it reads as finished
copy rather than a working document. The interactive preview still shows them.

## Regenerating it

The PDF is rendered from the live preview, so it stays in step with the copy.

```
# from the scratchpad build dir
chromium --headless --disable-gpu --no-sandbox \
  --print-to-pdf-no-header \
  --print-to-pdf=6D-website-copy.pdf 6d-print.html
```

`6d-print.html` is the preview with the navigation stripped, every page
expanded, gaps forced visible and print styles added. Fonts are inlined as
base64 rather than linked, because the Google Fonts request fails through the
proxy and the document silently falls back to system fonts otherwise.

Interactive version: the artifact link in the chat.
