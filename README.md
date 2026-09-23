# Project Name

> 3d Printed RC-Car

## Project Owner

**Name:** Ethan Davidson  
**Virginia Tech Email:** ethand04@vt.edu

## Project Overview
This project focuses on the design and development of a custom 3D-printed RC car with functional front-wheel steering, independent suspension, and dual-motor rear-wheel drive. The goal is to create a responsive and durable RC platform while integrating mechanical design, electronics, controls, and embedded software into a single system. The car is designed to provide responsive steering and acceleration so that the vehicle feels directly connected to the driver's inputs. Two rear hub motors are independently controlled, allowing the software to vary the power delivered to each rear wheel during turns to improve handling. A servo-controlled steering system provides mechanical steering of the front wheels. The vehicle is controlled wirelessly using an Xbox controller connected to an onboard Raspberry Pi. The Raspberry Pi processes driver inputs and communicates with the motor controller and steering system. The control software includes adjustable steering response, forward and reverse operation, regenerative braking, and differential rear-wheel power during turns. Another goal of the project is to develop the car into a platform for autonomous and assisted-driving experiments. A front-facing camera has been integrated to allow the Raspberry Pi to process the vehicle's surroundings. Future development can use this system for obstacle detection, collision avoidance, and autonomous steering. The extent of these features will depend on the processing capability and available hardware resources of the onboard computer.

## What I Hope to Learn
I really want to learn more controls, and software systems just to have some experience with converters, and motor controllers. I also want to develop my CAD skills which is why I want to implement working suspension and steering systems, as well as a design that will hold against possible collisions and damage.

## Design and Implementation
Spring 2026 — Initial Design and Component Selection
Initial development focused on determining the overall architecture of the vehicle and selecting the major electrical and mechanical components. This included selection of the electronic speed controller, onboard computer, motors, steering servo, battery system, and control method. Early CAD models were also developed to determine the general size and layout of the vehicle.

Summer 2026 — Mechanical Prototyping
The first major 3D-printed components were designed and manufactured. Development focused primarily on the chassis, suspension geometry, wheel mounting, and packaging of the electrical components. An initial suspension system was developed and tested to determine how the printed components behaved under load and throughout the suspension travel. These tests helped identify areas where the steering and suspension systems needed to be redesigned to work together.

Fall 2026 — System Integration and Control Development
The suspension system was refined and integrated with the front steering system using a servo-driven steering bar and tie rods. The mechanical design was modified so that steering could operate throughout the suspension's range of motion. The electrical and software systems were then integrated into the vehicle. A Raspberry Pi Zero 2 W receives commands from an Xbox wireless controller and communicates with the motor controller and steering servo. Initial vehicle testing was performed at motor duty cycles below 30% to verify drivetrain stability, steering response, communication, and safe operation before progressing to higher speeds.

The control software was expanded to include:
Wireless Xbox controller input
Proportional steering control
Independent control of the rear motors
Forward and reverse operation
Regenerative braking
Automatic startup of the vehicle control software
Differential rear-wheel power during steering to improve turning response
Modified steering response curves for more precise control
Camera integration for future obstacle detection and autonomous driving

The current vehicle is capable of controlled driving using the wireless controller, with continued development focused on improving mechanical reliability, steering performance, higher-speed testing, and camera-based autonomous features.


## Bill of Materials

Document the major components and materials used for the project.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Component | 1 | $0.00 | Link |

**Estimated Total Cost:** $0.00

## Timeline and Milestones
Milestone    Target Date    Status

Project planning and component selection    Spring 2026    Complete

Initial CAD design    Spring 2026    Complete

First mechanical prototype    Summer 2026    Complete

Suspension development    Summer/Fall 2026    Complete

Steering integration    Fall 2026    Complete

Motor controller integration    Fall 2026    Complete

Wireless controller integration    Fall 2026    Complete

Low-speed driving tests    Fall 2026    Complete

Camera integration    Fall 2026    In Progress

Obstacle detection / driving assistance    Fall 2026    In Progress

Higher-speed testing    Fall 2026    Planned

Final mechanical and software revisions    Fall 2026    Planned

## Progress Log
Spring 2026
Began development of the RC car and selected the primary electrical and mechanical components. Created initial CAD models and established the overall vehicle architecture.

Summer 2026
Produced the first major 3D-printed prototypes. Developed the chassis and suspension layout and began testing the mechanical movement of the suspension system.

Fall 2026
Refined the suspension and steering geometry and integrated the steering servo, steering bar, and tie rods. Integrated the Raspberry Pi, VESC motor controller, rear hub motors, steering servo, and Xbox controller. Developed the initial Python control software and successfully tested steering and rear-wheel motor control. Added forward/reverse switching, regenerative braking, automatic startup, steering response adjustments, and independent rear-wheel duty-cycle control during turns. Initial driving tests were intentionally limited to less than 30% motor duty cycle while verifying mechanical and electrical stability. Integrated a front-facing camera and began developing basic image-processing and obstacle-detection functionality for future assisted and autonomous driving.

## Project Files

Organize and document important project files in this repository. Depending on the project, this may include:

- Source code
- KiCad files
- Schematics
- PCB layouts
- CAD files
- Datasheets
- Test results
- Documentation

## Useful Links

Add any references, datasheets, documentation, tutorials, or other resources relevant to the project.

## Project Image

Replace the `hero.png` file in the root of this repository with an image representing your project.

**Keep the filename as `hero.png`.**

This image is used as the project cover image on the AMP Lab website.
