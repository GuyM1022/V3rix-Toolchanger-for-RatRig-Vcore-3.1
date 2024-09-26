# V3rix-Toolchanger-for-RatRig-Vcore-3.1

This is a modified version of 3dfiymylife V3rix from the DAKSH Tool Changer Discord.
Here is a list of the mods I did to make it fit the RatRig V-Core 3.1:

1. Carriage hole location now fit mgn 12c block.
2. Carriage belt tension grabbers now use a similar version to the EVA3 grabbers, also now using 9mm belts.
3. Extrude is now orbiter V2, modified the EBB mount to fit the orbiter
4. Dock and Dock mount changed to be able to mount to the Vcore 3030 back extrusion, also the dock mount have more mounting hold to have a more rigid connection to the frame.

Some information about my current setup:
* For nozzle offsets I'm using nudge probe attached to the back bed arm.
* For bed probing I'm using klicky but right now the probe only works on Tool 0, so every time I need to home Z first I home XY then pickup tool 0 and the probe then home Z.
* The X endstop that was originally on the EVA toolhead has been moved to the X gantry.
* The Y endstop has been moved from the back of the printer also to the X gantry so now the printer homes at (0,0).
* I am still using RatOS on my printer, I did do a few overwrites to some macros and variables to make it work.

I tried to include pictures of most of the parts, if something is unclear feal free to ask me on discord at the DAKSH server.