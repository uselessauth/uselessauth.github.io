---
layout: post
title: Thoughts on /e/OS.
date: 2026-03-17 17:40:19 +0100
categories: privacy degoogle android
tags: opinion
media_subpath: /assets/04-eos
image:
  path: e-foundation-logo.png
  alt: /e/ Foundation Logo
---

It's been more than two and a half years since I flashed my phone with the [LineageOS](https://lineageos.org/) fork [/e/OS](https://e.foundation/e-os/). Looking back, I landed on /e/OS because it seemed to be the best fit for my Fairphone 4 in terms of compatibility and preserving functionality by e.g. having [MicroG](https://en.wikipedia.org/wiki/MicroG) preinstalled. After such a long time daily driving the OS, I have some thoughts. Since I've only used /e/, I don't exactly know which of the things I'll be describing are exclusive to /e/ or are also available on Lineage, or other custom ROMs; so keep that in mind.

## The Good

/e/OS doesn't just mostly meet stock Android's functionality, it exceeds it in some regards. For example, when the display is off one can hold the phone's buttons for quick actions. Holding the volume buttons allows you to skip/rewind the current media, and holding the power button turns on the flashlight. Taking it out of my pocket while holding the power button to immediately have a flashlight is genuinely one of the things I like most about my phone.

/e/ also adds more granular network permissions. The reason I still use GBoard on my degoogled phone is that I have the ability to disallow network connection for the app entirely.

The app store ("App Lounge") aggregates Google Play Store and F-Droid apps in one place. F-Droid apps are labeled "Open Source" and every app has an [Exodus](https://exodus-privacy.eu.org/en/) privacy rating next to it, along with a list of all known trackers it embeds and the exact permissions the app requests. This transparency makes filtering out harmful apps and gauging which apps to install much easier.

Also, I have barely had any apps not working with /e/OS. Even my banking apps, which I was most worried about, all work flawlessly. Obviously, this isn't necessarily the case for everyone, and there is no way to test app functionality beforehand.

There is a module in the settings app called "Advanced Privacy", which combines a few different pieces of functionality: First off, it blocks traffic to known tracking domains (such as Google Ad Services) to make it harder for apps to phone home. Since this can impact functionality, one is given very granular control over which trackers to allow for which app. Advanced Privacy also acts as a mock location app, allowing one to give apps fake GPS data to throw off tracking. To make this feature as practical as possible, it is possible to allow certain apps to access your real GPS data. The third function is a VPN that allows you to route specific apps' traffic through the TOR network to hide your IP address. I personally don't use this feature since it doesn't have the best performance, and I am happier using a different VPN.

Being able to scramble the lock screen PIN layout is a great security feature in my opinion, and I use it constantly. It's easy to get used to and makes me feel far less anxious in cases I have to type my PIN in public.

Installing /e/OS has become ridiculously easy. Their "Easy Installer" has been in development for quite some time and now runs in basically any Chromium browser. It guides one through all the steps required to get /e/OS running on an officially supported device. I have installed /e/OS on three Fairphone devices using the installer and was always done in less than 20 minutes. In all three cases, though, the installer failed to lock the bootloader at the end, which I ended up having to do manually. Locking the bootloader is quite important, especially for app functionality, and device security. I would like to see this being fixed, or (at the very least) have it made clear in the installation process that this has to be done manually. Currently, the installer just says everything is done, when the bootloader remains open.

Interestingly, I had noticed my phone's performance and battery life improving after installing /e/OS, which could be due to less background network activity.

## Murena Cloud

[Murena](https://murena.com/) is a company started by the founder of /e/ that, among other things, sells smartphones with /e/OS preinstalled. They also have a partnership with Fairphone to sell Fairphones with /e/OS. Additionally, Murena offers a cloud workspace, which includes email, a Nextcloud, and office apps.

Recently, /e/OS has been somewhat pushing Murena's cloud services, prompting for login/account creation during the initial setup process. The Murena Workspace app is also preinstalled. It's important to note that the setup prompt can easily be skipped, and the Workspace app can be uninstalled like any other app. I also don't think Murena's offerings are bad per se. For people coming from a very integrated environment like Android who may want cloud photo backups, documents, etc. Murena's cloud could be a viable option. I would certainly prefer it over Google's. The [cloud storage prices](https://murena.com/cloud-subscriptions/) also seem to be reasonable, though obviously more expensive than Google.

## The Bad

After using /e/ for so long, I obviously have some stuff to complain about, too, starting with the default launcher: It's an iOS clone. It's minimal, it's smooth, and I hate it. It's just not for me, and I have yet to find anyone who likes it. Everyone I know who uses /e/OS immediately installed a different launcher, which is why I don't necessarily see it as a big issue. After all, Android is very flexible in terms of UI modifications, although I'd prefer if the default launcher was just a little bit better.

During the early days of me using /e/OS, stability and performance were still quite lacking compared to today. This obviously won't affect anyone installing /e/ now, but it is part of my long-term experience.

The preinstalled maps app "Magic Earth" is proprietary, which I think is just stupid. It uses OSM data, and I've tried it for driving, which it handles quite well. In the end, I still wound up using Organic Maps, though, since I didn't see the point in using a proprietary maps app on an OS that is supposed to be open.

Speaking of apps, "App Lounge" is great when it works, but it often has long loading times, or trouble installing apps. Often times when tapping "install" on an app, it won't work and shows a "retry" button that also doesn't work. I would guess that this is due to the way that App Lounge sources apps from Google Play. I have gotten around it by installing [F-Droid](https://f-droid.org/) and [Aurora Store](https://store.auroraoss.com/) as a backup.

Multitasking sometimes acts weird, with the task switching gestures occasionally not working properly and leaving me with a blank screen that says "no recent items". I haven't heard anyone else complain about this, though.

Generally, the out-of-the-box experience isn't as good as I would like it to be. It takes most people quite a bit of effort to make their phone look and feel the way they want. Most of this comes down to replacing the default launcher and some default apps. Though, this is to be expected from an Android phone that doesn't have any of the default Android apps, I suppose.

## Conclusion

All-in-all, I've been happy with /e/. It's an easy way to degoogle one's phone, and even though it is far from the most private or most secure ROM, it's still way better than stock Android. Especially since the release of version 3.0, it has become pretty easy to recommend /e/ even for less tech-savvy people. I've installed /e/ for five people, all of whom still use it to this day with pretty much no issues. Once one gets over the initial bump of setting everything up, it's a pretty smooth experience.

*Image credit: [Wikimedia](https://en.wikipedia.org/wiki/File:E_Foundation_logo.svg)*
