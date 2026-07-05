# Cadence Projects

A collection of IC design and layout projects built using **Cadence Virtuoso**. This repository serves as a central hub for individual circuit design projects, each organized as its own self-contained subfolder with schematics, layouts, simulation results, and documentation.

## Repository Structure

```
Cadence_Projects/
├── CMOS_Inverter/
├── (future project folders...)
└── README.md
```

Each project subfolder follows a consistent internal structure:

<div align="center">

<table>
  <tr>
    <th>Folder</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>design/</b></td>
    <td>Cadence Virtuoso design database (schematic, layout, symbol, extracted views)</td>
  </tr>
  <tr>
    <td><b>docs/</b></td>
    <td>Design specifications, theory, calculations, and notes</td>
  </tr>
  <tr>
    <td><b>reports/</b></td>
    <td>DRC, LVS, RCX, and post-layout verification reports</td>
  </tr>
  <tr>
    <td><b>screenshots/</b></td>
    <td>Schematic, layout, waveforms, and verification images</td>
  </tr>
  <tr>
    <td><b>simulations/</b></td>
    <td>Testbenches, Spectre netlists, ADE setups, and simulation outputs</td>
  </tr>
</table>

</div>

---

## Design Flow

<p align="center">
  <img src="assets/design_flow.png" alt="Cadence Design Flow" width="100%">
</p>

---

## Design Environment

- **EDA Tool:** Cadence Virtuoso Layout Suite XL
- **Circuit Simulator:** Spectre
- **Verification:** Assura (DRC, LVS, RCX)
- **Technology:** GPDK090 CMOS Technology


---

## Projects

| Project | Description | Status |
|:--------:|:-----------:|:------:|
| [**CMOS Inverter**](./CMOS_Inverter) | Complete custom IC design flow from schematic to post-layout verification using Cadence Virtuoso and Spectre | 🚧 In Progress |

----
## Purpose

This repository documents practical experience with the complete custom IC design flow using industry-standard Cadence tools. The projects are intended to strengthen understanding of:

- CMOS circuit design
- Analog and digital layout techniques
- Physical verification (DRC/LVS)
- Parasitic extraction
- Pre-layout and post-layout simulation
- Design documentation and reproducibility

---

## Author

**Lalith Kishore M**

Electronics and Communication Engineering (ECE)

Cadence Virtuoso • Analog IC Design • Digital IC Design • Physical Layout • CMOS VLSI
