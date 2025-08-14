# 🎬 EchoVid Project – Contributions

## 🚀 Project Overview
**EchoVid** is a GenAI tool that transforms **text, audio, or image prompts into animated videos**.  
It leverages **Stable Diffusion** and open-source tools to generate **high-quality frames with consistent backgrounds and smooth character motion**.

---

## 🛠️ Our Key Contributions
While we used pre-trained models for image generation, our work focused on **enhancing outputs and creating a seamless video pipeline**:

### 1️⃣ Smart Prompt Analysis
- Detects **human-related** and **motion-related keywords** in prompts.
- Dynamically **enhances prompts** to improve frame consistency and motion realism.
- Ensures scenes include characters naturally, even if not explicitly mentioned.

### 2️⃣ Motion & Scene Management
- Maintains **consistent characters, clothes, and backgrounds** across frames.
- Adds **scene-specific context** (e.g., Conversation, Fight, Chess, Magical scenes) for better storytelling.
- Tuned **motion parameters** for realistic and smooth animation.

### 3️⃣ Audio Integration
- Converts **voice prompts into text** for video generation.
- Seamlessly integrates audio transcription into the video pipeline.

### 4️⃣ Video Compilation
- Combines generated frames into a **cohesive video** using **MoviePy**.
- Optional background music (demo version) added for better engagement.
- Advanced features like **AI face animation, interpolation, and AI music** are marked as Pro/future work.

### 5️⃣ User-Friendly Interface
- Built a **Gradio UI** for easy interaction.
- Users can provide **text or audio prompts**, select scene type, style, and customize frame count & FPS.

---

## 🌟 Highlights
- Focused on **enhancing outputs**, not just using pre-trained models as-is.
- Improved **motion rendering, background consistency, and character coherence**.
- Pipeline handles **text, audio, and scene-specific prompts efficiently**.

---

## 🔮 Future Improvements
- Implement **AI-based face animation** and **frame interpolation** for smoother videos.
- Add **AI-generated music** as a Pro feature.
- Advanced motion handling for **complex multi-character scenes**.

---

**💡 Note:** This file describes our contributions and pipeline logic without exposing the full code, keeping sensitive implementations private.

