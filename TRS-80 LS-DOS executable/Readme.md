The LS-DOS 6.3 image file is bootable and contains the CLK2/CMD file.\
Date and time prompt have been disabled by:
- system (Date=OFF)
- system (Time=OFF)

You can activate the prompts again by:
- system (Date=ON)
- system (Time=ON)
   
System time and date are set by CLK2 T, which was placed as AUTO sequence by:
- auto CLK2/CMD T

You can turn off the auto execution by typing:
- auto

When CLK2 reports that the SmartWatch is not set use:
- clk2 s 1033000901251   (Setting time and date to 10:33:00 09/01/25 Sunday)

When CLK2 reports that the SmartWatch is not found, you will have to add the SmartWatch to your system.\
A low back-up battery voltage (<2.8V) can also cause the SmartWatch not to be found.

Remember to run "CLK2 O" to turn off the RTC when not used for a longer time. Keeping the RTC running might drain the battery.
