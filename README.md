Differences from Original

Video: Uses vo=gpu, gpu-api=vulkan, gpu-context=waylandvk for Wayland.
Hardware Decoding: hwdec=vaapi-copy
Audio: ao=pipewire for Wayland audio.
Subtitles: fontconfig for fonts, supports Chinese (sub-codepage=gb18030).
Profiles: Includes HQ, HDR2SDR, Anime4K, etc., with Linux paths.
Paths: Uses ~/.config/mpv/ for logs, shaders, and watch history.

Shorter: Reduced from ~1000 to 367 lines.
Windows Settings Removed: Dropped d3d11-*, wasapi, and other Windows-specific options.
Obsolete Settings Cut: Removed redundant defaults (e.g., hwdec-codecs=all) and experimental profiles (e.g., DoVi-P5).
Linux-Optimized: Adjusted for Wayland (vo=gpu, ao=pipewire) and Linux paths.
