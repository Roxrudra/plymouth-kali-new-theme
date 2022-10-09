
# plymouth-kali-new-theme
Slightly different Kali-linux splash screen

![](https://github.com/Roxrudra/plymouth-kali-new-theme/blob/main/kalinew.gif)

## Instructions
1. unzip the downloaded `.zip` file
2. copy the `kalinew/` directory to `/usr/share/plymouth/themes/`
3. Run the `plymouth-set-default-theme` command as root
``` 
sudo plymouth-set-default-theme -R kalinew
```
### Alternatively
After unzipping the `.zip` file run the `install.sh` script provided as `root`
```
chmod +x install.sh
sudo ./install.sh
```
