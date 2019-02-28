# The Tin-Foil-Hat List
###### A list of privacy respecting alternatives to apps and services that track you around.

First and foremost, understand that the point of this list is to _improve_ your privacy, and not make you "disappear" online. Depending on your threat model, you should look elsewhere, like: [privacytools.io](https://privacytools.io) or [/r/privacy](https://reddit.com/r/privacy).

I'm not going to try to convince you on _why_ you should ditch Google, Facebook and other privacy offending services. I believe that if you're here, you're already aware of how these companies follow you around the web and use your data to profile, tailor your experience and worst of all, sell all your moves to third-parties.

It's worth saying that most of the following apps, devices and services are either open source or at very least, companies that have my _personal_ trust. Choose whatever suits you better because **there’s no warranty here. If it breaks, you get to keep both parts.** 😉

## Chapters

1. [Google Chrome](#google-chrome)

    1.1. [Mozilla Firefox](#mozilla-firefox-)
    
    1.2. [Brave](#brave-)
    
    1.3. [Apple Safari](#apple-safari-)
    
    1.4. [DNS Level AdBlockers](#bonus-blocking-ads-and-trackers-on-a-dns-level)
    
2. [VPN](#vpn)

3. [Google Search](#google-search)
    
4. [YouTube](#youtube)

5. [Gmail](#gmail)

6. [Dropbox](#dropbox)

7. [News Aggregators (Feedly, Flipboard, Twitter, etc)](#news-aggregators-feedly-flipboard-twitter-etc)


### Google Chrome

#### [Mozilla Firefox →](https://www.mozilla.org)
With a few tweaks and extensions, Firefox is known as one of the most secure browsers available. 

##### Recommended Extensions and Tweaks

- [uBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/): Block Ads and Trackers.
- [Privacy Badger](https://www.eff.org/privacybadger): Some extra protection to Ublock Origin.
- [HTTPS Everywhere](https://www.eff.org/https-everywhere): Encrypts your communications with many websites, making your browsing more secure.
- [Cookie AutoDelete](https://addons.mozilla.org/firefox/addon/cookie-autodelete): Automatically delete cookies.
- [Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/): Firefox Multi-Account Containers lets you keep parts of your online life separated into color-coded tabs that preserve your privacy. Which means, if you _really_ want to keep using Facebook for example, you should at least isolate it from your normal browsing.
- [Firefox "about:config" Tweaks](https://www.privacytools.io/#about_config): Some tweaks you can perform to make Firefox safer. 

#### [Brave →](https://www.brave.com/)
Brave automatically block ads and trackers, and it also supports HTTPS Everywhere and browser fingerprinting protection by default.

##### Recommended Extensions

Brave is built on top of Chromium, so it supports extensions too. You may be able to find some of the extensions—or at least good alternatives to the ones I listed in the [Mozilla Firefox](#mozilla-firefox-) section.

#### [Apple Safari →](https://www.apple.com/safari/)
Not the best of the options, but one I use often between Apple devices (because well… convenience?). Apple has been taking some interesting steps towards protecting users privacy, and more importantly, they're in business of getting your money, not selling your data (until proved wrong!).

Safari has a few built-in features that protect you from third-party trackers and fingerprinting—it's called Intelligent Tracking Protection. You can read more about it [here](https://webkit.org/blog/8613/intelligent-tracking-prevention-2-1/).

##### Recommended Extensions
Sadly, there are not many good extensions available for Safari. Due to some API limitations, extensions like Ublock Origin, HTTPS Everywhere, Cookie AutoDelete and custom tweaks cannot be supported—but I told you, right? Safari is not the best of the options and you should only use it if you put convenience over greater protection.

The only extension I have currently installed is [1Blocker](https://1blocker.com), it does a pretty good job at blocking ads, and in combination with something like a DNS Lever ad blocker (more info below), it's enough for most needs.

#### Bonus: Blocking Ads and Trackers on a DNS Level

This is something I really recommend you invest your money and time on. Why? Because it will protect _all_ your devices on your network, especially those you cannot install extensions or tweaks, like your Smart TV, Streaming Boxes, Smart Speakers, Smart Fridges (lol), etc.

There are mainly 2 options I recommend:

1. Buy a [Raspberry Pi](https://www.raspberrypi.org) if you don't have one already (you should, it's fun!) and install [Pi-Hole](https://pi-hole.net) on it. It's super easy and only requires a few commands to get it running. If you have a Mac, there's a quick and pretty good installation tutorial you can [watch here](https://invidio.us/watch?v=4RZ4ptuWAyw).
2. Ok, you want to save the trouble of messing up with some code and only need a little more protection. In that case, you can replace your ISP DNS by [Adguard's](https://adguard.com/en/adguard-dns/overview.html). Adguard is a respectable service that has a solid reputation—but it's worth saying you'll be trusting a third-party here, and besides, it doesn't offer the level of customization you get from Pi-Hole, which runs in your own network, under your control.

### VPN

Even after setting up some ad blockers, extensions and taking other privacy actions, companies and your own ISP can still snoop on your traffic. VPNs are mainly used to circumvent geo-restrictions and censorship but another benefit of using them is that you'll be assigned a shared IP instead of your private one, which makes tracking significantly harder.

About your ISP, they might very well be your worst enemy depending on where you live: They know all yours steps and many also sell your stuff to advertisers. For instance, this is a common and regulated practice in the U.S. Go figure…

Choosing a good VPN is all about trust. Although some of them are audited, you cannot be 100% sure that they will not log your activity, even if they explicitly say they won't. And at the end of the day, you'll be basically trading a party (your ISP) by another (a VPN service), and it's up to you to decide who you trust the most and what you're trying to protect from.

If you happen to choose the VPN route, **DO NEVER use a free VPN service**. The chances they'll log your activity and sell you on are also pretty big. In fact, if you were to use a free VPN, I'd just say you'd be better off not using anything.

The following are respectable services that have a solid reputation:

- [Mullvad](http://mullvad.net): All you need is account number and nothing else. Log free, several payment options. 
- [ProtonVPN](http://protonvpn.com): Built with the support of Protonmail team.

Regardless, I suggest you take a good look at [That One Privacy Site](https://thatoneprivacysite.net) for a comprehensive list.

### Google Search

I think this is one of the easiest habit changes, and takes very little effort to get used to. There are many alternatives out there but my two favorites are:

- [DuckDuckGo](https://duckduckgo.com/): Integrates with most desktop and mobile browsers, support shortcuts (a.k.a. [!Bang](https://duckduckgo.com/bang)), unbiased results outside the "Filter Bubble".
- [Startpage](https://startpage.com/): A pretty solid alternative if you can't get used to DuckDuckGo's results. Startmail displays Google Search results without letting them build a profile out of your queries. Bonus points: They're based in Europe, where privacy laws are more friendly.

### YouTube

Youtube is a tricky one to be replaced, I get that—and its alternatives are not really great. But anyway, there's a way to a improve things a bit by using a third-party client.

[Invidio.us](https://invidio.us) is an open source front-end for YouTube with playlists supports, video/audio downloads and (mostly) no trackers or ads. I say mostly because Google will still log your IP address while watching a video, since the videos come from their server.

I also suggest you install the [Invidious Redirect](https://addons.mozilla.org/en-US/firefox/addon/hooktube-redirect/?src=search) extension so you can open YouTube links straight in Invidio.us. On iOS, you can use this [Open in Invidious](https://www.icloud.com/shortcuts/a78847c422804045b391cc3f33b97ee6) shortcut I've put together.

### Gmail

If you asked me 6 months ago, I'd blindly say go with [Fastmail](https://fastmail.com) as it's the most user friendly email provider you'll find while migrating from Gmail but… a few months ago Australia approved [this bill](https://www.scmp.com/news/asia/australasia/article/2176759/australia-has-become-first-western-country-pass-bill-forcing) that allows the government to demand tech companies to create a back door to users’ data, so yeah…

I'm not going through each of the following services because it really depends on your what exactly you need feature-wise and the level of security you're looking for (as secure as an email can be). Comparing its features and limitations is my best advice. E.g. Some providers support the IMAP protocol, others you have to stick to their own apps for enhanced security; Some you have stick to their domain names, and others you can use your own.

- [Protonmail →](https://protonmail.com)
- [Tutanota →](https://tutanota.com)
- [Mailfence →](https://mailfence.com)
- [Posteo →](https://posteo.de)
- [StartMail →](http://startmail.com)

### Dropbox

Because this is a complicated topic depending on what you do for a living, your company may require you to use Dropbox. So I'll split this section in two:

#### Clients

- [Transmit (Mac)](https://panic.com/transmit/): For a long time I've been using Panic's Transmit as a Dropbox file browser. Files are kept remotely, and you can open and save them on demand.
- [Dropbox (Web)](https://dropbox.com/): Alternatively, you can also use the web version of Dropbox. It's decent, but inconvient as you'll have to download and upload your files manually.

#### Alternatives

- [OwnCloud](https://owncloud.org): A full-featured Dropbox replacement with a handful number of extensions to install. Your files are end-to-end encrypted, there's support for CalDav/CardDav sync—which you can use to sync your Contacts and Calendars to any of your devices, and you can even run your server locally.
- [Syncthing](https://syncthing.net): If all you need is a simple way to sync files between devices and with colleagues, this is a very lightweight solution that I couldn't recommend enough.

### News Aggregators (Feedly, Flipboard, Twitter, etc)

I know it's too tempting to use any of these services as a way to consume your news, but they're generally aggressive at building a profile based on what you click and interact to. And as you know, these apps are pretty good at keeping you on a "Filter Bubble" by sorting entries by what AI thinks you'll like better. A good old-fashioned RSS service is usually a fantastic antidote to that.

- [Feedbin](https://feedbin.com): You can subscribe not only to RSS Feeds, but also Twitter accounts and email newsletters. You can also set up mute filters to mark entries as read automatically. Feedbin works with a bunch of mobile and desktop apps, and their web interface is fantastic too.
- [Tiny Tiny RSS](https://tt-rss.org): It's also a solid alternative if you want to run your own RSS aggregator. It supports the Fever API, making it possible to use with many third party apps like [Unread](https://www.goldenhillsoftware.com/unread/) and [Reeder](http://reederapp.com) for iOS.
