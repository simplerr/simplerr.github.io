---
layout: collection
title: "Utopian Engine"
permalink: /utopian-engine/
author_profile: true
---

<img src="/assets/images/readme-print.png" title="Utopian Engine editor" width="100%" />

<p style="font-size: 15px;">
Utopian Engine is an open source game engine written in C++ with a renderer that uses Vulkan as graphics API.
The main focus in the development of the engine so far has been on the rendering pipeline. The first milestone (v0.2) have been to be able
to render a terrain scene that showcases some of the renderers features. Using the editor the user can modify the terrain, paint the ground texture,
place objects in the world, modify rendering settings and test the physics interactions.
<br><br>
Techniques I would like to extend the renderer with includes atmospheric scattering, clouds, raytraced shadows and PBR to name a few.
<br><br>
Short-term the engine will be used for personal experimentation and research with the plan to in the end make my own game using it and also to make it stable, fast and documentated enough to be used by others as well.
<br><br>
You can follow the development of Utopian Engine on <a href="https://github.com/simplerr/UtopianEngine">GitHub</a>.
</p>

### Features
+ Vulkan backend
+ Deferred shading
+ Casacade shadow mapping
+ Screen Space Reflections
+ Normal mapping
+ God rays
+ SSAO
+ Instancing
+ Runtime shader compilation
+ Shader reflection
+ Basic Lua scripting
+ Terrain generation
+ Modifiable terrain
+ Skydome with sun
+ ImGui user interface
+ ECS layer
+ Terrain tesselation
+ Displacement mapping
+ Water
{: style="font-size: 15px;" }
