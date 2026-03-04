Made by: @Dhiaan Dave // Dhiaan Dave
Repository link: https://github.com/the-X-alien/Storm/
Total hours so far: 7.5

- [] I have a 3D printer or will be getting one before March 21st (printing legion pls save me)

---
### Goals:

- Beat the A1 at everything
- Cartesian bedslinger (like Bambu A1)
- 256×256×300mm build volume
- 500–700mm/s, sub-5min Benchy, high quality
- Screen, WiFi, rollable wheels
- Under $300 including shipping/taxes
- Portable, rollable base for easy travel

---
### Day 1 - Feb 28 2026 - 2 Hours
I thought that Campfire SJ would be a good place to start making my printer because I was an org and not a participant.

But the second I opened the Infill website, I was lost by all the terms like Gantry, Toolhead, and Extrusions. 

But after googling and asking various AI chatbots, I learned that the Gantry is the frame system that allows movement, the toolhead is the part that encompasses the hotend and extruder, and extrusions are metal parts that make up the frame of a printer.

But I was still lost on how to actually make the 3D printer.

After watching a few YouTube videos on how to assemble the frame of a Cartesian 3D printer, I learned that the frame is built of a square base made from metal extrusions, and then there are two extrusions attached vertically on each side with one extrusion connecting them, allowing X Y and Z movement.

One video that really helped me was this one video on how the Bambu Lab A1 works, because it is also a Cartesian printer: https://www.youtube.com/watch?v=f94CnlQ0eq4

I understood the frame completely, but now I was lost on how to make things like the toolhead.

<img width="1240" height="820" alt="image" src="https://github.com/user-attachments/assets/8e75f1ee-b2e3-4fc5-a71a-6963a64ac9bc" />

And right then, Alex (@alexren) pulled up to the event and I asked him for help.

He explained to me how he made his tool head by modeling the inside with the dimensions of the hotend, and how he added magnets to make the hotend hotswapable.
He also recommended that I look at other 3D printers to see what they did for their toolhead and other parts.

So I viewed printers like PandA and Nighthawk and saw their toolhead design.

And now I need to pick a hotend and an extruder so I can model my toolhead.

---
### Day 2 - Mar 3 2026 - 5 Hours

I spent some more time researching what parts I am actually using to build the 3D printer.

(to come up with this list, I had to read alot of reddit, watch many youtube videos, and I had to ask many questions to Claude and Grok)

So, I had to decide what kind of Aluminum extrusions to use.

I needed the frame to be both sturdy and impact resistant.

So, I had a large base made up of 4x 350mm 4040 Extrusions to spread vibration impact,

Then 2x 2040 Extrusions for the Z axis movement,

And the cross bar uptop will be a 2020 extrusion.

To connect them, I will be using cornerplates.

The extruder will be a Orbiter V2.5 which is the evolution of the V2.0 which is the standard lightweight direct-drive extruder for fast bedslingers

And the hotend will be a Trianglelab TZ V6 2.0 Hotend which is considered to be a budget A1 hotend, because it prints 30–45 mm³/s on PLA with a 0.6 mm nozzle compared to the A1's 20–25 mm³/s speed, and it has a bi-metal heatbreak, copper block, fast heating, and it is CHT-compatible nozzle options. It is also super  lightweight, reliable, and it will work with with most V6-style mounts. (V6 style mount to keep in mind when im cadding the toolhead)

For the nozzle, I'll go with any generic no name 0.4 mm hardened steel CHT-style (3-hole/high-flow) nozzle because 0.4mm is the industry standard for a balance of speed and quality for nice printers like the A1, A1 Mini, and Ender 3.

For cooling, I will get Dual 5015 blower fans with high static pressure (24V) because the nozzle and hotend are going to run hot, and so this powerful combination should cool it down.

For leveling, im using the Klicky probe, which is better than the CR Touch and the BL Touch in everysingle way of acuracy, weight, noise.

---
### Day 3 - Mar 4 2026 - 0.5 Hours

Made some modifications to the above parts list after reading more on Reddit

Aparently since the Klicky probe needs to dock, it's not ideal for bedslingers, and designed for other printers.
So instead, I am switching to the BTT Eddy, because it is super fast and scans the entire bed in one go, making my printing time faster.

Aparently CHT nozzles are a pain to clean if they get a clog and are annoying, and you might just have to throw them away altogether.
So I'll start with a basic standard hardened steel 0.4mm V6 nozzle because I'm a beginner and I want the printer to work before I start trying anything crazy.
