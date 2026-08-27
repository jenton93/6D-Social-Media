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

## The two links

| | For | Shows gaps |
|---|---|---|
| **Working preview** | Jenton and Christian | Yes, with a toggle |
| **Clean version** | Sending onward: Will, a client, anyone else | No |

`6D-website-clean.html` is the same copy with the drafting chrome stripped:
no gap blocks, no toggle, no draft banner. It's the one to share.

Artifacts are private until shared. Use the share menu on the page itself to
make either one viewable, then send that link.
