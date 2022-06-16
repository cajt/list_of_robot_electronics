# A list of resources, projects and products useful for robot electronics
If you have additions, please open an issue or pull request.

## Open Source Modules & Subsystem

### Motor drivers
- [VESC](https://github.com/vedderb/bldc-hardware) - Brushless DC Motor controller
- [Cheap FOCer 2](https://github.com/shamansystems/Cheap-FOCer-2) - Low-cost VESC 6-based Brushless DC Motor Controller
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
- [ODrive](https://github.com/madcowswe/ODrive) - High performance motor control (later versions /wo open HW)
- [BetzDrive](https://github.com/BetzDrive/bldc-controller-hardware) - low-speed, high torque motor applications
- [rp2040-motor-controller]([https://github.com/madcowswe/ODrive](https://github.com/Twisted-Fields/rp2040-motor-controller)) - still in devellopement, based on RP2040 chip
- [Moteus](https://github.com/mjbots/moteus) - Joint Controller and quadruped robot design
- [Dagor](https://github.com/byDagor/Dagor-Brushless-Controller) - ESP32-based brushless controller that has an on-board magnetic encoder

### Actuators
- [Mechaduino](http://tropical-labs.com/index.php/mechaduino) - Closed Loop Stepper Servo
- [OpenTorque Actuator](https://github.com/G-Levine/OpenTorque-Actuator) - Joint for legged robots
- [3D Printed Robot Actuator](https://hackaday.io/project/157812-3d-printed-robot-actuator) - Motorcontroller + BLDC + cycloidal gearbox and position feedback
- [DirectServo](https://github.com/DizzyRobot/DirectServo) - Robotic joint controller with BLDC driver and magnetic encoder.
- [Moteus](https://github.com/mjbots/moteus) - Joint Controller and quadruped robot design

### Computer Vision
- [OpenMV](https://github.com/openmv/openmv) - OpenMV, an embedded CV Module (CMOS Sensor with STM32)
- [PX4Flow](https://github.com/PX4/Hardware/tree/master/FLOWv1) - PX4Flow, Optical Flow Sensor

### Battery Management ###
- [DieBieMS](https://github.com/DieBieEngineering/DieBieMS) - DieBieMS (3-12S LiIon-based, 100A)
- [LibreSolar Project](https://github.com/LibreSolar) - with different sized BMS [BMS Li-Ion 5S](https://github.com/LibreSolar/BMS-5s), [BMS Li-Ion 48V](https://github.com/LibreSolar/BMS48V)
- [Ceech's BMS](https://github.com/ceech/BQ76920-BMS) - Arduino-based 5S BMS (BQ76920)
- [Battman BMS](https://github.com/raphaelchang/battman-hardware) - Li-Ion BMS (LTC6803)
- [ENNOID - BMS](https://github.com/EnnoidMe/ENNOID-BMS) [FW](https://github.com/EnnoidMe/ENNOID-BMS-Firmware) [GUI](https://github.com/EnnoidMe/ENNOID-BMS-Tool) - Modular BMS based on LTC68XX & STM32 MCU for up to 400V EV battery pack
- [foxBMS (Github)](https://github.com/foxBMS/foxbms) - Modular BMS (many chemistries, many cells)  [foxbms.org](https://foxbms.org/)

### FPGA based
- [LOA](https://github.com/loa-org) - Loa is a framework designed to build specialized IO subsystems.
- [Snickerdoodle](http://krtkl.com/) - Snickerdoodle is a Zynq based System-on-Module
- [Logi-Bone](http://valentfx.com/logi-bone/) - FPGA & Beaglebone, also [some VHDL modules](https://github.com/fpga-logi/logi-hard) relevant to robotics available
- [flink](https://github.com/flink-project) - Universal interface to FPGA's. Includes some IP-Cores for robotics.
- [RAPCores](http://rapcores.org/rapcores/) - RAPcores is a motor and motion control toolkit for FPGAs and ASIC devices

### Bus Systems
- [UAVCAN](http://uavcan.org/) - Protocol on top of CAN Bus, suited for robotics and aerospace control applications
- [UC4H: UAVCAN for Hobbyists](http://www.olliw.eu/2017/uavcan-for-hobbyists/)  [(on GitHub)](https://github.com/olliw42/uavcan4hobbyists) - UAVCAN applied to a multirotor plattform.
- [SAB](https://xpcc.io/api/group__sab.html) - Sensor Actuator Bus (SAB), also in [modm.io](https://modm.io/reference/module/modm-communication-sab/)
- [Simple Robot](http://www.simplerobot.net/) - RPI4 & EtherCAT
- [Lely CANopen](https://opensource.lely.com/canopen/) - Open Source CANopen Stack
- [CANopenNode](https://github.com/CANopenNode/CANopenNode) - Another Open Source CANopen Stack
- [CANopen driver framework for ROS](https://github.com/ros-industrial/ros_canopen) - CANOpen ROS bridge
- [KaCanOpen](https://kitmedical.github.io/kacanopen/) - an easy-to-use CANopen stack for ROS

### Sensors
- [OpenSimpleLidar](https://github.com/iliasam/OpenSimpleLidar) - Open Hardware scanning laser rangefinder
- [OSLRF-01](https://www.documents.lightware.co.za/OSLRF-01%20-%20Laser%20Rangefinder%20Manual%20-%20Rev%200.pdf) - An open source laser range sensor using time-of-flight

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
- [Open Dynamic Robot Initiative](https://github.com/open-dynamic-robot-initiative) - 8/12-Dof Walker, fast multi-axis force control, bldc-drivers
- [SCUTTLE](https://mxet.github.io/SCUTTLE/) - Mobile robot platform, uses RPI, OpenCV and lidar. 
- [Hoverboard + ROS](https://github.com/alex-makarov/hoverboard-driver) - Provides ROS support for modified hoverboard, to provide a differential drive plattform. Uses this [modified firmware](https://github.com/bipropellant/bipropellant-hoverboard-firmware).
- [Hello Robot](http://hello-robot.com/) - Mobile robot mit manipulation capabilities, also: [Github](https://github.com/hello-robot).

### Robot Competitions
- [CVRA](https://github.com/cvra) - CVRA's Github repositories (Eurobot Team)
- [RCA](https://github.com/roboterclubaachen) - RCA Github repositories (Eurobot Team)
- [APBTeam](http://apbteam.org/) - A Eurobot Team with opensource robot design

### University Projects, Thesis work, etc.
- [Litter Bot](https://github.com/Nurgak/Litter-collecting-robot) - Autonomous litter collecting robot (using OpenCV, Rpi and AVR)
- [Zynq + OV7670](https://github.com/laurivosandi/hdl) - Student project using Zynq and image sensor (OV7670)
