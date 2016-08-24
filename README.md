# Manipulation Kinodynamics Dataset

Download the [manipulation kinodynamics dataset](https://seafile.lirmm.fr/f/c77606ed69/).

The archive contains 193 folders, indexed between 000 and 192, each describing a manipulation experiment through the following files:
  - info.csv: object-grasp parameters
    - object mass, inertia
    - for each finger: friction coefficient, contact location w.r.t. center of mass and contact space in object frame
  - kinematics.csv: object kinematics expressed in the world frame
    - object orientation as unit quaternion (convention: qX,qY,qZ,qW)
    - rotational velocity and acceleration
    - linear acceleration
  - dynamics.csv: 3D contact forces expressed in the world frame

All physical quantities are expressed in SI units.
