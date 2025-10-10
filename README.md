# LightGeometry

LightGeometry is a modern web project that combines **dynamic geometric shapes** with **pulsating, blurred light effects**, creating an immersive visual experience. The project runs entirely in the browser using **HTML, CSS, and JavaScript**, with no external dependencies.

## Features

* **Dynamic Polygons**: Generates polygons with 3 to 8 sides that float upwards and disappear, without affecting page layout.
* **Vibrant Colors**: Each shape has randomly selected colors with subtle glow and shadow effects.
* **Blurred Light Effects**: Large, soft red and blue circles appear randomly across the screen, adding depth and atmosphere.
* **Full-Screen Canvas**: Shapes and light effects cover the entire viewport.
* **Background Blur Filter**: Adds a frosted glass-like effect for a polished look.
* **Responsive Design**: Works on any modern browser and adapts to screen resizing.

## How to Use

1. Open the `index.html` file in a modern browser (Chrome, Edge, Firefox, Safari).
2. Watch the polygons and light effects animate across the screen.
3. Optionally, control the shapes via the console:

```javascript
// Spawn a shape manually
window._lelga.spawn();

// Stop spawning new shapes
window._lelga.stop();

// Resume spawning shapes
window._lelga.start();
```

## Customization

Adjust the following directly in the script:

* **Shape properties**: number of sides, size, speed, color palette.
* **Light effects**: number of lights, colors, size, and fade speed.
* **Spawn rate**: interval of new polygon creation.

## Technologies Used

* **HTML5 Canvas**: Renders shapes and light effects.
* **CSS3**: Full-screen layout and blur filter.
* **JavaScript (ES6)**: Handles animation, randomness, and interactivity.
