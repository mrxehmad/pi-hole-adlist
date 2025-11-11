# Pi-hole Adlist Collection

A comprehensive collection of domain blocklists designed to enhance your Pi-hole ad blocking capabilities. This repository contains carefully curated lists that target various types of ads, tracking, and unwanted content across different platforms and services.

## 📚 Available Blocklists

This repository provides multiple specialized blocklists for different purposes:

### 🎮 Gaming

- **PUBG Blocklist** (`pubg-block.txt`): Blocks domains associated with PUBG game tracking, ads, and related services
- **HiTV Ads Blocklist** (`hitv.list`): Targets video advertising on HiTV platform

### 📱 Social Media & Apps

- **Facebook Blocklist** (`Facebook`): Comprehensive blocking of Facebook services and domains
- **Instagram Blocklist** (`instagram-pihole`): Blocks Instagram tracking and advertising domains  
- **Snapchat Blocklist** (`snapchat-pihole`): Blocks Snapchat tracking and advertising domains
- **TikTok Blocklist** (`tiktok-pihole`): Blocks TikTok tracking and advertising domains

### 🌐 Security & Privacy

- **DNS over HTTPS (DoH) Blocklist** (`doh-list`): Blocks public DNS over HTTPS providers (useful for privacy control)
- **Huawei Blocklist** (`huawei-host`): Blocks Huawei device tracking and services

### 🛡️ Additional Filters

- **uBlock Origin Ads Filter** (`ublock_ads_list`): Ads-only filters from the uBlock Origin project
- **Android Tracking** (`android-tracking`): Blocks Android device tracking domains
- **TikTok Tracking** (`tiktock-tracking`): Additional TikTok tracking domains

## 🚀 Usage

### Adding to Pi-hole Web Interface

1. Log in to your Pi-hole admin interface
2. Navigate to **Group Management** (or **Blacklist** in older versions)
3. Click on **Blocklists** (or **Adlists**)
4. Enter the raw URL for the list you want to add
5. Click **Add** and then **Save**

### Raw URLs for Each List

- **PUBG Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/pubg-block.txt`
- **Facebook Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/Facebook`
- **Instagram Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/instagram-pihole`
- **Snapchat Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/snapchat-pihole`
- **TikTok Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/tiktok-pihole`
- **DoH Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/doh-list`
- **HiTV Ads Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/hitv.list`
- **Huawei Blocklist**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/huawei-host`
- **uBlock Origin Ads**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/ublock_ads_list`
- **Android Tracking**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/android-tracking`
- **TikTok Tracking**: `https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/tiktock-tracking`

### Command Line Setup

You can also add these lists using the command line:

```bash
# Example for adding the PUBG blocklist
pihole -g https://raw.githubusercontent.com/mrxehmad/pi-hole-adlist/main/pubg-block.txt
```

## 📋 List Format

All lists follow the standard Pi-hole format:

- Each line contains an IP address (usually `0.0.0.0` or `127.0.0.1`) followed by a domain
- Lines starting with `#` are comments and will be ignored
- Some lists include wildcard patterns using `||domain.com^` format

## ⚠️ Important Notes

- **Testing**: Some domains may block legitimate functionality. Test thoroughly in your environment.
- **Update Frequency**: Lists are updated periodically as new tracking domains are discovered.
- **False Positives**: If you find a domain that blocks legitimate content, please [report an issue](https://github.com/mrxehmad/pi-hole-adlist/issues).
- **Backup**: Always backup your Pi-hole configuration before adding new lists.

## 🤝 Contributing

Contributions are welcome! If you have additional domains to add or find issues with current lists:

1. Fork the repository
2. Create a feature branch
3. Add your changes
4. Open a pull request

### Contribution Guidelines

- Add domains to the appropriate category list
- Maintain the standard Pi-hole format
- Include comments explaining the purpose of new domains (optional)
- Test changes before submitting

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [uBlock Origin uAssets](https://github.com/uBlockOrigin/uAssets) - For the uBlock Origin filters
- [wranders/doh-list](https://github.com/wranders/doh-list) - DoH provider list
- [oneoffdallas/dohservers](https://github.com/oneoffdallas/dohservers) - DoH server information
- [MohamedElashri/doh-list](https://github.com/MohamedElashri/doh-list) - DoH server references
- [deep-bhatt/huawei-block-list](https://github.com/deep-bhatt/huawei-block-list) - Huawei blocking information

## 🐛 Reporting Issues

If you encounter problems with any of the lists:

1. Check if the issue is already reported in the [issues section](https://github.com/mrxehmad/pi-hole-adlist/issues)
2. Create a new issue with:
   - The specific list causing issues
   - The domain causing the problem
   - What functionality was affected
   - Steps to reproduce the issue

## ⚖️ Disclaimer

These lists are designed to block unwanted content but may occasionally block legitimate content. Use at your own discretion. The maintainers are not responsible for any unintended consequences resulting from the use of these lists.

## 🔄 Updates

The lists in this repository are maintained and updated regularly as new tracking domains and ad servers are discovered. Check back frequently for updates or consider setting up automated list refreshes in your Pi-hole configuration.
