## Key Differences from the Original Configuration

**Changes:**

* **Video Rendering (Wayland):** Now leverages the efficient Vulkan API via `vo=gpu, gpu-api=vulkan, gpu-context=waylandvk` for optimal Wayland integration.
* **Hardware Decoding:** Employs `hwdec=vaapi-copy` for efficient hardware-accelerated video decoding.
* **Audio Output (Wayland):** Utilizes `ao=pipewire` for seamless audio integration with the PipeWire sound server.
* **Subtitles:** Configured to use `fontconfig` for font management and includes support for Chinese subtitles (`sub-codepage=gb18030`).
* **Curated Profiles:** Includes a selection of useful profiles such as HQ, HDR2SDR, and Anime4K, tailored with Linux-style file paths.
* **Standardized Paths:** All relevant paths, including those for logs, shaders, and watch history, now reside within `~/.config/mpv/`.
* **Windows-Specific Settings Removed:** All Windows-specific options, such as `d3d11-*` and `wasapi`, have been eliminated for a cleaner Linux focus.
* **Obsolete Settings Pruned:** Redundant default settings (e.g., `hwdec-codecs=all`) and experimental profiles (e.g., DoVi-P5) have been removed.
* **Linux-Optimized Foundation:** The entire configuration has been adjusted to better align with the Wayland display server and standard Linux file system conventions.
