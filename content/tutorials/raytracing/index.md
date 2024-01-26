---
title: Ray Tracing with WebGL and compute shaders
summary: A collection of Ray Tracing examples with WebGL and WebGL-ComputeShader.
tags:
  - WebGL
  - OpenGL
  - Javascript
  - GLSL
  - Ray Tracing
  - Compute Shader
date: '2024-01-24T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ray tracing
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Github
    url: https://github.com/sdevkota007/Ray-Tracing
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Ray Tracing with WebGL and compute shaders

This repository shows samples of Ray Tracing with WebGL and WebGL-ComputeShader. To enable
WebGL compute shader on a browser, refer to this github repo: 
https://github.com/9ballsyndrome/WebGL_Compute_shader

### A-1 Molecule Rendering
This repo shows basic ray tracing with WebGL. It implements ray-sphere intersection to render molecule data.
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-1.png)


### A-2 Molecule Rendering with light
This repo adds lighting computation using Blinn Phong model to A-1
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-2.png)


### A-3 Compute Shader - MandelBrot Set
This repo shows an example of using WebGL compute shader.
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-3.png)


### A-4 Compute Shader - Ray Tracing
This repo shows an example of using compute shader for RayTracing.
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-4.png)


### A-5 Compute Shader - Ray Tracing - Molecule Rendering - Light
This repo renders molecule data with ray tracing and lighting computation using Blinn Phong model
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-5.png)


### A-6 Compute Shader - Ray Tracing - Molecule Rendering - Light - Reflection
This repo adds reflection to A-5. It also adds ray-AABB intersection as an acceleration technique.
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-6.png)


### A-7 Compute Shader - Ray Tracing- Triangle Mesh - Light
This repo loads polygon mesh from a file and implements ray-triangle intersection in Ray Tracing. 
![html dark](https://raw.githubusercontent.com/sdevkota007/Ray-Tracing/master/screenshots/A-7.png)


*__Note:__ Repos A-3, A-4, A-5, A-6 and A-7 require WebGL enabled web-browsers*
