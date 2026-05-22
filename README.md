# ⚡ E.Box Proxy Manager

A high-performance, lightweight, and native Windows desktop application designed to manage and switch system proxy profiles instantly. Built entirely in raw Win32 C++ with zero external dependencies, offering a blazing-fast startup time and a premium modern pastel design footprint.

---

## ✨ Features

- **⚡ Native Performance:** Written in pure Win32 API. No Electron, no .NET, no heavy runtimes.
- **🎨 Premium Pastel Blue UI:** Clean interface styled around modern Windows typography (Segoe UI) using native theme anchors.
- **🔄 Instant Dynamic Switching:** Updates system-wide Internet Explorer/Windows proxy rules and broadcasts the settings change globally immediately. No reboot required.
- **💾 Quick Profiles:** Supports up to 4 configurable profile slots. Left-click to load, right-click to instantly save your current inputs.
- **🚨 Active Blinking Alert:** A clean, subtle animated indicator shows when a custom proxy routing configuration is live.
- **✨ Native Cue Banners:** Implements fast, integrated OS fallback input placeholder configurations.

---

## 📸 Interface Preview & Layout

The utility is designed around a compact, lightweight desktop window ($315 \times 265$ pixels) organized cleanly into structured zones:

> **Header & Inputs**
> * **IP Address Input:** Standard field with native placeholder fallback (`127.0.0.1`).
> * **Port Input:** Numeric-only input field with native placeholder fallback (`8080`).

> **Action Hub**
> * `[ Apply Proxy ]` — Commits settings to the Windows Registry and broadcasts globally.
> * `[ Status ]` — Instantly checks live registry values to confirm connection states.
> * `[ Disable ]` — Wipes custom configurations and falls back to a direct connection.

> **Dynamic Routing Panel**
> * **▲ Active Proxy State Indicator:** Displays active proxy parameters alongside a real-time animated health signal.

> **Quick Profiles System**
> * `[ P1 ]` `[ P2 ]` `[ P3 ]` `[ P4 ]`
> * *Quick Actions:* Left-click to instantly deploy a profile; right-click to overwrite a slot with current inputs.

> **Footer Anchors**
> * **GitHub Link** (Bottom-Left) | **Developed by Sam ♥** (Bottom-Right)


---


🎮 How to Use
Apply a Proxy: Input your IP address and Port number, then click Apply Proxy.

Quick Slots System:

Type an IP and Port, then Right-Click any profile button (P1–P4) to instantly bind that configuration.

Simply Left-Click any populated profile button to instantly switch paths to that proxy.

Check Status: Click Status to fetch the current live registry keys processing network interactions.

Disable: Click Disable to wipe custom system paths and restore raw direct network connectivity.

📝 License & Contributing
Contributions, bug reports, and optimizations are welcome! Feel free to open a Pull Request or file an Issue tracker ticket.

Developed with ♥ by Sam. Find more utilities or follow progress directly on GitHub.



