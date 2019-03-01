![Header Image](header_image.jpg)

# The Tin-Foil-Hat List
###### A list of privacy-respecting alternatives to apps and services that track you around.

First and foremost, understand that the point of this list is to improve your privacy, and **not** to make you "disappear" online. If you're exposed to a higher threat model, you should look elsewhere, like: [privacytools.io](https://privacytools.io) or [/r/privacy](https://reddit.com/r/privacy) to name a few.

Anyway, as you're likely aware, tech giants like Google, Facebook, Amazon and many others follow you around the web and use your data to profile, lock you into a "Filter Bubble", and worst of all, sell all your moves to advertisers and other third-parties.

In the following list, you'll find a few privacy-respecting alternatives to services, apps and devices I use the most. Most of them are open source, or at the very least companies that have my _personal_ trust.

It's worth reminding: Choose whatever suits you better and consider your options, because **there’s no warranty here. If it breaks, you get to keep both parts.** 😉

## Chapters

1. [Google Chrome](#google-chrome)

    1.1. [Mozilla Firefox](#mozilla-firefox-)
    
    1.2. [Brave](#brave-)
    
    1.3. [Apple Safari](#apple-safari-)
    
    1.4. [DNS Level ad blocking](#bonus-dns-level-ad-blocking)
    
2. [VPN](#vpn)

3. [Google Search](#google-search)
    
4. [YouTube](#youtube)

5. [Gmail](#gmail)

6. [Dropbox](#dropbox)

    6.1. [Clients](#clients)
    
    6.2. [Alternatives](#alternatives)

7. [News Aggregators (Feedly, Flipboard, Twitter, etc)](#news-aggregators-feedly-flipboard-twitter-etc)


### Google Chrome 

#### [Mozilla Firefox →](https://www.mozilla.org)
With a few tweaks and extensions, Firefox is known as one of the most secure web browsers.

##### Recommended Extensions and Tweaks

- [uBlock Origin](https://addons.mozilla.org/firefox/addon/ublock-origin/): Block Ads and Trackers.
- [Privacy Badger](https://www.eff.org/privacybadger): Some extra protection to uBlock Origin.
- [HTTPS Everywhere](https://www.eff.org/https-everywhere): Encrypts your communications with many websites, making your browsing more secure.
- [Cookie AutoDelete](https://addons.mozilla.org/firefox/addon/cookie-autodelete): Automatically delete cookies. Highly customizable to your needs.
- [Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/): Firefox Multi-Account Containers lets you keep parts of your online life separated into color-coded tabs that preserve your privacy. Which means, if you _really_ want to keep using Facebook for example (but you shouldn't!), you can at least isolate it from your normal browsing.
- [Firefox "about:config" Tweaks](https://www.privacytools.io/#about_config): Some tweaks you can perform to make Firefox safer. 

#### [Brave →](https://www.brave.com/)
Brave automatically block ads and trackers, has built-in support for HTTPS Everywhere and fingerprinting protection.

##### Recommended Extensions

Brave is built on top of Chromium, so it supports extensions too. You should be able to find some of the extensions—or at least good alternatives to the ones I listed in the [Mozilla Firefox](#mozilla-firefox-) section.

#### [Apple Safari →](https://www.apple.com/safari/)
Certainly not one of the best options, but it's a browser I use often because well… convenience? Anyway, Apple has been taking some important steps towards protecting users privacy lately, and more importantly, they're in business of getting your money, not selling your data (until proven wrong!).

With Safari 11, Apple introduced a new feature called Inteligent Tracking Protection which prevents cross-site tracking and browser fingerprinting. You can read more about it [here](https://webkit.org/blog/8613/intelligent-tracking-prevention-2-1/). It's pretty neat how it works.

##### Recommended Extensions
Sadly, there are not many good extensions available for Safari. Due to some API limitations, extensions like uBlock Origin, HTTPS Everywhere, Cookie AutoDelete and custom tweaks cannot be supported—but I told you, right? Safari is not the best of the options and you should only use it if you'd rather convenience over greater protection.

The only extension I have currently installed is [1Blocker](https://1blocker.com), it does a very good job at blocking ads, and in combination with DNS level ad blocking (more info below), it should be enough for most of your needs.

#### Bonus: DNS Level Ad Blocking

This is something I really recommend you invest your money and time on. Why? Because it will protect _all_ your devices on your network, especially those you cannot install extensions or tweaks, like your Smart TV, Streaming Boxes, Smart Speakers, Smart Fridges (lol), etc.

There are mainly 2 options I recommend:

1. Buy a [Raspberry Pi](https://www.raspberrypi.org) if you don't have one already laying around and install [Pi-Hole](https://pi-hole.net) on it. It only requires a few commands to get it running. If you have a Mac, there's a quick and reasonably easy-to-follow installation tutorial you can [watch here](https://invidio.us/watch?v=4RZ4ptuWAyw).
2. Nope? Ok, you want to save the trouble of messing up with some code and only need a little more protection. In that case, you can replace your ISP DNS by [Adguard](https://adguard.com/en/adguard-dns/overview.html)'s. Adguard is a respectable service that has a solid reputation—but it goes without saying you'll be trusting a third-party here, and besides, it will not offer the same level of customization you get from Pi-Hole, which runs in your own network, under your control.

### VPN

Even after setting up some ad blockers, extensions and taking the other privacy measures, companies and your own ISP can still snoop on your traffic.

Though, about your ISP, they might very well be your worst enemy depending on where you live: They know all yours steps and many also sell your stuff to advertisers and who knows what else. For instance, this is a common and regulated practice in the U.S. Go figure…

And that's where a good VPN comes in for help. VPNs are mainly used to circumvent geo-restrictions and censorship, but another benefit of using them is that you'll be assigned a shared IP, so the websites you visit cannot see your real and private IP. By doing that, profiling you becomes significantly harder.

Choosing a good VPN is _all_ about trust. Although some of them are audited, you cannot be 100% sure that they will not log your activity, even if they explicitly say they won't. And at the end of the day, you'll be basically trading a party (your ISP) by another (a VPN service)—it's up to you to decide who you trust the most and what you're trying to protect yourself from.

One very valuable advice: **DO NEVER use a free VPN service**. The chances they will mine your data the way it pleases is higher than you can imagine. In fact, if you were to use a free VPN, I'd just say you'd be better off not using anything.

The following are considered respectable services that have a solid reputation:

- [Mullvad](http://mullvad.net): You don't even need to create an account with them, all you'll get is an account number and nothing else. They claim not to log your activity and offer several payment options. 
- [ProtonVPN](http://protonvpn.com): Built by the Protonmail team. Highly recommended too.

For a comprehensive list of other VPN services, take a good look at [That One Privacy Site](https://thatoneprivacysite.net).

### Google Search

There are many alternatives out there but my two favorites are:

- [DuckDuckGo](https://duckduckgo.com/): Integrates with most desktop and mobile browsers, super very handy shortcuts support (a.k.a. [!Bang](https://duckduckgo.com/bang)), and best of all, you get unbiased results outside the "Filter Bubble" since they don't keep records of your past searches.
- [Startpage](https://startpage.com/): A solid alternative too if you can't get used to DuckDuckGo's results. Startmail displays Google Search results but act as a middle-man between you and Google, which means the latter cannot directly interact with you. Bonus points: They're based in Europe, where privacy laws are taken more seriously.

### YouTube

Youtube is a tricky one to be replaced, and its alternatives are not great. Still, there's a way to a improve things a bit by using a third-party client.

[Invidio.us](https://invidio.us) is an open source front-end for YouTube with playlists support, ability to download the videos, and no ads or trackers (mostly). I say mostly because Google will still log your IP address while watching a video, since the videos come from their server.

I also suggest you install the [Invidious Redirect](https://addons.mozilla.org/en-US/firefox/addon/hooktube-redirect/?src=search) extension so you can open YouTube links straight in Invidio.us. On iOS, you can use this [Open in Invidious](https://www.icloud.com/shortcuts/a78847c422804045b391cc3f33b97ee6) shortcut I've put together.

### Gmail

If you asked me 6 months ago, I'd blindly suggest [Fastmail](https://fastmail.com) as it's the most user friendly email provider you can find while migrating from Gmail but… a few months ago Australia approved [this bill](https://www.scmp.com/news/asia/australasia/article/2176759/australia-has-become-first-western-country-pass-bill-forcing) that allows the government to demand tech companies to create a back door to users’ data, so yeah… No-no.

Thankfully, there are many alternatives but I'm not going through each of the following services because it really depends on what exactly you need feature-wise and the level of security you're looking for (as secure as an email can be anyway). Comparing its features and limitations is my best advice. E.g. Some providers support the IMAP protocol, others you have to stick to their own apps for enhanced security; Some you have stick to their domain names, and others you can use your own.

- [Protonmail →](https://protonmail.com)
- [Tutanota →](https://tutanota.com)
- [Mailfence →](https://mailfence.com)
- [Posteo →](https://posteo.de)
- [StartMail →](http://startmail.com)

### Dropbox

This is a complicated topic depending on what you do for a living, as your company may require you to use Dropbox. So I'll split this section in two:

#### Clients

- [Transmit (Mac)](https://panic.com/transmit/): For a long time I've been using Panic's Transmit as a Dropbox file browser. Files are kept remotely, and you can open and save them on demand.
- [Dropbox (Web)](https://dropbox.com/): Alternatively, you can also use the web version of Dropbox. It's decent, but inconvient as you'll have to download and upload your files manually.

#### Alternatives

- [OwnCloud](https://owncloud.org): A full-featured Dropbox replacement with a handful number of extensions to install. Your files are end-to-end encrypted, there's support for CalDav/CardDav sync, so you can sync your Contacts and Calendars to any of your devices, and even run your server locally.
- [Syncthing](https://syncthing.net): If all you need is a simple way to sync files between devices or colleagues, this is a very lightweight solution that I couldn't recommend enough.

### News Aggregators (Feedly, Flipboard, Twitter, etc)

I know it's too tempting to use any of these services as a way to consume your news, but they're generally aggressive at building a profile based on what you click and interact to. Aside from that, these apps are pretty good at keeping you on a "Filter Bubble" by sorting entries by whatever the machine learning thinks you'll like better. A good old-fashioned RSS service is usually a fantastic antidote to that.

- [Feedbin](https://feedbin.com): You can subscribe not only to RSS feeds, but also Twitter accounts and email newsletters. On top of that, there are options to set up mute filters to mark entries as read automatically (_ahem_ Trump, Kardashian, Bieber, Pancakes?). Feedbin works with a bunch of mobile and desktop apps, and their web interface is very well designed too.
- [Tiny Tiny RSS](https://tt-rss.org): It's also a solid alternative if you want to run your own RSS aggregator. It supports the Fever API, making it possible to use with many third party apps like [Unread](https://www.goldenhillsoftware.com/unread/) and [Reeder](http://reederapp.com) for iOS.
