# ur_robotiq #

Automatic Addison ROS 2 support for UR robotic arms (specifically UR3e) made by Universal Robots with a 2F-85 adaptive gripper made by Robotiq.

![ur3e_robotiq_2f_85](./ur_robotiq_description/urdf/robotiq-ur3.jpg)

## Contents

- `ur_robotiq_description`: Contains URDF/Xacro files for the combined UR3e and Robotiq 2F-85 setup
  - `urdf/ur3e_robotiq_2f_85_urdf.xacro`: Main Xacro file combining the UR3e arm and Robotiq gripper
  - `urdf/ur3e_urdf.xacro`: URDF/Xacro description for the UR3e arm
  - `urdf/robotiq_2f_85_urdf.xacro`: URDF/Xacro description for the Robotiq 2F-85 gripper

## Usage

To use this description in your ROS 2 projects:

1. Clone this repository into your ROS 2 workspace
2. Build your workspace
3. Reference the `ur3e_robotiq_2f_85_urdf.xacro` file in your launch files or other URDF/Xacro includes

## License

This project is licensed under the BSD 3-Clause License. See the LICENSE file for details.

## Contributing

Contributions to improve the URDF descriptions or add additional features are welcome. Please submit pull requests or open issues on the GitHub repository.
