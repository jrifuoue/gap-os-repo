# GAP OS Custom Repository

Welcome to the **GAP OS Custom Repository**, crafted specifically for my personal distribution, **GAP OS**. This repository provides prebuilt binary packages aimed to simplify package management and speed up installations.

---

## About

This repository was created primarily to serve **GAP OS**, my custom Arch-based distribution. However, it is fully compatible and can be integrated with **any Arch Linux based system**, including vanilla Arch Linux itself.

---

## Features

- Prebuilt binary packages for faster installs  
- Includes popular packages difficult to install or compile from AUR (e.g., `yay-bin`, `paru-bin`, `neofetch-git`)  
- Easy to add to your pacman configuration  
- Regular updates depending on maintenance capacity

---

## Usage

1. Add this repository to your `/etc/pacman.conf`:

   ```ini
   [gap-os-repo]
   SigLevel = Optional TrustAll
   Server = https://raw.githubusercontent.com/jrifuoue/gap-os-repo/main/x86_64
2. Update your package list:
   ```ini
    sudo pacman -Sy

3. Install packages as usual:
    ```ini
    sudo pacman -S yay-bin paru-bin neofetch-git

Important Notes

    This repository is maintained by a single developer (me!).

    Package versions might lag behind AUR or official repos due to manual maintenance.

    This repo is intended as a convenience for easier access to specific binaries and may not always have the latest versions.

    If you want the newest versions, consider using AUR or official Arch repos.

    Contributions and feedback are welcome — check the issues tab or contact me directly!

Disclaimer

Use this repository at your own discretion. I am not responsible for any issues arising from the use of these packages or the repository.

Thanks for checking out GAP OS repo!
Let’s make Arch-based distros simpler, together. 🚀

