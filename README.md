# **Wireless-Tenkeyless-Keyboard**

A compact wireless mechanical keyboard designed using the **ESP32-WROOM-S3** module. This project was developed as part of academic coursework.

> **Disclaimer:**  
> This design has not been fabricated or tested on hardware. Use at your own risk.

![Final Keyboard Mockup](images/final_keyboard.jpg)

---

## **Keyboard Layout**

- Designed using [Keyboard Layout Editor](http://www.keyboard-layout-editor.com).
- Layout file: [layout.json](kle_files/keyboard-layout.json)
- Visual preview:

![KLE Layout Preview](images/keyboard-layout.jpg)

---

## **Schematic Overview**

**System-level design includes:**
- **ESP32-WROOM-S3** for BLE communication and GPIO-based key scanning.
- **Key matrix** arranged in rows/columns and scanned in firmware.
- **Power system**: 1000 mAh LiPo battery charged via **MCP73871**.
- USB interface used for charging and potential debug access.

![Schematic Block Diagram](images/schematic_block.png)

Full schematic: [schematic.pdf](hardware/schematic.pdf)

---

## **Case Design**

- Enclosure designed in Fusion 360.
- STL and STEP files available: [Download](case/)
- Rendered views:

![Top Case](images/case_top.jpg)  
![Bottom Case](images/case_bottom.jpg)

---

## **EMI Considerations**

EMI optimizations were made at the design level. No physical testing was performed.

**Design Measures:**
- Decoupling capacitors near power pins of ESP32.
- Ground pours under RF and digital sections.
- Separated high-speed signals and power lines.
- Compact trace routing to reduce emissions.

---

Let me know if you want to add firmware flow or simulation results.
