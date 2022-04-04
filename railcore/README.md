## *IG RailCore Usage*

The RailCore is a CoreXY-style printer which is a very accurate and fast. It uses a Bondtech Orbiter extruder with an LDO stepper with an E3D Revo hotend, and extremely precise Misumi linear rails to guide movement on every axis. Currently, the nozzle is a 0.25mm revo finger-swappable nozzle that can be used with all filaments. This is a more advanced printer than the Prusa or Xinkebot, but don't worry, it's actually fairly easy to operate. It runs using RepRap firmware on a Duet Ethernet board.

Details about the using the Duet can be [found here](https://duet3d.dozuki.com/Wiki/Duet_Web_Control_Manual).

Most of this is extra background information. Homing and leveling are taken care of in the slicer (Simplify3D) beginning scripts so you should not need to do any preparation work. You should not need to do any calibration such as Bed Mesh creation or any other advanced operations. The bed should be level and very flat as is.

*Beginning Steps:*

1. Clean the bed with Windex and a paper towel. If there is filament stuck to the bed, peel it off with your fingernail. If it's stuck, use a plastic razor blade. DO NOT use a metal blade on the RailCore!
2. Turn on the RailCore using the switch at the bottom rear of the electronics box on the right side of the printer.
3. Watch the readout on the LED panel above the electronics box for the assigned IP address. If you forget it, you can always press the "console" button at the bottom of the screen. Note that you will get a warning about the heater being overpowered. It's OK to ignore that. It will go away.
4. Using any computer on the Ithaca Generator wifi, type the IP address in any browser such as Chrome or Firefox. You should see the "Duet Web Control" interface.

*Load Your Filament:*

1. Be sure your filament is dry. If needed, dry your filament overnight in the filament dryer at IG.
2. Snip the end of your filament at an angle with scissors.
3. Feed your filament through the white tube until it gets all the way to the extruder. Note: if someone left filament in the printer, see "When your print is done" below.
4. Rotate the thumbwheel on the extruder (it's a white plastic gear) until the filament will no longer advance.
5. Using the Duet Web Control or the LCD Panel on the printer, heat the extruder to 220 degrees.
6. Rotate the thubmwheel on the extruder until your filament color is clearly seen.

*Upload your gcode:*

1. Click on the "Jobs" tab on the left.
2. Mount SD card 1 by choosing it from the green popup menu.
3. Click the dark blue "Upload G-code File(s)" button and upload your file. DO NOT do anything else until the upload is complete or the SD card could get corrupted.
IMPORTANT: If you did NOT use the Simplify3D slicer on our computer to create your G-code file, skip to the next section.
4. Click on your file in the list and click "Yes" when the prompt asks.
5. The printer will now go through a homing and leveling routine (if you used the Simplify3D slicer on our computer) and print your file.

For G-code not created with our Simplify3D profile:
Follow upload steps 1 through 3 above, then...
1. Click on the "Macros" tab on the left, choose "2 Auto Level" from the list, and run it.
2. After the machine is done, click on the "Jobs" tab on the left.
3. Click on your file in the list and click "Yes" when the prompt asks. Your file should now print.

You MUST stay for the duration of at least the first layer, longer if possible. A successful first layer is a good predictor of a successful print.

When your print is done:
Please remove your filament. The nozzle needs to reach around 100 degrees so it will take time. You can remove filament either right after the print, or when you come back later after the machine is cool. The macro described below will work either way.
1. Run the "1 Unload Filament" macro at the end of your print. You can use the Duet Web Control or the LCD panel.
2. Pull your filament out of the white tube and put your filament away. Be sure to keep it wound tight and to use the "stay" holes on the reel to keep it from unwinding.
3. Wipe the nozzle with a paper towel to remove any filament boogers. BE VERY CAREFUL NOT TO BREAK THE GREY COOLING SHROUD AROUND THE NOZZLE! If you need to lower the bed to properly wipe the nozzle, use the "3 Lower Bed" macro. 4. PLEASE remember to quit Simplify 3D if you have it open.
