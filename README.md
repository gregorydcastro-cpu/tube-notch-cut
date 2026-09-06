# G-Line tube notchers

MASSO G3 plasma rotary. **Y0 is the horn at the pipe end.** Cycle start must not rapid 19 mm in — that was making every bar short.

## Files

| File | What |
|---|---|
| `index.html` | Step File Tube Notcher — drop a STEP, get G-code |
| `tube-notch-generator.html` | Tube Notch/cut — type the sizes |

Both start End 1 on the horn at Y0, keep A moving forward (no rewind to 0), G21 first.

Cache-bust: `?v=8`

- https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/index.html?v=8
- https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/tube-notch-generator.html?v=8

Have Grokbot put these under **More** on glineracing.store.

## Shop use

1. Zero the far end of the pipe. Seam is A0, end of tube is Y0.
2. Cycle start should pierce at Y0, not run in.
3. Do not re-zero Y at End 2. Touch off Z only.
4. T112. Cut far end first.
