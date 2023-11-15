######## Juno's dot files ###########
My custom dot files that I use on arch with i3.

1) install MonofurNerdFont from nerd fonts to your font folder. This is the font i use, and it is required for the icons to display correctly, including those cute little pawprints!
2) move i3status config to ~/.config/i3status/ and rename to "config"
3) move i3 config to ~/.config/i3/ and rename to "config"
4) refresh i3, and the changes should take effect.

5) some tweaking may be required for your monitor outputs. Mine are set as HDMI-1 and DP-0, your monitors will likely have different names.
run xrandr in your terminal to get the proeper outputs. rather than declairing the correct orientation i used arandr in the CLI because im lazy. 

6) if you are on an amd card, comment out the nvidia startup command at the begining of the i3 config file. this will be of no use to you and may cause conflicts

7) For picom i am using picom-git from the AUR
8) My alacritty config has been changed slightly and it took a while for me to track down the original file, so i figured i would post it here for others to use.

# Some of these files are not modified yet, I have to rebuild my system over the course of the next few days. So these files are being dumped here so that I can fetch them later on. Following that they will be modified and edited. Please bear with me, I am in fact, just a silly doggo 󱙵󱙵󱙵
