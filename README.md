Repositories Used:
i3, i3-wm, i3status, i3blocks, feh, compton

Fonts used:
https://github.com/FortAwesome/Font-Awesome

Issues:
Adding new logo fonts from Font-Awesome dosent seem to work when compton is executed within the config file. To resolve this issue, remove the line "exec_always compton" before adding a new logo font to one of the workspace varibles.
