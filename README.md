# ST1507 DSAA - Peer Feedback and Coffee Drone Delivery Program

## Overview
This repository contains the project and peer feedback details for **ST1507 Assignment Two (CA2)**. The project focuses on a Coffee Drone Delivery Program implemented using Object-Oriented Programming (OOP) principles. Key functionalities include a city map system, drone navigation modes, a scoring mechanism, and dynamic scenario-based challenges.

Additionally, the document includes a peer feedback form assessing team members' contributions and performance.

---

## Project Features

### **1. Coffee Drone Delivery Program**

#### **Core Features**
1. **City Map Creation**  
   - A grid-based system for managing the city layout.
   - Each tile represents a section of the map.

2. **Drone Movement Modes**
   - **Manual Movement**: Allows user-controlled navigation for flexible pathfinding.
   - **Automatic Movement**: Enables autonomous navigation using the shortest calculated path.

3. **Scenario System**
   - **Player Mode Activation**: Accessible by pressing the 'X' key. Prompts users to input their name and generates a new map for navigation.
   - **Map Toggle**: Users can switch between dynamically generated maps after completing scenarios.

4. **Tracking and Recording System**
   -- **Timer Display**: Displays the time taken to complete the level. The best time is saved for reference.
   - **Score Counter**: Tracks the number of steps a user takes to complete scenarios, with the best score being the least number of steps.
   - **Record Keeping**: Saves all records (user names, time taken, and dates) in a text file for future reference.

5. **Dynamic Challenges**
   - **Invisible Maze Map (Night Delivery Scenario)**: Path visibility depends on the direction of the drone's movement. Non-visible paths remain hidden.
   - **Moving Obstacles Map (Traffic Scenario)**: Users must navigate the drone to avoid moving cars. Collisions send the drone back to the start.

---

## Contribution Details

### Team Members
- **Shaun Kwo Rui Yu (Adm. No.: 2317933)**
  - **Group Contribution**:
    - Developed the city map system using a grid structure.
    - Implemented manual and automatic drone movement.
  - **Individual Contribution**:
    - Created the scenario system, including player mode activation and map toggling.
    - Developed the tracking and recording systems (timer, score, and record-keeping features).

- **Loh Yip Khai (Adm. No.: 2317454)**
  - **Group Contribution**:
    - Designed and implemented key press logic for various drone actions (`q`, `r`, `f`, `g`, `h`, `p`, `c`, and arrow keys).
    - Integrated key delay mechanisms to prevent spamming.
  - **Individual Contribution**:
    - Created level-specific maps, including the Invisible Maze and Moving Obstacles maps.

