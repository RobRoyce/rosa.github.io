---
title: Home
layout: home
nav_order: 1
description: "ROSA is an AI Agent designed to interact with ROS-based robotics systems using natural language queries."
permalink: /
---

# Welcome to ROSA 🤖

ROSA (Robot Operating System Agent) is your AI-powered assistant for ROS1 and ROS2 systems. Built on the Langchain framework, ROSA helps you interact with robots using natural language, making robotics development more accessible and efficient.

## What is ROSA?

ROSA is designed to:
- Interact with ROS-based robotics systems using natural language queries
- Support both ROS 1 and ROS 2 environments
- Simplify robotics development and interaction

## Quick Start

Get started with ROSA in just a few steps:

1. **Install ROSA:**
   ```bash
   pip3 install jpl-rosa
   ```

2. **Basic Usage:**
   ```python
   from rosa import ROSA

   llm = get_your_llm_here()
   rosa = ROSA(ros_version=1, llm=llm)
   rosa.invoke("Show me a list of topics that have publishers but no subscribers")
   ```

## Key Features

- 🗣️ Natural language interaction with ROS systems
- 🔧 Adaptable to different robots and environments
- 🐢 TurtleSim demo available for hands-on experience
- 🔄 Support for both synchronous and streaming responses

## Learn More

- [📚 Wiki](https://github.com/nasa-jpl/rosa/wiki)
- [🗺️ Feature Roadmap](https://github.com/nasa-jpl/rosa/wiki/Feature-Roadmap)
- [🏷️ Releases](https://github.com/nasa-jpl/rosa/releases)
- [❓ FAQ](https://github.com/nasa-jpl/rosa/wiki/FAQ)

## Get Involved

- [📖 Read our Documentation](https://github.com/nasa-jpl/rosa/wiki/Developer-Documentation)
- [🤝 Contribute to ROSA](https://github.com/nasa-jpl/rosa/blob/main/CONTRIBUTING.md)
- [💬 Join the Discussion](https://github.com/nasa-jpl/rosa/discussions)

---

<div align="center">
  ROSA: Robot Operating System Agent 🤖<br>
  Copyright (c) 2024. Jet Propulsion Laboratory. All rights reserved.
</div>
