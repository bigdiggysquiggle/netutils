possible improvements:
-use inotify to monitor processes instead of using test commands (/proc/net/wireless)
-might be able to use jctl instead
- journalctl -r -g wlp7s0 -n 1 --no-pager
-that lets me get the last message related to my wifi card
-might need to either dig deeper or find another way to get the last status of my wifi card

future features:
-profile building script
-place profiles into a user directory instead of /etc/netctl
--organize profiles by which device they connect on
---use directory name as a variable for scripts
