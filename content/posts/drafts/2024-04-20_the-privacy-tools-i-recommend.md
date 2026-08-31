---
date: 2025-05-12
draft: true
title: My Guide to Privacy Respecting Apps You Should Be Using to De-Google Your Life
#description:
keywords: "privacy, open source technology, open source apps, degoogle your life"
category: privacy
tags:
- privacy
- technology
- open source
params:
  author: Joshua Casey
include_toc: true
showComments: true
---

I have always been a big supporter of human rights, freedom, free speech, privacy. I thought I would go ahead and make a post listing some of of price-respecting apps and services that I use in my day-to-day life.

# Browser
## [Firefox](https://www.mozilla.org/en-US/firefox/)
Not only does [Firefox](https://www.mozilla.org/en-US/firefox/) respect your privacy more than Chrome does. If everyone were to stop using Firefox (and I guess safari, although I have never owned an Apple device, so I tend to forget about them), then Google would essentially own the entire web. If people use Firefox instead of Chrome, then web developers have to make sure their websites work on non-chrome browsers.


# Phone / Phone operating system
## [Google Pixel](https://store.google.com/us/category/phones?hl=en-US) & [GrapheneOS](https://grapheneos.org/)
I know Google does not have a very good record with respecting user privacy. However, the [Google Pixel](https://store.google.com/us/category/phones?hl=en-US) phones are the most secure android phones in terms of hardware. Which is why I recommend using a Google Pixel phone (6a and newer), and then replacing the standard Pixel OS with [GrapheneOS](https://grapheneos.org/).


# Password manager
## [Bitwarden](https://bitwarden.com)
One of the worst things you can do is using insecure passwords. One of the other worst things you can do is reusing the same password for multiple or all of your accounts. This is where having a password manager comes in handy. With a password manager you can keep all of your login information stored in your "vault" which allows you to have a strong, randomly generated password for every account that you own. And you do not have to worry about remembering that complicated, secure password because the password manager "remembers" it for you. The **only** password that you are stuck needing to remember is the password that allows you to gain access to your password vault. The password manager that I recommend is [Bitwarden](https://bitwarden.com/). Not only do they offer the ability to use it for free (because I realize, many people simply cannot afford "extra" costs), but it is open source, and if you do choose to pay it is dirt cheap (a year subscription comes out to about $1 per month).

**Note:** Yes, they do offer a paid family plan for those of you that have families!


# Two-Factor Authentication
## [Bitwarden](https://bitwarden.com), [Ente](https://ente.io/auth), or [Yubikey](https://yubico.com)
Having just a secure password is not secure enough, however. We also need to make sure we secure our accounts with a second method (hence the name two-factor authentication). Now, there's a couple of ways to accomplish this. First of all, you should ideally never ever use SMS text messaging as your two-factor authentication. Email is slightly better than text message, but personally I'm not much of a fan of that either. I prefer using an app-based TOTP two-factor authentication or even better using a hardware security key like a [yubico](https://www.yubico.com/why-yubico/for-individuals/). Personally, the app-based TOTP 2FA provider that I use is one that is included as a paid feature of [Bitwarden](https://bitwarden.com/pricing/). However, Bitwarden just [recently launched a separate authenticator app](https://bitwarden.com/blog/bitwarden-just-launched-a-new-authenticator-app-heres-what-it-means-to-users/) that is available for free to everyone. Another good option, is [Ente](https://github.com/ente-io/ente/tree/main/auth#readme).


# Email
## [Proton Mail](https://pr.tn/ref/SFG18D34ZDT0)
It's time to ditch Gmail, Outlook, and Yahoo and make your emails YOURS. I made the switch to [Proton Mail](https://protonmail.com) years ago and if you value your privacy and value not having your emails canned to target advertisements at you, it would be wise for you to switch to a privacy-respecting email too! I won't deny that switching ANY email provider can certainly be a temporary hassle. But it's well worth it!


# Email Aliases
## [SimpleLogin](https://simplelogin.io/)
I'll admit. Email aliases are something that I have only started using more recently. But they are great because you can have emails sent to your email address, without having to give out your actual email address (you give the email alias address instead). For example, if I signup for a Facebook account, using the email alias of `facebook@example.com` and then I receive an email, not from facebook, but from someone else addressed to `facebook@example.com` I know that either facebook (in this example) has sold my email address, or they have been compromised by a data breach. The Email alias provider that I choose to use and recomend is [SimpleLogin](https://simplelogin.io/) because they are part of [Proton](https://pr.tn/ref/SFG18D34ZDT0) and I am a happy Proton user and customer.


# VPN
## [Proton VPN](https://pr.tn/ref/SFG18D34ZDT0)
The VPN provider that I recommend is [Proton VPN](https://protonvpn.com). Yes, partially because I'm already a Proton user. But also, they do offer a VPN for free and they are the only **free** VPN provider that I personally would recommend. Other "free" vpn providers sell your data (that's how they're able to be "free"). Proton does not do that. Proton's free tier is paid for by the paying Proton users, like myself (you're welcome).


# Calendar
## [Proton Calendar](https://pr.tn/ref/SFG18D34ZDT0)
I think [Proton Calendar](https://) might be one of the lesser known Calendar apps. But in an effort to de-google my life (mostly because Google has a trend of shutting down their products) I switched to Proton Calendar, partially because I was already using the other Proton service and partially because I just trust that they are taking my privacy and security seriously.


# Contacts
## [Proton Contacts](https://pr.tn/ref/SFG18D34ZDT0)
Not really much to say here. For contacts, I just use the contacts that is built into [Proton Mail](https://protonmail.com). I do wish that they had a separate mobile app for contacts. Perhaps someday?


# Cloud Storage
## [Proton Drive](https://pr.tn/ref/SFG18D34ZDT0)
The most recent Proton app is [Proton Drive](https://protondrive.com). As a paying user, I have 500GB of storage -- far more than the 15GB that Google Drive offers for free, and the benefit of being end-to-end encrypted. Proton can't spy on your and scan your files to target you with advertisements the way that Google does with Google Drive or Gmail.


# Photos
## [Proton Drive](https://pr.tn/ref/SFG18D34ZDT0), [Ente](https://ente.io), or [Immich](https://immich.app)
I'm actually currently still using Google Photos for my photo storage. I am hoping to eventually move to [Proton Drive](https://protondrive.com) for my photo storage when the app gets a bit better (preferably adding the ability to import photos from a Google Photos exported backup). If that doesn't work out, then [Ente](https://ente.io) is my second option - it's end-to-end encrypted and offers automatic backup with facial recognition. For those interested in self-hosting, [Immich](https://immich.app) is an excellent open-source alternative that provides Google Photos-like features including face recognition, automatic backup, and sharing capabilities.

# Notes
## [Standard Notes](https://standardnotes.com/), [Notesnook](https://notesnook.com/), or [Joplin](https://joplinapp.org/)
I've gone on a bit of a wild ride with notes apps. I started out just using Google Keep, but of course that isn't very secure. So I moved to [Standard Notes](https://standardnotes.com), which is a very good, private notes app. However, I was not happy with how expensive it is. I moved to another really good, private notes app called [Notesnook](https://notesnook.com) because it was priced far cheaper and much more reasonable. Now, the funny thing is, that Standard Notes just recently announced they are becoming part of the [Proton](https://proton.me) family. If my Proton subscription, at some point in the future, ends up getting me access to the paid version of Standard Notes, I will likely move back to Standard Notes and stop paying separately for Notesnook.

Another excellent option is [Joplin](https://joplinapp.org/), which is completely free and open-source. It supports markdown, has excellent organization features, and can sync across devices using various cloud services (including your own server). It's particularly great for those who want full control over their data.


# Search
It might be shocking to you that Google and Bing are not the only search engines. The following search engines claim to respect your privacy:

  - [Startpage](https://www.startpage.com/)
  - [DuckDuckGo](https://duckduckgo.com/)
  - [Brave Search](https://search.brave.com/)


# Messaging
There is an over abundance of privacy-centric messaging apps. However, these four are the ones I would recommend (in no particular order):

  - [Signal](https://signal.org/)
  - [Matrix/Element](https://element.io/download)
If you're a discord user, Element is by far more similar to Discord than these other apps. So if you're looking for a private discord alternative, this one is likely what you're looking for (as opposed to the other three recommended messaging apps).


# DNS
## [Quad9](https://quad9.net/) & [Cloudflare](https://one.one.one.one/)
For DNS, I recommend either [Quad9](https://quad9.net/) or [Cloudflare](https://one.one.one.one/) (or both). They're both free. They both offer malware blocking. And Cloudflare offers a "family-friendly" adult content blocking option.

**[Quad9](https://quad9.net/)**

  - IPv4: `9.9.9.9`
  - IPv4: `149.112.112.112`
  - IPv6: `2620:fe::fe`
  - IPv6: `2620:fe::9`
  - HTTPS: `https://dns.quad9.net/dns-query`
  - TLS: `tls::/dns.quad9.net`

**[Cloudflare](https://one.one.one.one/)**

  - [`1.1.1.1 1.0.0.1`](https://one.one.one.one/family/)
  - [`1.1.1.2 1.0.0.2`](https://one.one.one.one/family/) (Malware blocking)
  - [`1.1.1.3 1.0.0.3`](https://one.one.one.one/family/) (Malware and Adult Content blocking)


# Maps & Navigation
## [OpenStreetMap](https://www.openstreetmap.org/) & [OsmAnd](https://osmand.net/)
Google Maps is convenient, but it tracks your every movement. For privacy-respecting navigation, I recommend [OsmAnd](https://osmand.net/) which uses [OpenStreetMap](https://www.openstreetmap.org/) data. It works completely offline, doesn't track you, and is open-source. The maps are community-driven and often more detailed than Google Maps in many areas. Other good alternatives include [Organic Maps](https://organicmaps.app/) and [MAPS.ME](https://maps.me/).

# Office Suite
## [LibreOffice](https://www.libreoffice.org/) or [OnlyOffice](https://www.onlyoffice.com/)
Google Workspace (Docs, Sheets, Slides) scans your documents for advertising purposes. [LibreOffice](https://www.libreoffice.org/) is a completely free and open-source office suite that works offline and respects your privacy. [OnlyOffice](https://www.onlyoffice.com/) is another excellent option with better Microsoft Office compatibility and real-time collaboration features.

# Social Media
## [Mastodon](https://mastodon.social/), [Bluesky](https://bsky.app), or [Matrix](https://matrix.org/)
Social media platforms like Facebook, Twitter, and Instagram are privacy nightmares. [Mastodon](https://mastodon.social/) is a decentralized Twitter alternative that's open-source and privacy-focused. [Diaspora](https://diasporafoundation.org/) is a decentralized Facebook alternative. For more feature-rich social networking, [Matrix](https://matrix.org/) offers federated communication with end-to-end encryption.

# Complete Google Apps Alternatives Quick Reference

Here's a comprehensive table of privacy-focused alternatives to popular Google services:

| Google Service | Privacy Alternative(s) | Free/Open Source | Key Features |
|----------------|------------------------|------------------|---------------|
| **Gmail** | Proton Mail, Tutanota | Free tiers available | End-to-end encryption, no ads |
| **Google Drive** | Proton Drive, Nextcloud, Syncthing | Free tiers/Open source | Encrypted storage, self-hosting options |
| **Google Docs/Sheets** | LibreOffice, OnlyOffice, CryptPad | Free/Open source | Offline editing, collaboration |
| **Google Photos** | Ente, Immich, PhotoPrism | Paid/Open source | Face recognition, auto-backup |
| **Google Search** | DuckDuckGo, Startpage, Brave Search | Free | No tracking, unbiased results |
| **Chrome Browser** | Firefox, Brave, Tor Browser | Free/Open source | Ad blocking, privacy by default |
| **Google Maps** | OsmAnd, Organic Maps | Free/Open source | Offline navigation, no tracking |
| **YouTube** | PeerTube, Odysee, Invidious | Free/Open source | Decentralized, no ads |
| **Google Calendar** | Proton Calendar, Nextcloud Calendar | Free tiers/Open source | Encrypted events, CalDAV sync |
| **Google Contacts** | Proton Contacts, Nextcloud Contacts | Free tiers/Open source | Encrypted contacts, CardDAV sync |
| **Google Keep** | Standard Notes, Joplin, Notesnook | Free tiers/Open source | Encrypted notes, markdown support |
| **Google Translate** | LibreTranslate, Lingva | Free/Open source | No data collection |
| **Google Analytics** | Plausible, Umami, Matomo | Paid/Open source | GDPR compliant, no cookies |
| **Android** | GrapheneOS, LineageOS, /e/OS | Free/Open source | De-googled Android |
| **Google Assistant** | Mycroft, Rhasspy | Open source | Offline processing, customizable |
| **Google Authenticator** | Bitwarden, Ente Auth, Aegis | Free/Open source | Encrypted 2FA, backup options |
| **Google Pay** | No direct alternative | - | Use cash or traditional banking |

# Additional Privacy Tools Worth Considering

## App Stores
- **F-Droid** (Android): Open-source app store with privacy-focused apps.

_FTC disclosure: Some links in this article are my personal referral links._

<meta name="fediverse:creator" content="@JoshuaACasey@social.dftba.xyz">
