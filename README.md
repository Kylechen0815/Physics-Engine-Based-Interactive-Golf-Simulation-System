# Physics-Engine Based Interactive Golf Simulation (大三專題：MediaPipe 與 Unity 結合)

This is my college capstone project (September 2024 - June 2025). The goal was to build an interactive, real-time golf simulation game that only requires a standard webcam, eliminating the need for expensive hardware sensors. 

It uses **MediaPipe** to track the player's swing posture, calculates the physical forces, and simulates a realistic ball trajectory in **Unity** using a custom-built 3D physics engine.

#  Demo & Documentation

- Video Demo: [Watch the real-time simulation in action](https://www.youtube.com/watch?v=CsEDxNdRhNc)
- Speech Report: [View the full PDF documentation](https://drive.google.com/file/d/12Rherkt5Mp_6AAFTCAjWRr-qW2hOhjL4/view?usp=drive_link)
- Post：  [View the full PDF documentation](https://www.csie.ntpu.edu.tw/uploads/file/f1_202506041531096131.pdf)
- Analyzed Report:  [View the full PDF documentation](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://drive.usercontent.google.com/download?id=1mZwggFLGVw9H-41jKrYmuNdJ70bjM0dv&acrobatPromotionSource=gdrive_chrome-native_view&gdriveEmail=true#authuser=1&gdriveEmail=kylechen2004815%40gmail.come)

##  Tech Stack & Implementation Details
- **Game Engine & UI:** Unity (C#)
- **Computer Vision:** MediaPipe (2D Pose Estimation)
- **Physics Engine:** Python
  - Built the core physics from scratch, handling gravity, air damping, surface friction, and collision handling.
- **Performance Optimization:** 
  - Implemented Temporal Differencing and motion constraints to reduce processing overhead.
  - Successfully bridged lightweight pose estimation with the physics engine to ensure smooth, real-time feedback.
 

---

##  Screenshots & Development Progress

Below are screenshots from different stages of development, showing the integration of pose tracking and the physics simulation environment:

<img width="1673" height="814" alt="屏幕截图 2026-01-09 024103" src="https://github.com/user-attachments/assets/81399403-2e44-427a-ae2d-8dd87e3b88f7" />

<img width="1675" height="787" alt="屏幕截图 2026-01-09 024120" src="https://github.com/user-attachments/assets/ff0bb603-43e7-494e-93a6-fc3e3bb6733d" />

<img width="1147" height="575" alt="屏幕截图 2025-03-26 222951" src="https://github.com/user-attachments/assets/dadffcf6-aa60-41f8-a2ff-1940ae0ecfb4" />

<img width="1243" height="691" alt="屏幕截图 2025-03-26 223021" src="https://github.com/user-attachments/assets/c73c23e2-e55d-423a-9db5-dd2976959f6b" />

<img width="1172" height="752" alt="屏幕截图 2025-04-17 150509" src="https://github.com/user-attachments/assets/ddaad591-7c3d-4611-af5a-a7734e11face" />

<img width="991" height="697" alt="屏幕截图 2025-05-17 225425" src="https://github.com/user-attachments/assets/d87fd3b2-1160-4c44-b620-373e7ff2d9ce" />

<img width="952" height="746" alt="屏幕截图 2025-05-17 225450" src="https://github.com/user-attachments/assets/ebac3532-06e1-4fde-b956-94a7d496f515" />

<img width="1096" height="708" alt="屏幕截图 2025-05-17 225341" src="https://github.com/user-attachments/assets/475fe27a-ddf0-492e-b9ca-5e8c2b623243" />

<img width="731" height="742" alt="屏幕截图 2025-03-26 223200" src="https://github.com/user-attachments/assets/426e35e9-1969-4671-aa35-fa1d4769a727" />

<img width="606" height="612" alt="屏幕截图 2025-03-26 223049" src="https://github.com/user-attachments/assets/4a20638e-4fdd-4fe7-9633-363dceec6c30" />

<img width="1726" height="832" alt="屏幕截图 2025-05-17 190721" src="https://github.com/user-attachments/assets/435ec17e-1ce6-4891-8245-e9629a77988e" />

