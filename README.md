Fork w. following changes:
- new mode where only current activity is shown & clicking cycles between them
- opacity selector for current activity

to test: `plasmoidviewer -a "$PWD" -l topedge -f horizontal && kquitapp6 plasmashell && kstart plasmashell`

to install: `kpackagetool6 --type Plasma/Applet --install . && kquitapp6 plasmashell && kstart plasmashell`

to upgrade: `kpackagetool6 --type Plasma/Applet --upgrade . && kquitapp6 plasmashell && kstart plasmashell`