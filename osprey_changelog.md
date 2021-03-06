December 18th, 2020

- ASB Security string 2020-12-05
- System Webview 87.0.4280.101 (Standard variant)
- Bromite Webview 87.0.4280.106 (microG build variant)
- Updated microG from upstream to 0.2.14.204215-15 (picked until 720b089)
- F-Droid updated to 1.10-alpha1-114 (microG build variant)


November 14th, 2020

- ASB Security string 2020-11-05
- Additional Fix for CVE-2020-15999
- Fix of AOSP E-Mail widget
- System Webview 86.0.4240.185 (Standard variant)
- Bromite Webview 86.0.4240.181 (microG build variant)
- Updated microG with fixes in GCM and EN API (microG build variant)
- Replaced weak F-Droid signatures with ROM's V2 signatures (microG build variant)


October 13th, 2020

- ASB Security string 2020-10-05
- Bromite Webview 86.0.4240.73 (microG build variant)
- microG 0.2.12.203315 - including "Exposure notification API" for use of Covid tracing apps (microG build variant)
- Additional hardening: bionic and constified JNI method tables (microG build variant)


September 13th, 2020

- ASB Security string 2020-09-05
- Kernel: Wireguard tag v1.0.20200908
- System Webview 85.0.4183.101 (Standard build variant)
- Bromite Webview 85.0.4183.86 (microG build variant)
- Added eSpeak TTS engine (microG build variant)


August 10th, 2020

- ASB Security string 2020-08-05
- Kernel: Wireguard tag v1.0.20200729
- System Webview 84.0.4147.89 (Standard build variant)
- Bromite Webview 84.0.4147.113 (microG build variant)
- Location of the firewall functionality moved to Network > Data usage in Settings (microG build variant)


July 12th, 2020

- ASB Security string 2020-07-05
- Kernel: Wireguard tag v1.0.20200623
- microG: updated prebuilt GmsCore fom /e/ project to fix FCM registration issues (microG build variant)
- F-Droid updated to 1.8 / F-Droid privileged extension updated to 0.2.11 (microG build variant)
- Aurorastore updated to 3.2.9 / AuroraServices updated to 1.0.6 (microG build variant)


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

