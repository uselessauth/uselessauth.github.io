---
layout: post
title:  "Thoughts on Discord's Age Verification."
date:   2026-02-18 20:30:00 +0100
categories: privacy discord online-safety
tags: opinion privacy
media_subpath: /assets/03-discord-age-verification
image:
  path: discord-age-verification_preview.png
  alt: discord logo face scan by luna
---

In 2023, [I wrote a piece about Discord](https://uselessauth.github.io/posts/discord-not-main-messenger/). I argued that Discord was not built to be a private messenger and not suitable for sharing private information. Back then, I still thought of Discord as tolerable for its intended use case: Non-sensitive communication about gaming. I think that as of March 2026, this will no longer be the case.

# Discord Is Changing

Discord will be rolling out age verification, [which may require users to scan their face or upload an image of a government ID](https://support.discord.com/hc/en-us/articles/30326565624343-How-to-Complete-Age-Assurance-on-Discord). Although Discord assures that this will not be required for the vast majority of users and that all the information Discord receives is the age of the account holder ([s](https://discord.com/safety/how-discord-is-building-safer-experiences-for-teens)), [people are still upset](https://www.reddit.com/r/discordapp/comments/1r05vkj/discord_will_require_a_face_scan_or_id_for_full/) about these changes. It doesn't help that just a few months ago, they had a massive data leak related to their UK age verification process, which may have included ID photos of around 70,000 users ([s](https://www.bbc.com/news/articles/c8jmzd972leo)), which obviously doesn't make the "your data will be safe" claims as believable as Discord would like them to be.

Speaking of the UK, it's arguably their Online Safety Act that kickstarted this whole "upload your ID" thing we see pop up everywhere.

Now one may think "This may be a horrible precedent for privacy around the world, but at least it keeps our kids safe, right?".

# An Aside: Kids' Safety

Well, not really, no. Kids have been known to bypass age verification methods with ease, using methods like scanning the face of a video game character or uploading someone else's ID ([s](https://shuftipro.com/blog/age-verification-evasion-in-2025-how-minors-outsmart-weak-age-gates-and-how-to-fight-back/)). Deepfakes are also getting better and better, with live video deepfakes being a thing that exists now and can be [downloaded for free from GitHub](https://github.com/iperov/DeepFaceLive).

It is extremely questionable whether or not these age verification efforts are making kids safer online. One would think that making kids safe online would involve education. Teaching them about online safety, having an eye on them when they are online, restricting the amount of time they spend online. Working *with* the kids to have them grow into competent adults that can safely navigate the internet on their own.

I think kids' online safety is a social problem which requires social solutions, not technical ones. An age verification check will not keep a 14-year-old from watching porn if they really want to because one way or another, they'll manage to find what they want to see. That's the nature of the internet, whether we like it or not.

I like to think of the internet as a tool (which to most people it most certainly is). Take any tool, like a hammer, and see what it can do. You can nail things, you can bend things, you can break things, all very useful. You can also hit your thumb and hurt yourself, or hurt someone else, not very useful.
Now, most people will at some point in their life use a hammer. How do we make sure this can be done safely? Do we forbid anyone under the age of eighteen from ever seeing or touching a hammer and then as soon as they turn eighteen we say "Here, you're eighteen and know how to use this now, go nuts!" and expect them to be able to handle it? That sounds kind of ridiculous, because it is.

An approach I think is better would look something like this: If you are doing something with a hammer, let your kid watch. Maybe let them hold the hammer a little, let them "help" you by "nailing a piece of wood all on their own", maybe give them a small kids hammer that they can play with and use to put one or two utterly useless nails in, just because it's fun. Teach them how to use a hammer and spend some quality time with your kid at the same time. The more capable they grow, the more freedom you can give them. Any good parent will think "that's not a new idea, that's parenting". Exactly; and if they hit their thumb and hurt themselves, that's okay; they'll learn from it.

A 15-year-old kid that was gradually taught how to use a tool will be infinitely more capable of using it safely and responsibly than an adult who has been sheltered from it all their life. I know this because this is how I was raised (and I wasn't even raised by very tech-smart people). Letting kids try things in a supervised environment and occasionally fall on their face is invaluable.

The solution to kids' safety online is the same as with every other tool: Education. Of course not just at home, but in schools, too.

# Now, What About Discord?

Judging by [this Reddit thread](https://www.reddit.com/r/discordapp/comments/1r05vkj/discord_will_require_a_face_scan_or_id_for_full/), Discord will most certainly lose some users to this change in policy, just like Reddit did back in 2023 when their API changes rolled out. Will this end Discord? Probably not. Will this end Discord for me? Absolutely.

I think that even if all of Discord's claims are true (which is as always debatable), it does open a door I firmly believe should stay shut. I think protecting documents that have a huge impact on your real life is vitally important for everyone and the inhibition people feel when they're asked to share this information is an important part of keeping private data private. If people are willing to share their ID with Discord or any other social platform ([looking at you, Facebook](https://www.facebook.com/help/755374461973127/)), their general willingness to share such documents will increase. This is not only a privacy nightmare but can have tremendous real-world consequences such as identity-theft, when these documents inevitably fall into the wrong hands.

When faced with the choice of sharing your ID with a platform or leaving that platform, I would advise you to choose the latter.

# Goodbye, Discord

The reason I made a new Discord account in January of 2025 was friends. They were on Discord and had no reason to switch, so I decided that spending quality time in voice channels with friends was worth the cost of having a Discord account. A few days ago, some friends approached me about Discord's upcoming changes and told me they were uncomfortable with the new policies and were wondering if I had a solution to the problem. I was very happy about this, because I felt that my relentless ranting about online privacy had stuck with them and I was very happy that everyone was ready to jump ship.

I set up an [Element](https://element.io/en) server that very night (which took less than 15 minutes with [this guide](https://github.com/element-hq/ess-helm?tab=readme-ov-file#getting-started)) and everyone had migrated to Element within 30 minutes. It is far from a drop-in replacement for Discord (which is good in lots of ways), but it is perfectly adequate for our needs, since it provides good video calling (with far superior stability and quality compared to Discord!) and that is pretty much all we needed.

Everyone is quite content with the change and while it may be a little bittersweet (especially since we had to say goodbye to our custom music bot), we all feel more comfortable on a self-hosted open-source E2EE platform.

_Image Credit:_ [_Wikimedia_](https://upload.wikimedia.org/wikipedia/en/9/98/Discord_logo.svg)
