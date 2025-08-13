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

## 📂 Repository Structure

```
/Assets            # Unity assets (scenes, scripts, prefabs, shaders)
/Docs              # Notes, guides, technical explanations
/Prototypes
   /XR-Basics
   /Video-Texture
   /Chroma-Key
   /Camera-Passthrough
   /Streaming
   /VR-UI
/StreamingTests    # FFmpeg commands, test videos
README.md
```

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

## 🚀 Deployment

1. Put the smartphone into **developer mode** & enable USB debugging  
2. In Unity → **Build Settings → Android**  
3. Connect the USB cable and select *Build & Run*  
4. Test the app in the VR headset
