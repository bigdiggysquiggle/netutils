possible improvements:
-journalctl -g wlp7s0 -r -n 1 --output-fields=dhcpcd --no-pager
-- lets me get the last dhcpcd message related to my wifi card
relevant messages:
Jun 28 18:28:52 Nuthouse dhcpcd[9983]: wlp7s0: deleting default route via 10.10.254.254
Jun 28 18:28:52 Nuthouse dhcpcd[9983]: wlp7s0: deleting route to 10.10.0.0/16
Jun 28 18:28:52 Nuthouse dhcpcd[9983]: wlp7s0: carrier lost
Jun 28 18:28:52 Nuthouse kernel: wlp7s0: deauthenticating from 00:f6:63:fa:75:41 by local choice (Reason: 3=DEAUTH_LEAVING)

future features:
-profile building script
-place profiles into a user directory instead of /etc/netctl
--organize profiles by which device they connect on
---use directory name as a variable for scripts
-attempt to connect through a given profile passed as argument
-consider having the script exit if networks are unavailable unless told otherwise
-consider having wifi-manager disown the process after the connection has been established so I don't feel like I can do internet things too early
-make the scripts identify the wireless device instead of hardcoding it in
