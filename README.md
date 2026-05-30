# rOS 2.0 🚀

Welcome to **rOS**, a custom-tailored, lightweight, and highly portable operating system built for developers, power users, and tech enthusiasts. Designed to run completely live from a single USB drive, rOS gives you an indestructible desktop environment you can carry in your pocket.
rOS is distributed as a monolithic system image. To modify or contribute, download the ISO and unpack the squashed filesystem.
SCROLL AT THE BOTTOM FOR DOWNLOAD LINK

---

## 💳 Credentials

Credentials Are Here For The Live System - 

Username - ros

password and sudo password - ros

---

## ✨ Features

- **Ubuntu MATE 20.04 Engine:** Powered by a rock-solid, incredibly stable Linux core with excellent hardware compatibility.
- **Native YAD Applications:** Includes custom, lightweight utility apps built completely from scratch using graphical bash scripts.
- **Sleek Aesthetics:** Fully pre-configured with the premium **Papirus Dark** icon pack and matching modern dark mode themes.
- **Zero-Footprint Live CD:** Runs entirely in your computer's temporary memory (RAM). Your physical hard drive remains completely untouched unless you choose to install.

---

## 💻 System Requirements

- **Processor:** Intel or AMD 64-bit CPU (`amd64` architecture).
- **Memory:** 2 GB RAM minimum (4 GB recommended for smooth web browsing).
- **Storage:** A USB flash drive with at least 8 GB of free space (Ventoy recommended).
- *Note: This OS is designed for standard PC hardware and will not boot on older ARM micro-computers like the Raspberry Pi 1.*

---

## 🚀 How to Try rOS

1. **Download the ISO:** You can download the ISO file from here!
2. **Bootable** Get a pendrive and use any software to make the drive bootable as you do.
4. **Boot Up:** Restart your computer, enter your boot menu (usually F12, F11, or F8), select your USB, and launch **rOS 2.0**!

---

## 🛠️ Versioning Strategy

We follow a structured adaptation of Semantic Versioning to track development:
- **Major (X.0.0):** Tracks the underlying Base OS engine (e.g., `2` for Ubuntu MATE 20.04 base).
- **Minor (2.X.0):** Tracks major feature milestones, custom application additions, and design sprints.
- **Patch (2.1.X):** Tracks quick stability updates, optimization patches, and software bugfixes.

---

## 📄 License

This project is proudly licensed under the **GNU General Public License v3 (GPLv3)**. This ensures that rOS remains free, open-source, and community-driven forever. 

## 📜  Log

Here is the log which i made to tell how this OS was developed - 

rOS 2.0.0 Build Log

Base:

* Ubuntu MATE 20.04 (VM)

Cleanup (Debloat):

* Removed: libreoffice*, thunderbird, aisleriot, gnome-mahjongg, gnome-mines, gnome-sudoku
* Removed: rhythmbox, transmission*, cheese
* Removed: hexchat, pidgin, simple-scan, drawing
* Removed: firefox
* Removed: snapd
* Removed: fonts-noto-cjk
* Removed: mate-user-guide

System Optimization:

* Disabled: bluetooth.service
* Disabled: cups.service
* Disabled: avahi-daemon.service
* Disabled: update-notifier
* Disabled: compositing (MATE settings)

Base Features Installed:

* neofetch (system info branding)
* htop, bashtop (system monitoring)
* gnome-disk-utility, gparted (disk tools)
* vlc (media player)
* featherpad (lightweight text editor)
* synaptic (GUI package manager)
* curl, wget, git (core tools)
* zenity (GUI dialogs for scripts)
* cowsay, lolcat (fun/branding)

Custom System Setup:

* Created directory: /opt/rOS-apps/packs
* Added script packs:

  * gamer.sh
  * student.sh
  * dev.sh
  * minimal.sh
* Made scripts executable

System State:

* Idle RAM ~860MB
* Swap usage minimal

- Replaced: bashtop → btop (not available in repo)
- Skipped: btop -> Not AVailable
- Used .bashrc to enforce custom neofetch ASCII branding
- Added custom neofetch branding via .bashrc (forced ASCII method)
- Terminal now shows rOS 2.0.0 branding on launch

- Customized desktop UI:
  - Applied Arc-Dark theme
  - Applied Papirus icons
  - Modified panel layout
  - Set custom wallpaper (rOS branding)
  - Cleaned desktop icons
  
  - Reset /opt/rOS-apps structure
- Recreated all script packs cleanly
- Improved app selection for Gamer, Student, Dev, Minimal packs
- Rebuilt Welcome App using YAD
- Added button-based UI for pack selection
- Enabled auto-start on login

- Rebuilt Welcome App v2
- Added startup toggle checkbox
- Added buttons for packs, HTML apps, Control Center, About
- Replaced old welcome app autostart

- Created rOS Special Control Center
- Added cleanup/update/system info tools
- Integrated script packs into control center
- Added desktop launcher
- Added rOS Welcome to applications menu
- Added rOS Control Center to applications menu
- Registered desktop entries

- Created rStore HTML application
- Added built-in packs section
- Added desktop launcher for rStore
- Rebuilt rStore using YAD
- Rebuilt About rOS using YAD
- Removed browser dependency for core apps
- Improved startup speed and native feel
- Removed Luakit browser
- Removed old HTML-based rStore launcher
- Switched core apps fully to YAD
- Created rNotes sticky-note style app
- Added persistent note saving
- Added applications menu launcher
- Created rArcade game hub
- Added DVD Bounce simulator
- Added Fake Hacker terminal
- Added Clicker mini-game
- Added applications menu launcher
- Made rNotes App
-Fixed Menu Problem WIth rNotes
- Created rBrowser Start app
- Added quick web links and system shortcuts
- Added applications menu launcher
- Created rCleaner utility
- Added cache cleanup tools
- Added temp file cleanup
- Added applications menu launcher
- Created rSysInfo app
- Added RAM, CPU, disk, uptime, kernel information
- Added applications menu launcher
- Installed Audacious lightweight music player
- Created rMusic music hub
- Added music folder integration
- Added applications menu launcher
- Created rFiles Guide app
- Added filesystem and folder explanations
- Added applications menu launcher

  # rOS 2.1.1 [BETA] Update Log

  Change Log For rOS 2.1.1

-----

1. Added Libreoffice Suite Back. 
2. Fixed Minor Bugs. 
3. Removed Firefox. 
4. Added Firefox ESR. 
5. [BETA] Added Local Repository For .deb Packages Tailored To The Core of rOS. 
6. Terminal Colour Scheme Has Been Changed. 
7. Revamped The look of the panels. 

[NOTE THAT THE RELEASE rOS 2.1.1 WILL BE IN BETA FOR 1 MONTH]


-----


## 📲 | DOWNLOAD |

 rOS 2.0.0 [STABLE] - https://drive.google.com/file/d/1r3lNmvvEcIGmtmaiAGzQtJVr6FT0i_lb/view?usp=drive_link

 rOS 2.1.1 [BETA] - COMING SOON
