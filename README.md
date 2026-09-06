# Step File Tube Notcher

Drop a round-tube STEP. Get MASSO G3 plasma rotary G-code. Torch follows the tube ID so it sits on the parent OD.

## Grab it for the store

File: `index.html` in this repo.

https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/index.html?v=5?v=5

GitHub Pages (one-time: repo Settings → Pages → Deploy from branch `main`, folder `/ (root)`):

https://gregorydcastro-cpu.github.io/tube-notch-cut/

## Put it under More on glineracing.store

1. Shopify admin → **Online Store → Pages → Add page**
2. Title: `Step File Tube Notcher`
3. Switch to the HTML (`<>`) editor and paste:

```html
<iframe
  src="https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/index.html?v=5?v=5"
  title="Step File Tube Notcher"
  style="width:100%;min-height:90vh;height:90vh;border:0;background:#121418"
></iframe>
```

4. Save. The page URL is usually `/pages/step-file-tube-notcher`.
5. **Online Store → Navigation** → the menu that has **More**.
6. Add a link: **Step File Tube Notcher** → that page.
7. Save the menu.

## How to use

1. Drop the STEP of the round tube you want to cut (not the whole chassis).
2. Check OD, wall, length, and the pipes each end sits on.
3. If STEP parent is 1.528 and the chassis tube is 1.5, type 1.5.
4. Download .nc. MASSO: T112, zero far end at Y0, seam A0, chuck is End 2. Cut far end first.
