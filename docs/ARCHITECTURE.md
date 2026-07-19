# FlexOS NEXT Architecture

## Overview

FlexOS NEXT is a next-generation operating system based on Arch Linux. Its goal is to provide a modern, fast, flexible, and highly customizable experience for desktop users while maintaining the simplicity and performance of its Linux foundation.

---

## Layers

```text
Hardware
    ↓
Linux Kernel (Arch Linux)
    ↓
FlexCore
    ↓
FlexUI
    ↓
FlexApps
```

---

## Components

### FlexCore

The core of FlexOS NEXT. Responsible for system services, startup, process management, configuration, and communication between system components.

### FlexUI

The graphical user interface of FlexOS NEXT. Includes the desktop, window manager, launcher, taskbar, notifications, and system settings.

### FlexApps

Native applications developed specifically for FlexOS NEXT.

Examples:

- File Manager
- Settings
- Terminal
- Software Center
- Text Editor

### Build

Contains build scripts, packaging tools, configuration files, and ISO generation.

---

## Goals

- Modern user experience
- Lightweight and fast
- Modular architecture
- Open source
- Easy customization
- Stable and secure
- Designed for everyone

---

## Development Status

Current Version:

**Pre-Alpha 0.0.1**

### Roadmap

- [x] Repository created
- [x] Initial project structure
- [x] Architecture documentation
- [ ] FlexUI prototype
- [ ] Window manager
- [ ] Settings application
- [ ] File manager
- [ ] Software Center
- [ ] First bootable ISO

---

## License

Licensed under the GNU General Public License v3.0 (GPL-3.0).
