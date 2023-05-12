<!DOCTYPE html>
<html>
<body>

# <h1 style="color:yellow;"> Swarm Robot</h1>

## Table of Content
- [History of Swarm Robot](#history-of-swarm-robot)
- [Main components of the vehicle](#main-components-of-the-vehicle)
    - [Robot Design](#robot-design)
    - [Propulsion](#propulsion)
    - [Navigation System](#navigation-system)
    - [Data Collection](#data-collection)
    - [Data Transmission](#data-transmission)
    - [Power System Management](#power-system-management)

## History of Swarm Robot

<b>Swarm robotics</b> is an approach to the coordination of multiple robots as a system which consists of large numbers mostly simple physical robots.

<i style="color:red;">Facts!</i>
<br><i>The term 'swarm' was first used in robotics by G.Beni and Fukuda in 1988. According to G.Beni, cellular robotics is composed of autonomous robots that operate in an n-dimensional cellular space without any central entity. Additionally, they coordinate and cooperate to accomplish common goals.</i>

- 1993
    - C. Ronald Kube and Hong Zohng constructed a multi-robot system inspired by the collective behaviours of natural swarms.

        <img src="https://i.ibb.co/r57CLVX/C-Ronald-Kube-and-Hong-Zhang-Collective-Robotics-From-Social-Insects-to-Robots-Q320.jpg" width="300">

    - In the same year, Gregory Dudek defined swarm robotics based on their different features, including the size, communication range, communications topology, communication bandwidth, reorganization rate, abilities of the members, an swarm homo or heterogeneity.

- 1994 
    - Stigmergy was first explored in detail in two research papers: “From local actions to global tasks: Stigmergy and collective robotics” (1994) and “Stigmergy, self-organization, and sorting in collective robotics” (1999).
    - The first study in 1994 illustrated several experiments where mobile robots collect randomly distributed objects in an environment via stigmergy. The second paper explored the feature of stigmergy and self-organization amongst robots, having the same capabilities.

- 2004 
    - G. Beni made a fresh attempt to describe a swarm more precisely. According to him, robots in a swarm are simple, identical, and self-organizing. The system must be scalable, and only local communication is available among the swarm members.

## <b>Main components of the vehicle</b>

## Robot Design

| Robot Type | Description |
|-------|-------------|
| RoboBees | <img src="https://i.natgeofe.com/n/96318e81-3015-418e-b642-117d185d822f/FingerPhotos15.jpg" width="300"> |
|   | The robot design inspired by the biology of bees. It is a small robots that can fly and communicate with one another to accomplish tasks such as pollination or search and rescue. |
| Aquatic Swarm Robots | The robot is designed to move smoothly on the surface of water or in the water. The robots are designed to work together in underwater environments, such as oil spills or coral reef research. |
|   | <img src="https://imechewebresources.blob.core.windows.net/imeche-web-content/pe-news/cocoro_project-main.jpg?sfvrsn=c94f812_2" width="300"> |
|   | <img src="https://assets.newatlas.com/dims4/default/635ee3d/2147483647/strip/true/crop/3408x2272+0+0/resize/2880x1920!/quality/90/?url=http%3A%2F%2Fnewatlas-brightspot.s3.amazonaws.com%2Fe7%2Fea%2Fef5200cd434fa98af9bac7d9dc7b%2Fbluebot-led.jpeg" width="300"> |
| Swarm of Drones | Although the robot's design is quite similar to that of unmanned aerial vehicles (UAVs), UAVs may perform multiple tasks while the robot's system is more focused on a single goal. |
|   | <img src="https://cdn.nextgov.com/media/img/cd/2022/01/25/swarm_of_drones_flying_in_the_sky_picture_id638714614/860x394.jpg" width="300"> |
| Swarm of Ant Robots | Ant robots are small, wheeled robots that can work together to move large objects or perform complex tasks. They use pheromone communication to coordinate their movements and assign roles within the swarm. |
|   | <img src="https://spectrum.ieee.org/media-library/epfls-jumping-robots-called-tribots-can-be-built-on-a-flat-sheet-and-then-folded-into-a-tripod-shape-origami-style.jpg?id=25589191" width="300"> |
|   | <img src="https://assets.newatlas.com/dims4/default/5583887/2147483647/strip/true/crop/843x562+0+0/resize/1200x800!/quality/90/?url=http%3A%2F%2Fnewatlas-brightspot.s3.amazonaws.com%2Fdb%2F96%2Fa00cc351466dabc3ed042abdfae2%2Ffig1-1-feature.jpeg" width="300"> |

## Propulsion

Swarm robots can use a variety of propulsion and locomotion methods depending on their design, environment, and task requirements. Here are some of the common methods used for propulsion and locomotion in swarm robots:

1. <b>Wheeled locomotion</b>: This is one of the most common methods used in swarm robots. The robots use wheels to move along the ground. This method is effective in flat and even terrain but may be limited in rough terrain.

    <img src="https://wevolver-project-images.s3.amazonaws.com/0.aif6epv23np20190216_200241%20-%20Matt%20N.jpg" width="300"> <i>The Swarm Robotic Platform MONA</i>

2. <b>Legged locomotion</b>: Some swarm robots use legs for movement, which allows them to navigate over uneven terrain and obstacles. This method is useful in outdoor environments where the ground is uneven and rough.

    <img src="https://bigthink.com/wp-content/uploads/2021/10/Swarm2.png?w=820&h=492&crop=1" width="300"> <i>Centipede-like Robot</i>

3. <b>Flying locomotion</b>: Swarm robots can use small rotors or wings to fly through the air. This method is useful in environments where there are obstacles or difficult terrain to navigate on the ground.

    <img src="https://robohub.org/wp-content/uploads/2019/11/Delft1.png" width="300"> <i>Micro Aerial Vehicle</i>

4. <b>Aquatic locomotion</b>: Some swarm robots are designed to swim or move through water. They can use propellers or fins to move through the water, and may also use buoyancy control to regulate their depth.

    <img src="https://bugbot.files.wordpress.com/2008/10/photo_aquajelly.jpg" width="300"> <i>Aqua Jelly</i>

5. <b>Hybrid locomotion</b>: Swarm robots can also use a combination of the above methods to move through their environment. For example, a robot might have wheels for ground movement and a small rotor for flying over obstacles.

Overall, the choice of propulsion and locomotion method will depend on the environment and task requirements of the swarm robot. Swarm robots must be able to move efficiently and adapt to changing environments, so they often use multiple methods of locomotion to ensure they can navigate through various terrains and obstacles.

## Navigation System

Swarm robots require a robust and reliable navigation system to move through their environment, avoid obstacles, and achieve their objectives. Here are some of the common navigation systems used in swarm robots:

1. <b>GPS and satellite navigation</b>: Global Positioning System (GPS) and other satellite-based navigation systems can be used to provide location information to swarm robots. This system works well for outdoor environments where the robots have a clear line of sight to the sky.

2. <b>Visual navigation</b>: Swarm robots can also use cameras and computer vision algorithms to navigate through their environment. They can recognize and avoid obstacles, follow specific patterns or landmarks, or identify targets for their objectives.

3. <b>Acoustic and ultrasound navigation</b>: Some swarm robots use acoustic or ultrasound signals to navigate through their environment. These signals can be used to detect obstacles and other robots, and can also be used for communication between robots.

4. <b>Inertial navigation</b>: Inertial navigation uses sensors to track the robot's movement and orientation relative to its starting position. This system is useful for environments where GPS signals are weak or non-existent.

5. <b>Swarm intelligence</b>: In some cases, swarm robots can navigate using swarm intelligence, which is the collective behavior of the swarm. The robots can communicate with each other to share information and coordinate their movements, allowing the swarm to move towards a common goal.

## Data Collection

### <b>Cameras and Vision Sensor</b>

<img src="https://assets.rbl.ms/25575981/origin.jpg" width="400"> <i>Kilobot</i>

- The Kilobot robot is a swarm robot that uses <b>infrared communication and onboard cameras</b> to detect and avoid obstacles and to form patterns and shapes.

### <b>Acoustic and Ultrasound Sensors</b>

<img src="https://static01.nyt.com/images/2019/07/23/science/26TB-ROBOBEE/26TB-ROBOBEE-superJumbo.jpg" width="400"> <i>The RoboBees</i>

- The RoboBees developed at Harvard University are tiny bee-inspired robots that use <b>piezoelectric actuators</b> to generate wing motions, and also use <b>ultrasound sensors</b> to navigate and communicate with other robots in the swarm.

### <b>Inertial Sensor</b>

<img src="https://news.mit.edu/sites/default/files/images/201803/1SoFi%2520swimming%2520close-up.jpeg" width="400"> <i>The RoboFish</i>

- The RoboFish developed at MIT are aquatic swarm robots that use <b>accelerometers, gyroscopes, and magnetometers</b> to navigate and maintain a specific depth and position.

### <b>Environmental Sensors</b>

<img src="https://static.generation-robots.com/16270-product_cover/dingo-indoor-robotic-platform.jpg" width="400"> <i>The SwarmRobotics Dingo</i>

- The SwarmRobotics Dingo is a land-based robot that uses <b>gas sensors</b> to detect the presence of toxic chemicals and other hazards.

## Data Transmission

| Data Transmission | Description |
|-------------------|-------------|
| Wireless | Wireless communication is the most common data transmission method used in swarm robots. It can be implemented using various wireless technologies such as Wi-Fi, Bluetooth, Zigbee, and others.|
| Infrared | Infrared communication is a type of wireless communication that uses infrared light to transmit data between robots in the swarm. This type of communication is often used in low-cost swarm robot platforms due to its simplicity and low power requirements.|
| Acoustic | Acoustic communication is a type of wireless communication that uses sound waves to transmit data between robots in the swarm. This type of communication is often used in aquatic or underground environments where radio signals do not propagate well.|
| Optical |  Optical communication uses visible light or infrared light to transmit data between robots in the swarm. This type of communication is often used in line-of-sight scenarios or when radio signals are not feasible.|
| Swarm Intelligence | In some cases, swarm robots can use swarm intelligence to communicate with each other. Swarm intelligence refers to the collective behavior of the swarm, where individual robots communicate with each other to coordinate their movements and achieve a common goal.|
| Centralized Control | Centralized control system can be used to manage the swarm. In this approach, a single robot or a computer system can act as a central controller that coordinates the movements and behavior of the swarm.|

## Power System Management

Swarm robots require a reliable and efficient power management system to ensure that they can operate for extended periods without needing frequent battery replacements. Here are some of the common power management systems used in swarm robots:

1. <b>Rechargeable batteries</b>: Rechargeable batteries are the most common power source used in swarm robots. They provide a reliable and convenient power source that can be recharged when needed. The type and capacity of the battery used will depend on the robot's power requirements and size.

2. <b>Solar power</b>: Some swarm robots, such as those used for environmental monitoring, can be powered by solar panels. This type of power source can provide a sustainable and environmentally friendly power source for the robots.

3. <b>Energy harvesting</b>: Energy harvesting is a technique where the robot can harvest energy from the environment, such as kinetic energy or solar energy. This technique can be used to supplement or replace the robot's battery power, providing extended operating times.

4. <b>Power management circuits</b>: Power management circuits are used to regulate and manage the power supply to the robot's components. These circuits can optimize the power usage and extend the battery life of the robot.

Here are some examples of swarm robots and their power management systems:

1. Kilobot: The Kilobot swarm robot uses a rechargeable <b>lithium-ion battery</b> that can provide up to 3 hours of continuous operation. The robot also includes a power management circuit that can detect when the battery is running low and automatically shut down the robot to prevent damage.

2. RoboBees: The RoboBees swarm robots use a <b>thin film solar cell</b> to power their onboard electronics. The solar cell can convert light into electricity and can provide power to the robot's microcontroller and sensors.

3. DASH: The DASH (Dynamic Autonomous Sprawled Hexapod) swarm robot uses an <b>energy harvesting technique</b> to power the robot's onboard electronics. The robot can convert the kinetic energy from its movements into electricity and store it in a capacitor for later use.

Overall, the power management system used in swarm robots will depend on the robot's size, power requirements, and task requirements. A reliable and efficient power management system is critical for swarm robots to operate for extended periods and achieve their objectives.