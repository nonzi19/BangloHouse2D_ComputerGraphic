# 2D Banglo House Visualization using JavaScript and GLSL (WebGL Environment)

This project showcases a **2D representation of a Banglo house** rendered in a **WebGL environment**. The visualization uses **JavaScript** and **GLSL** for rendering and interaction, focusing on showcasing the capabilities of WebGL for 2D graphics.

## Features

### 2D Graphics
- A detailed rendering of a Banglo house, including:
  - Roof
  - Windows
  - Door
- Rendered using WebGL with custom GLSL shaders.

### Lightweight and Browser-Based
- No need for external libraries apart from `gl-matrix-min.js` for matrix operations.
- Runs efficiently on modern web browsers with WebGL support.

## Getting Started

### Prerequisites
To view or modify this project, you'll need:
- A modern web browser that supports WebGL.
- Basic knowledge of JavaScript and WebGL (optional for customization).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nonzi19/BangloHouse2D_ComputerGraphic.git
   ```
2. Navigate to the project directory:
   ```bash
   cd BangloHouse2D_ComputerGraphic
   ```
3. Open the `ASSIGNMENT2.html` file in your web browser:
   - Double-click the file to open it in your default browser.
   - Alternatively, you can serve it locally with an HTTP server:
     ```bash
     python -m http.server
     ```
     Then, navigate to `http://localhost:8000/ASSIGNMENT2.html` in your browser.


## Built With

- **JavaScript**: To handle WebGL initialization and user interactions.
- **GLSL**: For creating shaders that render the 2D graphics and effects.
- **WebGL**: To render the 2D scene in the browser.
- **gl-matrix-min.js**: For handling matrix transformations efficiently.

## Screenshot
![image](https://github.com/user-attachments/assets/a126d4b5-016b-48b2-ace7-8eda2e821b88)

## Potential Applications
- Visualization of architectural designs.
- Educational tools to teach WebGL and 2D rendering concepts.
- Lightweight prototypes for 2D browser-based applications.

## Future Enhancements
- Add interactive elements like opening and closing doors/windows.
- Implement day and night cycles with dynamic lighting.
- Allow users to customize house colors or textures.
- Enhance the surroundings with animated elements like moving clouds or trees.


## Acknowledgments
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) for WebGL tutorials.
- [gl-matrix](http://glmatrix.net/) for matrix and vector math operations in WebGL.
