# Unmanned Aerial Vehicle (UAV)

## Table of Content
- [History of UAV](#history-of-uav)
- [Applications of UAV](#applications-of-uav)
- [Main components of the vehicle](#main-components-of-the-vehicle)
    - [Robot Design](#robot-design)
    - [Propulsion](#propulsion)
    - [Navigation System](#navigation-system)
    - [Data Collection](#data-collection)
    - [Data Transmission](#data-transmission)
    - [Power System Management](#power-system-management)

## History of UAV
- The earliest recorded use of an unmanned aerial vehicle for warfighting occured in July 1849, with a balloon carrier (the precursor to the aircraft carrier) in the first offensive use of air power in naval aviation.
- In 1903, a Spanish engineer Leonardo Torres y Quevedo introduced a radio-based control-system called the _"Telekino"_ at Paris Academy of Science.
- Significant development of drones started in the 1900s, and originally focused on providing practice targets for training military personnel.

    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/Teledyne-Ryan-Firebee-hatzerim-1.jpg/330px-Teledyne-Ryan-Firebee-hatzerim-1.jpg" width="50%">_(Ryan Firebee)_

- In 1940, the Radioplane Company (started by Denny) and more models emerged during World War II - used both to train anti aircraft gunners and to fly attack-missions.

- After World War II, development of UAV continued such as the American JB-4 (using television/radio-command guidance), the Australian GAF Jindivik and Teledyne Ryan Firebee I of 1951.

- In the 1990s, the U.S. DoD gave a contract to AAI Corporation along with Israeli company Malat. The U.S. Navy bought the AAI Pioneer UAV that AAI and Malat developed jointly.

## Main components of the vehicle

## Robot Design

Unmanned aerial vehicles can classified into different types based on their aerodynamic features.

### Multi-rotor UAV

<img src="https://edis.ifas.ufl.edu/image/Inct2t2vs9/screen" width="50%">

- Widely used for aerial photography, aerial mapping, and aerial recreational sports.
- Can be classified based on the number of rotors on the UAV: tricopter (three rotors); quadrocopter (four rotors); hexacopter (six rotors); and octocopter (eight rotors).

### Fixed-wing UAV

<img src="https://edis.ifas.ufl.edu/image/I2xcc0pg6i/screen" width="50%">

- These types of UAVs are built similarly to regular airplanes.
- They do not require a lot of energy to stay in the air because they make use of the aerodynamic lift provided by their structure.
- Due to this, they can fly for a longer time compared to the multi-rotor UAVs.

### Single-rotor UAV

- The design similar to helicopters and also the structure of it.
- Usually equipped with a large rotor on top and a small rotor on the tail to control their direction.

### Hybrid VTOL UAV

<img src="https://edis.ifas.ufl.edu/image/Iikq3rbmq5/screen" width="50%">

- This type of UAVs is a combination of the ability of the fixed-wing and multi rotor UAVs with vertical takeoff and landing capabilities.

## Propulsion

- The majority of rotary drones on the market today are fueled by electric power from lithium-ion polymer (LiPo) batteries. However there are other power sources used for the propulsion of the vehicle.

### Electric

- Solar power has also been employed as a source of electricity, with solar cells mounted on the upper surface of the drone. This concept could turn the industry on its head as it would effectively eliminate flight time limitations as long as the sun keeps shining.

  <img src="https://cdn.shopify.com/s/files/1/0033/6317/6560/files/solar-drone.png?v=1674499602" width="50%">

### Gas-Powered

- Gas-powered drones have become major sources for carrying out long-distance missions.
- Gasoline has about 50x the energy density of LiPo batteries, which lead an advantage.
- Most gas-powered drones have a fixed wing configuration since they can more easily accommodate larger engines. Their aerodynamic shape produces so much natural lift that little gas is needed to achieve flight times of many hours or even days.
- Despite all the advantages above, they can be noisy and require ignition of the motor to start. That said, some models are in development, such as the Goliath quadcopter, which uses a single gas-powered motor to power four propellers.

    <img src="https://cdn.shopify.com/s/files/1/0033/6317/6560/files/VA001_drone_600x600.jpg?v=1605560792" width="50%">

### Hydrogen and Laser-Charging

- Hydrogen fuel is a clean and energy-dense power source with a lot of potential in the drone, aviation and general transportation industries.
- South Korean company Doosan claims their DS30W drone is the "world's first mass manufactured hydrogen fuel cell drone". It is truly unique as it has a rotory-wing octocopter design, yet it can achieve 2 hours of flight time.

  <img src="https://cdn.shopify.com/s/files/1/0033/6317/6560/files/DS30W_hydrogen_powered_drone.jpg?v=1674503265" width="50%">

- Laser-charging of drones is a technology that has been on the scene since 2012. Recently, a team of researchers at Northwestern Polytechnical University in Xianyang, China demonstrated their laser-charging drone that can stay airborne indefinitely. They use an "intelligent visual tracking algorithm" to keep the laser beam targeted on the drone so it never loses power.

## Navigation System

- UAV Navigation is a leading autopilot manufacturer with extensive experience in the aerial target market. They offers product for the navigation system of UAV.

| Navigation System | Product | Description |
|-------------------|---------|-------------|
| Autopilot | Vector-400 | The VECTOR-400 is a compact autopilot designed specifically for Unmanned Aerial Targets (UAT). Its robust enclosure and military grade connector are designed to withstand the toughest environmental conditions and conform to MIL-STD 810 and MIL-STD 461 |
|   | <img src="https://i.ibb.co/Lgvpp0x/vector-400-desc.jpg"> | It has built-in physical and logical redundancy, allowing it to survive all individual sensor failures and even jamming attacks while maintaining accurate estimates of attitude and position. Advanced algorithms, such as stall protection and an automatic gliding capability, ensure flight safety in case of engine failure |
| Mission Computer Control | Vector-MCC | The VECTOR Mission Control Computer (VECTOR-MCC) is highly suitable for projects that require extensive I/O capabilities and/or custom payload management|
|   | <img src="https://i.ibb.co/zHWzr5m/VECTOR-MCC-Official2-0.jpg">  | <img src="https://i.ibb.co/n7XN4MR/VECTOR-MCC-Schemas-EN.png"> |
| AHRS-IMU | Polar-300 | The POLAR-300 is a high-end, MEMS-based Air Data and Attitude and Heading Reference System (ADAHRS) and Inertial Navigation System (INS). It is perfect for system integration in avionics packages or other attitude sensing applications, and includes: Attitude Heading & Reference System (AHRS); Inertial Measurement Unit (IMU); Inertial Navigation System (INS); Air Data System (ADS); Global Navigation Satellite System (GNSS, including: GPS, Galileo, GLONASS, BeiDou) |
|   | <img src="https://i.ibb.co/PFQTWvq/polar-300-web.jpg"> | Redundancy built into the POLAR-300 software allows it to survive individual sensor failures while maintaining accurate estimates of attitude and position. Its high-performance MEMS-based IMU is calibrated and compensated over the full industrial temperature range |
| Ground Control Station | GHU-100-Ground Hub Unit | The GHU-100 is a network hardware device for connecting multiple peripheral devices and making them act as a single network segment. The GHU-100 is compatible with all the flight control solutions provided by UAV Navigation: Target, Fixed Wing, Rotary Wing, and VTOLs. The Hub Unit has been designed to increase mission safety thanks to the implementation of safety-relevant functionalities on a self-developed RTOS |
|   | <img src="https://i.ibb.co/Bthw9kb/GHU-100-3.jpg"> | Bi-directional communications between Visionair (on the ground) and the onboard autopilot (in the air)
|   |   | Internal GNSS for GCS autonomous geolocalization. The integrated GNSS receiver has been upgraded compared to what the GCS03 featured to be more accurate and robust against jamming or spoofing |

## Data Collection

- Inertial Measurement Units (IMUs) - Information are fused together from different sensors such as gyroscopes, accelerometers and magnetometers to provide measurements that can be used to calculate orientation and velocity of the drone. Also, this data can combined with another source of information such as GPS to further increase the accuracy of calculation of the data.

  <img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2021/03/drone-sensor-300x188.jpg" width="50%"> _(PNI Sensor’s Motion and Measurement (M&M) module)_

- LiDAR Sensors - measure the reflection time of a pulsed laser beam. This can be used for navigation and collision avoidance by UAVs, as well as for mapping and other imaging applications such as agricultural and forestry surveying.
- Thermal imaging - building inspection, search and rescue, and security.
- Electro-optical (EO) sensors - operate in the visible spectrum. Hyperspectral precision agriculture drone sensors measure reflected light to provide data on the health of crops, allowing farmers to optimize application of pesticides and fertilizers and maximise crop yields.

## Data Transmission

### Halo UAV Communication System
[![Halo UAV Communication System](https://img.youtube.com/vi/uO6RJJnoLKs/maxresdefault.jpg)](https://www.youtube.com/watch?v=uO6RJJnoLKs&t=1s)

- Halo provides reliable connectivity in dynamic conditions for even the smallest drones and robots.
- The highly compact system has been designed with an extremely low power consumption and heat index, and allows you to save space and weight, fly further, and undertake challenging missions beyond the line of sight while maintaining secure communications.

  <img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2020/10/Elsight-Halo-router-300x187.png"> _(Stand-alone UAV Communication System)_

| Advantages | Description |
|------------|-------------|
| High bandwidth | Halo maximises available bandwidth by multiplexing multiple communication links into one secure network tunnel, providing the ability to seamlessly transmit large quantities of video, audio, and data.|
| Low latency | By utilizing all available cellular network infrastructure, latency is kept ultra-low, allowing near-real time data transmission for drones and robotics.|
| Cybersecure high-integrity data transmission | Malicious interception of data streams is a major threat to drones and robotic systems that transmit critical data and intelligence over standard mobile technologies.|
| Redundant capabilities for enhanced reliability | Many traditional UAV data links do not guarantee reliable and always-on connectivity, making seamless control and data transmission impossible.|
| Multilayer hybrid connectivity | Halo safeguards against system failure by utilising multiple cellular pathways, with automatic detection of malfunctions and transmission to a different channel to ensure continuous uptime.|
| Multiple system configuration options | Halo’s flexible communications capabilities allow drones and robots to be connected via multiple options, with the ability to control multiple vehicles from one control centre.|

## Power System Management

- UAVs and drones are typically powered either by an engine - which may be a two- or four-stroke internal combustion engine, a rotary engine, or a gas turbine engine - or by batteries.

- Power supplies may be designed specifically for the embedded systems utilised in UAVs and drones, and may thus be designed in various form factors such as PCI-104 and VPX 3U. Power supplies and power converter cards for embedded systems may take in a larger DC voltage such as 270V DC or 28V DC and output a much lower voltage such as 5V DC or 3.3V DC.

### Rugged & Mil-Spec Power Supplies

<img src="https://www.unmannedsystemstechnology.com/wp-content/uploads/2014/12/1PH60A-Single-Phase-AC-DC-Power-Supply-300x148.jpg">

- Power supplies for UAVs and unmanned systems may have to be engineered to withstand especially harsh environments, including extremes of temperature, shock, vibration and EMI (electromagnetic interference). These rugged power supplies may be engineered to particular military specifications and standards, such as MIL-STD-810F for shock and vibration, and MIL-STD-461E for EMI.