📘 Overview

This repository contains a collection of EAGLE PCB design files and reference schematics for Nordic Semiconductor’s nRF5 series SoCs, including the nRF52810, nRF52832, and nRF51x22 families.
Each reference design includes both schematic (.sch) and board (.brd) files, along with PDF exports for easy viewing.

💡 Features

Reference PCB designs for:

nRF52810 (QCAA, QCAA_DCDC, QFAA, QFAA_DCDC)

nRF52832 (QFAA, QFAA_DCDC, QFAA_NFC)

nRF51x22 (QFAA, QFAA_DCDC)

EAGLE project files (.sch, .brd, .epf)

Readable PDF schematics and layouts

Custom Nordic libraries (.lbr files) for EAGLE

Organized folder structure by device and configuration

🧩 Folder Structure
MJ's-nrf5-eagle-design/
│
├── Library/                     # Custom EAGLE libraries
│   ├── Nordic_misc.lbr
│   └── Nordic_nRF.lbr
│
├── nRF51x22_reference/          # Reference designs for nRF51x22
│   ├── nRF51x22_qfaa/
│   └── nRF51x22_qfaa_dcdc/
│
├── nRF52810_reference/          # Reference designs for nRF52810
│   ├── nRF52810_qcaa/
│   ├── nRF52810_qcaa_dcdc/
│   ├── nRF52810_qfaa/
│   └── nRF52810_qfaa_dcdc/
│
├── nRF52832_reference/          # Reference designs for nRF52832
│   ├── nRF52832_qfaa/
│   ├── nRF52832_qfaa_dcdc/
│   └── nRF52832_qfaa_nfc/
│
└── nRF52832_qfaa_dcdc_reference.png   # Example board layout preview

⚙️ Requirements

To open or modify the design files, you’ll need:

Autodesk EAGLE (version 9.0 or newer)

Nordic Semiconductor documentation for device pinouts and layout guidelines


👨‍💻 Author

Mandar Goavakar (MJ)
EAGLE PCB Designer | Embedded Systems Developer
