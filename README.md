

```
xacro simple_pendulum_editted.xacro > simple_pendulum_editted.urdf
```

```
ros2 topic pub  /joint_command sensor_msgs/msg/JointState "{name: ['continuous_joint'], position: [0.0], velocity: [1.0], effort: [0.0]}"
```