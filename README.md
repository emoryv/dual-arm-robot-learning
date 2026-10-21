# Dual-Arm Robot Learning

**Praxis Lab · Cornell University · Research Intern · June 2026–present**

I developed a data-collection pipeline for imitation learning with a dual-arm xArm6 robotic system, connecting simulation, teleoperation, camera streams, and recorded datasets. I was invited to continue beyond the summer research program.

## My contributions

- Developed the dual-arm robot-learning data-collection pipeline, integrating **MuJoCo simulation, ROS teleoperation, multi-camera streams, and Zarr recording**.
- Adapted and debugged recording infrastructure in both simulation and the physical-robot setup.
- Worked with recording of arm states, gripper observations, wrist-camera streams, and external-camera streams.

## Pipeline components

| Component | Role in the project |
| --- | --- |
| Dual xArm6 system | Physical manipulation platform |
| MuJoCo | Simulation environment |
| ROS teleoperation | Operator control interface |
| Wrist and external cameras | Multiple views of demonstrations |
| Arm and gripper observations | Robot-state information |
| Zarr | Recording demonstrations for the learning workflow |

## Engineering focus

The work centered on making the data-collection pieces operate together across simulation and hardware. Debugging covered the robot-state, gripper, and camera recording infrastructure so demonstrations could capture the information needed for imitation-learning research.

## Repository scope

This is a technical portfolio case study of my contribution within Cornell's Praxis Lab. It does not distribute the lab's original source code or research datasets, and it does not claim a completed learned policy or a measured policy-success rate.

**Technologies:** Python, MuJoCo, ROS, xArm6, multi-camera recording, Zarr

[Back to my profile](https://github.com/emoryv)
