# A list of resources, projects and products usefull for robot electronics
If you have additions, please open an issue or pull-request.

## Open Source Modules & Subsystem

### Motor drivers
- [ODrive](https://github.com/madcowswe/ODrive) - High performance motor control
- [VESC](https://github.com/vedderb/bldc-hardware) - Brushless DC Motor controller
- [OpenBLDC](https://open-bldc.org/wiki/Open-BLDC) - Open-BLDC stands for Open Source Brush Less DC Motor Controller.
- [HighPower-Mechaduino](https://github.com/pointhi/HighPower-Mechaduino) - Closed Loop Stepper Servo (50V@10A)
- [motor-control-board](https://github.com/cvra/motor-control-board) - CVRA DC-Motor Driver, using STM32F3, supports CAN Bus and was designed using KiCAD
- [MotCtrl](https://github.com/osannolik/MotCtrl) - A BLDC motor controller
- [OtterControl](https://github.com/NiklasFauth/ottercontrol) - OtterControl BLDC motor controller
- [stmbl](https://github.com/rene-dev/stmbl) - High-Voltage AC Servo Driver
- [RCA's µMotor](https://github.com/roboterclubaachen/micro-motor) - control any BLDC and DC motor up to 250W
- [Brushless DC motor controller board](https://danstrother.com/2011/01/12/brushless-dc-motor-controller-board/) - Dan Strother's STM32f103 based BLDC controller Board
- [Closed Loop Motor Controller](https://github.com/ottoragam/Tarocco) - Step/Dir input for CNC use. Based on PSoC4.
- [DC Servomotor Controller](http://elm-chan.org/works/smc/report_e.html) - DC-Motor driver build around an AVR.
- [STM_MotorController](https://github.com/open-rdc/STM_MotorController) - Of Robot Design and Control Lab @ CIT

### Actuators
- [Mechaduino](http://tropical-labs.com/index.php/mechaduino) - Closed Loop Stepper Servo
- [OpenTorque Actuator](https://github.com/G-Levine/OpenTorque-Actuator) - Joint for legged robots
- [3D Printed Robot Actuator](https://hackaday.io/project/157812-3d-printed-robot-actuator) - Motorcontroller + BLDC + cycloidal gearbox and position feedback
- [DirectServo](https://github.com/DizzyRobot/DirectServo) - Robotic joint controller with BLDC driver and magnetic encoder.

### RC-Servo
- [16 Channel Servo Controler](https://www.tindie.com/products/deshipu/16-channel-servo-shield-for-d1-mini-version-10/) - I²C RC-servo controller with 16 channels

### Computer Vision
- [OpenMV](https://github.com/openmv/openmv) - OpenMV, an embedded CV Module (CMOS Sensor with STM32)
- [PX4Flow](https://github.com/PX4/Hardware/tree/master/FLOWv1) - PX4Flow, Optical Flow Sensor

### Battery Management ###
- [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) - DieBieMS (3-12S LiIon-based, 100A)
- [LibreSolar Project](https://github.com/LibreSolar) - with different sized BMS [BMS Li-Ion 5S](https://github.com/LibreSolar/BMS-5s), [BMS Li-Ion 48V](https://github.com/LibreSolar/BMS48V)
- [Ceech's BMS](https://github.com/ceech/BQ76920-BMS) - Arduino-based 5S BMS (BQ76920)
- [Battman BMS](https://github.com/raphaelchang/battman-hardware) - Li-Ion BMS (LTC6803)

### FPGA based
- [LOA](https://github.com/loa-org) - Loa is a framework designed to build specialized IO subsystems.
- [Snickerdoodle](http://krtkl.com/) - Snickerdoodle is a Zynq based System-on-Module
- [Logi-Bone](http://valentfx.com/logi-bone/) - FPGA & Beaglebone, also [some VHDL modules](https://github.com/fpga-logi/logi-hard) relevant to robotics available

### Bus Systems
- [UAVCAN](http://uavcan.org/) - Protocol on top of CAN Bus, suited for robotics and aerospace control applications
- [UC4H: UAVCAN for Hobbyists](http://www.olliw.eu/2017/uavcan-for-hobbyists/)  [(on GitHub)](https://github.com/olliw42/uavcan4hobbyists) - UAVCAN applied to a multirotor plattform.
- [SAB](https://xpcc.io/api/group__sab.html) - Sensor Actuator Bus (SAB), also in [modm.io](https://modm.io/reference/module/modm-communication-sab/)

### Sensors
- [OpenSimpleLidar](https://github.com/iliasam/OpenSimpleLidar) - Open Hardware scanning laser rangefinder
- [OSLRF-01](http://www.lightware.co.za/shop2017/download/Documents/OSLRF-01%20-%20Laser%20Rangefinder%20Manual%20-%20Rev%200.pdf) - An open source laser range sensor using time-of-flight

## Projects with open and reuseable designs

### Open Source Project
- [MORPH](https://hackaday.io/project/25730-morph-modular-open-robotics-platform-for-hackers) [on GitHub](https://github.com/roaldlemmens/morph) - Modular platform for open robotics development. Supports ROS and uses VESC.
- [Evezor](https://hackaday.io/project/20416-evezor-robotic-arm) - Evezor is an open source SCARA class robotic manufacturing platform
- [Octanis Rover](https://github.com/Octanis1/Octanis1-Electronics) - Octanis Rover Projects Electronics
- [OAP](http://oap.sourceforge.net/) - Open Automaton Project (Source Repo inactive since 2008)
- [Linorobot](https://linorobot.org/) - A suite of Open Source ROS compatible robots [GIT](https://github.com/linorobot/linorobot)
- [Bobble-Bot](https://hackaday.io/project/164992-bobble-bot) - Demo robot for real-time control using Rpi, RT Linux, and ROS.
- [StanfordDoggoProject](https://github.com/Nate711/StanfordDoggoProject) - 8-DoF quadruped robot
- [Pulurobots](https://www.pulurobotics.fi/page/github) - Open Source mobile service robot

### Robot Competitions
- [CVRA](https://github.com/cvra) - CVRA's Github repositories (Eurobot Team)
- [RCA](https://github.com/roboterclubaachen) - RCA Github repositories (Eurobot Team)
- [APBTeam](http://apbteam.org/) - A Eurobot Team with opensource robot design

### University Projects, Thesis work, etc.
- [Litter Bot](https://github.com/Nurgak/Litter-collecting-robot) - Autonomous litter collecting robot (using OpenCV, Rpi and AVR)
- [Zynq + OV7670](https://github.com/laurivosandi/hdl) - Student project using Zynq and image sensor (OV7670)
