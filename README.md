Woogaloo -- a bash+yad application which provides a GUI toward easing
assorted system tweaking, and administrative, tasks.

derived from "UnlockMe" by Ralphy Rhdez https://github.com/ralphys <br>
License: GPLv2, or later


## WIP 
This prototype is a work-in-progress

BUG (same as observed in other yad apps):
needlessly tall window height when rendering wordwrapped text
TODO: try using --fixed (yad manpage states: Makes window fixed width and height)

TODO: consider placing a 4th column, display help icon for idividual line items
(open helpdocs in antix-viewer / mx-viewer)

<!--
	$ dpkg-query -S /usr/local/bin/zram
antix-goodies: /usr/local/bin/zram
demo@antix1:/usr/share/applications
$ dpkg-query -S /sbin/zramctl
util-linux: /sbin/zramctl
	$ locate zswap
/usr/src/linux-headers-4.10.5-antix.3-amd64-smp/include/config/zswap.h
/usr/src/linux-headers-4.13.4-antix.1-amd64-smp/include/config/zswap.h
-->


## Screenshots
![](https://vgy.me/4YOcm2.png)
