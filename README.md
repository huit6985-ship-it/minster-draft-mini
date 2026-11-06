# MINSTER DRAFT · mini

A small demo of an automatic drawing-set generator: a parametric brick Gothic church
("St. Mary's Minster", mini) drawn entirely as code-generated SVG — no external images.

Open `index.html` in any modern browser (double-click). No build step, no server.

- Sliders: tower height, number of bays, bay width, nave width, eave height, roof pitch. All sheets redraw live.
- Sheets (DRAWING SET RW-14): 01 Erection Plan (isometric wireframe), 02 Ground Plan + Member Schedule, 03 Section A-A, 04 South Elevation. Each has a frame, title block, dimension lines and labels.
- ▶ 演示播放: wireframe (line-by-line draw) → structural section (cut hatching, trusses) → colour render (red brick, green copper roof).
- 🖨 打印 / 导出 PDF: browser print, one sheet per A3 landscape page.
- `index.html#wire`, `#struct`, `#render` open directly in a given mode.

Quantities in the schedule are rough estimates derived from the parameters, for demo only.
