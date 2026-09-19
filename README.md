# Hackpad

My 3x3 macropad project for Hack Club Stardance. It features 9 MX switches, a 0.91" OLED display, and a rotary encoder, powered by a Seeed Studio XIAO RP2040.

## Hardware / BOM
* Seeed Studio XIAO RP2040
* 9x Cherry MX style switches + keycaps
* 0.91" I2C OLED display (SSD1306)
* EC11 Rotary encoder + knob
* Custom PCB
* 3D printed case (top & bottom)
* M3 screws

## Project Structure
* `cad/` - 3D case model (.step)
* `pcb/` - KiCad PCB files (.kicad_sch, .kicad_pcb)
* `keyboards/hackpad/` - QMK firmware setup
