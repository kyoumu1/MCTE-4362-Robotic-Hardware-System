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

