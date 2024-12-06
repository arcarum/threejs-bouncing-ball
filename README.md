# Bouncing Ball Simulation

This project creates a 3D simulation of bouncing balls within a box using **Three.js** and **WebGL**. The balls interact with the environment through physics simulations including gravity, friction, and collision detection. This simulation offers interactive features controlled through the keyboard such as changing the material and modifying gravity and friction.

## Demo
https://github.com/user-attachments/assets/29b14dd3-18ea-4491-bb7c-b56a703be1ab

## Keyboard Controls
| **Key**               | **Action**                                           |
|-----------------------|------------------------------------------------------|
| `+` or `=`            | Increase gravity (up to `maxGravity`)                |
| `-` or `_`            | Decrease gravity (down to `minGravity`)              |
| `]`                   | Increase friction (up to `maxFriction`)              |
| `[`                   | Decrease friction (down to `minFriction`)            |
| `F`                   | Toggle friction on/off                               |
| `G`                   | Toggle gravity on/off                                |
| `C`                   | Cycle through cube visibility: solid, wireframe, or none |
| `B`                   | Toggle ball wireframe mode (for all balls)           |
| `0`                   | Toggle all balls                                     |
| `1` to `7`            | Toggle specific rainbow ball (1 to 7)                |
| `D`                   | Change material to `MeshLambertMaterial`             |
| `S`                   | Change material to `MeshPhongMaterial`               |
| `N`                   | Change material to `MeshBasicMaterial`               |
| `M`                   | Toggle mirror effect on center ball                  |
| `Z`                   | Toggle shadow casting and receiving for all balls    |
| `A`                   | Add a new ball                                       |
| `R`                   | Reset the scene                                      |
