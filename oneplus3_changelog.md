December 13th, 2020

- ASB Security string 2020-12-05
- Kernel: Upstreamed to tag ASB-2020-12-05_3.18
- Bromite Webview on 87.0.4280.106
- Updated microG from upstream to 0.2.14.204215-15 (picked until 720b089)
- Updated F-Droid to 1.10-alpha1-114


November 08th, 2020

- ASB Security string 2020-11-05
- Kernel: Upstreamed to tag ASB-2020-11-05_3.18
- Kernel: Fix of bug causing crashes with Wireguard in native mode
- Fix of AOSP E-Mail widget
- Fix for CVE-2020-15999
- Bromite Webview on 86.0.4240.181
- Updated microG with fixes in GCM and EN API
- Replaced weak F-Droid signatures with ROM's V2 signatures


October 8th, 2020

- ASB Security string 2020-10-05
- Bromite Webview on 86.0.4240.73
- Kernel: Upstreamed to tag ASB-2020-10-05_3.18
- microG 0.2.12.203315 - including "Exposure notification API" for use of Covid tracing apps
- Additional hardening (constified JNI method tables)


September 12th, 2020

- ASB Security string 2020-09-05
- Bromite Webview updated to 85.0.4183.86
- Kernel: Upstreamed to tag ASB-2020-09-05_3.18
- Kernel: Wireguard tag v1.0.20200908
- Kernel: Fix USB-OTG unplug crash
- Added eSpeak TTS engine (FOSS TTS solution)


August 8th, 2020

- ASB Security string 2020-08-05
- Bromite Webview updated to 84.0.4147.113
- Kernel: Upstreamed to tag ASB-2020-08-05_3.18
- Kernel: Wireguard tag v1.0.20200729
- Kernel: qcacld-2.0 merge of CAF tag LA.UM.7.6.r1-07800-89xx.0
- Location of the firewall functionality has moved to Network > Data usage in Settings


July 10th, 2020

- ASB Security string 2020-07-05
- Kernel: Wireguard tag v1.0.20200623
- microG: updated prebuilt GmsCore fom /e/ project (fixed FCM registration issues)
- F-Droid updated to 1.8 / F-Droid privileged extension updated to 0.2.11
- Aurorastore updated to 3.2.9 / AuroraServices updated to 1.0.6


June 10th, 2020

- ASB Security string 2020-06-05
- Kernel: Wireguard tag v1.0.20200520
- Bromite Webview on 83.0.4103.101
- Sepolicy: Netmonitor exception f. "Tracker Control" app


May 6th, 2020

- ASB Security string 2020-05-05
- Telephony: Option to set different ringtones in case of Dual SIM
- Kernel: Native Wireguard support
- Kernel: Merged CAF tag LA.UM.7.6.r1-07400-89xx.0 (also f. WLAN)
- Kernel: Misc. optimizations
- Bromite Webview on 81.0.4044.127
- AuroraStore updated to 3.2.8


April 10th, 2020

- ASB Security string 2020-04-05
- Fix for CVE-2020-8597 (external/ppp)
- Kernel: CVE-2019-10638 siphash 128bit for IP generation
- Bromite Webview on 81.0.4044.76
- AuroraStore updated to 3.2.4


March 16th, 2020 - interim release

- Vendor blob update to reflect OOS 9.0.6 - vendor sec. patch level now 2019-10-01
- Debloated from Alipay, WeChatpay, Soter and IFAA


March 7th, 2020

- Security string 2020-03-05
- Bromite System Webview 80.0.3987.118
- AuroraStore 3.2.0
- Added Netguard app (F-Droid) to SELinux domain allowing /proc/net


February 19th, 2020 - interim release

- Kernel fix for crash when doing VoIP telephony


February 7th, 2020

- Security string 2020-02-05
- Bromite System Webview 79.0.3945.139
- AuroraStore 3.1.8


January 14th, 2020 - Initial feature list:

- Pre-installed microG and F-Droid same as the LineageOS for microG project
- Pre-installed AuroraStore (Version 3.1.7) with AuroraServices 1.0.5
- OTA Support
- Access to /proc/net blocked for user apps
- Bundled netmonitor app to allow network monitoring
- Enhanced Privacy Guard: Switches for motion sensors and other sensors
- Cloudflare as default DNS (instead of Google)
- Privacy-preferred default settings
- Optional blocking of Facebook- and Google-Tracking
- Optional disable captive portal detection
- Firewall UI
- No submission of IMSI/IMEI to Google/Sony when GPS is in use
- Default hosts file with many blocked ad/tracking sites
- Privacy-enhanced Bromite SystemWebView 79.0.3945.107
- Additional restrictions for secondary users
- Increased password length
- (Temporary: Phonograph instead of Eleven music player)

