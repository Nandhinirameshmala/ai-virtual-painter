# 🎨 AI Virtual Painter 🤖✋

A real-time AI-powered virtual painting application using **Hand Tracking (MediaPipe)** and **OpenCV**.  
Draw, erase, and control colors in the air using just your fingers — no mouse or touchscreen needed.

---

## ✨ Overview

AI Virtual Painter allows users to interact with a virtual canvas using hand gestures detected through a webcam.  
It uses **MediaPipe hand landmarks** to track finger movement and converts it into drawing actions.

---

## 🚀 Features

- ✋ Real-time hand tracking using MediaPipe
- ☝️ Draw using index finger only
- ✌️ Switch to selection mode using two fingers
- 🎨 4 bright colors (Blue, Green, Red, Yellow)
- 🧽 Eraser mode (gesture-based)
- 🗑️ Clear canvas option
- 🖥️ Smooth 640×480 interface
- ⚡ Fast real-time performance

---

## 🧠 How It Works

```text id="flow1"
Webcam Input
      ↓
MediaPipe Hand Detection
      ↓
21 Hand Landmarks Extraction
      ↓
Finger Gesture Recognition
      ↓
Mode Selection (Draw / Select)
      ↓
Virtual Canvas Rendering (OpenCV)
