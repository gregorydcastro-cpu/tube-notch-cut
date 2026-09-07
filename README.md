# G-Line tube notchers

MASSO G3 plasma rotary. **Y0 is the horn at the pipe end.** Cycle start must not rapid 19 mm in — that was making every bar short.

## Files

| File | What |
|---|---|
| `index.html` | Step File Tube Notcher — drop a STEP, get G-code |
| `tube-notch-generator.html` | Tube Notch/cut — type the sizes. **Single crotch notch** for pipes longer than the table. |

**Single crotch notch:** enter parent center-to-center (or a tape on the horns). The app tells you **how long to square-cut the stick**. One saddle at Y0, weld seam A0. Flip the pipe, line the seam, zero, run it again.

**Stand-on (parent smaller than the tube):** fishmouth on **both sides** of the pipe (0° and 180°), with **straight sand-line cuts** on the two sides that miss the parent. Same on the other end if that parent is small too.

Both start End 1 on the horn at Y0 (single crotch starts at the crotch), keep A moving forward (no rewind to 0), G21 first.

Cache-bust: `?v=12`

- https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/index.html?v=12
- https://cdn.jsdelivr.net/gh/gregorydcastro-cpu/tube-notch-cut@main/tube-notch-generator.html?v=12

Have Grokbot put these under **More** on glineracing.store.

## Shop use

1. Enter the span (parent centers unless you change the dropdown).
2. **Saw the pipe** to the length on the orange card. Square both ends.
3. Zero the far end of the pipe. Seam is A0, end of tube is Y0.
4. Cycle start pierces at Y0 — unless Single crotch notch, which starts in the crotch.
5. Do not re-zero Y at End 2 in one-setup. Touch off Z only.
6. T112. Cut far end first.
7. Long pipe: check **Single crotch notch**. Cut one end, flip, cut the other.
