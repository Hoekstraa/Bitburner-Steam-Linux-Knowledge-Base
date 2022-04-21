# Bitburner-Steam-Linux-Knowledge-Base

This file contains a few helping hands to bitburner (Steam Linux variant) not starting up correctly.
It is assumed you are knowledgeable enough to use the package manager of your distro,
and to be able to find packages' names if they do not correlate with the names used in this guide.

Issues have been divided into categories, if you run into an issue, go through *all* possible problems/solutions within the category.

## Nothing happens when I start bitburner

### Arch Linux (or derivatives)
If you run an install of the Arch Linux distro or any of it's derivatives,
try starting the game with `--no-sandbox`.

### Libva

Have a look at the file `/home/$USER/.local/share/Steam/logs/cef_log.txt`;
If you get a similar error to [cef log libva](files/cef_log_libva.txt):

Install libva-intel-driver, libva-mesa-driver and/or any libva driver for the GPU brand you're using.


