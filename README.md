# junos-i3-configs
My custom i3 config files for i3WM.

1) install icons.ttf as well as MonofurNerdFont to your font folder. These are required for the icons to display correctly
2) move i3status config to ~/.config/i3status/ and rename to "config"
3) move i3 config to ~/.config/i3/ and rename to "config"
4) refresh i3, and the changes should take effect.

5) some tweaking may be required for your monitor outputs. Mine are set as HDMI-1 and DP-0, your monitors will likely have different names.
run xrandr in your terminal to get the proeper outputs. rather than declairing the correct orientation i used arandr in the CLI because im lazy. 

6) if you are on an amd card, comment out the nvidia startup command at the begining of the i3 config file. this will be of no use to you and may cause conflicts
