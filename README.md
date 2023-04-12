# Ros 2 Humble Docker

It'a a easy to use Docker container package with ROS 2 Humble distro.
Created mainly for Robotics and Autonomus Systems specialization
students in Poznan University of Technology.

## Key features

- predifined Shared folder `/home/$USER/Shared/RiSA_Ros2Humble`
- Pre-sourced ROS
- Working command hints
- Easy way to add apt-get libraries in packages.txt

## Quick guide

### Build and run

To build Dockerfile use this command:

```
./build
```

To run Docker container use this command:
```
./run
```

### Moving in container shortcuts

Leave container:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> D <br> </kbd>

Kill active proces:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> C <br> </kbd>

Create new terminal:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> N <br> </kbd>

Create new tab:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> T <br> </kbd>

Change tab:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> -> <br> </kbd>

or

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> <- <br> </kbd>

In one tab run:

```
ros2 run turtlesim turtlesim_node
```

in another run:

```
ros2 run turtlesim turtle_teleop_key
```

While you are focused in second tab you can move turtle in new window. <br>
Rest instruction you find in offical ROS 2 Humble [Wiki](https://docs.ros.org/en/humble/index.html).

