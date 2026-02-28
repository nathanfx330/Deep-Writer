# Deep Writer

🌐 **Project Page**  
https://nathanfx330.github.io/blog/posts/deep-writer/

![Deep Writer Screenshot](https://nathanfx330.github.io/blog/posts/deep-writer/dw.png)


---

## Overview

**Deep Writer** is a nonlinear, AI-assisted narrative engine designed for visual thinking and complex storytelling.

This repository currently contains **Node Writer V1.1**, a lightweight **Proof of Concept (PoC)** that serves as the technical foundation for the broader Deep Writer vision.

Node Writer: https://github.com/nathanfx330/node-writer
https://nathanfx330.github.io/blog/posts/node-writer/

It combines:

- A distraction-free visual node graph  
- Local, private AI text generation  
- Nonlinear narrative construction  

Ideal for:

- Interactive fiction  
- Game writing & dialogue systems  
- Branching narratives  
- Story architecture & planning  

All AI processing runs locally using your own models.

---

## ✨ Features

### 🧠 Local AI Generation *(New in v1.1*
Native integration with **Ollama**.

Automatically detects locally installed models (such as `gemma3:12b`, `llama3`, etc.) and enables:

- Rewriting
- Brainstorming
- Narrative expansion
- Context-aware generation from compiled story paths

---

### 🚫 “No Backtalk” AI Mode *(New in V1.1)*
Optional strict system prompt mode forcing the AI to output **only raw story text**.

Removes conversational filler such as:
> “Sure! Here is your rewritten version…”

---

### 🎨 Infinite Canvas
Freely pan and zoom across an unlimited workspace to organize narrative structures visually.

---

### 🔀 Visual Branching
Connect scenes using Bézier curves to clearly map story flow and decision paths.

---

### ✍️ Rich Text Lite
Minimal formatting support inside a distraction-free editor:

- **Bold**
- *Italic*

---

### ⚡ Live Preview & Compile
- Instantly preview compiled narrative paths  
- Export selected story flows seamlessly  

---

### 🏷 Custom Terminology
Rename nodes to match your workflow:

> Scenes • Passages • Beats • Cards • Dialogue • Anything

---

### 💻 Cross-Platform
Runs natively on:

- Linux
- Windows
- macOS

---

## 🚀 Getting Started

### Prerequisites

#### 1. Install Flutter
https://flutter.dev/docs/get-started/install

Verify installation:

```bash
flutter doctor
````

---

#### 2. Install Ollama (Required for AI Features)

Install Ollama and download at least one model:

```bash
ollama run gemma3:12b
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/nathanfx330/deep-writer.git
cd deep-writer
```

Fetch dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

---

## 🏗 Build Release Versions

### Windows

```bash
flutter build windows
```

### Linux

```bash
flutter build linux
```

### macOS

```bash
flutter build macos
```

---

## 📜 License

MIT License

Copyright (c) 2026 Nathaniel Westveer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
