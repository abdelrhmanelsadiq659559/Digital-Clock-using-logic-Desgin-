# Digital Clock with AM/PM Display using Logic Gates and Components

## Problem Statement

Creating a digital clock with an AM/PM display using logic gates and components involves several essential steps and connections.

## Solution

The digital clock project is composed of four key components, each with its specific design and functionality.

### 1. Clock Generation
- The clock is generated using a 555 timer in stable mode.
- Resistor values R1=108.225k and R2=36.075 are used to ensure a 1Hz cycle.

### 2. Seconds Counter
- Designed using two counters, one for units (0-9) and the other for tens (0-5).
- D flip-flops are used in both counters.
- Logic is implemented to increment the tens counter when the units counter reaches 9 and flips to zero.

### 3. Minutes Counter
- Similar to the seconds counter.
- The clock for the minutes counter depends on the seconds counter reaching 59 and flipping to zero.

### 4. Hours Counter
- Designed to count from 1 to 12, ensuring compatibility with a 12-hour clock format.
- A correction circuit is used to format the hours output for display on two 7-segment displays.
- A circuit is included to switch between AM and PM based on the time (i.e., when the clock reaches 11:59, it flips to 12).

### 5. Display
- All outputs are connected to 7-segment displays for visual representation.

## Access and Resources

For detailed circuit designs, equations, and project resources, you can explore the project repository on GitHub. This repository contains the schematics, code, and documentation for the digital clock with AM/PM display, providing valuable insights into the design and implementation.

We believe that this project offers a comprehensive example of digital logic design and electronic timekeeping, serving as a practical demonstration of a digital clock with extended functionality.

Thank you for your interest in our work.

