# What is Piux

**Piux** is a lightweight, experimental 32-bit x86 operating system built from scratch using NASM, freestanding C, and GNU `ld`. It boots via GRUB Multiboot1 and features its own custom text-based environment!

✨ **Key Features:**
* 🖥️ **pwm (Text Window Manager):** Tiled terminal environment supporting up to 4 split terminals with full mouse & keyboard focus!
* 🎨 **Framebuffer Graphics:** Native 1280×720 @ 32-bit color rendering with custom bitmap fonts & software double buffering (no flickering!).
* 💾 **Ext2 Filesystem & Persistent Editing:** Full read/write support on ext2 disks with a built-in `nano` text editor (plus RAMFS fallback).
* 🔒 **Auth & Installation:** Includes a first-boot installer TUI, user login, and SHA-256 password hashing.
* ⚡ **Ultra-Lightweight:** Runs on a minimum of **16 MiB RAM** and an **8 MiB disk**!

🛠️ **Quick Start (QEMU):**
``git clone https://github.com/madebyanto/piux-kernel.git &&
cd piux-kernel-main &&
make &&
make run``

Or simply run ``./fast-all.sh`` for an interactive setup TUI!
Check out the repo on GitHub: https://github.com/projectpiux/piux-kernel
