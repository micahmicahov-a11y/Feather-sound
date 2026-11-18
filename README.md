# Feather Sound
Feather Sound is a minimalist, flicker-free CLI YouTube Music client built for Linux terminal enthusiasts. 
Unlike heavy TUI frameworks that cause screen tearing and terminal flashing, Feather Sound uses a completely static, lightweight text interface. It pairs the raw power of yt-dlp and mpv with a seamless, zero-config OAuth login flow, giving you a buttery-smooth music experience right in your terminal.
# Features
  Zero Flicker UI: Completely static text rendering. No heavy progress bars or layout loops means 0% screen tearing and instant response times.
  Zero-Config Auth: Uses public YouTube TV OAuth credentials. No need to manually create a Google Cloud project or copy-paste browser headers. Just click the link, log in, and play.
  Lightning Fast Search: Powered by yt-dlp's native search extractor for instant results.
  High-Quality Playback: Streams the best available audio directly through mpv.
  Auto-Setup: Includes a launcher.sh script that automatically detects your distro (Arch, Ubuntu, Fedora, etc.), installs dependencies, and sets up the Python virtual environment.

# Controls (kinda broken)
play/pause - 1
other controls don't work properly

# Quick Start
Clone the repo and run the launcher. It handles everything else. 

    git clone https://github.com/micahmicahov-a11y/Feather-sound.git 
    cd feather-sound 
    bash launcher.sh

# Dependencies
Feather Sound requires the following system packages (automatically installed by launcher.sh):
   
    python3
    mpv
    yt-dlp
    socat

Made with <3 by nicearchie.
