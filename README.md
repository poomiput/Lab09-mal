# Operation Aegis — Lab 09 Walkthrough

Full bypass walkthrough for all 6 Anti-Analysis challenges in **CP423322 Malware Analysis and Protection, Lab 09**.

Open [`index.html`](./index.html) in a browser, or view it live via GitHub Pages once enabled (Settings → Pages → Deploy from branch `main` / root).

## Covers

1. Anti Capture — single-byte patch
2. Anti Packing — UPX unpack + 4-point gate patch
3. Anti Reverse — no patch needed, just clean up analysis-tool footprint
4. Anti Temper — 4-point gate patch
5. ClockCheck — data-byte fix (not a jump patch)
6. VBoxDetection — 4-point gate patch

Each section includes DIE triage output, Ghidra decompiled logic, exact file offsets, and x64dbg patch steps.
