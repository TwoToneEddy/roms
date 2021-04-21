Repo to store roms and save states

The following emulators should be used for the save states to be transferrable:

SNES      = lr-snes9x2010

NES       = lr-nestopia

GB        = lr-gambatte

GBC       = lr-gambatte

GBA       = lr-gpsp

MEGADRIVE = lr-picodrive


You can find which emulators are currently configured with the following command:

Retropie:
grep -nr --include emulators.cfg default /opt/retropie/configs
