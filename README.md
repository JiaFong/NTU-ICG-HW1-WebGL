# [108-2] NTU CSIE5805 ICG-HW1-WebGL

## Introduction
This repository contains the source code of my WebGL project, the HW1 assignment for the ICG course at NTU CSIE. It implements three rendering methods: Flat, Gouraud, and Phong shading, along with multiple light sources and objects. A dynamic effect is included, where object size changes based on the amplitude of the background music. I also added buttons for random lighting and continuous rotation.

Since the project was originally built over five years ago, many features had become outdated. I have refactored the code to ensure it runs in 2025, including removing some buttons and replacing the background assets with AI-generated, royalty-free content. The core WebGL rendering code has been minimally modified.

If you have any questions, feel free to open an issue. Moreover, if you are currently enrolled in this course and **intend to use my code for your assignment**, please **make sure to check [this note](#)**.


## How to Run the Project

**1. Set up a local server**

In 2025, running the project locally is challenging due to modern web browsers enhancing security by blocking access to local files. Therefore, we need to set up a local server. You can easily do this by (i) navigating to the project directory and (ii) using Python or third-party software like [Servez](https://greggman.github.io/servez/) to start the server:

```
cd /path/to/the/project/
python -m http.server 8000
```

**2. Run the project**

Once the server is set up, you can open the project by accessing the .html file in your browser and interact with it. If you run into any issues, feel free to open an issue. Otherwise, you can also find a live demo on my [personal website](https://www.cmlab.csie.ntu.edu.tw/~jiafongyeh/projects/webGL/).

## Citation

If you find the project is helpful for your work, feel free to cite my project.
```bibtex
@misc{YehWebGL2020,
  author       = "Yeh, Jia-Fong",
  title        = "WebGL project",
  howpublished = "available at: \\url{https://github.com/JiaFong/NTU-ICG-HW1-WebGL}",
  year         = "2020"
}
