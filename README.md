# Kasumi's Tweaking Utility

**Version:** 2.4.1  
**Category:** Windows Optimization Suite  
**License:** MIT (or specify your license)

---

## Overview

**Kasumi’s Tweaking Utility** is a precision Windows optimization suite designed to maximize performance, streamline system processes, and reduce bloat. With **12 targeted tweaks across 6 categories**, this utility runs in under 30 seconds and requires no extra installations.  

It provides an interactive dashboard with real-time terminal-style feedback, allowing users to filter and view tweaks before execution.

---

## Features

- **Real-time terminal output** simulating PowerShell initialization.
- **12 configurable tweaks** in categories:
  - Performance
  - Network
  - Privacy
  - System
  - Gaming
  - Storage
- **Copy-to-clipboard functionality** for executing PowerShell commands.
- Animated **glitch-style headings and scanline effects** for a modern UI experience.
- Minimalistic design optimized for readability and usability.

---

## Tweaks

| Category     | Tweak Label                     | Description |
|-------------|---------------------------------|-------------|
| Performance | CPU Priority Boost               | Sets process priority and disables CPU throttling for maximum throughput. |
| Performance | RAM Optimizer                    | Clears standby memory, trims working sets, and optimizes pagefile usage. |
| Network     | TCP/IP Stack Tuning              | Optimizes TCP settings, disables Nagle algorithm, tunes buffers. |
| Network     | DNS Cache Flush & Optimize       | Clears stale DNS entries and adjusts resolver timeouts. |
| Privacy     | Telemetry Disable                | Disables Windows diagnostic data collection and feedback endpoints. |
| Privacy     | Activity History Clear           | Wipes timeline data, clipboard history, and recent files tracking. |
| System      | Service Cleanup                  | Disables non-essential background services. |
| System      | Visual Effects Strip             | Removes animations, transparency, and shadows for low-overhead desktop. |
| Gaming      | Game Mode Enhancement            | Enables GPU scheduling, disables HPET, and reduces DPC latency. |
| Gaming      | Input Lag Reduction              | Disables mouse acceleration, adjusts USB polling rate, sets raw input mode. |
| Storage     | SSD TRIM & Optimize              | Runs TRIM, tunes defrag schedule, flushes write-cache buffers. |
| Storage     | Prefetch & Superfetch Tune       | Adjusts prefetch parameters for SSDs and HDDs. |

---

## Tech Stack

- **HTML5 & CSS3** for structure and styling  
- **React 18 (UMD)** for interactive UI  
- **Babel Standalone** for JSX compilation  
- **Custom CSS animations** for scanlines, glitch effects, and transitions  

---

## Design Notes

- Dark mode with neon accents for readability.  
- **Responsive layout**, optimized for desktop viewing.  
- Interactive tweak cards with hover effects for improved user experience.  
- Terminal block simulates PowerShell with animated prompts and copy buttons.  

---

## Stats

- **Tweaks:** 12  
- **Categories:** 6  
- **Execution Time:** <30 seconds  
- **Version:** 2.4.1  

---
