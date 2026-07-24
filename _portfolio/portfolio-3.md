---
title: "Computer graphics project : 3D room"
show_permalink: false
excerpt: "<img src='/images/graphic_project.png' alt='3D room'>"
collection: portfolio
---
<div style="text-align: justify;">
I carried out this project as part of my computer graphics course during my first year at Polytech. The goal was to create an interactive 3D scene using OpenGL for rendering and Blender for object modeling.<br/><br/>

<div style="text-align: center;">
  <img src='/images/graphic_project.png' alt='3D room' height="300" width="350">
</div>
<br/><br/>

I designed a complete room with a floor, textured walls, a desk, a bed, a computer, a lamp, and other decorative elements. The scene includes a free camera (FPS style) and an orbital camera, with the ability to switch between them using the C key. The lighting is dynamic, based on the Phong model, with a movable light source. I also added a transparent window by creating a hole in the wall and simulating an outdoor view, which allowed me to manipulate the stencil buffer and depth testing. The 3D objects (furniture, screen, keyboard, etc.) were modeled in Blender. A small animation makes the PC fan rotate and the light pulse. This project taught me a great deal about the OpenGL graphics pipeline, managing transformation matrices, shaders, textures, and lighting. I also deepened my understanding of object-oriented architecture to organize the scene into nodes and reusable shapes. Solving rendering issues and optimizing performance were very challenging and instructive. <br/><br/>

I invite you to check out the source code on <a href='https://github.com/ArmandCl/3D-Room'>GitHub</a> for more details.<br/><br/>

Feel free to contact me for more details about this project .
</div>