February 21st, 2023

- Custom build release 2023-02-01
- microG on 0.2.27.223616-3
- Spoof apps installed by G*PlayStore 


Janaury 8th, 2023

- Custom build release 2023-01-01
- Bromite Webview 108.0.5359.156
- microG 0.2.26.223616-16


December 12th, 2022

- Custom build release 2022-12-01
- Bromite Webview 108.0.5359.106
- microG 0.2.26.223616-2


November 13th, 2022

- Custom build release 2022-11-01
- Bromite Webview 106.0.5249.163
- microG 0.2.25.223616-10
- F-Droid 1.15.3
- Timezone data updated to 2022e


October 13th, 2022

- Custom build release 2022-10-01
- Bromite Webview 105.0.5195.147
- microG 0.2.24.223616-61
- APN configurations updated


September 11th, 2022

- Custom build release 2022-09-01
- Many kernel patches
- Bromite Webview on 104.0.5112.91
- microG 0.2.24.214816-30
- Contacts app slightly 'de-Googled'


August 12th, 2022

- Custom build release 2022-08-01
- Bromite Webview updated to 103.0.5060.140


July 16th, 2022

- Custom build release 2022-06-01


June 16th, 2022

- Custom build release 2022-06-01
- Some kernel patches
- Bromite Webview on 102.0.5005.96
- microG updated to 0.2.24.214816-11
- F-Droid 1.15.2


May 9th, 2022

- Custom build release 2022-05-01
- Some kernel patches
- Bromite Webview on 101.0.4951.53
- microG updated to 0.2.24.214816-10
- Mozilla Location provider on 1.5.0
- F-Droid 1.15


April 15th, 2022

- Custom build release 2022-04-01
- Bromite System Webview updated to 100.0.4896.57


March 17th, 2022

- Custom build release 2022-03-01
- Bromite System Webview updated to 99.0.4844.58
- microG 0.2.24.214816-2
- AuroraStore 4.1.1


February 19th, 2022

- Custom build release 2022-02-01
- F-Droid updated to 1.14, F-Droid privileged extension to 0.2.13
- Bromite System Webview updated to 97.0.4692.106
- microG updated to 0.2.24.214816-2


January 22nd, 2022

- ASB Security string 2022-01-05
- Some kernel patches
- Backported Audio balance (accessibility settings) from Android 10


December 26th, 2021 - BACK AGAIN

- Relaunch of LineageOS 16.0 microG builds
- ASB Security string 2021-12-05
- Bromite Webview 96.0.4664.54
- microG 0.22.214516-21
- F-Droid 1.13
- Many kernel sec. patches
- Updated DRM blobs


-----------------------------------------------------------------------

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

