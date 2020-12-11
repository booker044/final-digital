# Step 3: Creating Pac Man
Now you must use the `<svg>` tag.
 
`<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Challenge: SVG</title>
    <h1>Pac Man</h1>
    
  </head>

  <body>

    <svg height="100" width="300">
      <circle cx="50" cy="50" r="40" stroke="black" stroke-width="2" fill="yellow" />
      <circle cx="64" cy="33" r="5" stoke="black" fill="black" />
      <polygon points="100,25 50,60 100,75" style="fill:white" />
      <line x1="87" y1="33" x2="50" y2="60" stroke="black" stroke-width="2" />
      <line x1="50" y1="60" x2="85" y2="71" stroke="black" stroke-width="2" />
      <circle cx="100" cy="50" r="12" stroke="blue" stroke-width="2" fill="blue" />
      <circle cx="150" cy="50" r="12" stroke="blue" stroke-width="2" fill="blue" />
      <circle cx="200" cy="50" r="12" stroke="blue" stroke-width="2" fill="blue" />


    </svg>


  </body>

</html>`

When you enter in these commands you will get Pac Man.
1. Breaking it down the **height and width** command are what give you the size of the playing field you have to create the picture.
2. The **circle** command is how you get the size of pacman with **cy** meaning how far in the y direction and **cx** how far in the x direction.
3. **polygon points** is how I made the mouth of the pac man. The **line** command creates a triangle that makes the mouth.
4. Then the final **circle** commands are how I made what Pac Man eats. This code is all the same besides the **cx** command which should go up in an interval to create the particles that pac man eats.

[First Part](https://github.com/booker044/final-digital/blob/main/First%20Part.md)
