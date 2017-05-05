Drivetek_MPPT
=============

Drivetek_MPPT This code came from Cal Sol (Berkeley CA) solar car team (https://github.com/CalSol/Impulse). We at NUsolar have copies of the v3.0 versions (v4.0 shown below). We plan to change the operating values in this code. It is critical to note that Cal Sol has licensed this as GPL2. Any update that is made to this code must be shared. 

According to drivetek, the compiled hex file can be uploaded to the MPPT's using a ICD2/3 or a Pickit. We plan on using a Pickit 3 to upload the code.

For questions, please contact engineering@nusolar.org or team@nusolar.org

![Drive-tek mppt Version 4](img/device.JPG)

Programming
-----------
The Drivetek MPPT's New Generation (v3) runs on a PIC 16F877A chip (http://www.microchip.com/wwwproducts/en/PIC16F877A). This is a 5V chip and can be programmed using an Microchip ICD2/3 or a PICkit3. The MCW file is the main project file and can be opened with MPLAB V8.91 (downloadable at http://www.microchip.com/development-tools/downloads-archive).

Current Status
--------------
The project has been set up for compiling on MPLAB V8.91. Next Steps:
  - Input parameters for SC6
  - Build project and upload hex file via PICkit 3
  - Test MPPTs
  - Install MPPTs on car.
