# Rev B – FMU V1.1 documentation

| File | Content |
|---|---|
| [FMU_V1.1_RevB_Schematic.pdf](FMU_V1.1_RevB_Schematic.pdf) | Schematic, 7 sheets (Capture CIS 24.1) |
| [REVIEW_RevB.md](REVIEW_RevB.md) | Schematic + layout design review (Vietnamese) |
| [layers/pdf/FMU_V1.1_RevB_Layers.pdf](layers/pdf/FMU_V1.1_RevB_Layers.pdf) | All artwork films, vector PDF, one page per film |
| [3d/](3d) | Renders from the STEP model |

Source files are in [`hardware/rev-b-v1.1`](../../hardware/rev-b-v1.1).

## 3D

| Isometric top | Isometric bottom |
|---|---|
| ![](3d/3d_iso_top.png) | ![](3d/3d_iso_bottom.png) |
| **Top** | **Bottom** |
| ![](3d/3d_top.png) | ![](3d/3d_bottom.png) |

## Layers

Plots exported from Allegro (*File → Export → PDF*, artwork films), viewed from the top.

| | |
|---|---|
| **L1 – Top copper** | **L2 – GND plane** |
| ![TOP](layers/TOP.png) | ![SOLID_TOP_GND](layers/SOLID_TOP_GND.png) |
| **L3 – Signal** | **L4 – Power (+5, +3.3_MCU, +3.3_SENS)** |
| ![SIGNAL](layers/SIGNAL.png) | ![POWER](layers/POWER.png) |
| **L5 – GND plane** | **L6 – Bottom copper** |
| ![SOLID_BOTTOM_GND](layers/SOLID_BOTTOM_GND.png) | ![BOTTOM](layers/BOTTOM.png) |
| **Silkscreen top** | **Silkscreen bottom** |
| ![SSTP](layers/SSTP.png) | ![SSBT](layers/SSBT.png) |
| **Solder mask top** | **Solder mask bottom** |
| ![SMTP](layers/SMTP.png) | ![SMBT](layers/SMBT.png) |
| **Paste top** | **Paste bottom** |
| ![SPTP](layers/SPTP.png) | ![SPBT](layers/SPBT.png) |
| **Assembly top** | **Assembly bottom** |
| ![ASSYTP](layers/ASSYTP.png) | ![ASSYBT](layers/ASSYBT.png) |
| **Board outline** | **Drill chart** |
| ![OUTLINE](layers/OUTLINE.png) | ![NCLEGEND-1-6](layers/NCLEGEND-1-6.png) |
