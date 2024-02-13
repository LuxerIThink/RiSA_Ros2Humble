# Ros Docker Template

This repository offers an easily deployable ROS Docker Template, streamlining your ROS development environment setup.

## Supported Ros Versions (branches)

- Ros 2 Humble
- Ros 2 Foxy
- Ros 1 Noetic

## Key features

Simplify your ROS Docker experience with these key features:

- Launch with a single command `docker compose up`
- Centralized management of apt-get packages in `packages.txt`
- Convenient management of Python libraries in `requirements.txt`
- Predefined workspace folder
- Automated build of C++ packages when building container
- ROS pre-sourced for immediate use
- Helpful ROS command hints provided
- Fix for not showing ros windows: `fix_display.sh`

## Quick guide

### Build and run

Start your container effortlessly:

```bash
docker compose up
```

Connect to the container's console:

```bash
docker exec -it humble kitty
```

### Quick docker tips

primarily for kitty/linux shortcuts

Leave from container:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> D <br> </kbd>

Terminate an active process:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> C <br> </kbd>

Open a new terminal:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> N <br> </kbd>

Open a new tab:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> T <br> </kbd>

Switch tabs:

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> → <br> </kbd>

or

<kbd> <br> CTRL <br> </kbd> + <kbd> <br> SHIFT <br> </kbd> + <kbd> <br> ← <br> </kbd>

### Purpose

Designed to cater to students specializing in Robotics and Autonomous Systems at Poznan University of Technology.
