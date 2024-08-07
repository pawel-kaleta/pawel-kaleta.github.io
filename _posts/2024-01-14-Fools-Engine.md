---
layout: post
title:  "Fools Engine"
summary: "C++ Game Engine"
date:   2022-10-09 15:39:40
preview: /assets/FoolsTools.jpg
---

![Picture 1](/assets/FoolsTools.jpg)

A germ of a game engine being written in **C++** (ongoing). I believe, despite its early development stage, it **represents most accurately my current knowledge of C++ and coding principles and practices**. It allows me to constantly improve my programming skills by facing challenging problems from every aspect of game development.
Check out the github page for more details.

[![GitHub](https://img.shields.io/badge/GitHub--red.svg?style=social&logo=github)](https://github.com/pawel-kaleta/FoolsEngine)

### Here's some cool stuff I did:

- IoC (inversion of control) using layers stack
- Cross-platform OSI (operating system interoperability) abstraction layer: window, events, input
- Windows specific implementation of the above using GLFW
- Buffered events system
- Dear ImGui integration
- Debugging functionalities: logging (spdlog), profiling (Chrome event tracing tool), assertions
- Hybrid Actor/GameObject/ECS scene representation and execution model - authorial design (check out documentation folder in github repository)
- Simple 2D batch renderer in OpenGL
- Editor features: overall UI setup, edit and play viewports, editor camera, edit and play modes, mouse picking, transform gizmos
- Editor UI panels: performance stats, scene hierarchy, multiple inspectors, content browser
- Serialization and deserialization (YAML format)
- ECS-based assets system
