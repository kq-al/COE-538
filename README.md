# COE-538 Final Project

# Overview:
**Project Title**: EEBOT Maze Runner Project

# Project Description:

The EEBOT Maze Runner Project involved implementing assembly language code to enable a robot (EEBOT) to autonomously navigate complex mazes using various algorithms. The primary goals included guiding the robot through the maze, making decisions at intersections, and finding the way out of dead ends. The project required integrating sensors, LCD displays, motors, and developing software routines to manage these components effectively

# Main Code Blocks:

**Initialization and Configuration**: Set up foundational elements, define constants, initialize sensors, configure timers, and define variables for data conversions.

**Decision-Making with Dispatcher**: Implemented a Dispatcher module to make decisions based on the robot's current state, determining whether the robot should move forward, turn, or stop.

**Interactions with LCD**: Initialized ADC (Analog to Digital Converter) subroutines to communicate with the LCD. The ADC facilitated reading analog values from sensors and converting them into digital values for real-time feedback to the user.

**Navigation**: Developed navigation logic using sensors to enable the robot to perform right or left turns based on instructions and algorithms.

**Data Conversion**: Created subroutines to convert data between different formats (e.g., BCD or ASCII) for tasks such as displaying numbers on the LCD.

# Challenges Encountered:

**Code Organization**: Managing a large assembly language project required careful structuring into manageable modules and subroutines.

**Hardware & Software Synchronization**: Ensuring software accurately interfaces with hardware demanded precise timing and iterative development.

**Debugging**: Debugging assembly language programs can be challenging, necessitating the use of emulators and step-through execution.

# Reflection & Future Recommendations: 

**Modular Design:** Emphasizing modular design from the beginning simplifies development and debugging.

**Real-time Feedback:** Using LCD screens for instant updates enhances user experience.

**Iterative Development:** Incremental development and thorough testing result in a robust system.

**Collaboration:** Utilizing version control tools like Git/GitHub streamlines group collaboration.
