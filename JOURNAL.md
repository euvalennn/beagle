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

# May 30: Did more routing and fixed DRC errors

Today I changed the neopixels' connections on the schematic so that they match the actual layout on the PCB and then started routing! I actually finished routing all of them as well as the VCC connections, so the only thing left to route now is GND. I also ran a DRC check and moved around some components that were overlapping so I shouldn't have any problems with that now.
Here's a pic of the PCB right now:

<img src="assets/pcb-may-30.png" width=500px>

Even though I already finished routing all the neopixels, I think I might get rid of them and replace them with reverse mount ones on every switch. Right now I don't think they'll be too visible as the case will (probably) be 3D printed and all the neopixels are on the back on the PCB :pf:

Anyway once I figure the neopixels thing out I want to start with the case design!!

Wish me luck 😭

**Time spent this session 1.5h**

# May 31: Re-did all neopixels and did even more routing

Well, I ended up removing all of the neopixels I had already routed from the schematic and PCB to add reverse mount ones just like I said :pf:

Here's how they look on the schematic now:

<img src="assets/neopixels-may-31.png" width=500px>

After that, I placed all of them on their respective keys (I actually found out KiCad has an array feature which made this 100x easier!!) and then I routed all of them. It took quite some time because traces I routed before were going over the neopixels' holes and pads, so I had to move around a lot of them to fix the million new DRC errors that popped up 😭

Anyways here's how the PCB looks:

<img src="assets/pcb-may-31.png" width=500px>
<img src="assets/pcb-3d-front-may-31.png" width=500px>
<img src="assets/pcb-3d-back-may-31.png" width=500px>

I still have to route VCC and GND and do silkscreen but I feel like I'm closer to finishing now!!

**Time spent this session: 3h**
