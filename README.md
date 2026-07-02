# beagle

<img src="assets/renders/render1.png" width=500px>

my first (and only) keyboard!!

It's been almost a month since I started working on this! I wanted to try making a keyboard myself, but soon realized it's easier said than done 😭\
Overall I'm really happy with how it turned out, I have to admit it took me a pretty long time to finish but I wanted to make sure it was polished and I think I've achieved that :)

The layout resembles that of my MacBook's keyboard (since that's what I mostly use) and I also included a rotary encoder (intended for volume but can be customized) and an OLED screen to show animations, graphics, or anything else you may want to put there. There's an SK6812MINI-E behind every switch to allow for individual key backlighting.\
I designed the case in Fusion and it consists of an angled base for the keyboard to sit on, the main body of the case covering all of the components from the sides, a plate, and a top part covering it. All of the parts will be put together with 20mm M3 screws, one in every corner.\
The PCB also features a silkscreen hand-drawn by myself! :D

## Features:

- 77 total keys
- rp2040 based mcu
- customizable knob to control whatever your heart desires
- 0.91" OLED screen for graphics and useful info
- neopixels under each switch for RGB backlighting
- sick hand-drawn silkscreen!!

## More CAD pictures

<img src="assets/renders/render2.png" width=500px>\
<img src="assets/renders/render3.png" width=500px>

NOTE: the actual color scheme is subject to change based on availability 😭

## PCB and schematics screenshots

see it online [here](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2Feuvalennn%2Fbeagle%2Ftree%2Fmain%2Fpcb)!

<img src="assets/pcb-final.png" width=500px>\
<img src="assets/pcb-front-final.png" width=500px>\
<img src="assets/pcb-back-final.png" width=500px>\
<img src="assets/schematics-final.png" width=500px>

## BOM

| Item                   | Quantity | Price                               | Total  | URL                                                  |
| ---------------------- | -------- | ----------------------------------- | ------ | ---------------------------------------------------- |
| Orpheus Pico           | 1        | Already owned                       | $0     | N/A                                                  |
| OLED display           | 1        | $6.06                               | $6.06  | https://es.aliexpress.com/item/1005008640108394.html |
| EC11 Rotary encoder    | 1        | $5.33                               | $5.33  | https://es.aliexpress.com/item/1005007644083514.html |
| SK6812MINI-E           | 100      | $10.53                              | $10.53 | https://es.aliexpress.com/item/1005005193716172.html |
| 1N4148 diodes          | 100      | $5.26                               | $5.26  | https://es.aliexpress.com/item/4001126137167.html    |
| Keyboard switches      | 80       | $1.75                               | $1.75  | https://es.aliexpress.com/item/1005012157731141.html |
| M3x5x4 heatset inserts | 30       | $7.04                               | $7.04  | https://es.aliexpress.com/item/1005006071488810.html |
| M3 20mm screws         | 50       | $8.14                               | $8.14  | https://es.aliexpress.com/item/32810872544.html      |
| Stabilizers set        | 1        | $9.97                               | $9.97  | https://es.aliexpress.com/item/1005004229140548.html |
| Keycap set             | 1        | $15.51                              | $15.51 | https://es.aliexpress.com/item/1005007321700850.html |
| AliExpress VAT         | 1        | Included in item prices             | $0     | N/A                                                  |
| PCB                    | 1        | $22.20                              | $22.40 | https://jlcpcb.com                                   |
| PCB shipping           | 1        | $48.19                              | $47.36 | https://jlcpcb.com                                   |
| 3D printed case        | 1        | Will get someone to print it for me | $0     | N/A                                                  |
| 3D printed plate       | 1        | Will get someone to print it for me | $0     | N/A                                                  |
|                        |          |                                     |        |                                                      |
| Total cost:            | $139.35  |                                     |        |                                                      |

---

thank you to [hack club](https://hackclub.com) for funding this project :D
