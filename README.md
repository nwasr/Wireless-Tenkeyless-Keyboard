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

![alt text](images/block_level_diagram.png)

The design follows a modular, hierarchical schematic structure:
- Root (page 1)
  - Block Level Architecture (page 2)
    - USB C (page 3)
    - MCP73871 (page 4)
    - LDO (page 5)
    - MCU (ESP32-WROOM-S3) (page 6)
    - Keyboard Matrix (page 7)

Full schematic: [schematic.pdf](schematic.pdf)

---

## **PCB Design**

![alt text](images/front_view_pcb.png)
![alt text](images/back_view_pcb.png)


---

## **Case Design**

- TODO

---

## **EMI Considerations**

- TODO
---

