# Assembly

## Table of Contents

* [Prep Work](#Prep-Work)
	* [Tapping and Assembling the X and Z Axis Assembly](#x-and-z-axis-sub)
	* [Assembling to the X and Z Axes](#Assembling-to-the-X-and-Z-Axes)
* [Making the Cr8](#Cr8-Start)
	* [Cr8 Assembly](#Cr8-Assembly)
* [Y Axis Start](#Y-Axis-Start)
* [Window](#window)
* [Spindle Mount](#Spindle-mount)

## Prep Work

3d-print all your 3D printed parts per the [instructions](printing.md).

Make sure you have two of all the jigs marked 2x in the Fusion360 Project. Pre-drill all the holes. Most can be predrilled with a 1/4" bit. Use an 1/8" bit for smaller holes. The only holes that should be pre-drilled smaller than 1/8" are for the M2 screws that hold in the limit switches.


## X and Z axis Sub

### Punch, Drill and Tap the X-Axis 

![x_jig](./assets/images/screen_shots/x_jig.png)

Take a look at your 4x1.5x18" steel tube and see if one side is flatter along the 4" length than the other.

If one side is noticeably flatter, set up your printed X-Axis jigs and linear rails on that side. 

We recommend using a transfer punch to make a light mark for each of the holes, and then enlarging those holes slightly with a center punch. 

Drill all 16 holes for each rail, and tap with an M3 0.5 tap and plenty of tapping fluid. There is an M3 tap guide in the jigs folder on the github to help keep the tap straight. You may have to adjust the scale slightly depending on the settings and nozzle size on your 3D printer.

At this point, you can start screwing down your rails to the tube with M3x10 SHCS and check if the rails are flat. It's not uncommon for the rails to both be tilted in toward the center of the axis. If this is the case (or if they are otherwise out of parallel with each other) check out the [shimming](shimming.md) guide.

![x_bearings](./assets/images/screen_shots/X_bearings.png)

### Assembling to the X and Z Axes

![x_z_plate](./assets/images/screen_shots/x_z_plate.png)

Use 16 M3x10 SHCS to bolt the Z to X Plate to the carriage.  

![x_leadnut](./assets/images/screen_shots/xleadnut_mount.png)

M3 nuts pressed into X Lead Nut mount.
M3x12 SHCS to bolt the X Lead Nut to Z to X plate.


![Z_limit](./assets/images/screen_shots/z_limit.png)

M2x12mm bolts to attach the limit switch to the Z Linear Motor Mount. You cannot attach the limit switch once the Z Motor Mount is attached to the Z to X Plate.
Solder wires before bolting. The "Normally Closed" (NC) configuration is recommended for best safety practices.
Run wire for the Z limit switch through slot in the Z Linear Motor Mount. 

![Z_motor](./assets/images/screen_shots/zmotor.png)

M3x10 screws into motor, through the Z Linear Motor Mount. You cannot attach the Z Motor after the Linear Motor Mount is attached to the Z to X Plate.  
Make sure lead nut is mounted now, it's a real pain to mount it later. 

![Z_motor_mount](./assets/images/screen_shots/zmotor_mount.png)

M4x12 SHCS to through the Z Linear Motor Mount to the Z to X Plate  
Use M4 self tapping screws if using plastic plates

![Z_leadnut](./assets/images/screen_shots/Z_leadnut_mount.png)

Use M4x12 SHCS to attach the Z Lead Nut Mount to the Z Plate.
Insert M5 nylock nuts into the Z Plate now. It is impossible to insert these once the Z Plate is mounted on the carriage. If they are loose, you can hold them in place with M5 screws until you attach the tram plate and router mount.

![Z_rails](./assets/images/screen_shots/Z_rails.png)

Use M3x10 SHCS, or M3 self-tapping screws to attach the Z Linear Rails to the Z Plate.

![Z_bearings](./assets/images/screen_shots/Z_bearings.png)

Put two Z bearings on each Z rail.

![Z_spacer](./assets/images/screen_shots/z_spacer.png)

Put 1 Z Spacer over each set of bearings.
Drill out the bolt holes if needed to make sure the M3 bolts slip through cleanly  

![Z_plate](./assets/images/screen_shots/Z_plate.png)

Use M3x10 SHCS attach the Z Plate to the bearing blocks through the spacers.

![Z_leadnut](./assets/images/img/xz_sub5.jpg)

Use M3x10 SHCS tp attach the Z Lead Nut Mount to the Z Plate. Use the holes in Z Linear Motor Mount to slip allen key through and access bolts. You may have to rotate the lead screw to properly align the Z Lead Nut Mount in order to screw in the bolts.

![X_limit](./assets/images/screen_shots/x_limit_mount.png)

Solder the wires to the X limit switch and attach the X limit switch to the X Tube Left Idler with M2 screws. Do not attach the left X Tube Left Idlder to the X Tube at this time.

## Cr8 Start

Check the length of your X-tube. Midwest Steel has a tendency to cut the tubes 1/8" long. So you'll either need to file that down, or increase the width of the front, back, top, and bottom by 1/8" to compensate. 

A soft recommendation is to get the crate sides cut on a CNC. There are a lot of holes to drill and it's easier to get them all aligned if it's done by a computer. That said, there are also large format [PDFs](../Panel_Drawings/pdfs) to print and attach to the panels with spray adhesive that work as good guides. It's very possible to make it with hand-drilled holes in the crate, it's just harder.  

![Cross Dowel](./assets/images/img/cross_dowel.jpg)

### Cr8 Assembly

Press the jig into large holes in the frame to align your side drills  

Drill the holes about 10mm past the dowel hole to allow for bolt clearance

![Cr8 ](./assets/images/screen_shots/cr8_start.png)

Build up Cr8 with 3 sides like this  

![X-tension ](./assets/images/screen_shots/threaded_rod.png)

Put lock washer, and nuts on the side of 2 threaded rods  

Put through the X holes  

Lie the Cr8 on its side

![X Cr8 ](./assets/images/screen_shots/X_cr8.png)

Attach the X Tube Right Motor Cap to the right side of the X Tube. Sometimes these need to be pounted in with a mallet, if it's tight, use a 2x4 over the plastic to avoid damaging it.

Slide the X-Z Sub-Assembly over the threaded rods all the way down. This can be a little fiddly but this is the easiest way. Thread the threaded rod through the X Tube Left Idler cap over the X Tube, use the 2x4 and mallet method to secure it.

![X Mounts](./assets/images/screen_shots/X_mounts.png)

Attach the left side of the Cr8. Add a lock washer and nut to each threaded rod on the left side. 

![Cr8 Side 2 ](./assets/images/screen_shots/side_2.png) 

## Y Axis Start

![Y Rail Punch](./assets/images/screen_shots/y_rail_jig.png)

![y punch](./assets/images/img/y_punch1.jpg)

![y punch](./assets/images/img/y_punch2.jpg)

Punch drill and tap all holes

![Y Axis Mounts](./assets/images/screen_shots/Y_mounts.png)

![Y Axis Box](./assets/images/screen_shots/Y_axis_box.png)

M5x25 SHCS in the middle holes of the mounts.  

Slide the last two threaded rods in the outer holes through the tubes. Ive found it can be helpful to lay the frame on it's back so you are droppin the threaded rod through the holes.  

![Thrust_bearing](./assets/images/screen_shots/Thrust_bearing.png)

Press 1 608 bearing into the front and back of each thrust block.  

![x lead](./assets/images/img/x_lead1.jpg)

![x lead](./assets/images/img/x_lead2.jpg)

![x lead](./assets/images/img/x_lead3.jpg)

Put the coupler on the motor shaft 10.5mm (ish) from the motor face

Slide the shaft collar and one M8 washer onto the leadscrew and then slide the leadscrew through the thrust block.

On the inside of the thrust block, slide the thrust bearing stack onto the lead screw and then tighten the coupler onto the lead screw.

4- M3x50 SHCS to bolt through the thrust block to the motor

Pull the lead screw away from the motor and press the shaft collar against the thrust block while tightening the set screw. - the goal is to remove the possibility for axial play. 

![Y Axis limit](./assets/images/screen_shots/Y_limit.png)

Solder the wires for the limit switch and use an M2x12 SHCS to bolt it the thrust block with 2 small holes in the side.  

![Y Motor Stack](./assets/images/screen_shots/Y_stackup.png)

Put the coupler on the motor shaft 11.5mm (ish) from the motor face

Slide the shaft collar and one M8 washer onto the leadscrew and then slide the leadscrew through the thrust block.

On the inside of the thrust block, slide the thrust bearing stack onto the lead screw and then tighten the coupler onto the lead screw.

4 - M3x50 SHCS to bolt through the thrust block to the motor

Pull the lead screw away from the motor and press the shaft collar against the thrust block while tightening the set screw. - the goal is to remove the possibility for axial play. 

Y Leadnut mount - press M3 nuts into the pockets and screw to the leadnut

![Y Axis Plate](./assets/images/screen_shots/Ybed.png)

M3x16 FHCS for all the carriages and lead nut mount

![Top](./assets/images/screen_shots/top.png)

Loosen all the screws on one side to make it easier to slide the top in and loosely bolt it in.  

## Window

![window mounts](./assets/images/screen_shots/window_mounts.png)

Screw all the window mounts to the Cr8 with 3/4" wood screws. Pay attention to the hinge mount holes on the top mounts. 

![window components](./assets/images/screen_shots/window_components.png)

M3x12 SHCS bolted through the window 

![window hinges](./assets/images/screen_shots/Hinge_top.png)

M3 plastic tap screws or M3 SHCS to bolt the hinges to the top mounts.

![window pin](./assets/images/screen_shots/hinge_pin.png)

M5x25 SHCS for hinge pins

## Spindle mount

![Spindle Mount](./assets/images/screen_shots/spindle_tram.png)

M5x20 FHCS bolted through the back of the tram plate

add the 4 90 brackets to the top and bottom of the mount and tramp plate

Use 4 M5x16 bolts to bolt the tram plate to the z plate. 

One of the 4 M5 holes is on size and the other 3 are overside to allow for small adjustments of tilt on the spindle
