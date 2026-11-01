# Syncthing for WD My Cloud EX2 Ultra

The included package installs Syncthing v2.1.7 on the My Cloud EX2 Ultra with OS 5.
Installation downloads the official Syncthing binary and requires internet access.
Syncthing can update itself after installation; the WD package version does not change.

## Installation

1. Download [MyCloudEX2Ultra_syncthing_2.1.7.bin](MyCloudEX2Ultra_syncthing_2.1.7.bin).
2. Back up your Syncthing configuration and data before replacing an existing installation.
3. Install the package manually through the My Cloud OS 5 Apps interface.
4. Open `http://NAS-IP:8384` and configure GUI authentication.

SHA-256: `ae3a0bebff99968f19d88f980e680bc8031dd95a4397c4c7646ad54e7db8d5a5`

## Source

The package is built from [WDCommunity/wdpksrc](https://github.com/WDCommunity/wdpksrc/tree/master/wdpk/syncthing).
This version uses [commit 0fd3214](https://github.com/Bischtinius/wdpksrc/tree/0fd3214055bdc534f7cad174a7b11a9703f715fe/wdpk/syncthing), proposed in [WDCommunity/wdpksrc#133](https://github.com/WDCommunity/wdpksrc/pull/133).

See [Syncthing documentation](https://docs.syncthing.net/) for usage and licensing.
