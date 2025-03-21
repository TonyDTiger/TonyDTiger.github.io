## Mathworks Toolboxes and Add-Ons Needed
* None

# Project Details

## Overview
This project focuses on demonstrating coplanar phasing rendezvous maneuvers that a chaser satellite can perform to rendezvous with a target satellite. 

## Assumptions Made

* Chaser and target satellites have the same initial circular orbit
* Delta-V maneuvers are instantaneous

## Results

https://github.com/user-attachments/assets/2dd619eb-004f-4f52-a32b-d22f42684850

Here the chaser satellite is ahead of the target satellite by 30 deg in phase. At the "top" of the orbit, the chaser satellite performs the first delta-V maneuver to enter the phasing orbit to lag behind the target satellite. Once the target satellite has caught up to the chaser satellite and both meet at the "top" of the orbit, then the chaser satellite performs the second delta-V maneuver to re-enter the original orbit. The remaining distance between both satellites is ~1km, which allows proximity operations to be performed.

https://github.com/user-attachments/assets/d60bbada-b6ab-4c80-b7f7-80376505542a

Here the chaser satellite is behind the target satellite by 30 deg in phase. At the "top" of the orbit, the chaser satellite performs the first delta-V maneuver to enter the phasing orbit to catch up to the target satellite. Once the chaser satellite has caught up to the target satellite and both meet at the "top" of the orbit, then the chaser satellite performs the second delta-V maneuver to re-enter the original orbit. The remaining distance between both satellites is ~1km, which allows proximity operations to be performed.

https://github.com/user-attachments/assets/82bf2eb3-cf98-41ab-b1e2-4ebe4e0170e3

Here the chaser satellite is behind the target satellite by 60 deg in phase. This is an interesting case because the phasing orbit that the chaser satellite has to take to catch up to the target satellite is not feasible as it collides into Earth's surface. As an alternative, the chaser satellite can utilize a different higher altitude phasing orbit that takes the long way around. Another (more delta-V efficient) alternative is to utilize the phasing orbit in the previous case above, to have the chase satellite decrementally approach the target satellite in 30 deg steps. **TODO: try this alternative and compare the time vs. delta-V used** The remaining distance between both satellites is ~1km, which allows proximity operations to be performed.
