# Compact OneRingTranslator installer for Windows

## How to launch

1. Run "install" to download OneRingTranslator and install dependencies.
2. Launch "start-webapi.bat" to start service.

3. To get application updates, run "install" again.
This will only install updates, so it should be much faster.

You can open a command prompt connected to a virtual environment by running the "micro mamba-cmd" script.

Based on https://github.com/oobabooga/one-click-installers

## Transfer to another machine / to another location

The installation is portable; but after transferring to another location, it will give the error "Micromamba not found"

To solve the problem, delete all the BAT files from installer_files\mamba\condabin and restart OneRingTranslator -
BAT files will be regenerated.