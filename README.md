# AVstudio Desktop (macOS & Windows)

AVstudio Desktop is a **cross-platform desktop edition of AVstudio Editor** for macOS and Windows. 
It provides a powerful, professional UI design environment for modern AV, automation, and control systems — optimized for working across **secure and non-secure networks**, **mixed environments**, and **real-world integration constraints**.

This repository hosts the desktop distribution of AVstudio Editor for:
- **macOS**
- **Windows**


Download links:

- [AVstudio Editor 1.0.1 arm64 Win.zip](https://github.com/AVstudio-Inc/avstudio-editor-desktop/raw/refs/heads/main/Windows/AVstudio%20Editor%201.0.1%20arm64%20Win.zip)
- [AVstudio Editor 1.0.1 x64 Win.zip](https://github.com/AVstudio-Inc/avstudio-editor-desktop/raw/refs/heads/main/Windows/AVstudio%20Editor%201.0.1%20x64%20Win.zip)
- [AVstudio Editor-1.0.1-arm64.dmg](https://github.com/AVstudio-Inc/avstudio-editor-desktop/raw/refs/heads/main/Mac%20OS/AVstudio%20Editor-1.0.1-arm64.dmg)


## What Is AVstudio Desktop?

AVstudio Desktop is a **local desktop application** that runs AVstudio Editor outside of a browser, while still requiring an **internet connection**.

Its primary advantage is **environment flexibility** — allowing UI designers and integrators to work with:
- Secure networks
- Non-secure networks
- Self-signed SSL certificates
- CORS-restricted APIs
- Mixed HTTP / HTTPS environments

This makes AVstudio Desktop especially valuable for **professional AV and IT workflows**, where browser security policies often block real integrations.

---

## Key Capabilities

### Full AVstudio Editor
AVstudio Desktop includes the complete AVstudio Editor experience:
- Visual WYSIWYG UI editor
- Page-based navigation and layouts
- Containers, lists, and reusable components
- Responsive design for touch panels and tablets
- HTML5, CSS, and JavaScript extensibility
- Data-driven UI via JSON and APIs
- Live preview

---

### Secure & Non-Secure Environment Support
Unlike browser-only tools, AVstudio Desktop can work in **real integration environments**:

- Connect to HTTP and HTTPS endpoints
- Work with **self-signed certificates**
- Bypass typical browser CORS limitations
- Integrate with local or remote APIs
- Test against development, staging, and production systems

This makes it ideal for:
- Commissioning
- Lab environments
- On-site development
- Controller-local APIs
- Prototyping against unfinished systems

---

### Control-System Agnostic by Design
AVstudio Desktop is **not tied to any single control system or manufacturer**.

Interfaces can communicate using:
- WebSocket
- HTTP / REST
- MQTT
- JSON APIs
- Custom JavaScript logic

Common ecosystems include (but are not limited to):
- AMX (NetLinx / MUSE)
- Crestron (CH5 / Web UI)
- Node-RED
- Q-SYS
- Custom controllers and services

---

## Installation

There is **no installer**.

Installation is simple:
1. Download the archive for your platform
2. **Unarchive**
3. Run AVstudio Desktop

No system-level installation or admin privileges required.

---

## Output & Deployment

### Project Output Format
AVstudio Desktop exports projects as a **ZIP archive**.

This archive can be deployed to:
- Crestron touch panels (e.g. TS-1070, TS-1080)
- Android-based touch panels
- Embedded web runtimes
- Custom control system web servers
- PWA
- IOS devices

---

### App Container (iOS / Android)
For mobile platforms, AVstudio provides **App Container**.

Important:
- App Container can host **any web project** even created in Notepad, VS Code, Crestron Construct
- Projects do **not** need to be created in AVstudio
- Works with HTML/CSS/JS from any tool or framework

App Container supports:
- Local project hosting
- Switching between multiple projects
- iOS and Android deployment
- Secure and non-secure connections

AVstudio Desktop + App Container together form a complete **cross-platform UI workflow**.

---

## Why Use AVstudio Desktop?

### Built for Real-World Integration
AVstudio Desktop exists because:
- Browsers enforce strict security rules
- AV systems rarely follow “web-perfect” conditions
- Integrators need freedom, not limitations

This version gives you **control over the environment**, not the other way around.

---

### Vendor-Independent UI Strategy
Your UI:
- Is not locked to a controller
- Is not locked to a panel
- Is not locked to a vendor ecosystem

Interfaces remain reusable even when:
- Hardware changes
- Control systems change
- Backend logic evolves

---

### Ideal Use Cases
- Professional AV integrators
- UI/UX developers for control systems
- Manufacturers building demo interfaces
- Consultants and system designers
- Complex multi-room and enterprise AV projects
- Secure or mixed-security environments

---

## Desktop vs Browser-Only Editors

| Feature | Browser-Only Tools | AVstudio Desktop |
|------|------------------|------------------|
| Self-signed SSL | ❌ | ✅ |
| CORS flexibility | ❌ | ✅ |
| Secure / non-secure mix | ❌ | ✅ |
| Local API access | Limited | Full |
| Large project stability | Medium | High |
| Real integration testing | Limited | Full |

---

## Compatibility

AVstudio Desktop projects:
- Use standard web technologies
- Are portable and future-proof
- Can be deployed across multiple platforms
- Can be reused outside AVstudio if needed

---

## Official Resources

- Website: https://avstudio.app 
- Documentation: https://docs.avstudio.app 
- Community & Updates: https://community.avstudio.app 
- YouTube: https://www.youtube.com/@AVstudioApp 

---

## Philosophy

AVstudio Desktop is built around a simple idea:

> **UI should be flexible, portable, and independent — not constrained by vendor tools or browser policies.**

Controllers handle logic. 
UI handles presentation. 
AVstudio connects the two — cleanly and openly.

---

## Feedback

This project is actively developed.

Feedback, bug reports, and feature discussions are welcome via the community portal.