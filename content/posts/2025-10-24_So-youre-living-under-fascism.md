---
date: 2025-10-24
#description:
draft: false
title: So you're living under fascism -- what do you do now?
keywords: "fascism, privacy, technology, encryption"
#series:
category: blog
tags:
- privacy
- technology
- encryption
params:
  author: Joshua Casey
include_toc: true
show_comments: true
#hiddenFromHomePage: false
---

For those of us not living under a rock, and with the unfortunate ability of pattern recognition, it's not hard to realize that if you're living in the United States right now we are living under a fascist regime. You have the [President of the United States ordering the Texas National Guard to invade another state (Illinois)](https://abcnews.go.com/US/texas-national-guard-headed-illinois-gov-pritzker-calls/story?id=126283676), and [children and their parents forced to hide from government agents thanks to the kindness of a neighbor](https://chicago.suntimes.com/immigration/2025/10/10/neighbor-shielded-7-year-old-during-south-shore-federal-raid-i-didnt-want-them-to-take-her), it's understandable to feel like needing to take steps to protect yourself. If you're clueless on how to protect yourself, read on.

## Encrypt, encrypt, encrypt
First things first, make sure your sensitive information is encrypted. IOS and Android are encrypted by default, so there's no extra steps you have to go through to encrypt your cell phone.

- On Windows, your best option is to use [Veracrypt](https://veracrypt.io/en/Home.html) to encrypt the disk that Windows is installed on and any other disks that your computer has.

- For MacOS, your encryption options are either Veracrypt or [FileVault](https://support.apple.com/guide/mac-help/protect-data-on-your-mac-with-filevault-mh11785/mac).

- On Linux, you can use [LUKS](https://www.howtogeek.com/what-is-luks-and-how-does-it-secure-your-linux-file-system/) to encrypt your disk during the Linux installation process. You can install Veracrypt to unencrypt any devices that were encrypted with Veracrypt, for example, on a Windows computer or if you need to access your storage device on multiple different devices that use different operating systems.

**Warning! This action is destructive! If you forget your encryption password or lose your recovery key you WILL lose access to all of your data. If you lose your recovery key or decryption password, there is no way to recover your data. Make sure that you keep your recovery key/image stored in a safe place.**


Use apps that offer end-to-end encryption, such as:

- Messaging: [Signal](https://signal.org/), [Element](https://element.io/), or [Session](https://getsession.org/)
- Email: [Proton Mail](https://go.getproton.me/SH1pu)
- Cloud Photo Storage: [Ente](https://ente.io)
- Cloud File Storage: [Proton Drive](https://go.getproton.me/SH1pc)
- Notes: [Notesnook](https://notesnook.com/) or [Joplin](https://joplinapp.org/)
- Calendar: [Proton Calendar](https://proton.me/calendar)

## Do not use Biometric Unlock
You should unlock your device with a password or PIN, not face unlock, eye scan, or fingerprint unlock because password and PIN unlock is [protected by the Fourth Amendment](https://www.eff.org/wp/digital-privacy-us-border-2017). While you would logically think that biometric unlock methods such as fingerprints should also be protected by the Fifth Amendment, unfortunately some courts have held that they are not. Better to err on the side of caution and use a password/passphrase or PIN.

## Use a Password Manager
Keep all your passwords securely stored in a Password Manager, such as [Bitwarden](https://bitwarden.com/) or [Proton Pass](https://go.getproton.me/SH1ph). The other bonus to using a password manager is that you can generate strong randomly generated passwords for all of your logins because the passwords are securely stored inside your password manager. Because all of your passwords are stored securely in the password vault of whichever password manager you choose, the only password you really should ever need to remember with your brain is the password that unlocks your password manager vault.

Additionally, make sure you are using two factor authentication everywhere you can. You should avoid SMS-based two factor authentication (where possible) as it is [vulnerable to SIM swapping attacks](https://blog.1password.com/what-is-sim-swapping/). You should instead use apps such as [Ente Auth](https://ente.io/auth) or [Proton Authenticator](https://proton.me/authenticator).

## Shut the Fuck Up
If you have an encounter with law enforcement, you should inform them that you are exercising your Fifth Amendment right to remain silent and that you are not speaking to them without a lawyer present. And then you should proceed to Shut the Fuck Up.

{{< youtube nWEpW6KOZDs >}}

## Don't lose hope
Things may feel dark and hopeless realizing that you are living under fascism. Don't give up hope. You're not alone, [there are many people out there that do not agree with authoritarianism](https://www.npr.org/2025/10/19/nx-s1-5579042/no-kings-protests-takeaways). Just remember that this is a temporary set back and we will move past this.

<meta name="fediverse:creator" content="@JoshuaACasey@social.dftba.xyz">

*FTC Disclosure: Proton Partner affiliate links were used in this article.*
