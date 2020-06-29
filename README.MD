This is a set of scripts I wrote that allows me to
completely get rid of NetworkManager. It effectively
automates the use of netctl and its associated
profiles so all I have to do is log in and my leptop
gets itself some internet. It's designed such that
you can either run 'connection-monitor' or
'wifi-manager start' on startup (such as, for example
in an i3 config). 'wifi-manager' also works as a
means to start and stop the scripts from a terminal
if for some reason that is needed. Planned features
and half-thoughts are included in TODO.MD
