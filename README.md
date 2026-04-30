# TSI SmartVent — KiCAD Design Documents (May 2026)

This repository contains the KiCAD design documents for the **TSI SmartVent** project.  
All schematics, PCB layouts, libraries, and fabrication outputs are stored here and will be regularly updated.

---

## Repository Structure

```
TSI_SmartVent_KiCAD_May2026/
├── Schematic/       # KiCAD schematic files (.kicad_sch, .kicad_pro)
├── PCBLayout/       # KiCAD PCB layout files (.kicad_pcb)
├── Libraries/       # Custom symbol and footprint libraries
│   ├── Symbols/     # Custom schematic symbols (.kicad_sym)
│   └── Footprints/  # Custom PCB footprints (.pretty/)
└── Outputs/         # Fabrication outputs
    ├── Gerbers/     # Gerber files for PCB manufacturing
    ├── BOM/         # Bill of Materials
    └── PDF/         # PDF exports of schematics and layouts
```

---

## Getting Started

1. Install [KiCAD 8.x](https://www.kicad.org/download/) or later.
2. Clone this repository:
   ```bash
   git clone https://github.com/ishron256/TSI_SmartVent_KiCAD_May2026.git
   ```
3. Open the project file (`.kicad_pro`) in `Schematic/` with KiCAD.

---

## Contribution Guidelines

- Commit schematic and layout changes together where possible.
- Export updated Gerbers and BOM to `Outputs/` whenever a design revision is finalized.
- Use descriptive commit messages referencing the design revision (e.g., `Rev A – added power stage schematic`).
- Do **not** commit KiCAD auto-save or backup files (`*.kicad_sch-bak`, `_autosave-*`).

---

## License

© TSI — All rights reserved.
