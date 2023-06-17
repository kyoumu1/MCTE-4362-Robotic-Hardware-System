<!DOCTYPE html>
<html>
<body>

# <h1 style="color:yellow;"> Humanoid Robot</h1>

## Table of Content
- [History of Humanoid Robot](#history-of-humanoid-robot)
- [Main components of the vehicle](#main-components-of-the-vehicle)
    - [Robot Design](#robot-design)
    - [Locomotion](#locomotion)
    - [Navigation System](#navigation-system)
    - [Data Collection](#data-collection)
    - [Data Transmission](#data-transmission)
    - [Power System Management](#power-system-management)

## History of Humanoid Robot

A <b>humanoid robot</b> is a robot resembling the human body in shape. The design may be for functional purposes, such as interacting with human tools and environments, for experimental purposes, such as the study of bipedal locomotion, or for other purposes. 

<q><i>In general, humanoid robots have a torso, a head, two arms, and two legs, though some humanoid robots may replicate only part of the body, for example, from the waist up.</q></i>

<i style="color:red;">Facts!</i>
<br>Some humanoid robots also have heads designed to replicate human facial features such as eyes and mouths. Androids are humanoid robots built to aesthetically resemble humans.

### <u>History</u>

| Period |  Origin   |   Description |
|--------|----------|----------------|
| 13th Century | Middle East | Muslim engineer, <b>Ismail al-Jazari</b> designed various humanoid automata. He created a waitress robot that would dispense drinks from a liquid reservoir and appear out of an automatic door to serve them. Another automaton he created was used for hand washing to refill a basin with water after being drained. |
| 1400s | Italy | Leonardo da Vinci conceptualized a complex mechanical robot clad in a suit of armor, capable of sitting, standing, and independently moving its arms. The entire robot was operated by a system of pulleys and cables. |
|   |   |   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Leonardo-Robot3.jpg/330px-Leonardo-Robot3.jpg" width="300"> |
|17th to 19th Centuries| Japan | The Japanese built humanoid automata called <b>karakuri puppets</b>. These puppets resembled dolls and were used for entertainment in theatre, homes, and religious festivals. Karakuri puppets that were used for theater plays were called butai karakuri. Small karakuri puppets found in homes, called zashiki kurakuri, were placed on tables to dance, beat drums, or serve drinks. The puppets used in religious festivals were known as Dashi karakuri, and they served to reenact myths and legends. |
|   |   |   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/KarakuriBritishMuseum.jpg/300px-KarakuriBritishMuseum.jpg" width="300"> |
|18th Century|France|French inventor <b>Jacques de Vaucanson</b> created a significant humanoid automaton called <i>The Flute Player</i>. This wooden, human-sized robot was capable of playing various melodies with the flute. It consisted of a system of bellows, pipes, weights, and other mechanical components to simulate to the muscles necessary to play the flute|

## <b>Main components of the vehicle</b>

## Robot Design

The physical robot design of a humanoid robot encompasses the structural elements and components that enable it to embody human-like appearance and movement. Here are the key aspects of the physical robot design needed for a humanoid robot:

1. Body Structure: Humanoid robots typically have a structure consisting of a head, torso, arms, and legs. The body structure is designed to resemble the proportions and size of an average human, although variations can exist based on specific applications.

2. Skeleton: The robot's skeleton provides the framework for supporting the body and allowing movement. It is usually made of lightweight and sturdy materials such as aluminum or carbon fiber composites. The skeleton incorporates joints and linkages that mimic the human skeletal system, enabling a wide range of motion.

3. Joints and Actuators: Humanoid robots have joints at various locations, such as the neck, shoulders, elbows, wrists, hips, knees, and ankles. These joints allow the robot to bend, rotate, and move its limbs in a manner similar to humans. Actuators, such as electric motors or hydraulic/pneumatic systems, are used to drive these joints and provide the necessary force for movement.

4. Limbs and Hands: Humanoid robots possess arms and hands with multiple degrees of freedom. The arms are designed to reach, grasp, and manipulate objects with dexterity, while the hands may have fingers or grippers to interact with the environment. The fingers are often equipped with sensors for precise control and tactile feedback.

5. Locomotion Mechanism: Humanoid robots are designed to walk and balance on two legs, mimicking human locomotion. The legs consist of joints and linkages, similar to the skeletal structure, allowing for smooth and coordinated walking or running. Some humanoid robots may also have the ability to crawl, climb stairs, or even use wheels for additional mobility.

6. Sensory Systems: Humanoid robots are equipped with various sensors to perceive the environment. These sensors include cameras for vision, microphones for audio input, and touch sensors for detecting contact and pressure. Other sensors like accelerometers, gyroscopes, and force sensors may also be used to provide feedback on the robot's motion and external forces.

7. Power and Energy Management: Humanoid robots require a power source to operate their actuators, sensors, and computational systems. This can be achieved using batteries, external power supplies, or a combination of both. Efficient power management systems are necessary to optimize energy usage and ensure the robot can operate for extended periods.

8. Outer Covering and Aesthetics: Humanoid robots may have an outer covering made of materials such as plastic, rubber, or synthetic skin to enhance their appearance and provide protection for the internal components. Synthetic skin, often made of soft and flexible materials, can contribute to a more human-like tactile experience and natural interaction.

9. Weight and Balance: Consideration of weight distribution and balance is crucial in humanoid robot design to ensure stability and prevent toppling during movement. The placement of heavier components, such as batteries or actuators, is carefully balanced to maintain the robot's stability.

10. Safety Measures: Humanoid robots incorporate safety features to prevent accidents and ensure user safety. These can include emergency stop buttons, torque sensors to detect excessive forces, and collision detection and avoidance systems to prevent collisions with objects or humans.

## Locomotion

Humanoid robots employ various locomotion systems to enable movement and navigate their environment. Here are some common locomotion systems used in humanoid robots, along with examples for each:

1. Bipedal Walking: Bipedal walking is the most common form of locomotion for humanoid robots, where the robot walks on two legs, similar to humans. The robot's legs are designed with joints and actuators that allow it to imitate human walking patterns. One example of bipedal walking is the ASIMO robot developed by Honda. ASIMO uses advanced control algorithms and precise motor control to achieve stable walking on different surfaces and terrains.

    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Honda_ASIMO_%28ver._2011%29_2011_Tokyo_Motor_Show.jpg/1200px-Honda_ASIMO_%28ver._2011%29_2011_Tokyo_Motor_Show.jpg" width="300">

2. Wheeled Locomotion: Some humanoid robots incorporate wheeled locomotion systems to enhance mobility on flat surfaces. These robots typically have legs that can transform into wheels, enabling faster movement across even and smooth terrains. For instance, the Segway Robot Loomo combines a humanoid upper body with a wheeled base, providing both humanoid interaction capabilities and efficient wheeled locomotion.

    <img src="https://m.media-amazon.com/images/I/61IyBHTrxlL._AC_UF1000,1000_QL80_.jpg" width="300">

3. Climbing and Crawling: Certain humanoid robots are designed to climb or crawl, allowing them to navigate uneven surfaces or reach areas inaccessible to wheeled or walking robots. These robots often possess limbs with grippers or specialized appendages for grasping and maneuvering in various environments. An example is the RHex robot developed by Boston Dynamics, which uses legged locomotion to traverse rough terrains, including climbing stairs and scaling obstacles.

    <img src="https://www.robotpark.com/academy/wp-content/uploads/2013/01/RHex-Rough-Terrain-Robot.jpg" width="300">

4. Stair Climbing: Humanoid robots with the ability to climb stairs can navigate multi-level environments more effectively. These robots have specialized leg mechanisms and control algorithms to handle the unique challenges posed by stairs. One notable example is the HRP-2 robot developed by AIST in Japan. HRP-2 can autonomously climb stairs by adjusting its balance, foot placement, and trajectory during each step.

    <img src="https://d.ibtimes.co.uk/en/full/1442412/hrp-2-promet-humanoid-robot-kawada-industries.jpg" width="300">

5. Wheel-Leg Hybrid: Some humanoid robots combine the benefits of both wheeled and legged locomotion by incorporating a hybrid system. These robots have wheels for faster movement on even surfaces and legs for traversing more complex terrains. The ANYmal robot developed by ANYbotics is an example of a hybrid locomotion system. It has four legs equipped with wheels, allowing it to move efficiently on flat surfaces and transition to legged walking when encountering obstacles or challenging terrains.

    <img src="https://spectrum.ieee.org/media-library/image.jpg?id=28159639" width="300">

6. Flying: While not strictly limited to humanoid robots, some robots integrate flying capabilities to navigate environments that are otherwise challenging or inaccessible for ground-based locomotion. These robots, often referred to as aerial humanoid robots, combine humanoid features with drones or flying mechanisms. An example is the DALER (Deployable Air-Land Exploration Robot) developed by the Laboratory of Intelligent Systems. It can walk and fly using wings that can be folded or extended based on the locomotion requirements.

    <img src="https://i.ytimg.com/vi/MZhtJ0GGnOg/maxresdefault.jpg" width="300">

These locomotion systems highlight the versatility of humanoid robots, enabling them to adapt to various environments and perform a wide range of tasks. The choice of locomotion system depends on the specific application and the challenges the robot needs to overcome.

## Navigation System

| Robot | Developer | Description |
|-------|----|--------|
|PEPPER|SoftBank Robotics|Utilizes a combination of perception sensors and navigation techniques. It uses <b>stereo cameras and depth sensors</b> to perceive the environment and create a 3D map. Pepper employs a Simultaneous Localization and Mapping (SLAM) algorithm called FastSLAM to estimate its own position in real-time. For navigation, Pepper incorporates a hybrid path planning approach that combines a grid-based representation for global path planning and a potential field method for local obstacle avoidance. This allows Pepper to navigate autonomously, avoiding obstacles and optimizing its path.|
|   |   |<img src="https://images.wsj.net/im-367980/square" width="300">
|ATLAS|Boston Dynamics|Employs advanced navigation systems for dynamic movement and agility. It uses <b>stereo cameras, LIDAR sensors, and inertial measurement units (IMUs)</b> for perception and environment mapping. Atlas utilizes a state-of-the-art version of SLAM called Incremental Mapper Localization and Planning (IMLP) to build a map of the environment and localize itself accurately. For path planning and navigation, Atlas incorporates model predictive control (MPC) algorithms that generate dynamically feasible trajectories while considering terrain, obstacles, and stability constraints. This enables Atlas to perform complex locomotion tasks and navigate challenging terrains with high adaptability and stability.|
|NAO|SoftBank Robotics|Employs a combination of perception sensors and navigation techniques. It uses <b>cameras, sonar sensors, and touch sensors</b> for environment perception. NAO incorporates a localization method called particle filter localization, which uses landmarks detected from the environment to estimate its own position. For navigation, NAO utilizes a graph-based path planning algorithm that generates collision-free paths based on the connectivity of the environment. NAO's navigation system allows it to avoid obstacles, walk smoothly, and perform tasks in various indoor environments.
|   |   |<img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Nao_Robot_%28Robocup_2016%29.jpg" width="300">|
|ASIMO|Honda|Integrates advanced navigation systems for autonomous walking and stair climbing. It uses <b>cameras, depth sensors, and floor surface sensors</b> for environment perception. ASIMO incorporates a hybrid localization approach that combines visual odometry, which estimates the robot's position using visual information, and a pre-built map of the environment. For navigation, ASIMO employs a sophisticated trajectory generation algorithm that takes into account the terrain, obstacles, and stability requirements. ASIMO's navigation system enables it to walk, run, turn smoothly, and even climb stairs autonomously.|
|TALOS|PAL Robotics|Incorporates a robust navigation system for versatile humanoid locomotion. It uses a combination of <b>perception sensors, including cameras, depth sensors, and laser scanners</b>, for environment perception and mapping. TALOS employs state-of-the-art SLAM techniques, such as OctoMap, for accurate 3D mapping and localization. For navigation, TALOS integrates a motion planning algorithm based on Rapidly Exploring Random Trees (RRT) that generates dynamically feasible and collision-free paths. TALOS also incorporates real-time reactive control strategies to adjust its movements and avoid obstacles during navigation.|
|   |   |<img src="https://i.ytimg.com/vi/xUeApfMAKAE/mqdefault.jpg" width="300">|

## Data Collection

The data collection system in humanoid robots refers to the sensors and mechanisms used to gather information from the environment and the robot's own body. These sensors enable the robot to perceive and understand its surroundings, detect objects, measure physical quantities, and obtain feedback about its own state. Here are some commonly used sensors in humanoid robots:

1. Cameras: Cameras, such as RGB cameras or depth cameras (e.g., stereo or time-of-flight cameras), are essential for visual perception. They capture images or depth information, allowing the robot to recognize objects, navigate, and interact with the environment. Examples include RGB cameras used for color perception and object recognition, and depth cameras used for 3D mapping and obstacle detection.

2. Inertial Measurement Units (IMUs): IMUs consist of accelerometers, gyroscopes, and sometimes magnetometers. They measure the robot's linear acceleration, angular velocity, and orientation in space. IMUs provide information about the robot's motion, stability, and orientation, enabling balance control, gait generation, and gesture recognition.

3. Force/Torque Sensors: Force/torque sensors measure the forces and torques exerted on the robot's limbs or end-effectors during interactions with the environment or objects. These sensors provide feedback on contact forces, allowing the robot to grasp objects with appropriate force, detect collisions, and ensure safe interactions.

4. Tactile Sensors: Tactile sensors are used to measure pressure, touch, or deformation at various points on the robot's body or fingers. These sensors enable the robot to perceive and react to tactile stimuli, facilitating object manipulation, grasping, and fine motor control. Tactile sensors can be based on different technologies, including resistive, capacitive, or optical sensing.

5. Range Sensors: Range sensors, such as laser scanners or ultrasonic sensors, provide distance measurements to detect obstacles, create maps, and estimate the robot's surroundings. Laser scanners use laser beams to measure distances accurately, while ultrasonic sensors emit sound waves and measure their reflections for proximity sensing.

6. Proximity Sensors: Proximity sensors detect the presence or proximity of objects without direct contact. They are often used for obstacle detection, collision avoidance, and robot-human interaction. Examples include infrared proximity sensors, capacitive proximity sensors, or time-of-flight sensors.

7. Joint Encoders: Joint encoders are used to measure the position, velocity, and sometimes the torque applied to the robot's joints. They provide feedback on joint angles and enable accurate control of the robot's movements, joint coordination, and position control.

8. Microphones: Microphones capture audio signals and enable sound localization, speech recognition, and audio interaction with humans. They play a vital role in humanoid robots that need to respond to voice commands, communicate verbally, or perceive environmental sounds.

These are just a few examples of sensors commonly used in humanoid robots. Depending on the specific robot's capabilities and tasks, additional sensors such as gas sensors, temperature sensors, or even specialized sensors for specific applications (e.g., medical sensors) may also be integrated into the data collection system. The combination of these sensors enables humanoid robots to perceive, interpret, and interact with the environment in a manner that resembles human sensory capabilities.

## Data Transmission

The data transmission system in humanoid robots involves the mechanisms and technologies used to transmit data from sensors to the robot's central processing unit or control system. It ensures reliable and efficient communication between sensors and the robot's computational resources. Here are some common components and examples of data transmission systems used in humanoid robots:

### <i>Cabling and Wiring</i>
In many humanoid robots, especially those with a wired setup, data transmission occurs through physical cables and wiring. High-speed data cables, such as <b>Ethernet or USB cables</b>, are commonly used to connect sensors and actuators to the robot's control unit. These cables ensure fast and reliable transmission of sensor data.

### <i>Fieldbus Systems</i>
Fieldbus systems provide a standardized communication protocol for industrial automation and robotics. They allow multiple devices, including sensors and actuators, to be connected on a single network, facilitating efficient data transmission. Examples of fieldbus systems used in humanoid robots include <b>CAN (Controller Area Network)</b>, <b>EtherCAT (Ethernet for Control Automation Technology)</b>, and <b>Profibus.</b>

### <i>Wireless Communication</i>
Wireless communication methods are becoming increasingly popular in humanoid robots, enabling greater mobility and flexibility. These methods include <b>Wi-Fi, Bluetooth, or Zigbee</b>, among others. These wireless technologies allow sensors to transmit data to the robot's control system without the need for physical cables. The choice of wireless communication technology depends on factors such as data transfer speed, range, and power consumption requirements.

### <i>Data Acquisition Boards</i>
Data acquisition boards or modules are commonly used in humanoid robots to interface with sensors and convert analog sensor signals into digital data. These boards typically include <b>analog-to-digital converters (ADCs)</b> and provide a means to transmit the digitized sensor data to the robot's central processing unit. Companies such as National Instruments, Advantech, and Measurement Computing offer data acquisition solutions used in humanoid robotics applications.

### <i>Sensor-Specific Communication</i>
Some sensors may have their own proprietary communication protocols or interfaces. Manufacturers often provide <b>software development kits (SDKs)</b> or libraries that enable seamless integration and data transmission between the sensors and the robot's control system. For example, Intel RealSense cameras have their own SDKs for integrating depth sensing and computer vision capabilities into humanoid robots.

### <i>Custom Communication Protocols</i>
In certain cases, humanoid robots may utilize <b>custom communication protocols or interfaces</b> specific to the robot's manufacturer or research institution. These protocols are often designed to optimize data transmission for the specific requirements of the robot's sensor suite. For instance, companies like SoftBank Robotics, Boston Dynamics, PAL Robotics, and Honda (ASIMO) may employ custom communication protocols tailored to their respective humanoid robot platforms.

## Power System Management

1. Pepper: Pepper, developed by SoftBank Robotics, incorporates a power system management that involves a rechargeable battery as its power source. The battery is typically a high-capacity lithium-ion battery that provides DC power to the robot's electrical system. Pepper's power management system includes power conversion modules, such as DC-DC converters and voltage regulators, to ensure proper voltage levels for different subsystems. Power distribution is achieved through a combination of power distribution boards and cables, routing power to motors, sensors, and the central processing unit. Pepper also includes power monitoring mechanisms to track power consumption and optimize power usage for extended operation.

2. Atlas: Atlas, developed by Boston Dynamics, utilizes a power system management architecture that combines onboard batteries with a tethered power supply. The robot's primary power source is a set of high-capacity lithium-ion batteries located within its body. These batteries deliver power to the robot's electrical system and are managed through power conversion modules for voltage regulation. Atlas also features a tethered power supply that provides additional power when required. The power distribution network within Atlas routes power to its various subsystems, including the motors, sensors, and onboard computational units. The power management system in Atlas incorporates monitoring capabilities to optimize power consumption and ensure efficient operation.

3. NAO: NAO, developed by SoftBank Robotics, utilizes a rechargeable battery as its primary power source. The battery, typically a lithium-ion battery, provides DC power to the robot's electrical system. NAO's power system management involves power conversion modules, such as DC-DC converters and voltage regulators, to adjust and regulate the power supply for different components. Power distribution within NAO is achieved through power distribution boards and cables that deliver power to the robot's motors, sensors, and processors. The power management system in NAO includes monitoring capabilities to track power usage and optimize power distribution, ensuring efficient operation and extended battery life.

4. ASIMO: ASIMO, developed by Honda, incorporates a power system management architecture that relies on a combination of rechargeable batteries and an external power supply. ASIMO's primary power source is a set of high-capacity lithium-ion batteries located within its body. These batteries supply power to the robot's electrical system. ASIMO also features an external power supply that can be used for extended operation or recharging the internal batteries. The power management system in ASIMO includes power conversion modules to regulate voltages and power distribution networks to route power to various subsystems. ASIMO's power system management incorporates monitoring mechanisms to optimize power consumption and ensure reliable operation.

5. TALOS: TALOS, developed by PAL Robotics, utilizes a power system management architecture that incorporates a high-capacity lithium-ion battery as its primary power source. The battery supplies DC power to TALOS' electrical system, including motors, sensors, and onboard computers. TALOS employs power conversion modules such as DC-DC converters and voltage regulators to ensure proper voltage levels for different subsystems. Power distribution within TALOS is achieved through power distribution boards and cables that route power to the robot's components. The power management system in TALOS includes monitoring capabilities to track power usage, optimize power distribution, and ensure efficient operation.

It's important to note that the specific power system management in humanoid robots can vary depending on the robot's design, requirements, and the technologies employed. These examples highlight some general aspects of power system management in humanoid robots and the use of rechargeable batteries, power conversion modules, and power distribution networks to efficiently manage power supply to different subsystems.