# Omni PNG ↔ WebP Converter

Lite browser tool that converts **PNG ↔ WebP** automatically from the file you drop or pick.

- Drop a **WebP** → downloads a **PNG**
- Drop a **PNG** → downloads a **WebP**
- Status bar shows **Converted X → Y**

Runs entirely in the browser via HTML canvas (no upload to a server).

## Use online

https://windstrikeone.github.io/omni-png-webp-converter/

## Run locally

Open `index.html` in a modern browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Credits

Based on [hijack-x/webp-to-png](https://github.com/hijack-x/webp-to-png).
