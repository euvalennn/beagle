# May 26: Did research, started (and finished!) first schematic design, and positioned all components in the PCB

I wasn't really sure if I could make this because it's been a really long time since I last made a hardware project and making a keyboard sounds a bit complicated but I finally decided to give it a try, so here we are :D

I'm planning on making a 75% keyboard with a 0.91" OLED display, a rotary encoder for volume and an Orpheus Pico as the MCU. It's my first time making a keyboard and I'm not too sure how hard it will be but I've been doing some research and already started designing the PCB.

Here's how the schematic is looking so far:

<img src="assets/schematic-may-26.png" width=500px>

I positioned all components in the PCB, although I had to spend some time looking for 3D models and footprints for every one of them (especially the stabilizers) and seeing where to place everything (I'm still not sure if I'll keep the current layout but it serves as a starting point for now, I already spent way too much time on this today so I'll figure it out later 😭)

Here's how the PCB looks right now, both from the editor and 3D viewer:

<img src="assets/pcb-may-26.png" width=500px>
<img src="assets/pcb-3d-front-may-26.png" width=500px>
<img src="assets/pcb-3d-back-may-26.png" width=500px>

For the next time I work on this I'd like to figure out the final layout and start routing the PCB!

**Time spent this session: 4h**

# May 28: Updated PCB and switch matrix (schematic) and started routing

I got a lot of stuff done today!!

First off, I moved around some components and switches in the PCB so that the spacing makes more sense and I can make the PCB smaller.

Once I was happy with how the general layout looked, I was going to start routing the switches but then I realized the rows and columns were a total mess :pf:

I had to change the switch matrix in the schematic to reflect how the switches were actually laid out in the PCB and therefore make routing easier.

Here's how the matrix looks now:

<img src="assets/switch-matrix-may-28.png" width=500px>

Once that was done I started routing everything! I had to redo it a couple of times but here's how the traces look now (I think it looks pretty neat!)

<img src="assets/pcb-may-28.png" width=500px>

Now I only have to route the neopixels (I'll also have to update the schematic for those so that the connections make sense) and add silkscreen art. Once I'm done with that I think I can move on to the case design :D

Here's how the PCB looks right now from the 3D view:

<img src="assets/pcb-3d-front-may-28.png" width=500px>
<img src="assets/pcb-3d-back-may-28.png" width=500px>

**Time spent this session: 4h**
