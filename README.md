# iWidgetOS 📱

iWidgetOS is a sleek, web-based operating system simulation built entirely in a single HTML file. It replicates modern iOS design aesthetics, featuring an interactive **iOS 16 Lock Screen Clock**, a fully functional **Dynamic Island** search engine, and a massive dashboard of **50 real-data widgets** powered by native browser APIs and live cloud data streams.

---

## 🚀 Live Demo & Preview
To run this project, simply download the `index.html` file and open it in any modern web browser. No installation, server setup, or build tools are required!

---

## ✨ Features

* **iOS 16 Typography & Clock:** A working 12-hour system clock that matches your local timezone automatically.
* **Dynamic Island Search Bar:** A fluidly animated, liquid-morphing pill container that handles live Google searches.
    * *Triggers:* Click the **🔍 Search** button in the top right, or mimic an iOS edge gesture by **dragging right from the far-left screen boundary**.
* **50 Real-Data Widgets:** 100% active data blocks pulling metrics from your hardware, browser engine, live mathematical formulas, and external financial/weather APIs.
* **Live Glassmorphism Customizer:** Dual top sliders allowing users to instantly adjust background tint opacity and blur levels in real-time.
* **Audio Pipeline:** Loopable background MP3 integration with an active master mute/unmute control.

---

## 🛠️ How to Add Your Own Music

By default, the system streams online royalty-free test music. To use your own soundtrack:

1. Download your preferred audio file and move it into the same directory as your project file.
2. Rename the audio file to `music.mp3`.
3. Open `index.html` in a text editor, locate line **127**, and update the track source:
   ```html
   <audio id="bg-music" loop src="music.mp3"></audio>
   ```

   ---
   # Verison history

    ## v1.1.0
     * Added the dynamic island search bar

   ## v1.0.0
       * Initial Release

   
