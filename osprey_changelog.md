June 10th, 2020

- ASB Security string 2020-06-05
- Kernel: Wireguard tag v1.0.20200520
- System Webview on 81.0.4044.138 (Standard build variant)
- Bromite Webview on 83.0.4103.101 (microG build variant)
- Disabled NearbyMessagingService and DiscoveryService (only relevant, if genuine Gapps are used) to improve WiFi performance, when BT is used
- Sepolicy: Netmonitor exception f. "Tracker Control" app (microG build variant)


May 6th, 2020
Initial feature list:

- OTA Support
- Enforcing SELinux
- Forked Hybrid-X kernel with native Wireguard support and current sec. patches
- System Webview on 81.0.4044.117 (Standard Build)

Below listed initial features apply to the "microG" build variant:
- Pre-installed microG and F-Droid same as the LineageOS for microG project
- Pre-installed AuroraStore (Version 3.2.8) with AuroraServices 1.0.5
- Access to /proc/net blocked for user apps
- Bundled netmonitor app to allow network monitoring
- Enhanced Privacy Guard: Switches for motion sensors and other sensors
- Cloudflare as default DNS (instead of Google)
- Privacy-preferred default settings
- Optional blocking of Facebook- and Google-Tracking
- Optional disable captive portal detection
- Firewall UI
- No submission of IMSI/IMEI to Google when GPS is in use
- Default hosts file with many blocked ad/tracking sites
- Privacy-enhanced Bromite SystemWebView 81.0.4044.127
- Additional restrictions for secondary users
- Increased password length
