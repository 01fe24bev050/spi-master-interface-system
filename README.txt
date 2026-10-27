SPI-MASTER INTERFACE SYSTEM — ULTIMATE EDITION

Contents
- index.html: Home, project theme, team and guides
- introduction.html: Problem statement and overview
- design.html: Master/slave block diagram, bidirectional data flow, interactive component explorer, IC references
- simulation.html: Browser-based 2-bit two-way transaction demo with selectable transfer speed and clock waveform monitor
- results.html: Expected results and observations
- bom.html: Invoice-based bill of materials with line-item prices and ₹674.00 invoice total (invoice dated 27-10-2026)
- style.css, stars.js, site.js, simulator.js, architecture.js: Styles and interaction scripts

Deploy to GitHub Pages
1. Download and extract the ZIP.
2. Upload all files to the root of the existing GitHub repository, replacing the old versions.
3. Commit the changes. In repository Settings > Pages, confirm the intended branch/folder is selected.
4. Wait for the Pages deployment, then hard-refresh the live site.

Important technical note
The live simulation is an educational browser model of the intended 2-bit password/status transaction. It is not an electrical simulator and does not prove pin-by-pin correctness or timing of a Proteus circuit. Validate the exact 74HC165 LOAD/SHIFT polarity, 74HC595 latch timing, 74HC85 input mapping and defined unused inputs, status encoding logic, and counter decode against the actual schematic and component datasheets before hardware implementation.
