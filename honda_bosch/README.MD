## Hardware:
- Tools: Saw, 3D Printer (I used FDM with PLA), Bubble level, laser (optional), tape (doesn't matter. I used painters and ducktape), string, measuring tape.
- Reflector: any metal should do. I used galvanized steel; about 28ga. The OEM Honda tool looks to be welded aluminum with a plastic nut to secure the target to the clamp, with a threaded rod on the other end.
- Stand: PVC. 1.5" ID. A "T" shape will do. I printed some adjustable feet to level out the stand and vertical mounting point.
- Mount: PLA. 10-20" infill. Not too important. You may need to tap/chase any printed threads.
- Reflector to mount screw: Must be plastic! Size spec: 1/4" - 20(TPI). I used a license plate screw from the hardware store but I suppose one could use a printed piece.
- Rod: 5/18 - 18(TPI) threaded rod. About 1 ft long.

## Electronics:
- Software: HDS from Honda (techinfo.honda.com)
- Interface: comma.ai white panda or other suitable VCI like a tactrix

### Prereqs:
Find the car's centerline. I used a laser and go as close as I could. Probably best to draw the car's box and find it from there.

Begin the alignment process in HDS in an open space without the radar target in place. When HDS prompts you, align and place the target. Align the threaded rod to the bottom of the radar unit, then raise the target 22mm upward. Next, place the target 4 meters forward of the centerline of the front wheels and directly inline with the radar.

Radar Offset:
- Civic Hatch: 22.95inches (0.58 meters) from center
- Insight: ?
- Center mounted (Accord, CRV): Center on vehicle center line

### Adjustment Process
Continue in software, adjusting the alignment screws until the display shows an alignment error of +/- 0.1 degrees. The display is capable of showing error accuracy to down to 0.01 degrees. When satisifed, finish the radar alignment process on the display. Next turn off ignition and then back on. Job Done!

#### Questions:
- **What if the target doesn't work?:** Check setup alignment and bend quality of the reflector. The reflector faces should be as flat as possible. If all else fails, buy a real one if you can or pay a dealer $300 to do it. Mine worked great with minor attention paid during the setup process.

Disclaimer: All of this info and design work is free. I'm not responsible for anything that goes wrong as a result of using any of my designs or information in this repo.
