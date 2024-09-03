README
Overview
This application is a simple 3D visualization built using the Three.js library. It loads two spheres and an arrow from GLTF files and allows users to interact with the scene. Specifically, users can click on the arrow to change the positions of the spheres.

Prerequisites
Before running this application, ensure you have the following files and libraries:

Files:
index.html: The main HTML file containing the JavaScript and Three.js setup.
styles.css: Optional CSS file for styling, if applicable.
objects/ folder:
ZweiSpheren.gltf: GLTF file containing the two spheres.
Pfeil_G.gltf: GLTF file containing the arrow.
Libraries:
three.js: The core Three.js library.
GLTFLoader.js: A loader for importing GLTF models.
OrbitControls.js: Allows orbiting around the objects with the mouse.
Make sure all the files are correctly placed in the same directory as index.html or in the specified objects/ folder.

Setup and Usage
File Structure: Ensure the following file structure is maintained:

bash
Code kopieren
/NORMAN-JAUCHEN-360-PHOTO-PATH
├── index.html
├── styles.css
├── three.js
├── GLTFLoader.js
├── OrbitControls.js
└── objects/
    ├── ZweiSpheren.gltf
    └── Pfeil_G.gltf
Open the Application: Open the index.html file in a web browser that supports WebGL (e.g., Chrome, Firefox).

Interacting with the Scene:

Orbit Controls: Use your mouse to rotate, zoom, and pan around the scene.
Right-Click (Context Menu Click): Right-click anywhere on the canvas to trigger the sphere position change.
Left-Click on Arrow: Left-click on the arrow in the scene. If the arrow is successfully clicked, the positions of the two spheres will swap.
Adjusting the Camera: The camera is set at a fixed position, but you can orbit around the scene using the mouse for a better view.

Notes
The application is designed for educational purposes and serves as a simple demonstration of using Three.js with GLTF models.
If the models are not loading or the scene appears blank, check the console for errors. Ensure that the paths to the GLTF files are correct and that they are located in the objects/ directory as specified.
Troubleshooting
No models visible: Ensure the paths to the GLTF files are correct. The GLTF files should be inside the objects folder.
Interactivity issues: Ensure you are clicking directly on the arrow for it to respond. You can also check the browser console for any JavaScript errors.

License
This project is released under the MIT License.