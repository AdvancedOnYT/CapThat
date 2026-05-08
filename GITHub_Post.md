# 🚀 Introducing CapThat: The Ultra-Low Latency Capture Viewer

I'm excited to share **CapThat**, a lightweight Windows application designed specifically for high-performance video capture monitoring.

If you've ever struggled with the lag in OBS previews or generic "webcam" viewers when using a capture card for console gaming or professional monitoring, CapThat is for you.

![CapThat Preview](capthat.png)

### 🔍 Why CapThat?
Most viewers introduce several frames of delay due to complex rendering pipelines or software-based processing. CapThat strips away the bloat, utilizing **Windows Media Foundation (Async)** and **DirectX 11** to pass hardware textures directly to your GPU.

### 🌟 Highlights:
*   **Minimal Input Lag**: Optimized for 60FPS+ capture cards with low-latency flags enabled.
*   **Hardware Accelerated**: Pure D3D11 rendering pipeline.
*   **Sleek Control**: Toggle-able UI (powered by ImGui) keeps the focus on the content.
*   **One-Key Features**: Screenshot (PNG), Mute, Fullscreen, and Always-on-Top are all a single keystroke away.
*   **Smart Selection**: Automatically finds and selects the best format (FPS/Resolution) your hardware offers.

### 🛠️ Built With:
*   C++17
*   DirectX 11
*   Dear ImGui
*   Miniaudio

### 📈 What's Next?
I'm looking into adding support for custom shaders/filters and multi-device simultaneous viewing.

Check it out on GitHub and let me know what you think! 
[Link to Repository]

#CapThat #OpenSource #CPP #DirectX #LowLatency #Gaming #Streaming #TechShowcase
