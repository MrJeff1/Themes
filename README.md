# Themes
themes for linux mint
# Installation
run this command in terminal ***linux only***
```bash
git clone https://github.com/MrJeff1/Themes.git
cd Themes
tar --use-compress-program=unzstd -xvf themes.tar.zst
tar --zstd -xvf themes.tar.zst
sudo rm themes.tar.zst -f -r
sudo rm README.md -f -r
sudo mv ~/Themes/* ~/.themes
reboot # rebooting is optional
```
# Done!
have fun!
