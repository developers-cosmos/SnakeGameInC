# 2d Snake game in C using OpenGL

<h4>About OpenGL:</h4> <br>
<p>Open Graphics Library (OpenGL) is a cross-language (language inependent), cross-platform (platform independent) API for rendering 2D and 3D Vector Graphics(use of polygons to represent image).</p><br>
<b>Design:</b> <p>This API is defined as a set of functions which may be called by the client program. Although functions are similar to those of C language but it is language independent.</p><br>
<b>Development:</b><p>It is an evolving API and Khronos Group regularly releases its new version having some extended feature compare to previous one. GPU vendors may also provide some additional functionality in the form of extension.</p><br>
<b>Associated Libraries:</b><p>The earliest version is released with a companion library called OpenGL utility library. But since OpenGL is quite a complex process. So in order to make it easier other library such as OpenGL Utility Toolkit is added which is later superseded by freeglut. Later included library were GLEE, GLEW and glbinding.</p><br>
<h4>INTRODUCTION<h4> <br>
<p>The following is an example game written in C using glut based on the game called ‘snake’ which has been re-emerged in recent years on mobile phones. It isn’t the greatest game, but it does give you an idea of what you can achieve with OpenGL, and perhaps the basis by which to extend the principles and create more interesting games of your own.</p><br>
<p>Let’s  talk about game and its controls to move the snake use<br>
•	‘UP ARROW’ for UP,<br>
•	‘DOWN ARROW’ for DOWN,<br>
•	‘LEFT ARROW’ for LEFT,<br>
•	‘RIGHT ARROW’ for RIGHT.</p><br>
<p>The aim of the game is to collect the dots (food) and avoid obstacles (window and the snake itself). As you collect food, the snake gets longer, so increasing your chance to crashing yourself. If the snake crashes with obstacles you get score according to the length of the snake. There is no concept of lives. Once you hit an obstacle, that’s it, game over.</p></br>
<h4>Design</h4> <br>
  ![System design](/design.JPG)

