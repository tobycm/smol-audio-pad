# Smol Audio Pad Project Journal :D

Start of something great. Made by <img src="./assets/logo.png" width="16"> <a href="https://github.com/tobycm">tobycm</a> for Hack Club's [Pendant](https://pendant.hackclub.com/) YSWS.

1. Picked XIAO nRF52840 for good power efficiency, a small lithium ion battery pouch, a rotary encoder for volume control with integrated switch for play/pause, and 2 switches for next and previous control.

![rotary encoder](assets/encoder.png)
![xiao nrf52840](assets/xiao_nrf52840.png)

2. Started initial schematic

![sch1](assets/sch1.png)

![sch2](assets/sch2.png)

3. General layout

![pcb1](assets/pcb1.png)
![3d pcb1](assets/pcb1_3d.png)

At this point, I realized I have quite a bit of space left, so I think I will add a neopixel and 2 more switches. I also realized that I need battery protection circuit to avoid overcharging and overdischarging.

4. Added a bunch of battery stuff: resistor divider to gauge battery voltage, overcharging and overdischarging protection, JST connector for battery

![sch3](assets/sch3.png)
![sch4](assets/sch4.png)

time for more pcb layout 😋

5. PCB Layout and Routing done!

![pcb2](assets/pcb2.png)
![pcb2_3d1](assets/pcb2_3d1.png)
![pcb2_3d2](assets/pcb2_3d2.png)

gotta add neopixel and expose swd pads then im done with the pcb :D

nvm no neopixels, just swd pads

6. Added SWD pads for debugging and flashing, as well as mounting bites and holes

![pcb3](assets/pcb3.png)
![pcb3_3d1](assets/pcb3_3d1.png)
![pcb3_3d2](assets/pcb3_3d2.png)

7. Case designing

![cad1](assets/cad1.png)

good enough, i left enough of the plus sign to fit the keycaps