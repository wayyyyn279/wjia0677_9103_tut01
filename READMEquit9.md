# Emotion Garden

![cover](images/cover.jpeg)


## 1. Overview

Emotion Garden is an interactive generative concept that explores how emotional states can be externalised through visual systems.

The project aims to create a calm and reflective space where users can express and observe their current emotions through growth, movement, colour, and decay.


## 2. Inspiration

These inspirations explore how digital environments can respond to internal states and create space for emotional reflection.

teamLab’s installations demonstrate how visual elements such as flowers and particles can evolve in response to human presence, creating immersive environments that feel alive and responsive. This influenced our approach to designing a system that reacts to subtle changes rather than fixed inputs.

“Pulse Room” by Rafael Lozano-Hemmer translates invisible bodily signals into visible light, making internal states perceivable. This inspired us to consider how emotions can be externalised in subtle and non-verbal ways.

In Emotion Garden, we apply these ideas by allowing users to express their current mood through interaction. The garden grows, shifts, and fades over time, encouraging users to observe and release their emotions in a calm and reflective space.

### 2.1 teamLab – Floating Flower Garden

![teamLab flowers](images/inspo1.jpeg)

Link: https://www.teamlab.art/w/ffgarden/?utm_source=chatgpt.com

### 2.2 teamLab – Koi and People

![teamLab koi](images/inspo2.jpeg)

Link: https://www.teamlab.art/w/koi_and_people/

### 2.3 Rafael Lozano-Hemmer – Pulse Room

![pulse room](images/inspo3.jpeg)

Link: https://www.lozano-hemmer.com/pulse_room.php?utm_source=chatgpt.com


## 3. Concept

Emotion Garden explores how emotions can be externalised through a dynamic visual system.

The system is not designed to categorise emotions, but to provide a space for emotional awareness and gentle self-reflection.

The project introduces a two-layer interaction design:

### 3.1 Mood (Environment Layer)
This layer defines how the system behaves, including:

a. Growth speed
b. Motion patterns
c. Environmental dynamics

### 3.2 Colour (Expression Layer)

This layer allows users to personalise their contribution within the system.

This structure balances system control and user freedom, allowing emotions to be experienced rather than explicitly labelled.


## 4. Interaction Design

This interaction design allows users to engage with their emotions in a non-verbal and intuitive way.

### 4.1 Mood Controls (Environment Layer)

| Key | Emotion   | Behaviour                              |
| --- | --------- | -------------------------------------- |
| 1   | Calm      | Slow movement and soft transitions     |
| 2   | Sadness   | Rain-like particles and slower growth  |
| 3   | Joy       | Increased variation and lively motion  |
| 4   | Intensity | Chaotic motion and stronger distortion |


### 4.2 Colour Controls (Expression Layer)

| Key | Colour       |
| --- | ------------ |
| R   | Red tones    |
| B   | Blue tones   |
| G   | Green tones  |
| Y   | Yellow tones |
| P   | Purple tones |

Colours are generated within controlled ranges to maintain visual consistency.

### 4.3 Other Controls

X key resets the garden


## 5. Techniques

The project proposes the use of time-based animation, Perlin noise, and interactive input to simulate organic behaviour and emotional variation.

### a. Time-based animation
   Controls the lifecycle of flowers, including growth, bloom, and decay

### b. Perlin noise and randomness
   Generates organic shapes and smooth motion

### c. User input (keyboard interaction)
   Implements the mood and colour system

### d. Audio input
   Controls real-time intensity

### e. Particle systems and flow fields
   Simulate environmental dynamics


## 6. System Structure

sketch.js
│
├── time-mechanic.js
├── noise-mechanic.js
├── input-mechanic.js
├── audio-mechanic.js

Each mechanic is implemented as a separate module and integrated in the main sketch.


## 7. Mechanic Ownership

### a. Time-based mechanic – [Xinyu Chen]
   Responsible for the flower lifecycle, including growth, bloom, and decay

### b. Perlin noise and randomness – [Wenjia Jiang]
   Responsible for organic motion and flow field behaviour

### c. User input – [Fanfei Li]
   Responsible for the mood and colour interaction system

### d. Audio – [All group members]
   Responsible for microphone-driven behaviour


## 8. AI Acknowledgement

This project was developed with the assistance of ChatGPT.

It was used for:

### a. Create project concept pictures
### b. Provide interaction suggestions

All generated content was reviewed and adapted by the team.


## 9. External References

###a. https://p5js.org/
###b. https://p5js.org/reference/#/p5/noise


## 10. Proposed Interaction

Users will interact with the system through keyboard input.

Different emotional modes will influence:
- movement
- colour
- growth behaviour
- environmental effects

The project is intended to be developed as an interactive visual experience.



