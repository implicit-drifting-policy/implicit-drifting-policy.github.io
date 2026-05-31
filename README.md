# Implicit Drifting Policy Homepage

Website source files for the Implicit Drifting Policy project page.

## Local preview

This is a static GitHub Pages site. The files served online are the same root
`index.html`, `static/`, and `juxtapose/` files in this repository.

From PowerShell:

```powershell
cd "D:\CoRL 2026\demo_page"
npm.cmd install
npm.cmd run dev
```

Then open:

```text
http://127.0.0.1:5173/
```

Keep the terminal running while editing. Vite will refresh the page after most
HTML, CSS, and JavaScript changes.

If port `5173` is already occupied, stop the old preview terminal first with
`Ctrl+C`, then run `npm.cmd run dev` again.
