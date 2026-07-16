---
title: About
permalink: /about/index.html
description: 'A bit about Timothy Meade.'
layout: page
---

# Timothy Meade

**Systems thinker building a 20-year vision of Personal AI**

## Professional Background

I'm a Senior Software Developer and Senior DevOps specialist with 15+ years of experience. As a lifelong programmer, learner, and systems thinker I adapt quickly to new technologies and paradigms.

## Current Projects

For the last four months I've been building the future one idea at a time.

### Personal OS

This is the big one. I'm starting with a simple APK you can install on an Android phone. It will give you:

1. ***A local AI assistant with a real memory core***. It learns who you are, what you need, how you think, and how to be the best personal/executive assistant it can be. It does this without the massive token spend and instability of a system like OpenClaw.

2. ***Voice-driven but not voice-only.*** Voice is a critical part of the system that allows you to direct its behavior, but the interface is graphical. It uses cards which are like mini-apps but without the walled garden of traditional mobile apps. They are directly connected to the ***memory core***. They update in real-time and can be created and destroyed with your own words. You can even manifest a full featured card out of nothing with just your voice.

3. ***Personal sovereignty that extends to your Chitin Sandbox.*** Chitin Sandbox gives you a 24/7 agent that accepts tasks and executes them in the background. You can communicate with it via communication channels of your choice, as well as directly from Personal OS.

#### Pro Tip

> For the best experience with local AI you want to use a newer phone with plenty of RAM and ideally GrapheneOS which will eliminate some of the built-in AI features Google requires that use your memory, leaving it free for Personal OS.

#### The Ultimate Goal

The ultimate goal is to build a full OS removing the graphical features of Android entirely and replacing them with the cards-based UI. You won't lose Android though, it will be available to you in a VM ready to instantly swap in or out of memory.

### Local AI

As part of the Personal OS mission (and the wider ecosystem) I have been working on various libraries for Local AI:

| Project | Description |
| :--- | :--- |
| **[rusty-genius](https://github.com/tmzt/rusty-genius)** | Opinionated Rust bindings to llama.cpp with a message-passing interface. |
| **[smol-genius](https://github.com/tmzt/smol-genius)** | C Library implementing small language and vision models, speech-to-text with thinker interface, and others. Based on @antirez's qwen-asr. |
| **[shady-thinker](https://github.com/tmzt/shady-thinker)** | Rust+WGPU library for LLMs including recent innovations such as TurboQuant, online learning (Lora-JIT), etc. Main driver of LocalAI on PersonalOS. Also runs on Mac. |
| **[facecrab](https://github.com/tmzt/facecrab)** | HuggingFace model downloader supporting GGUF, Safetensors, and MLX formats in Rust. Library and CLI version. |

### MatterStream

#### [matter-stream](https://github.com/tmzt/matter-stream)

This is the UI library (and much more) that powers PersonalOS. It compiles TSX directly into a VM that can be interpreted by a compute shader and renders SDF to a pixel shader. It's basically a mobile version of React including hooks support without the JS runtime (and no React code).

It is also the VM that enables deterministic skills, vector-based queries in TSX (inspired by Cypher and GraphQL) that execute directly in Sqlite (no SQL parsing), and much more.

It has a security system that prevents secrets from even being used (entropy detection), capabilities that limit access to personal data and hardware resources like your camera and microphone, as well as automatic API authentication. Inspired by blockchain VMs, it limits looping and strictly applies a 'gas' system to tax instructions which also limits run-away processes, battery draining, etc.

### Other Projects

| Project | Description |
| :--- | :--- |
| **[deadsimpleseo](https://github.com/deadsimpleseo/vite-deadsimpleseo)** | Vite plugin to render React pages to static html. Useful for including easily crawable content in your app directly. |
| **[rusty-refinery](https://github.com/tmzt/rusty-refinery)** | A simple implementation of Gas Town MCP/ACP server with prd (spec) and wt (worktree) beads. Uses Redis for cordination.|

### Contact

I'm open to contracting and full-time work via my LinkedIn at [/in/timothymeade](https://linkedin.com/in/timothymeade). View my full work history and other details there.

I'm building in public on *𝕏* [@tmztmobile](https://x.com/@tmztmobile).

Reach me via email at [info@chitin.sh](mailto:info@chitin.sh).

More to come, and I'll update this when it does.

