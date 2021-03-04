#### Contents

- [Introduction](#introduction)
- [Operating System](#operating-system)
- [Browser](#browser)
- [Social Networks](#social-networks)
- [VPN](#vpn)
- [Messenger](#messenger)
- [Email](#email)
- [Passwords](#passwords)
- [Authenticator](#authenticator)

## Introduction

True privacy cannot be accomplished without a competent layer of security, and often times than not users make compromise security for "privacy". As a wise man once said "we must not assume that there are power users. If anything they could take decisions that reduce their security and feel they are improving it"

## Operating System

Use [GrapheneOS](https://grapheneos.org/) or stock operating system on a google pixel device, the only recommended OEM is google 

**Warning: Do not root or keep the bootloader unlocked. Avoid custom roms like [Lineage OS](https://lineageos.org/) and its derivatives. It weakens various [SELinux polices](https://github.com/LineageOS/android_system_sepolicy/search?p=2&q=userdebug&type=code) and exposes root access via adb. The majority of custom ROMs severely weaken the security model by disabling [verified boot](https://source.android.com/security/verifiedboot/verified-boot), failing to provide firmware patches, using [userdebug builds](https://github.com/LineageOS/hudson/blob/master/lineage-build-targets), [disabling SELinux](https://nitter.nixnet.services/topjohnwu/status/1359054106019565571#m), and various other issues, they focus on customization not security or privacy. Also Comparing [Magisk manager](https://github.com/topjohnwu/Magisk) (as an excuse to root the device) to Android's incredibly tight SELinux policy is ludicrous**


## Browser

Use [Vanadium](https://github.com/GrapheneOS/Vanadium) (if posible) or [Bromite](https://www.bromite.org/)

warning: These projects don't priorities on anti-fingerprinting nor anonimity, Use the [Tor browser](https://www.torproject.org/) instead

## Social Networks

Don't even think of that


## VPN

[Don't use VPN services](https://gist.github.com/joepie91/5a9909939e6ce7d09e29) Use [Orbot](https://play.google.com/store/apps/details?id=org.torproject.android) instead. It is a Proxy server project to provide anonymity on the Internet. It acts as an instance of the Tor network on such devices and allows traffic routing from a device's web browser, e-mail client, map program, etc., through the Tor network, providing anonymity for the user. The VPN mode in Orbot, is not a real VPN. the VPN mode makes use of Androd VPN-api to force all apps to through its own tor connection. They do it this way because the only alternative would require rooting your device.

## Messenger

[Signal](https://signal.org/) with VoIP number


## Email

[ProtonMail](https://protonmail.com/) and [Tutanota](https://tutanota.com/) are providers with a strong focus on security 

**Warning: Email itself is a legacy technology and there is no private or secure email, Don't go anywhere near email at all if any remotely sophisticated adversary is involved. **

## Passwords

Use a password manager like [Keepassdx](https://www.keepassdx.com/) or [Bitwarden](https://bitwarden.com/) that generates secure passwords and stores them for you safely.

## Authenticator

Use two-factor authentication (2FA) wherever possible, Use [Aegis.](https://getaegis.app/)






















