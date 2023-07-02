# Humanoid Robot Design
This is a research document on the design and implementation of a full scale humanoid robot.  This is a complex task which has many ongoing research projects being done by very smart people.  Therefore, it will take many years to complete. At this point in time many of the components are expensive, but this may become less so as robotics become more mainstream.  

The best way to approach this is to break in down into a set of sub-projects, so as the task is not so overwhelming.  Here's some possible sub-projects:

- Low powered stationary robot arm that can servo to a specific object.  A camera is used to identify the object that the arm should move to.

- Low powered stationary robot arm with hand that can servo to and manipulate light objects.  A camera is used to identify the object that the arm should move to.

- A wheeled robot drivetrain that can navigate on a single floor, similar to the iRomba.  Possibly using a swerve drive. This will use a camera instead of a lidar.

- A high powered robot that can pickup heavy objects and move them to another location within the same floor.  Can be wheeled.

- A high powered robot that can pickup heavy objects and move them to another location on different same floors.  Must be legged.

These technologies will get combined into the final project.

## Requirements

- Must get a BLDC control board with an onboard microcontroller for under $30.  This will need to be self made since they don't currently exist at that price.  Use an open-source project and make them in bulk.

- Learn SMD soldering.

- Learn how to design intergrated circuit boards.

- Use CAD to design parts to 3D print and CNC.  Get this process down so as it's quick to prototype.

- Understand more about motors.  Maybe even make your own.

- Need to have linear actuators.  These will most likely have to be self made.

- Need to learn Reinforcement Learning to manipulate objects.

- Camera navigation will be required.

- Eventually will need voice command and feedback.

## References

- [5DOF Arm project](https://www.youtube.com/watch?v=NCQFlha8_fA&ab_channel=Dangineering) - Youtube

- STL files [5DOF Arm project](https://github.com/danslovich/5DOF_Robot_Arm) - Shows 3D printed planatery gears

- [Dexter Robotic Arm](https://github.com/HaddingtonDynamics/Dexter)

- [Dingo Dog](https://grabcad.com/library/dingo-robot-quadruped-2)

- [Dingo Dog](https://github.com/Yerbert/DingoQuadruped) - Github

- [3D Printed Storage](https://www.youtube.com/watch?v=ra_9zU-mnl8&ab_channel=ZackFreedman)