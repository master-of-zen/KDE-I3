# .dot
Files for KDE + I3-gaps configuration, including Rofi and Compton-Tryone

## KDE preparation
1. Installing full KDE desktop. This is starting point.
2. In KDE settings center:
    1.Disabling 'Splash screen' (other way you will have splash that drawing over entire desktop)
    2.Disabling compositor startup on login
    3.Download wm.sh script and put him in ~./config , add script [wm.sh] in Autostart, set 'Run On' to 'Before session startup' (don`t forget tomake wm.sh executable)
3. Move 'i3' folder into ~/.config

## Instaling necessary packages
1. 'i3-gaps' (Window manager), 
2. 'compton-tryone-git' (Window compositor with trasparency and blur, alternatively install basic 'compton')
3. 'wmctrl' (Cli uttilite we use to close plasma on startup)
4. 'nitrogen' (For wallpaper management)
5. 'dunst' (Notification manager)

At this point computer can be rebooted into i3, dont forget to have default login session 'Plasma' 

## Optional installs
1. 'polybar' (Customizable bar)
2. 'rofi' (application startup application)
3. 'ttf-yosemite-san-francisco-font-git'(Good font)
