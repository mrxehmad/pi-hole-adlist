# Pi-hole Adlist

This repository contains lists of domains to be used with Pi-hole, a network-wide ad blocker. These lists can be added to your Pi-hole configuration to block ads and other unwanted content at the network level.

## Lists Available

### PUBG Domains

The `pubg.txt` file contains a list of domains associated with PUBG (PlayerUnknown's Battlegrounds), a popular online multiplayer battle royale game. These domains are often used for tracking, ads, or other unwanted content related to the game.

To use this list, add the following URL to your Pi-hole configuration:

https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/pubg.txt



### DNS over HTTPS (DoH) Domains

The `doh.txt` file contains a list of domains associated with DNS over HTTPS (DoH) providers. DoH is a protocol for performing remote Domain Name System (DNS) resolution via the HTTPS protocol. While DoH offers privacy benefits, some users may prefer to block connections to DoH providers for various reasons.

To use this list, add the following URL to your Pi-hole configuration:

https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/doh.txt


## How to Use

To add these lists to your Pi-hole, follow these steps:

1. Log in to your Pi-hole admin interface.
2. Navigate to the "Group Management" tab.
3. Select the "Adlists" tab.
4. Enter the URL of the list you want to add.
5. Click on "Add" and then click on "Save and Update".

Your Pi-hole will now block the domains listed in the added lists.

## Contribution

Contributions to this repository are welcome. If you have additional domains to add to the lists or suggestions for improvement, feel free to open an issue or submit a pull request.

## Disclaimer

While these lists aim to block unwanted content, they may also block legitimate content. Use them at your own discretion. The maintainers of this repository are not responsible for any unintended consequences of using these lists.
