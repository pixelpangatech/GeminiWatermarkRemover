<div align="center">

# Watermark Studio PRO

**Mathematically remove visible watermarks from Gemini/Omni AI-generated videos with a clean Windows UI**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![.NET](https://img.shields.io/badge/.NET-9.0-512BD4.svg)](https://dotnet.microsoft.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6.svg)]()

</div>

---

## Overview

**Watermark Studio PRO** is a highly optimized native Windows application that removes the visible watermark from Gemini Omni AI-generated videos.

Unlike mainstream approaches that rely on lossy AI inpainting (LAMA, STTN), this tool uses **reverse alpha blending** — a deterministic mathematical formula — to achieve **lossless restoration**. The output quality is mathematically identical to the original video, with no blurring, ghosting, or artifacts.

## Features

- 🖥️ **Native Windows UI**: Clean, modern desktop interface. No command lines or Python environments needed.
- ⚡ **Lightning Fast**: Powered by raw C# memory pointers and native OpenCV C++ bindings.
- ✨ **Lossless Quality**: Math-based reverse alpha compositing leaves zero artifacts.
- 🔄 **Smart Auto-Updater**: Built-in OTA updates pull the latest releases directly from GitHub.
- 🎵 **Audio Preservation**: Automatically merges the original audio track back into the cleaned video using FFmpeg.

## Download & Run

1. Download the tiny, standalone `WatermarkStudioPRO.exe`.
2. Run it, browse for your video, and click **Start Processing**.

### Prerequisites
- .NET 9.0 SDK (or newer) installed on your system.

## License

MIT - Copyright © 2026 PixelPanga Tech.
