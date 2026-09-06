# Step File Tube Notcher

GlineRacing shop tool for MASSO G3 plasma rotary. Drop a STEP-measured tube (preloaded: cage24 back angle bar) and cut so the ID sits on the parent OD.

## Grab it for the store

File: `index.html` in this repo.

jsDelivr:

https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/index.html

GitHub Pages (one-time: repo Settings → Pages → Deploy from branch `main`, folder `/ (root)`):

https://gregorydcastro-cpu.github.io/tube-notch-cut/

## Put it under More on glineracing.store

1. Shopify admin → **Online Store → Pages → Add page**
2. Title: `Step File Tube Notcher`
3. Switch to the HTML (`<>`) editor and paste:

```html
<iframe
  src="https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/index.html"
  title="Step File Tube Notcher"
  style="width:100%;min-height:90vh;height:90vh;border:0;background:#121418"
></iframe>
```

4. Save. The page URL is usually `/pages/step-file-tube-notcher`.
5. **Online Store → Navigation** → the menu that has **More**.
6. Add a link: **Step File Tube Notcher** → that page.
7. Save the menu.

If jsDelivr still shows an old file after an update, add `?v=2` to the iframe `src`.

## On the machine

- Tool **T112** plasma (not T111)
- Zero the far end: seam = A0, Y0
- Chuck is End 2, negative Y
- Cut far end first so the pipe does not drop
