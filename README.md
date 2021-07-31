👋 Hi, ELCI-Linux is an open source project aimed at creating a forked Linux distro for deployment in small-to-medium sized business.
During the course of development, elements of the project will be published publicly for open collaboation and feed back.
As of August 2021, the framework for the general software installer is public.
Alphav1 features a combination of scripts designed to install and/or run various applications on debian based systems.

You can use Alphav1 by typing 

$ git clone https://www.github.com/ELCI-Linux/Alphav1

Once downloaded open the folder in your terminal and type in

$ bash elci.sh

You can then follow the use the terminal to execute over 100 automated software installs.
Installs are grouped.


Mobile support tools:
  - These tools allow users to quickly install adb and scrcpy. 
  - iOS support is coming in Alphav1
Music:
  - Audacious + Byte + Celementine + Gnome Music Plater  : Open source audio players.
  Audacious plays music without stealing away your computer’s resources from other tasks.
  - Ardour,Bitwig + Fami Studio: A suite of three open source DAWs.
  - Hydrogen: An open source drum machine.
  - Spotify: The official Spotify client for Linux
  - Lyrics: A Karaoke Application
    
Emulators:
    Nintendo system Emulators
  - Citra, DeSume and Melon (DS)
  - Dolphin (Gamecube + Wii)
  - mGBA (Gameboy + Gameboy Advanced)
  - Nestopia (NES)
  
    Sony System Emulators
  - Duckstation (PS1)
  - PCXS2 (PS2)
  - RPCS3 (PS3)
  [Migrations]
  This script also installs Chiaki, which can be used for remote play with PS4 and PS5.
  Steam and Steamlink are also included. 

Linux Software package Installers
  - Pacman
  - Flatpak
  
(System) Terminal Emulators
  - Terminator
  - Yakuake
  
Mobile OS Support
  - ADB (Android Debugging Bridge)
  - scrcpy (ADB Assisted Android-to-Linux screen mirroring)
  
 Virutalisation (Virtual Machines)
 - Oracle Virtualbox
 
ELCI Shell Apps (In Development)
  These apps are designed by ELCI using bash scripts to automate Terminal Processes.
   TubiX
    - TubiX is a terminal based Front-End for the Youtube-dl application.
  
Working ELCI Installers
To use any of these installers type in
$ cd alphav1
$ bash "filename.sh"

elci
  - Installs neofetch via NeofetchX
  - Instals pacman via PacmanX
  - Installs console emulators via EmulatorsX
  - Installs Music Players via MusicX
  - Installs video conferancing and messaging tools via ToolsX.sh
  - Installs mobile specific applications in MobSupX
  - Installs Terminal Emulators via TermEmuX
  - CS: Install Steam, Steamplay, Discord and Chiaki via GameX
AndroidX
  - AndroidX is the element of MobSupx designed to install Android specific applications
EmulatorsX
    - EmulatorsX is an element of GameX that installs a variety of portable and home console emulators.
FranzXInstall
   - Installs Franz (a multiplatorm social media client)
GameX.sh
    - Installs emulators (via EmulatorsX), Steam (and SteamPlay) and Chiaki (PS4 and PS4 remote play support).
IPFirewall
  -Installs an IP table Firewall (Script from github.com/ChrisTitusTech)
MusicX
    - Imnsta;;s a variety of music players and production tools, including DAWs and Terminal Players,
NewsX
    - Installs a range of RSS feed readers and other News focused applications.
PacmanX
    - Installs the pacman Package manager
RSTwitterXInstall
    - Installs the Rainbow Stream terminal-based Twitter Client
VMOracleX.sh
  - Installs Virtualbox VM by Oracle   
YouTubeUtilityX
  - Installs Youtube-dl, an open-source YouTube Downloader. 
    
  

👀 I’m interested in:
  - expanding the library of applications available through ELCI.sh
  - adding more complex command-based install instructions to the installer scripts.
  - Improving the graphical interface for the individual installers and TubiX
  - Building a GUI for future ELCI Installer versions./
  - Adding HDMI CEC applications
  -
  - Automating the install process for AMD and Nvidia Graphics and Display Drivers
  - Macrodroid and IFTTT integration
  - Google Assistant and Alexa integration
  
  
🌱 I’m currently learning bash scripting for automation, linux application install methods.
- 💞️ Now that a simple terminal-based installer for applications has created
📫 How to reach me
  - Twitter: @danniwah

<!---
ELCI-Linux/ELCI-Linux is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
