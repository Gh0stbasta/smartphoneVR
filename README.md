# Smartphone VR Learning Project with Unity & Google Cardboard

This project is designed to learn **VR development with Unity** –  
specifically for Android smartphones in a VR headset (Google Cardboard compatible).

---

## 🎯 Learning Objectives

This project will cover the following elements:

1. **Unity XR Basics**  
   - Integrate Google Cardboard XR Plugin  
   - Use gyroscope-based head tracking  
   - Set up stereoscopic rendering  

2. **Video in VR**  
   - Display MP4 as a texture in 3D space  
   - Control play/pause via VR UI   

3. **Shaders & Masking**  
   - Create a chroma key shader (make a color transparent)  
   - Control transparency with a UI slider  

4. **Passthrough Simulation**  
   - Use smartphone camera as VR background  
   - Overlay video with transparency-based compositing  

5. **Basic Streaming**  
   - Send PC video via UDP to the smartphone  
   - Receive and display in Unity  

6. **VR UI Interaction**  
   - Gaze/tap-based menus  
   - Adjust parameters live (key color, transparency)  

---

## 🛠 Minimum Required Setup

**Hardware**
- Android smartphone (Android 10 or newer)
- Google Cardboard-compatible VR headset
- USB cable for deployment  
- PC with Windows 10/11 (for Unity development)

**Software**
- Unity LTS (2023 or newer) with Android Build Support (SDK, NDK, OpenJDK)
- Google Cardboard XR Plugin for Unity
- Android Studio (for ADB and Logcat)
- Git (optionally with Git LFS for videos)
- FFmpeg (only for streaming tasks)

---

## 🐳 Development Environment

This repository includes a **VS Code Dev Container** for docs, scripting, tooling (FFmpeg, Node, Python), linting/formatting, and Git operations. Unity/Android builds run natively on your host.

**To use the Dev Container:**
1. Open this repository in VS Code
2. When prompted, click **"Reopen in Container"** (or use Command Palette → "Dev Containers: Reopen in Container")
3. VS Code will build the container and install recommended extensions automatically

**Environment setup:**
- Copy `.env.example` to `.env` and configure your local settings
- The Dev Container includes Python, Node.js, and development tools
- Unity Editor should be installed and run on your host system

---

## 🚀 Deployment

1. Put the smartphone into **developer mode** & enable USB debugging  
2. In Unity → **Build Settings → Android**  
3. Connect the USB cable and select *Build & Run*  
4. Test the app in the VR headset
