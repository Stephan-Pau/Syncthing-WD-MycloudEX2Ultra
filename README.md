# Syncthing-WD-MycloudEX2Ultra
Syncthing for WD Mycloud EX2 Ultra and Mycloud OS 5
<br>
<br>

The included binary file was downloaded from https://syncthing.net/
<br>
It was packaged with the instructions listed on https://github.com/WDCommunity/wdpksrc
<br><br>


For license and instructions how to use, please refer to https://syncthing.net/

<br><br><br>

root@debian:/home/s/wdpksrc# docker run -it -v $(pwd):/wdpksrc wdpk /bin/bash<br>
root@4b13fa40272f:/wdpksrc# cd wdpk/syncthing/<br>
root@4b13fa40272f:/wdpksrc/wdpk/syncthing# ../../mksapkg-OS5 -E -s -m MyCloudEX2Ultra<br>

============================================<br>
	mksapkg-OS5 version: 2.0<br>
============================================<br>
MinFWVer: []<br>
MaxFWVer: []<br>
<br>
***[../MyCloudEX2Ultra_syncthing_1.18.1.bin(08082021)]<br>

NAS type:		MyCloudEX2Ultra<br>
module name:		syncthing<br>
module versioin:	1.18.1<br>
packager:		Spa<br>
<br>
header length:		8720664<br>
header checksum:	7338AC2D<br>
<br>
Add-ons "../MyCloudEX2Ultra_syncthing_1.18.1.bin(08082021)" create!<br>
