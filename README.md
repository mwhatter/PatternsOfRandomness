**PatternsOfRandomness** is an experimental Internet art project that blends randomized visuals with a procedurally generated melody. It’s an evolving experience that explores the balance between **familiarity and uniqueness**, where each session offers new patterns while maintaining recurring elements that provide a sense of coherence.

By interacting with the page, viewers trigger a flow of swirling shapes and shifting tones that evolve continuously. No two experiences are the same, yet there is enough repetition to feel familiar, resulting in a dynamic and captivating interplay between chaos and order.

## 🎨 Concept

The project emphasizes the beauty found in randomness. Through random, ever-shifting visuals and melodies, **PatternsOfRandomness** conveys how repetition and novelty can coexist. The visual continuously evolves, with each session offering a new arrangement while retaining recognizable patterns. Similarly, the procedural music evolves with each loop but maintains recurring motifs, creating a blend of the known and the unexpected.

**Key Features**:
- **Randomized Visuals**: Constantly moving and changing shapes that exhibit patterns of both familiarity and uniqueness. Shapes vary in size, position, and color with every session.
- **Procedural Music**: A continuous generative melody that evolves with subtle variations in each loop while retaining recurring harmonic patterns, providing both novelty and consistency.
- **Interactive Start**: The experience begins upon user interaction (touch or click), synchronizing the start of the visuals and music.

## 🖼️ Live Demo

You can view and interact with **PatternsOfRandomness** by visiting the live demo [here](https://bubbleflow-ocfq4.kinsta.page/).

## 📂 Project Overview

The project is built using HTML5 Canvas for rendering the dynamic visuals and the Web Audio API to generate the melody. Together, they create an evolving audiovisual loop.

### Key Components:
- **`index.html`**: The core HTML file that contains the structure of the webpage, as well as the JavaScript that handles the procedural visuals and melody generation.
- **HTML5 Canvas**: Used for drawing continuously moving and evolving shapes, ensuring a constantly shifting visual experience.
- **Web Audio API**: Handles the procedural generation of the melody, ensuring the music evolves smoothly without pauses between loops.

## 🚀 Running the Project

To run **PatternsOfRandomness** locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mwhatter/PatternsOfRandomness.git
   ```

2. **Open `index.html`** in any modern browser:
   ```bash
   open index.html
   ```

3. **Interact with the screen** to start the experience. The visuals and audio will begin in sync once the user clicks or taps the screen.

## 🎛️ Customization

The project offers several opportunities for customization to alter the visuals and sounds:

- **Shape Patterns**:
  - Modify the number of shapes, speed, and movement by tweaking the `generateRandomShapes()` and `updateShapes()` functions in the JavaScript.
  - Adjust the colors, transparency, and behaviors in the `drawPsychedelicVisual()` function to explore different visual styles.

- **Melody**:
  - Customize the musical scale, tempo, and randomness of the melody by changing `noteFrequencies`, `tempo`, and note duration choices in the `catchyMelody()` function.

## 💡 Inspiration

**PatternsOfRandomness** is inspired by the intersection of randomness and structure. It draws from elements of both psychedelic art and avant-garde music, embracing the balance between familiar repetition and unexpected novelty. The project showcases how randomness can create recurring patterns while also introducing constant newness, resulting in a mesmerizing audiovisual experience.

## 📄 License

This project is licensed under the MIT License. Feel free to use, modify, and expand upon this code for your own creative work. See the [LICENSE](LICENSE) file for more information.

---

Explore the randomness and discover patterns in the chaos through **PatternsOfRandomness**!

---
