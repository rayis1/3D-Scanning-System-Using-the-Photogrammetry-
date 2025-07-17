This is my Mechatronics Engineering graduation project: an automated 3D scanning system that uses photogrammetry to create accurate 3D models of physical objects.

The system is built with a Raspberry Pi, stepper motors, and a camera module, capturing images from multiple angles in a fully automated sequence. These images are processed using VisualSFM, COLMAP, or other open-source tools to generate sparse and dense point clouds, ultimately producing a detailed 3D reconstruction.

🔧 Key Features
Automated camera movement and capture using stepper motors

Synchronized image acquisition and motor control via Python

Image transfer to PC for processing

High-quality 3D reconstruction using photogrammetry software

Experimental analysis on factors like lighting, background, and number of images
