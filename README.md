# Flyt - The airplane game
**Demo:**

Experience the thrill of high-speed flight and precision control in our interactive game! Navigate your plane through the dynamic environment, intercept floating targets, and engage turbo mode for an adrenaline-fueled rush. 

Visit the demo site [here](https://flyt-beta.vercel.app/) to try out the game firsthand.


(i am terrible)

https://github.com/deathmukh/Flyt/assets/91791452/39569d84-6c4a-4b3a-ae02-833352d16244


**Instructions:**

- Use the keyboard controls to steer your plane:
  - **A**: Move left
  - **D**: Move right
  - **W**: Pitch up
  - **S**: Pitch down
  - **SHIFT**: Activate turbo mode
  - **R**: Reset plane position and velocity

- Aim to intersect floating targets to progress and score points.
- Engage turbo mode (**SHIFT**) for a speed boost, experiencing the dynamic motion blur effect as you soar through the sky.

Immerse yourself in the captivating world of aerial maneuvers and speed. Enjoy the exhilarating experience of piloting your plane to victory!

(Note: For optimal performance, i recommend using a desktop browser.)

---

**Motion Blur Effect:**

When activating turbo mode (by pressing **SHIFT**), the game applies a motion blur effect to enhance the sense of speed and intensity. The motion blur effect is computed dynamically as follows:

1. **Turbo Speed Calculation:**
   - Turbo speed is gradually increased upon activation of turbo mode (**SHIFT**).
   - Turbo speed diminishes over time when turbo mode is not engaged.

2. **Motion Blur Intensity:**
   - Motion blur intensity is proportional to the turbo speed.
   - The higher the turbo speed, the more intense the motion blur effect.

3. **Implementation Details:**
   - The motion blur effect is implemented using the `easeOutQuad` function to smoothly adjust the turbo speed.
   - The camera's field of view (FOV) is modified based on the turbo speed to simulate the sense of acceleration.
   - Motion blur is achieved by adjusting the position of the plane in each frame, taking into account both the base speed and the turbo speed.

---

**Technologies Used:**

This game and its features are implemented using React Three Fiber, a library that enables the integration of React with Three.js for creating 3D web applications.

---

**Note:**

Please ensure your system meets the necessary requirements to run React Three Fiber applications. Refer to the official documentation for installation instructions and compatibility details.

---

**Enjoy the game and happy flying!** 🛩️🎮
0 comments on commit 2246de4
