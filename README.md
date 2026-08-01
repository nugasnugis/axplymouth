sudo apt update && sudo apt install plymouth-themes -y
sudo plymouthd --debug; sudo plymouth show-splash --theme=/usr/share/plymouth/themes/debian-fallback/debian-fallback.plymouth; sleep 15; sudo plymouth quit
