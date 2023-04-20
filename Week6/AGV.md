<!DOCTYPE html>
<html>
<body>

# <h1 style="color:yellow;"> Automated Guided Vehicle (AGV) and Autonomous Mobile Robot (AMR)</h1>

## Table of Content
- [History of AGV and AMR](#history-of-agv-and-amr)
- [Main components of the vehicle](#main-components-of-the-vehicle)
    - [Robot Design](#robot-design)
    - [Propulsion](#propulsion)
    - [Navigation System](#navigation-system)
    - [Data Collection](#data-collection)
    - [Data Transmission](#data-transmission)
    - [Power System Management](#power-system-management)

## History of AGV and AMR

An <i style="color:red;">automated guided vehicle</i> (AGV) is a portable robot that navigates through physical assists or guided such as follows along marked long lines or wires on the floor, use radio waves, vision cameras, magnets, or lasers for navigation.

- The first AGV was brought to the market in the 1950s by Barrett Electronics of Northbrook, Illinois - simply a tow truck that followed a wire in the floor.

An <i style="color:red;">autonomous mobile robot</i> (AMR) is a type of robot that can understand and move through its environment independently. AMRs differ from their predecessors, AGVs, which rely on tracks or predefined paths and often require operator oversight.

- Although first AGV was brought to the market in the 1950s, the first development of AMR were started in the late 1940s, where William Grey Walter sucessfully made two prototypes, Elmer and Elsie - robots were used in his research for neurophysiology advancement.

## <b>Main components of the vehicle</b>

## Robot Design

| Type | Description | Example |
|------|-------------|----------|
| Automated Guided Carts | Most basic type of AGV with minimal features; they can transport a variety of materials, from small parts to loaded pallets, and are often used in sorting, storage, and cross-docking applications | <img src="https://www.bastiansolutions.com/assets/1/6/M4A_Mouse_AGV_towing_cart_1.jpg" width="500"> |
| Forklift AGVs | Forklift automated guided vehicles; designed to perform the same functions as a human-operated forklift performs - transporting pallets, but without the need for a human operator | <img src="https://www.bogaertsgl.com/images/ProductImages/Slideshows/Qii-Pal/QP0.png" width="500"> |
| Towing AGVs | Towing vehicles - pull one or more non-powered, load-carrying vehicles behind them in a train-like formation; used for transporting heavy loads over longer distance | <img src="https://www.iqsdirectory.com/articles/automated-guided-vehicle/automated-guided-vehicle/towing-agv.jpg" width="500"> |
| Heavy Burden Carriers | For the heaviest loads, this type of AGV used in applications of large assembly, casting and coil and plate transport; some of it have self-loading capabilities  and may have standard, pivot or omni-directional steering | <img src="https://i.ytimg.com/vi/nzWhnaCIDYM/maxresdefault.jpg" width="500"> |

## Propulsion

Locomotion is the ability of automated guided vehicles to propel themselves from one point to another. The mode of locomotion can be divided into several sections:

### <b style="color:blue;">Wheeled AGVs</b>

1. <u>Standard  Wheel</u>

    A standard wheel offers two degrees of freedom; rotation around the wheel axle and around the contact point. The axis of rotation around the contact point passes through the center of the wheel, usually along the plane of the wheel.

    <img src="https://www.iqsdirectory.com/articles/automated-guided-vehicle/automated-guided-vehicle/standard-wheel.jpg" width="350">

2. <u>Caster Wheel</u>

    Offers two degrees of freedom; one is rotation around the wheel axis, while the other is around an offset from the center of the wheel. Caster wheels are generally used to provide supoort fot the chassis.

3. <u>Mecanumm Wheel</u>

    Referred as Swedish wheels - has three degrees of freedom; rotation around the wheel axis, rotation around the rollers, and rotation around the contact point. A Mechanumm wheel has rollers along the circumference of the main wheel arranged at 45 angles.

    <img src="https://www.iqsdirectory.com/articles/automated-guided-vehicle/automated-guided-vehicle/mecanum-wheel.jpg" width="350">

### <b style="color:blue;">Legged AGVs</b>

- This AGVs developed to take advantage of its high maneuverability in irregular terrain. It can cross gaps or holes as long as the reach of its legs exceeds the width of the gap.
- However, it is less often used in industrial applocations due to limitations in load-carrying capacity and the mechanical complexity of the leg assembly.
- A leg is composed of several links and joints that typically require independent drivers.

### <b style="color:blue;">Aerial AGVs</b>

Aerial automated guided vehicles can be categorized into two:

1. Lighter Than Air (LTA)

    Balloons and blimps - Balloons are limited to elevation control, while blimps have propellers to move laterally

2. Heavier Than Air (HTA)

    Gliders, planes, and rotorcraft - Gliders and planes rely on wings and airfoils and their dynamic reaction with air. Rotorcrafts generate lift and lateral movement using rotary blades or propellers

### <b style="color:blue;">Submersible/Aquatic AGVs</b>

- Submersible automated guided vehicles, also known as autonomous underwater vehicles (AUV), can be likened to blimps that float using buoyant force and propel laterally using rotor blades. They are used in scientific and industrial applications such as seafloor mapping, environmental monitoring, and pipeline and cable inspections.

## Navigation System

- <b>Magnetic guide tape</b> - AGVs have magnetic sensor that will detect and follow a track using magnetic tape.
- <b>Wired navigation</b> - AGVs follow wire paths embedded into the facility floor. The wire transmits a signal that AGVs detect via an antenna or sensor.
- <b>Laser target navigation</b> - Reflective tape is mounted on objects such as walls, fixed machines and poles. AGVs are equipped with a laser transmitter and receiver. The lasers reflect off of the tape within the line of sight and used to calculate the object's angle and distance from the AGV.
- <b>Inertial (gyroscopic) navigation</b> - Controlled by a computer system with the aid of transponders embedded into the facility floor to verify that the AGV is on the proper course.
- <b>Vision guidance</b> - No modification is required to the infrastructure for vision-guided AGVs. Cameras record the features along the route, and AGVs rely on these recorded features to navigate.

## Data Collection

| Function | Type of Sensor | Application |
|---------|-----------------|-------------|
| Safety Sensors | Safe 2D LiDAR, Bumper, Encoder | Safe personnel detection; Vehicle stoppage if contact; Vehicle speed and steering detection |
| Environment Perception | 2D & 3D LiDAR, Ultrasonic, Camera, Radar | Avoid impacts with objects |
| Load Handling | Cameras, 2D & 3D LiDAR, Ultrasonic | Pallet pocket detection |
|   | Optical distance sensors or Wire draw encoders | Fork Height Sensors |
|   | Photocells, Ultrasonic, inductive | Ensure the right load positioning |
| Identification | RFID, Laser or Image based bar code scanners | Transported material identification |

## Data Transmission

- An optical data transmission system consists of an optically aligned pair of devices (transmitter/receiver) that can communicate bidirectionally over various distances. Using infrared light, these optical couplers provide reliable wireless communication between a fixed station and a vehicle. 

- Optical data transmission systems are ideal for replacing complex cabling, slip rings and other transmission methods. These devices offer data transfer options via Ethernet, serially or in 4, 8, and 16-bit parallel modes.

Sources: https://hokuyo-usa.com/resources/blog/how-optical-data-transmission-helping-agvs-become-more-efficient

Hokuyo offers top devices that help AGVs perform efficiently:

1. <b>BWF Series</b>

    This series suits long-distance wireless transmission and uses infrared rays for improved communication speed. As AGVs require non-contact bi-directional communication, these devices can reliably transmit data between the vehicle and the control unit. Since they transfer data using modulated light, these transceivers are immune to physical damage. Unlike radio systems, they also don’t require recalibration.

2. <b>CWF/EWF Series</b>

    This series of devices is pretty compact, lightweight, and economical. They are suitable for data transmission over mid-range distances. They offer full duplex two-way transmission with FSK modulation.

3. <b>DMS Series</b>

    This series of devices offer parallel I/O data transmission within short distances. They use pulse-modulated beams for sending 4 or 8-bit signals wirelessly. They can indicate the destination of AGVs by interlocking with carrier robots. These devices link the AGV with the fixed docking station wirelessly.

4. <b>DMG Series</b>

    This series of devices come with a built-in data-logging feature to capture and record signals between the AMHS (Automated Material Handling Systems) and the semiconductor process equipment. This stored information helps locate and resolve any signal glitches or anomalies. Besides, this data can be accessed using a PC connection; for analysis, exclusive application software exists.

5. <b>DMJ Series</b>

    The DMJ series of optical transceivers offer greater flexibility as they can capture and record signals in expanded non-volatile memory. They help extend parallel I/O communications between the active and passive equipment.

6. <b>Optical Remote Controls</b>

    These devices are the top choice for simple data transmission operations. They can transmit data up to a distance of 10 meters between an operator and a machine. It also offers communication flexibility between a single transmitter and multiple receiver units. The device improves the system's efficiency by reducing the number of spare transmitters required.

## Power System Management

### <u>Wiferion Wireless Charging AGV and Power Supplies</u>
[![Wiferion Wireless Charging AGV and Power Supplies](https://img.youtube.com/vi/x7Z7VS0IHIk/maxresdefault.jpg)](https://www.youtube.com/watch?v=x7Z7VS0IHIk)

- Batteries for industrial trucks, mobile robots and autonomous vehicles have very special requirements in terms of performance, lifespan and charging cycles, which is why high-quality <b>lithium-ion batteries</b> are important to avoid unnecessary costs.

- Advantages of lithium-ion battery:

    - Higher efficiency, a much higher energy density and a longer life cycle
    - Less maintenance than lead acid batteries

### <b>etaSTORE LFP (Lithium iron phosphate) - Ideal for continuous use</b>

<img src="https://www.wiferion.com/wp-content/uploads/etastore_lfp_typb_2020_battery_li-ion.png.webp" width="250">

| Capacity (nominal) | 21Ah |
|---------------|-----------|
| Voltage nominal | 25,6 V |
| Charge rate (C-rate) | bis zu 2C |
| Cycles | <7500 |
| Charge current | 42A |
| Number of batteries per system | max. 20 |
| Communication system | CAN-BUS |
| IP-Protection | IP54 |
| Size (W x H x D) | 13,2cm x 18cm x 19,5cm |

- Modular, connectable in series and with an integrated BMS. With a high charging rate of up to 2C, etaSTORE LFP can be charged from 0-100% in the fastest case in around 30 minutes .

### <b>etaSTORE LTO (Lithium Titanate) - Ideal for high charging currents & many charge cycles per day</b>

<img src="https://www.wiferion.com/wp-content/uploads/etastore_lto_web.png.webp" width="250">

| Capacity (nominal) | 22Ah |
|---------------|-----------|
| Voltage nominal | 25,3 V |
| Charge rate (C-rate) | bis zu 5C |
| Cycles | <17000 |
| Charge current | 125A |
| Number of batteries per system | max. 2 |
| Communication system | CAN-BUS |
| IP-Protection | IP53 |
| Size (W x H x D) | 19cm x 16,8cm x 25cm |

- Modular, connectable in series and with an integrated BMS. With a high rate of up to 5C, etaSTORE LTO (Lithium-titanate) can be charged from 0-100% in around 12 minutes with high power and cycle life .

</body>
</html>