# Thief Detection System - Sensor-Based Art Gallery Security
## Project Description:
This project simulates a sensor-based security system for an art gallery. The sensors are randomly placed within a defined room, each having a random detection radius. The system then checks if it is possible for a thief to reach a piece of art without being detected by the sensors. It uses graph-based methods to connect sensors and walls, and determines if the thief can bypass the sensor network.

## Code Overview:
The project uses Python libraries to implement and visualize the security system, using graph-based logic to determine whether it is possible to bypass the security system. The core features include sensor placement, checking for overlaps (connections) between sensors, determining if sensors “see” the walls, and plotting the room with the security system.

## Required Libraries:
The following python libraries are needed for this project:
- NumPy for generating random sensor positions and radii.
- Matplotlib for plotting the room, sensors, and connections.

## Running the Code:
Input room dimensions, number of sensors, and the range for sensor radius.
The code will then generate the room and sensors, solve the problem, and plot the room with highlighted sensors and connections.
- Example Input:
```
Largura: 100
Altura: 100
Num de sensores: 20
Raio Minimo: 10
Raio Maximo: 12
```

## Authors
- [Lucas Fiuza Garcia](https://github.com/LuEx10)
- [Luis Felipe Marrote Ferreira](https://github.com/LuisFelipeMarrote)
- [Thiago Loureiro Kosciuk](https://github.com/ThiagoKosciuk)
