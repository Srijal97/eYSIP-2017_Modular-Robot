# eYSIP-2017_Modular-Robot
A modular robot largely based of Alberto's [Dtto:Modular Robot](https://hackaday.io/project/9976-dtto-explorer-modular-robot), with modifications to expand its sensing and autonomous decision making capabilities. 

Check out the wiki for a detailed documentation!

## Project Log
* ### Week 1: 23/05/2017 to 28/05/2017
     - Did some research on existing Modular Robots and planned our approach.
     - Added report on project approach. Resources can be found here: https://goo.gl/4ZXmfM
     - Tested the components given: Servo SG90, Bluetooth Module HC05, Arduino Nano, 1s 500mAh LiPos and Sharp IR GP2Y0A21.
     - Added Wiki page 'Testing the modules involved'
     - Started learning V-Rep and Lua scripting for simulating robot motions. 
* ### Week 2: 29/05/2017 to 4/06/2017
     - Tested the VL53L0X Lased Distance Measurement sensor, which offers precise distance measurement in a tiny package.
     - Learned Lua scripting for V-REP simulations and also practiced on the V-REP environment to learn basics of it.
     - Detected Wall/Obstacle using proximity sensor and restructured modules to cross it using 4 modules snake in V-REP.
     - Added Wiki page 'V-REP Simulations'
     - Edited CAD files of modules to increase hole diameter to 2mm due to screw unavailability
     - *NOTE: Module development delayed due to screw unavailability and also lately facing problems in 3D printer*
* ### Week 3: 05/06/2017 to 11/06/2017
     - Progress presentation 1 given on 06/06/2017.
     - Interfaced RF Module NRF24L01 and servo MG90S(for the hinges).
     - First Dtto V2 module build completed! Tested crawl motion with existing program.
     - 1.5x4mm screws found, decreased hole diameter for future modules.
     - Started writing program from scratch.
* ### Week 4: 12/06/2017 to 18/06/2017
     - Dtto modules 2 and 3 completed!
     - Interfaced the VL53L0X ToF sensor on one of the female faces.
     - Robot halts when it detects and obstacle and continues when obstacle is removed
     - Concluded that motor torque of MG90S is insufficient for most transformations.
* ### Week 5: 19/06/2017 to 25/06/2017   
     - Progress demonstration on 20/06/2017
     - Added Wiki page 'Building the modules', updated previous pages with more content.
     - Uploaded Arduino code with documentation
     - Edited CAD files and printed few parts for 'Mega Dtto', a scaled up version in order to support high torque servo GOTECK GS-5515MG
     - Started exploring methods to create a virtual Dtto environment for directly programming transformations, and also as a test bench.
* ### Week 6: 25/06/2017 to 02/07/2017 
     - Module 4 completed!
     - Implemented wheel motion using 4 modules.
     - Completed Virtual Dtto for setting angles, snake motion using Python remoteApi in V-REP.
     - Created poster for project exhibition.
     - Project Exhibition on 30/06/2017
* ### Week 7: 03/07/2017 to 05/07/2017 
     - Code updated and with better documentation.
     - Created Wiki page 'Wheel Motion: 4 modules' and 'Virtual Dtto'.
     - Created Final Report for project submission.
     - Did some basic testing for the Mega Dtto module.
     
 
 
