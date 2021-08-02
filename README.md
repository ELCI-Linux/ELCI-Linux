👋 Hi, ELCI-Linux is an open source project aimed at creating a forked Linux distro for home use and deployment in small-to-medium sized business.
During the course of development, elements of the project will be published publicly for open collaboation and feed back.


As of August 2021, the framework for the general software installer is public.
Alphav1 features a combination of scripts designed to install and/or run various applications on debian based systems.
The alpha program
Alpha is a great tool for first time Linux users. 
Alpha includes ELCI software installer (with over 100 applications) 
Alpha gives you access to Tubi, an experimental YouTube-dl frontend. 


You can use Alphav2 by typing the command below into your terminal

    $ git clone https://www.github.com/ELCI-Linux/alphav2
    $ cd /alphav2

From here you can use any of individual install/run scripts

For example, to use the ELCI software installer type
the command below into your terminal:

    $ bash elci.sh



You can then follow the prompts on screen 
to execute over 100 automated software installs.

EmulatorsX installs a variety of Nintendo and Sony Platform Emulators

To run EmulatorsX, type in the following command:

        $ bash EmulatorsX.sh
      
 

Installs are grouped in categories. 


Mobile support tools:
  - These tools allow users to quickly install adb and scrcpy. 
  - iOS support is coming in Alphav1


Music Applications:
  - Audacious + Byte + Celementine + Gnome Music Plater  : Open source audio players.
  Audacious plays music without stealing away your computer’s resources from other tasks.
  - Ardour,Bitwig + Fami Studio: A suite of three open source DAWs.
  - Hydrogen: An open source drum machine.
  - Spotify: The official Spotify client for Linux
  - Lyrics: A Karaoke Application

  [Migrations]
  This script also installs Chiaki, which can be used for remote play with PS4 and PS5.
  Steam and Steamlink are also included. These will be migrated in future releases

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

        $ bash AndroidX.sh

EmulatorsX
    - EmulatorsX is an element of GameX that installs a variety of portable and home console emulators.
          
        $ EmulatorsX.sh

FranzXInstall
   - Installs Franz (a multiplatorm social media client)
GameX.sh
    - Installs emulators (via EmulatorsX), Steam (and SteamPlay) and Chiaki (PS4 and PS4 remote play support).
IPFirewallX
  -Installs an IP table Firewall (Script from github.com/ChrisTitusTech)

          $ bash IPFireWallX.sh
MusicX
    - Installs a variety of music players, including Terminal Players.
          
          $ bash MusicX.sh
NewsX
    - Installs a range of RSS feed readers and other News focused applications.
PacmanX
    - Installs the pacman Package manager
RSTwitterXInstall
    - Installs the Rainbow Stream terminal-based Twitter Client
VMOracleX.sh
  - Installs Virtualbox VM by Oracle  

WX
- Installs tools for running Windows Applications on Linux Desktop Devices.

      $ bash WX.sh

elci.sh Application List (Incomplete)

Digital Audio Workstations
  - Ardour
  - Bitwig Studio
  - Fami Studio
  - Muse
  - Hydrogen Drum Machine (Will be migrated from MusicX to DAWX in V3)

Mobile Support and Development
  - ADB (Android Debugging Bridge) + scrcpy (Wired Only)

Music Players (GUI'd)
   - Byte
   - Clementine
   - C*
   - Darling
   - Gnome Music Player
   - Spotify

Music Players (Terminal Based)
   - CMUS
   - MPC
   - mpg123
   - mp3 Blaster
   - SoX
   -


Nintendo system Emulators
  - Citra, DeSume and Melon (DS)
  - Dolphin (Gamecube + Wii)
  - mGBA (Gameboy + Gameboy Advanced)
  - Nestopia (NES)
  
Sony System Emulators
  - Duckstation (PS1)
  - PCXS2 (PS2)
  - RPCS3 (PS3)

TWitter Terminal Clients
  - Rainbow Stream

Windows On Linux
  - Bottles
  - Phoenecics
 
Virtualisation 
   - Boxes
   - Oracle VM

YouTube and Web Video
   - Youtube-dl

INCOMPLETE
- AMDGX: A tool to automate installation of AMD graphics drivers. 
- BrowsersX: A browser installation tool. 

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

Coming in Alpvav2
- Mobsup (updates) : 
ifuse integration, 
sndcpy (android audio forwarding) 


- Tubi (updates): bug fixes,ascii output support
- ELCI badger
- NAStalgia: Terminal based NAS creator tool
- Miracle Cast support (Linux Out)
- Britney: UK TV support (BBC iplayer downloads)
- Eddy: Automated education tool built on Tubi+Youyube-dl
- Googler (integration): terminal based Google search tool
- Cloudeee : Cloudflare automation tool



<!---
ELCI-Linux/ELCI-Linux is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
