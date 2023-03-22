# Remotely Operated Vehicle (ROV)

## Table of Content
- [History of ROV](#history-of-rov)
- [Main components of the vehicle](#main-components-of-the-vehicle)
  - [Hull Design](#hull-design)
  - [Propulsion System](#propulsion-system)
  - [Navigation System & Controller](#navigation-system-and-controller)
  - Data Collection
  - Data Transmission
  - Power System Management

## History of ROV
A **remotely operated underwater vehicle** is tethered underwater mobile device, also called _underwater robot_.

The first ROV ever built was the _Poodle_ made in 1953 by Dimitri Rebikoff, a French pioneer in dive equipment and photography. The Poodle wan unmanned adaptation of his dive scooter with a tether and surface controls.

<img src="https://bluerobotics.com/wp-content/uploads/2019/09/poodle-rov.jpg" width="50%">

The U.S Navy started using ROVs in 1960 for recovery of underwater equipment, then by the 1980s there were more than 500 ROVs around the world, many of them being used in commercial applications.

## Main components of the vehicle
In the ROV world, the vehicles are ussualy broken into size ccategories, which also correspond with capabilities.

### Hull design

|                | Hull with Open frame | Frameless hull (close hull) |
|----------------|--------------|--------------------|
| Structure Type | <img src="https://img.nauticexpo.com/images_ne/photo-g/25353-14204891.jpg" width="45%"> | <img src="https://www.marinevision.es/images/products/saab/mil_deagle-sar-big.jpg" width="60%"> |
| | Seaeye Falcon | SAAB Double Eagle SAROV |
| Advantage | Well known structure adopted on most ROV | Greater mobility/highly manoeuvre |
| | Stable 3DOF translational motions based on large metacentre | Typically lightwewight and portable |
| | Large payloads and can carry object | More energy efficient |
| Disadvantage | These types of ROV have difficulties with motions requiring more than 3DOFs | Smaller paylaod|
| | | Not convenient for attaching tool or equipment|

### Propulsion system
The most common form of marine propulsion system for ROV is the marine thruster. Underwater thrusters are propulsion devices that combine a propeller with a hydraulic or electric motor.

#### Subsea Electric Motors
<img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2021/10/BlueROV2-T200-ROV-thrusters-300x225.png" width="30%">
Electric underwater thrusters usually use brushless DC or permanent magnet synchronous motors. These motors may be sealed within air- or oil-filled cavities, or use flooded design that allows water to come into contact with the motor, providing extra cooling and lubrication.

#### Underwater Propellers
<img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2021/10/Marine-Propulsion-Systems-300x265.jpeg" width="300">
Propellers, which convert rotation to thrust, need to be matched to the motor torque for maximum efficiency. They also need to be manufactured from a corrosion resistant material such as an aluminium-stainless steel alloy, as they will be constantly submerged in saltwater.

#### Variable-Buoyancy Propulsion
Underwater gliders use a different form of propulsion known as variable-buoyancy propulsion. This method utilises an internal bladder that can be inflated or deflated to change the density of the vehicle, making it ascend or sink as required. The glider uses hydrofoils to generate forward motion as the vehicle descends, with the result that the movement pattern of the glider resembles a sawtooth profile.

### Navigation System and Controller
#### Subsea Navigation Sensors
<img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2018/03/Syrinx-Doppler-Velocity-Log-e1585234521591-300x227.jpg" width="30%"> _Syrinx Subsea Dopller Velocity Log_

The Syrinx Doppler Velocity Log (DVL) is a 600 kHz system designed for both unmanned surface and subsurface vehicles that can be used as a standalone DVL, as part of an integrated system, or perform both functions at once. This dual capability means that only one DVL/altitude sensor is required for both ROV control and survey crews, saving on cost and payload space.

#### USBL Acoustic Technology
<img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2018/03/AUV-tracking-system-Ranger-2-USBL.webp" width="30%">
