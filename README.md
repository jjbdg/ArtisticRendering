# Artistic Rendering with GLSL Shaders

## Introduction
GLSL shaders make it possible to create awesome lighting effects in real-time computer graphics. These effects can range from photorealistic lighting, like a bunny made of gravel, to artistically inspired non-photorealistic rendering, like a cartoon bunny. This shader program, written in OpenGL, uses per-pixel lighting and normals as well as silhouettes to experiment with different shading styles and texture materials.

Using the interface in the top-right corner, you can view various models like a bunny or a teapot with a number of different shading models and textures. The shading models featured in this project are Gourad, Phong, and Legend of Zelda-inpired cartoon. Couple the Normal Map shading model with textures like gravel, tree bark, and stained glass to view implementations of photorealistic lighting.

## Prerequisites

To work with this code, you will first need to install [Node.js 16.17.0 LTS](https://nodejs.org/en/) (or newer) and [Visual Studio Code](https://code.visualstudio.com/). 

## Running

You will need to set up the initial project by pulling the dependencies from the node package manager with:

```
npm install
```

After that, you can compile and run a server with:

```
npm run start
```

Webpack should launch your program in a web browser automatically.  If not, you can run it by pointing your browser at `http://localhost:8080`.

## Acknowledgments

- This assignment was based on content from CSCI 4611 Fall 2021 by [Daniel Keefe](https://www.danielkeefe.net/).
- The PBR textures were from [3dtextures.me](https://3dtextures.me/). 
- Explanations and images were adapted from the Learn OpenGL articles on [stencil testing](https://learnopengl.com/Advanced-OpenGL/Stencil-testing) and [normal mapping](https://learnopengl.com/Advanced-Lighting/Normal-Mapping).

## License

Material for [CSCI 4611 Fall 2022](https://csci-4611-fall-2022.github.io/) by [Evan Suma Rosenberg](https://illusioneering.umn.edu/) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
