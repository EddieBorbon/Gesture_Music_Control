# 🎶 Gesture Music Control

**Eddie Jonathan García Borbón**

## 📜 Overview

Gesture Music Control explores the intersection of gesture and music through digital musical instruments. By leveraging machine learning, particularly neural networks, this project aims to translate hand gestures into musical control parameters for a granular synthesizer programmed in Pure Data. This research-creation project embraces open-source and DIY methodologies to foster collaborative, experimental learning.

## 🛠️ Technical Requirements

### Installation

- **PC**: Windows desktop or laptop
- **Leap Motion**
- **Headphones**
- **Audio System/Speakers**: Suspended from the ceiling
- **Table/Podium**: At elbow height
- **Security System**: For PC and Leap Motion
- **Television**: For visual output
- **Nylon**: For hanging speakers
- **Software**: Processing, Pure Data Extended, and Wekinator

#### Minimum Technical Specifications

- **PC**: Windows Core i3, 4GB RAM
- **Leap Motion**: For gesture tracking
- **Audio System/Speakers**: Suspended at least 2 meters from the floor
- **Table/Podium**: Approximately 1.5 meters from the floor
- **Television**: Approximately 1.7 meters from the floor

### Performance

- **Leap Motion**
- **Audio System/Speakers**: Connected to a subwoofer
- **Table/Podium**: At elbow height
- **Distribution**: The installation area is marked by blue shading.

## 🛠️ Software Execution

1. **Run Wekinator**
   - Open the project `entrenamiento.wekproj` located in the `wekinator/entrenamiento` folder.
   - Verify that the input port is set to 6500.
   - Click on "Start Listening."
   - Change the output port to 8000.
   - Go to `View/outputs/`, change the port to 8000 (IMPORTANT).
   - Click on "Run."

2. **Turn On Leap Motion**
   - Search for "Leap Motion Visualizer" in Windows and run it.
   - The visualizer window should appear on the TV screen.

3. **Run Processing Leap Motion**
   - Run the `LeapMotion_Fingertips_15Inputs.pde` file from the root folder or via the shortcut.
   - If the shortcut is not working, navigate to `Gesture Music Control Final/LeapMotionViaProcessing/LeapMotion_Fingertips_15Inputs`.
   - The hand tracking view will appear on the TV screen.
   - Verify that data is being sent to Wekinator.

4. **Run Pure Data**
   - Execute the `main.pd` file from the root folder, or use the file within `AUTOMATONISM_2.1`.
   - You should hear audio output if everything is set up correctly.

5. **Run Processing Particles**
   - Execute the `Particle.pde` file via the shortcut.
   - The particle visualization will also appear on the TV screen.

## 🎥 Video

Check out the project in action: [Gesture Music Control Video](https://www.youtube.com/watch?v=437lGx45HqU&t=171s)

## 🙌 Thank You!

Feel free to reach out with any questions or feedback. Enjoy your interactive musical experience!

**Developer**: Eddie Jonathan García Borbón  
