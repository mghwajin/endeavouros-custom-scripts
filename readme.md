# Endeavour OS custom scripts
This repo is a collection of beginner-friendly scripts I've created as general tools or workarounds. 

The collection will grow slowly as I slowly experiment with tweaking scripts to work on my personal setup.

## Content
- [xfce4-screenshooter-autosave](scripts/xfce4-screenshooter-autosave) - Automatically save a fullscreen screenshot with the date appended to the filename. Bypasses the window waiting for filename input from user. Useful keyboard shortcut.
- [convert-to-mp3](scripts/convert-to-mp3) - Requires `ffmpeg`. Runs a custom action in `Thunar` file manager to convert a selected video file into an .mp3 file. Script sets `ffmpeg` to use VBR (variable bit rate) for the highest possible audio quality.

## General tips
1. These scripts may require you to edit them slightly to match your setup.
    - Example: A script containing `/home/some-username` should be edited to match your `/home/user` directory.

2. Make sure to set the scripts as executable files with the `chmod` command: `chmod +x custom-script.sh`

3. Create a `/home/user/bin` directory to place your custom scripts for easy access and organization.

---

**Revision history**
- 01/2026 - Add convert-to-mp3 script, update readme

<!-- EOF -->