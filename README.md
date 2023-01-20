# eMMC-Data-Recovery

  The focus of this project is on data recovery from devices that use eMMC memory to store user data. Android smartphones often use this type of memory, and if the device becomes non-functional for some reason, data recovery can become complicated to near impossible. However, if the IC containing the user data can be removed and read independently of the main device, then user data could be recovered.
  
Interation: (Place holder for links to the iterations of attempted data recovery)

Materials and Tools:

    SD card reader to USB device
    Insulated 0.02mm copper jumper wire
    Soldering iron and solder
    Hot air rework station
    Mircoscope 

Construction of Apparatus:

1. Obtain an SD card reader to USB device.
2. Identify the lines needed for power, grounding, issuing commands, and syncing a clock on the SD card reader.
3. Solder jumpers to the identified lines on the SD card reader.
4. Label the jumpers for easy identification.


Identifying the eMMC IC on the Device:

1. Locate the eMMC IC on the motherboard of the device.
2. Remove the eMMC IC from the device.
3. Attempt to find a data sheet for the interface of the eMMC online.
4. Use the pads on the motherboard to identify the power and ground pads. Look for capacitors near the IC for filtering power.
5. Determine the data lines by studying the layout of the pads on the IC and the motherboard.
6. Identify the command and clock pads by studying the layout of the pads on the IC and the motherboard.


Connecting the Reader to the eMMC:

Use the jumpers to connect the lines from the reader to the eMMC.
Connect the reader to the eMMC by plugging it in.
Observe the reader and the eMMC to see if a connection is established.

Troubleshooting:

If the reader and the eMMC do not establish a connection, check the jumpers for proper connections.
If the reader and the eMMC establish a connection but data recovery is not successful, try different command and clock pad combinations.

Testing and Validation:

Verify that the data recovery is successful by checking the recovered data against the original data.
Verify that the apparatus and method are working correctly by repeating the process with different devices.
Safety precautions and legal considerations:

References:

https://www.blackhat.com/docs/us-17/wednesday/us-17-Etemadieh-Hacking-Hardware-With-A-$10-SD-Card-Reader-wp.pdf
http://www.interfacebus.com/Secure_Digital_Card_Pinout.html
