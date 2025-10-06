# kuka_kr3_description

Minimal ROS2 description package for a simplified KUKA KR3 (6-DOF) arm.
- `urdf/kuka_kr3.urdf`: primitive-geometry URDF (no external meshes).
- `data/kr3_dh_params.csv`: standard DH parameters (approximate).
- `config/joint_limits.yaml`: example limits.

> NOTE: Dimensions are placeholders approximating a KR3-class arm. 
> Replace with official parameters if you need accurate kinematics/collision.
