# RoboWars

RoboWars is an interactive simulation of evolving robot entities in a competitive and cooperative environment. Watch as different types of robots battle, form alliances, and evolve in a dynamic grid-based world.

## Live Demo

[RoboWars Live Demo](https://tflannagan.github.io/RoboWars/)

## Features

* Dynamic grid-based simulation with multiple types of evolving robot entities
* Complex entity formation, including small robots, large robots, and bases
* Interactive controls for starting, stopping, and resetting the simulation
* Adjustable simulation speed
* Real-time statistics display
* Customizable color themes
* Responsive design for various screen sizes
* Endgame detection and summary popup

## How to Use

1. Open the simulation in a web browser
2. Click "Start" to begin the simulation
3. Adjust the speed using the slider
4. Use the theme selector to change the color scheme
5. Click "Stop" to pause the simulation
6. Click "Reset" to restart the simulation with a new configuration
7. When one robot type dominates, an endgame popup will appear with statistics

## Entity Types

* **Small Robots**: Basic units with various specializations (Warrior, Explorer, Builder, Scientist)
* **Large Robots**: Formed when multiple small robots of the same type condense
* **Bases**: Created when multiple large robots of the same type gather in an area

## Technical Details

* Built with vanilla JavaScript, HTML5 Canvas, and CSS
* Efficient rendering using `requestAnimationFrame`
* Object-oriented design with classes for different entity types
* Responsive layout using flexbox
* Custom drawing functions for detailed robot representations

## Simulation Logic

* Robots move, interact, and evolve based on various factors:
  - Energy levels
  - Strength
  - Aggressiveness
  - Specialization
  - Alliance scores with other robot types
* Large robots can split into smaller robots when low on energy
* Bases produce new robots and maintain an area of influence
