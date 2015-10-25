# rtpengine-systemd
Runing Sipwise RTPEngine under systemd control.

Follow these steps:

	# git clone https://github.com/Binan/rtpengine-systemd.git

	# cd rtpengine-systemd

Edit the configuration file " rtpengine-conf " to reflect your configuration. Then install the files:

	# cp rtpengine-conf /etc/default/rtpengine-conf

	# cp rtpengine.service /usr/lib/systemd/system/rtpengine.service

	#  cp rtpengine-start /usr/bin/rtpengine/rtpengine-start
	#  cp rtpengine-stop /usr/bin/rtpengine/rtpengine-stop

	# chmod +x rtpengine-start

	# chmod +x rtpengine-stop

Restart your system. Check if RTPEngine is working under systemd control.
