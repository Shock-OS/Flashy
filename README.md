# Flashy
Flashy is a frontend for Adobe Flash Player runtimes and emulators that automates the process of installing the emulators/runtimes and creating desktop shortcuts for Flash games.

### Build
Flashy is currently only available for Debian based Linux distributions, although porting to other distros should be easy for those who would like to contribute to that.

Flashy currently only has development builds. To build a .deb package of the flashy, run the following commands in a terminal:

```git clone https://github.com/Shock-OS/Flashy.git```

```dpkg-deb --build -Zxz Flashy```

```sudo dpkg -i Flashy.deb```

```rm -rf Flashy Flashy.deb```

### Features
Flashy currently has support for the following:
- Automated installation of emulators/runtimes
- A tool for creating desktop shortcuts for Flash games (creates a .desktop file and places it in ~/.local/share/applications/flashy)

### Emulators and Runtimes
The following emulators/runtimes are listed in order of compatibility.
- Adobe Flash Player Standalone (recommended if available, only available on x86_64, flatpak)
- Ruffle
- Lightspark
