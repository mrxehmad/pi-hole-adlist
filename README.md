# Pi-hole Adlist

This repository contains lists of domains to be used with Pi-hole, a network-wide ad blocker. These lists can be added to your Pi-hole configuration to block ads and other unwanted content at the network level.

> [!NOTE]
> If somthing breaks please report that in issues

## Lists Available

### PUBG Domains

The `pubg-block.txt` file contains a list of domains associated with PUBG (PlayerUnknown's Battlegrounds), a popular online multiplayer battle royale game. These domains are often used for tracking, ads, or other unwanted content related to the game.

To use this list, add the following URL to your Pi-hole configuration:

https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/pubg-block.txt

### Snapchat Domains

The `snapchat-pihole` file contains a list of domains associated with Snapchat, a multimedia messaging app. These domains may include tracking, ads, or other unwanted content related to the app.

To use this list, add the following URL to your Pi-hole configuration:

https://github.com/mrxehmad/pi-hole-adlist/raw/main/snapchat-pihole

### Instagram Domains

The `instagram-pihole` file contains a list of domains associated with Instagram, a popular social media platform. These domains may include tracking, ads, or other unwanted content related to the app.

To use this list, add the following URL to your Pi-hole configuration:

https://github.com/mrxehmad/pi-hole-adlist/raw/main/instagram-pihole

### TikTok Domains

The `tiktok-pihole` file contains a list of domains associated with TikTok, a video-sharing social networking service. These domains may include tracking, ads, or other unwanted content related to the app.

To use this list, add the following URL to your Pi-hole configuration:

https://github.com/mrxehmad/pi-hole-adlist/raw/main/tiktok-pihole

### DNS over HTTPS (DoH) Domains

The `doh-list` file contains a list of domains associated with DNS over HTTPS (DoH) providers. DoH is a protocol for performing remote Domain Name System (DNS) resolution via the HTTPS protocol. While DoH offers privacy benefits, some users may prefer to block connections to DoH providers for various reasons.

To use this list, add the following URL to your Pi-hole configuration:

https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/doh-list

### HiTV ad Domains

The `hitv.list` file contains a list of domains associated with HiTV ads, a video-sharing social networking service. These domains may include tracking, ads, or other unwanted content related to the app.

To use this list, add the following URL to your Pi-hole configuration:

https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/hitv.list

## huawei-block-list

It's a block list. You can integrate this into your PiHole or local blocking software such as Blokada, AdAway... etc. to block out all the outgoing connections to the said domains.

It turns out, if your device has bloated softwares(ie. Apps that comes pre-installed and you can't remove them unless you root your device, you're forced into keeping those services running. Manufacturers like Huawei have stopped providing bootloader unlock codes thereby not allowing you to root your device. So, the best solution is to setup a local proxy server that blocks the connection. 

https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/huawei-host

## How to Use

To add these lists to your Pi-hole, follow these steps:

1. Log in to your Pi-hole admin interface.
2. Select the "Adlists" tab.
3. Enter the URL of the list you want to add.
4. Click on "Add" and then click on "Save and Update".

Your Pi-hole will now block the domains listed in the added lists.

## Contribution
These lists are not 100% accurate and I try my best to update these lists. If something is missed, please contribute to this repo 😊 

Contributions to this repository are welcome. If you have additional domains to add to the lists or suggestions for improvement, feel free to open an issue or submit a pull request.

## Disclaimer

While these lists aim to block unwanted content, they may also block legitimate content. Use them at your own discretion. The maintainers of this repository are not responsible for any unintended consequences of using these lists.

## Credit

- https://github.com/wranders/doh-list
- https://github.com/oneoffdallas/dohservers
- https://github.com/MohamedElashri/doh-list
- https://github.com/deep-bhatt/huawei-block-list
