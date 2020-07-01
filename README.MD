I wrote this as a means to run netctl with pop-up
notifications in order to merge the things I like
about netctl and the things I like about other
network managers. It effectively automates the use
of netctl and its associated profiles so all I
have to do is log in and my leptop gets itself
some internet. It's designed such that you can
either run 'connection-monitor' or
'wifi-manager start' on startup (such as, for
example in an i3 config). 'wifi-manager' also works
as a means to start and stop the scripts from a
terminal if for some reason that is needed. Planned 
features and half-thoughts are included in TODO.MD

If for some reason you stumbled across this repo
and decided you wanted to make use of it, it's
written under the assumption that wherever you
		sudo netctl stop-all &> /dev/null
place these scripts is added to your $PATH
