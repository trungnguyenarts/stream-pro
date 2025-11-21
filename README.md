# Stream Pro

> **The Professional Branch of Artemis (Moonlight Noir)**

**Stream Pro** transforms your Android device into a **Mobile Creative Studio** and a high-fidelity gaming console.

Unlike standard remote clients, Stream Pro grants you **Unrestricted Full Desktop Control**. Anything that runs on your powerful PC workstation can be streamed and controlled on your Android device with ultra-low latency and zero compromise.

### 🎯 Optimized for Wacom Movink & Pro Artists
We understand that for artists, latency and color accuracy are non-negotiable. Stream Pro is engineered to pair perfectly with high-end input devices:

* **Wacom Movink Ready:** Specifically tailored to leverage the **Wacom Movink OLED Pen Display** when connected to Android. Experience the deepest blacks, vibrant colors, and ghosting-free visuals that OLED provides, combined with our low-latency streaming pipeline.
* **Precision Stylus Support:** Full passthrough support for **Pressure Sensitivity** and **Tilt** for S-Pen, Wacom EMR, and external drawing tablets.

### 🚀 Comprehensive 2D/3D Ecosystem Support
Whether you are at a cafe or on the couch, Stream Pro allows you to continue your workflow on **Industry Standard Software** without being tied to your desk:

* **3D Sculpting & Modeling:** ZBrush, Blender, Maya, 3ds Max, Cinema 4D, Houdini.
* **2D Art & Illustration:** Photoshop, Clip Studio Paint (CSP), Paint Tool SAI, Krita.
* **Texture & VFX:** Substance Painter, Mari, After Effects, Nuke, DaVinci Resolve.
* **Game Development:** Unreal Engine 5, Unity, Godot.
* **Full Desktop Freedom:** Coding, file management, web browsing, or any Windows/Linux/macOS specific tasks.

---

# Why Stream Pro? (Key Features)

Built upon the robust `Artemis` (Moonlight-Noir) foundation, Stream Pro introduces specialized features for productivity and studio workflows that the standard Moonlight client may lack:

### 🎨 For Creators & Productivity
1.  **Advanced Mouse Modes:** Seamlessly switch between Normal Mouse, [Multi-touch](https://github.com/moonlight-stream/moonlight-android/pull/1364), Trackpad, and **Local Cursor** (using Android's native mouse cursor for zero latency feel).
2.  **Touch & Pen Optimization:** Natural trackpad mode with touchscreen support.
3.  **Samsung DeX Support:** Optimized scrolling and desktop-class window management.
4.  **External Monitor Mode:** Full native support for secondary displays (great for connecting to TVs or portable monitors).
5.  **Virtual Display Integration:** Works flawlessly with **[Apollo](https://github.com/ClassicOldSong/Apollo)** to create dummy screens for headless streaming configurations.
6.  **Clipboard Sync:** Copy/Paste text between Android and Host PC (requires Apollo).

### 🎮 For Hardcore Gamers
7.  **Custom Resolutions & Bitrates:** Unlock custom resolutions beyond the standard presets (refer to [PR #1349](https://github.com/moonlight-stream/moonlight-android/pull/1349)).
8.  **On-Screen Controls:** Fully customizable virtual buttons (Import/Export support), optimized gamepad skins, and Joycon D-pad support.
9.  **SBS 3D Support:** Stereoscopic 3D support for external displays and AR glasses (Using AI MiDaS v2 Lite).
10. **Performance HUD:** Simplified heads-up display for monitoring FPS, network latency, and decoding times.
11. **Vibration Control:** Force use of the Android device's vibration motor when the gamepad lacks one.

### 🛠️ Advanced Tweaks
12. Custom shortcut commands.
13. **Display-on-Top Mode:** Useful for foldable phones and multitasking.
14. Video Scale Modes: Fit / Fill / Stretch.
15. View Pan & Zoom support.
16. Portrait Mode support.
17. Server Command integration with Apollo.

---

# Credits & Acknowledgements

Stream Pro is a fork of **Artemis (Moonlight Noir)**. We owe a huge debt of gratitude to the open-source community for making this possible.

* **Core Base:** Based on [Moonlight Android](https://github.com/moonlight-stream/moonlight-android).
* **Major Enhancements:** Forked from the excellent work of [ClassicOldSong](https://github.com/ClassicOldSong) (Artemis/Apollo project).

### Original Authors
* [Cameron Gutman](https://github.com/cgutman)
* [Diego Waxemberg](https://github.com/dwaxemberg)
* [Aaron Neyer](https://github.com/Aaronneyer)
* [Andrew Hennessy](https://github.com/yetanothername)

---

## Building
* Install Android Studio and the Android NDK.
* Run `git submodule update --init --recursive` from within the project folder.
* Create a file called `local.properties`. Add an `ndk.dir=` property pointing to your NDK directory.
* Build the APK using Android Studio or gradle.
