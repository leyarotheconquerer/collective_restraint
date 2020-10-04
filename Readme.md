# Ludum Dare 47

Theme: **Stuck in a Loop**

## Concept

Use your many robots to retrieve the runaways in a capture loop. Unfortunately, you only have enough power for three robots, so you can only control three robots at a time.

* First person perspective
* Move robot around
* Can transfer control to another robot
* Remembers the last three robots controlled
* Can make a loop with the last three robots controlled
* The capture loop may not be larger than x amount
* Rogues will run away from your controlled robot
* To win a level, you must encircle each rogue robot in your capture loop

Core game:
* Capture
* Transfer control
* Figuring out how to get the robots you need to capture the others

## Requirements

- [x] Player can move around
- [x] Player can switch robots
- [x] Remembers last three robots
- [x] Can make a loop with robots
- [x] Loop captures rogue robots
- [x] Rogue robots run from active robot
- [ ] Captured robots (are controlled?, disappear?, Stay around?)
	- [ ] Captured robots may be used to capture others (extension) (early)
- [x] Indications of
	- [x] remembered robots
	- [x] active robot
	- [x] rogue robots
	- [x] captured robot
	- [x] capture loop
	- [x] loop viability
	- [x] loop active

### Extensions
- [ ] Different rogue robots
	- [ ] Captured join you
	- [ ] Large
	- [ ] Fast
	- [ ] Destroy inactive robots

## Assets
- [x] Player robots
	- [x] Activate animation
	- [x] Deactivate animation
	- [x] Move animation
	- [x] Loop animation
	- [ ] Move sound
	- [ ] Activate sound
	- [ ] Deactivate sound
- [x] Rogue robots
	- [x] Movement animation
	- [x] Run animation
	- [x] Capture animation
	- [ ] Move sound
	- [ ] Run sound
	- [ ] Capture sound
	- [ ] Fast (extension)
		- [ ] Fast (extension)
	- [ ] Destroy (extension)
		- [ ] Destroy animation (extension)
	- [ ] Join you (extension)
- [ ] Loop
	- [ ] Texture or animation
	- [ ] Activate sound
	- [ ] Deactivate sound
- [ ] Background music
- [ ] Floor
	- [ ] Variants?
- [ ] Wall
	- [ ] Variants?
- [ ] Pillar
	- [ ] Variants?

## Schedule

### Friday
* Concept
* Rudimentary FPS
* AI that runs

### Morning Saturday
* Base game
	- Robots you can control
	- Capture cylinder
	- Level winning

### Afternoon Saturday
* Sound
* Levels

### Morning Sunday
* Levels

### Afernoon Sunday
* Levels
* Polish