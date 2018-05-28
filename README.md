**Athens (Greece) FM Radios pls files**

These pls files were heavily based on the following m3u file:

https://gist.github.com/dennmtr/ac14e66adca47e5f7d60


In order to use them with Archphile, you will need to do the following:

	get https://github.com/archphile/AthensFMRadios/archive/master.zip
	unzip master.zip
	mv AthensFMRadios-master /var/lib/mpd/music/webradio-athens-fm
	chown -R mpd:audio /var/lib/mpd/music/webradio-athens-fm/
	rm master.zip
