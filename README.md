## install needed app
```bash
sudo apt update && sudo apt install plymouth-themes -y
```
## download neccessary files and extract
## for simulate the plymouth
```bash
sudo plymouthd --debug; sudo plymouth show-splash --theme=/usr/share/plymouth/themes/debian-fallback/debian-fallback.plymouth; sleep 15; sudo plymouth quit
```
## force-close simulation
- How to exit early: If you get stuck or want to stop the test early, press Ctrl+Alt+F7 (or whatever F-key returns you to your graphical window) or switch to a secondary terminal window and kill it manually with: sudo plymouth quit.
