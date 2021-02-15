<div style="text-align:center;">
    <h1>Privacy is not for everybody</h1>
    <h2>An honest view of all apps</h2>
</div> 

This is a list of alternatives to everyday software. But it's not just another 'Awesome List' as you might have seen on GitHub, it's much more than a simple enumeration. It's a guide for good practices and what to use and in what situations. Also, I'm not gonna talk only about the privacy aspects, but about the usage of services in general. The problem with going to more secure apps is not that some people want to, but in some cases, like social media or video platforms, you will find nobody, so there's no usage after all for these.

## Disclaimer
If you don't intend to change your workflow, you shouldn't read the entire list. Just the parts where I list the mainstream alternatives. Using non-mainstream software is not for everybody. I understand people using the popular software. It's easy and in most cases, it just works. Maybe there are some alternatives, but it's hard to change your lifestyle. I admit that, this guide is not for that kind of people. I'm not gonna list all the data breaches that big corporations did, if you want to check them go on [r/degoogle](https://reddit.com/r/degoogle/), [r/privacytoolsIO](https://www.reddit.com/r/privacytoolsIO/) or [r/privacy](https://www.reddit.com/r/privacy/). If your end goal is just to remove Google from your life, read [tycrek's degoogle guide](https://github.com/tycrek/degoogle). 

This list is originally posted on [SourceHut](https://sourcehut.org/) (open-source), but might end up being posted somewhere else. If you have another pieces of software or you disagree with something let me. Maybe, I will post it on Github, even if it's proprietary and it's actually from Microsoft, but more people have accounts on it.

Some of the alternatives are open source, some are not.

## Contents
- [Search Engines](#search-engines)
- [Messaging](#messaging)
- [Video Platforms](#video-platforms)
- [Social Media](#social-media)
- [Mail Providers](#mail-providers)
- [App Stores](#app-stores)
- [Cloud Platforms](#cloud-platforms)
- [Operating Systems](#operating-systems)
- [Map Services](#map-services)
- [Office Suits](#office-suits)
- [Code hosting](#code-hosting)
- [Final words](#final-words)

# Search engines:
The popular ones are:
- [Google Search](https://google.com) is owned by Google, probably the most tracked from all of these. Despite the privacy issues, it's the fastest and the most actual one, because it's the best at indexing. It is censoring some websites, so it might not be the right choice for you if you wanna check the 'other part' of the internet, and I'm not talking about Dark Web, but the actual web. [The Daily Stormer](https://dailystormer.su/) is the biggest I can think of. Also, it removes a lot of torrent websites.
- [Bing](https://bing.com) is owned by Microsoft. They do almost the same telemetry as Google. It's entirely proprietary, and it's slower than Google. Its advantage over Google Search is the Images category. Google Images provide cool settings, but you need to dig down to find them, while on Bing they are better displayed. I will not recommend it, but its indexes are used by other search engines like DuckDuckGo, Qwant, Searx. It's good to find torrents and websites are not censored like on Google.
- [Yahoo Search](https://yahoo.com) is owned by Yahoo. It's almost the same thing as Bing, as they share the indexes. 
- [Baidu](https://baidu.com) is owned by Baidu. As of the time of writing this, I can't even connect to Baidu, because of some problems with SSL. `Error code:SSL_ERROR_UNSAFE_NEGOTIATION`. It's used mostly by Chinese people. 
- [Yandex](https://yandex.com) is owned by Yandex. It's the most popular search engine in Russia. Some people state that it's better for American people because Russians don't have many things to do with their info.


Some alternatives to these are:
- [DuckDuckGo](https://duckduckgo.com) is the most used 'search engine' from this part of the list. Some of the parts are open-source, some are not. They had some controversial in the past. Check [this](https://github.com/duckduckgo/Android/issues/527). This is an issue with the search engine, but the company's browser. By the way, it's not actually a search engine, it's a [meta search engine](https://en.wikipedia.org/wiki/Metasearch_engine)
- [Qwant](https://www.qwant.com/) is actually a search engine. It's very popular in France. They provide a normal, a `light` and a `junior` version. They use Microsoft Azure for the cloud service. 
- [Searx](https://github.com/searx/searx) is also a meta search engine, which retrieves its information from Google, Bing, Reddit, Yahoo, Wikipedia, Wolfram, Yandex, DuckDuckGo and more. This is open-source. You can run your own instance if you are afraid of using a public instance. A list of public instances can be found [here](https://searx.space/). Some of them are using Tor.
- [YaCy](https://github.com/yacy/yacy_search_server) is a search engine. It's open-source, but the difference between it and Searx it's that it is decentralized. There is no center server. You need to deploy their server. Its big disadvantage is that it's slower than the others because it brings all the results from peers. 
- [Swisscows](https://swisscows.com/) is a meta search engine. It uses Bing for Web Searches, SoundCloud for music, Yandex for translation. It's based on Switzerland. This is a pro for many people.

The only two from these list that don't contain any trackers whatsoever are Searx and YaCy. DuckDuckGo, Qwant and Swisscows are tracked by [Improving DuckDuckGo](https://improving.duckduckgo.com/). They state that they 'do not collect or share any personal information'. Personally, I'm using DuckDuckGo, maybe I will change.

# Messaging
The messaging apps are:
- [WhatsApp](https://whatsapp.com) is owned by Facebook. It is end-to-end encrypted, so it shouldn't spy on your messages, but it's owned by Facebook, and this makes it feel not very safe. WhatsApp is the most used messaging app. Now the question comes 'and how do they make money?'. It's a valid question from my point of view. Searching through the web, I found sites claiming that it makes money using 'WhatsApp Business', but I don't know if that's true. Also, they changed their privacy policy and this made people change their default messaging app. 
- [Telegram Messenger](https://telegram.org/) is owned by Telegram. It is not entirely end-to-end encrypted. It's only encrypted while calling people, and it's optionally in 'secret' chats. Telegram is used by a lot of 'secret' groups, it provides access to an API used for making bots. Some parts are open source. Their phone apps are kinda open source, but they are using some Google software that's not. [This is the open source app for Android.](https://github.com/Telegram-FOSS-Team/Telegram-FOSS) Their desktop app is fully open source. They say that they aren't spying on users, and the money they make are only from donations.
- [Signal](https://signal.org) is owned by Signal, a nonprofit. It is fully open source, end-to-end encrypted. In January 2021, it blew up because of WhatsApp changing TOS. It had been unusable for more than 2 weeks. Also, even that they are open source they don't provide an apk for F-Droid. They are explaining this [here](https://github.com/signalapp/Signal-Android/wiki/F-Droid). It might be a pro or a con.

There are more messaging apps, I've been speaking only about these 3. None of these 3 include ads. Other messaging apps are:
- [Snapchat](https://www.snapchat.com/) - I don't wanna talk about this abomination.
- [Viber](https://www.viber.com/en/) is more like WhatsApp, but it includes ads.
- [Google Hangouts](https://hangouts.google.com/) is owned by Google and includes a lot of telemetry, doesn't include end-to-end encryption.

All of these messaging apps need some sort of authentication. They require a phone number or a real account. I've used WhatsApp, Telegram and Signal. To be honest with you, I'm using WhatsApp, not because I want to, but because I need to. 

# Video platforms
Video platforms that are used are:
- [Youtube](https://www.youtube.com/) is owned by Google. It's like Google Search for videos. Everybody knows about it. Every popular vlogger is there(I know that it sounds weird). It's being a place where all the idiots are producing millions of dollars doing nothing. It, like any other Google software(beside the go language), includes telemetry. If you wanna browse Youtube more private, should use either [Youtube Vanced](https://vancedapp.com/), [NewPipe](https://newpipe.net/) or [Invidious](https://invidio.us/).
- [PeerTube](https://github.com/Chocobozzz/PeerTube) is open source, free, decentralized. It also sounds like a dream, but it's far away. First of all, it's slower than Youtube because it's decentralized and it based on torrent protocols. Second, it's not moderated and this can be good or not depending on who you are and what you want to see. By joining a random instance, I found 4 porn videos on the recommended page, and I'm not interested in these videos. I advise kids to stay on Youtube(it also contains nudity, but you need to search for it in order to find it). It's approved by FSF.
- [LBRY](https://lbry.tv/) is a blockchain based alternative to Youtube. It's also open source, and it has its own reward program, but it comes also with problems. I think it's even slower than PeerTube, no moderation, so it also contains porn. But from what I've seen, it's more based on what you watch than PeerTube. A lot of Youtubers created LBRY accounts. Also, there is [Odysee](https://odysee.com/) which is another interface for LBRY. 
- [Dailymotion](https://odysee.com/) is owned by Vivendi. It has partnerships with Vice, BBC, Bloomberg and some sport competitions. It's not very private at all, contains telemetry. Furthermore, it also has a lot of ads.

I am using Youtube, not directly, but, via Vanced or NewPipe. The content from PeerTube is dangerous, and I don't wanna take the risk. PeerTube is approved by Free Software Foundation if you care about this. I'm not a parent, but if I was, I wouldn't let my kids on neither PeerTube nor LBRY. I've seen it by myself, but also on Reddit.

# Social Media
Complex topic. There are a lot of social media apps:
- [Facebook](https://facebook.com) is the biggest social media. It is also one of the oldest out there. It has more than 3 billions active users. Almost everybody has or had a Facebook account. It has been the object of multiple controversial like the one with (Cambridge Analytica data leak)[https://www.businessinsider.com/cambridge-analytica-whistleblower-christopher-wylie-facebook-data-2019-10]. It doesn't have any good points, over the others, just spyware and trackers.
- [Instagram](https://www.instagram.com/) is also owned by Facebook. Originally, it was created to compete with Facebook, but then Facebook bought it for 1 billion dollars. It has become just an extension to Facebook (you can create an Instagram account using a Facebook one). Not the best for privacy, containing trackers and spyware.
- [TikTok](https://www.tiktok.com/) is owned by ByteDance, a Chinese company. It became popular after merging with [Musical.ly](https://www.musical.ly/). It was in some big controversies. Donald Trump threatened to ban TikTok unless another company buys it. Also, it has problems with underage kids doing weird stuff, old boomers swearing and manipulating children. From a privacy perspective, there were some problems as well. Check [this](https://www.boredpanda.com/tik-tok-reverse-engineered-data-information-collecting/) and also [this](https://rufposten.de/blog/2019/12/05/privacy-analysis-of-tiktoks-app-and-website/). Not the best for privacy, maybe worse than Facebook.
- [Twitter](https://twitter.com) is very popular among Americans, and not only. It's used by tech experts. It also started to censor some personalities like Donald Trump(same for Facebook). This may be a good thing for some of you, but for me it's not, and not because I am Republican(I'm not even American), but I don't agree with 'politically correct' movement. As to privacy concerns, it had some problems with [data breaches](https://nypost.com/2020/12/15/twitter-fined-547k-for-privacy-breach-under-eu-law/).
- [Reddit](https://www.reddit.com/) is more than a social media. It's a news aggregation, discussion website. Some of the subreddits look like forums([r/linuxquestions](https://www.reddit.com/r/linuxquestions/), [r/AskReddit](https://www.reddit.com/r/AskReddit/)). It's in the 'chad group' with [4chan(NSFW)](https://4chan.org). It has a nice policy about NSFW and SFW content, as it marks the NSFW posts. It also marks spoilers and original contents ones. It's a nice place to talk about technology, sports, privacy, politics, etc., more like a 4chan for normies. [The big problems with Reddit are that it's being censored, it doesn't respect your privacy at all](https://restoreprivacy.com/stop-using-reddit/). 

Probably it's enough for social media apps. From this list the only thing I use is Reddit. At least in comparison with the others, sometimes you find something that it's actually good, not some garbage. From a privacy point, no one is good and probably you should use something like [Hacker News](https://news.ycombinator.com/news), [diaspora](https://diasporafoundation.org/) or [KARMA](https://karmaapp.io/). All of the popular social medias have some open source clients, for Reddit you will find a lot, for Instagram it's only [Bibliogram](https://sr.ht/~cadence/bibliogram/), in case of Twitter, just use RSS feeds, also in case of Facebook. 

# Mail providers
There are some popular ones like:
- [Gmail](https://gmail.com) is owned by Google. It's used by billions, but like in the case of other Google services, it's just spyware. Its advantage over the others is that it gives you 15 GB instead of 500 MB or 1 GB for the free versions of the others(maybe you understand why). Also it spies on your emails and filters them on what subject they are(like shopping stuff etc).
- [Outlook](https://outlook.live.com/) is owned by Microsoft. Like Gmail, it's full of spyware. It's used by corporations or just the people who use Windows 10 with a Microsoft account. 
- [Yahoo](https://yahoo.com/) is owned by Verizon these days. Maybe you remember the good old days when people were talking through Yahoo Messenger. It has also spyware.
- [ProtonMail](https://protonmail.com/) is owned by ProtonMail, a Swiss company. It's the most known secure email service. It can use GPG keys, and you can see your emails in a special Tor service. The biggest disadvantage is that it only gives you 500 MB of storage, and you can't use SMFT when you don't have a paid account. It has some [privacy issues](https://privacy-watchdog.io/truth-about-protonmail/). Most of them are theoretical, but who knows. ProtonMail is not fully open source.
- [Tutanota](https://tutanota.com/) is a fully open source email provider. It's cheaper than ProtonMail, and also it has more features than it. These two are very similar, and you can check this [website](https://www.cloudwards.net/tutanota-vs-protonmail/) for the differences about these. But from what I've seen Tutanota is more secure than ProtonMail.

My daily driver is ProtonMail. I have two Gmail accounts, an Outlook account and a Yahoo one. The Gmail accounts come from my Google accounts, the Outlook from the fact that I was using Windows and the Yahoo one from my childhood. This doesn't mean that I actually use them. I feel comfortable with ProtonMail, and I'm using PGP to encrypt my emails.

# Translate
Main translation sites are:
- [Google Translate](https://translate.google.com/) is owned by Google. It has the best translations, the most languages to translate to and from and comes with a lot of trackers.
- [Bing Translator](https://bing.com/translator/) is owned by Microsoft. It has fewer languages, but supports most weird languages, and it has less accurate translations, no pros in race with Google.
- [DeepL Translator](https://www.deepl.com/translator) is a lightweight, privacy respecting(at least in some cases) alternative. It supports only 11 languages. It doesn't have trackers on the website. The company behind it claims that it makes money from the commercial usage of their API.
- [Papago](https://papago.naver.com/) is an Asian translator. Not involved whatsoever in privacy, but probably the best for Asian speakers.

For my work, I'm using Google Translate. It may sound weird, but it's pretty private for me. No I'm not using their website, not instead either [gtranslate](https://sr.ht/~yerinalexey/gtranslate/) or my own go library [gotranslate](https://sr.ht/~dankwarrior/gotranslate/). You may say that it's unsafe because you ping google, but you can run Tor in background and just use it as a Proxy. Google will treat you as just another Tor imposter. Now you might ask why not just use Tor everywhere, isn't it the answer to ultimate privacy. No, it's not. It's slow for most actions, you can't see a photo, or watch a 10-second video from YouTube. Why I don't use DeepL? My native language isn't in their list, so I can't use it for translations from my native language to English or German. 
 
# App stores
This topic is big, because there are a lot of OSes, everyone with their App Stores.
## Windows:
- [Microsoft Store](https://www.microsoft.com/en-us/store/apps/windows) is the only real app store. It comes with Windows, and you can't remove it, to be honest, you can, but it reinstalls every time you update Windows. It's a copypasta of Google's Play Store from Android, it looks almost the same. It was first created for Windows Phones, but these disappeared, and Microsoft needed to do something with this. It doesn't have much software. It also comes with spyware bundled.
- [Chocolatey](https://chocolatey.org/) is a package manager, not actually an app store. It works like the ones from Linux, you install packages using a simple command, not going through websites, checking download URLs, getting malware. It became de facto, the only ever needed package manager for Windows. Most programming blogs teach you to install software through it. This is open source.
- [winget](https://github.com/microsoft/winget-cli) is Microsoft's counter for Chocolatey. Microsoft understood that Microsoft Store is garbage and Chocolatey is more and more downloaded on people's PCs and they finally made a good choice, coping Chocolatey, and agreeing that Linux like package management is better than some GUI program. Surprisingly, this is open source.

So on Windows, you need to choose from either Chocolatey or winget. I would go on Chocolatey because it's more stable and made for production. winget is much newer, and it was not tested in production environments.

## Linux:
- The app stores are just some GUI to your package manager or something like Snaps or Flatpaks, so I will talk about them.
- The package manager that comes with your distro. In most cases, it's the best to choice, even if it is `dpkg`, `rpm`, `pacman`, it doesn't matter. Only if you don't find a piece of software, you should go with something else.
These should work on every 'normal distro'(they have issues on Nix OS and GNU Guix).
- [Snaps](https://snapcraft.io/) are from Canonical, the corporation behind Ubuntu. Canonical claims that 'snaps' are sandboxed, but in reality, only a small part is. If some piece of software is installed using the '--classic' flag, it is not sandboxed. This happens to a lot of software, including VS Code. Snap client is open source, while the server is not.
- [Flatpaks](https://www.flatpak.org/) are from 'community', being supported by Red Hat. They claim like snaps to be 'secure', but they fail. Check [this](https://flatkill.org/2020/) for more information about this topic. This is the typical fight between Canonical and Red Hat. These are entirely open source.

AppImages aren't package managers. They are good when either you want to install a browser without his big number of dependencies, or a software that it's available only in this form. If you use Arch, just use AUR, people claim AUR to be unsafe, but the others aren't as well.

## MacOS:
- [App Store](https://www.apple.com/app-store/) is the default App Store. Many macOS users from `/g/` say that it's the best app store out there, while is the same as Windows Store, maybe with more apps. `Nice for privacy like any other Apple product`.
- [Homebrew](https://brew.sh/) is a community driven package manager. Probably all the guys saying how good is App Store are using Homebrew, but they will not admit it. Homebrew takes the philosophy of Linux package manager and brings it to macOS. Hard to admit I know. It doesn't come with spyware, like App Store.

I never used MacOS, I'm writing this thing like a guy using 4chan who hears all the Apple propaganda getting lost in saying why Apple products are better than the others. If you are a macOS nerd, let me know what you don't agree with.

## Android
Even if people complain about Android, being insecure and the monopoly of Google, the project itself is open source and also there are some app stores that fight with Play Store.
- https://tresorit.com/[Play Store](https://play.google.com/store/) is the default one that comes with OEM versions of Android. It's made by Google, needs a Google account, comes with spyware. It can't be uninstalled, but at least you can disable it. Play Store has a lot of software and most of the time you need a program from here.
- [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore) is an OSS alternative to Play Store. It can download software from Play Store without the usage of Play Service or even microG. It requires an anonymous account, but if you want to download purchased apps, you can use your own Google account. It features Exodus to see what trackers do an app uses. Also, Aurora can be installed on F-Droid.
- [F-Droid](https://f-droid.org/en/) is the real FOSS app store. It only includes FOSS. It allows app to use proprietary APIs, but they're source code should be open source. F-Droid is a good place to find FOSS alternatives. 

I'm using F-Droid as my main app store. I don't use Play Store apps at all, even with Aurora. There are open source alternatives to almost any software. 

# Cloud platforms
- [Google Drive](https://www.google.com/drive/) is owned by Google. It has 15 GB free storage, support for folders, sort by time. It allows users to upload as many pictures as they want for free(I know what you will say). It also comes with the typical spyware from Google.
- [Dropbox](https://www.dropbox.com/?_hp=c) is a free services that gives 2 GB of storage. It has basically no benefits over Google Drive. Dropbox had a lot of problems with privacy. Check [this](https://arstechnica.com/information-technology/2016/08/dropbox-hackers-stole-email-addresses-hashed-passwords-68m-accounts/) or [this](https://www.zdnet.com/article/dropbox-bug-kept-users-deleted-files-on-its-servers-for-six-years/).
- [OneDrive](https://onedrive.live.com) is Microsoft's cloud service. It comes with the Outlook account. It gives 500 MB of space, and comes integrated with Windows 10. The client for Windows 10 is laggy, it gave some headaches to Windows users. My friend can't get screenshots working because Windows defaults the screenshots to OneDrive, and not the Photos folder from the user's home folder. It comes with the same privacy issues as every Microsoft product. If you don't care about privacy, it's a good choice, probably worse than Google Drive.
- [Nextcloud](https://nextcloud.com/) is a self-hosted cloud platform. It is entirely open source. It became more than just a cloud service, but also a calendar, mail, calling providers. NextCloud doesn't provide fully end-to-end encryption. They say that it's 'under constant development'/. You can host it using a VPS, or on a local machine, like an old laptop, depending on the budget, but you can also use an free online provider. I've seen a VPS providing 8 GB free storage. 
- [Sync](https://www.sync.com/) is a proprietary cloud service. It is not open source, but I heard that it is more secure than the other proprietary cloud services. It gives 5 GB free storage, and provides 'end-to-end' encryption.
- [Tresorit](https://tresorit.com/) is another proprietary cloud service. It shares many similarities with Sync. It is based in Swiss, claims to be 'end-to-end encrypted', and provides collaboration tools.

I tried all of these beside Tresorit. Google Drive, Dropbox and OneDrive are mainstream so everyone knows how these work. NextCloud is intersting. I tried it using a free online provider, and it seems OK. I could like some folders with the cloud ones. Also, I used it on my phone and PC. On phone, the app looked like the other apps. On Windows, I had some problems. It displays the notifications regularly, sometimes it is crappy. On Linux, it was a little better than Windows, because I don't have notifications. I will probably end up setting a Nextcloud server on my old laptop running /g/entoo. Sync was interesting and tried it as well. It also has these features, but I found it very slow when uploading and downloading files. I waited 3 minutes to download a 80 MB file.

# Browsers
When it comes to browsers, it depends on what people like. There are only two real competitors, the Chromium based browsers and the Gecko based browsers. 

## Chromium based browsers 
- [Google Chrome](https://www.google.com/chrome/) is the flagship browser based on Chromium(it doesn't mean that it's the best). Google made Chromium for Chrome. It comes with the ability to sync your Google account, use Google Translate by default. 
- [Chromium](https://www.chromium.org/) is a browser that it's just Chrome without Google licenses and spyware. It is the open-source build of Google Chrome and it is very common in Linux package managers. In 2021, it lost the ability to sync the Google account with it, so if you want to continue using Google account to store passwords, bookmarks etc. you need to use Google Chrome, otherwise you can use it. 
- [Ungoogled-Chromium](https://github.com/Eloston/ungoogled-chromium) is a build of Chromium that comes without any Google service. Chromium and Ungoogled-chromium are now almost the same thing. It's built using some scripts, you can build it on your own.
- [Microsoft Edge](https://www.microsoft.com/en-us/edge) is a Chromium based browser offered by Microsoft. Microsoft dropped its own engine for Chromium in 2020. The differences about Edge and the others is that it uses a Microsoft account, and it has a different look. It comes preinstalled on Windows 10 and can't be uninstalled. If you really want to, you can install it on Linux, as they provide a binary.
- [Opera](https://www.opera.com/) is another proprietary browser. It dropped its own Presto engine for Chromium like the others. It provides a 'gaming' version. Now it's owned by a Chinese company, and people claim it to be packaged with Chinese spyware.
- [Vivaldi](https://vivaldi.com/) is a proprietary browser. Its advantage is its specific look. People say often that it's the most beautiful and functional browser. Some people say that it's the most secure browser from the proprietary category.
- [Brave](https://brave.com/) is probably the most controversial browser. Even if it is open source, it had some problems with privacy. [It was caught adding affiate links to crypto sites](https://www.cpomagazine.com/data-privacy/brave-privacy-browser-caught-automatically-adding-affiliate-links-to-cryptocurrency-urls/). Its difference is Brave Rewards, an add based reward system. It gives you BAT(Brave's specific currency) in order to check their ads. They say that the ads are random, and they're not based on the customer.
- [Dissenter](https://dissenter.com/download) is a Brave's fork. It builds removing things that connect to the Brave servers like Brave Rewards, cards etc. It's owned by Gab, but it's open source. Dissenter appeared after Dissenter extension, an extension that connects you to the Gab network was removed from both Chrome and Firefox extension stores. 

## Gecko based browsers 
- [Firefox](https://www.mozilla.org/en-US/firefox/) is the flagship of Gecko based browsers. It's made by Mozilla, but it's open source. It is the least browser to compete to Chromium based browsers. Even in this case, [Mozilla collects a lot of data from their users](https://www.privateinternetaccess.com/blog/the-firefox-browser-is-a-privacy-nightmare-on-desktop-and-mobile/).
- [LibreWolf](https://librewolf-community.gitlab.io/) is a fork of Firefox that removes all the Mozilla telemetry. It comes with uBlock Origin preinstalled(not a big deal) and updates as often as Mozilla. At the time of writing, it is limited to some Linux distros and not even on Windows. 
- [Waterfox](https://www.waterfox.net/) is another Firefox fork, but it's not like LibreWolf, as it is very different from Firefox. It was forked a long time ago and there is a legacy version that supports old plugins.
- [GNU Icecat](https://www.gnu.org/software/gnuzilla/) is the FSF approved browser. It's one of the best privacy browsers because it includes only LibreJS, so third parties can't run unfree scripts. It also comes with some extensions by default. They also have their own plugin collection.

From all of these, I chose both ungoogled-chromium and LibreWolf. I use ungoogled-chromium when I need to go to unfree sites(Google Classroom, Microsoft Teams) and LibreWolf in my free time. The best privacy browser is either Icecat or Hardened LibreWolf with extensions like HTTPS Everywhere. 

# Operating systems
# For PCs
Now comes the autistic part. Everyone knows how cool are /g/entoo and arch btw users. I can say that I'm both. 
- [Windows 10](https://www.microsoft.com/en-us/windows) is the operating system for over 60% of the PC users. It's closed source, costs money(you can get a cheap license for 2-3$ on eBay). If you want to be a truly gamer, you should go with Windows, either as your boot option, or as a VM. If you want to use it on bare metal, use [Ameliorated](https://ameliorated.info/) script to remove all Microsoft spyware. Be aware to not update your system because the bloat will appear again.
- [Linux](https://www.kernel.org/) is not itself an operating system. It's a kernel. In fact, it's GNU/Linux. Joke. There is Alpine Linux that doesn't use any GNU software at all. Beside the jokes, most distros are basically the same thing, beside the package manager and/or the init system. 
## Distros
I will not talk about every distro. Just to know that 60-70% of Linux users are using [Ubuntu](https://ubuntu.com/). Every Linux user might have used Ubuntu or Ubuntu based distros as some point. Ubuntu comes with snaps by default, Amazon ads also. Not the best privacy distro. Better go with [Linux Mint](https://linuxmint.com/) or [PopOS](https://pop.system76.com/). If you wanna look cool on the internet, go with [Arch](https://archlinux.org/) or [Gentoo](https://www.gentoo.org/). People claim that you will spend more time customizing them than using them. But they come with some nice features. They are rolling release, so you will have the newest software available. This can be good for gamers. If you wanna have even a weirder distro, go with [Nix OS](https://nixos.org/). If you want to use a FSF distro, check [this](https://www.gnu.org/distros/free-distros.html). Or just go with the good old [Debian](https://www.debian.org/). It's the one that 'just werks' on every single piece of software available. 
- [macOS](https://www.apple.com/macos/) is basically what you get if you buy an Apple product. It is based on NeXTSTEP, which is based on Mach kernel. It uses some BSD parts.You can't legally to run macOS on other than the Apple hardware, but it's possible using some additional tools. Some might say that it's the best OS, but I don't know. Personally, I don't like its look. If you really want that look, just copy some dotfiles from [r/unixporn](https://reddit.com/r/unixporn/) and install KDE. You will end up with a system where every software is not just another Apple spyware.
- [BSD](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution) itself hasn't being maintained for over 25 years. But there are some distros based on it, [FreeBSD](https://www.freebsd.org/), [OpenBSD](https://www.openbsd.org/), [NetBSD](https://en.wikipedia.org/wiki/NetBSD), [DragonFly BSD](https://en.wikipedia.org/wiki/DragonFly_BSD). Beside these, there is [HardenedBSD](https://www.hardenedbsd.org/) which is a more secure fork of FreeBSD. People will probably call you a memer if you use these, but there are some people using it unironically.

# For phones

- [Android](https://www.android.com/) isn't harmful. It's made by Google, but it's open source. The problem is that every OEM is pushing more and more bloat and spyware in their Android build. 
- [LineageOS](https://lineageos.org/) is a fork of Android that brings security and removes the spyware that OEMs gave to their users. The problem is that it's limited to only a few phone models. Also, you can use [microG](https://microg.org/) instead of OpenGapps. If you want to use microG, install the ISO that microG provides you.
- [GrapheneOS](https://grapheneos.org/) is another fork of Android, but it's different from LineageOS. GrapheneOS only can be installed on Pixel phones(ironically enough). Graphene doesn't need something like Google Play Services or microG at all. It implemented a more secure selinux policy and made some improvements to the OS security.
- [iOS](https://www.apple.com/ios/) is Apple's proprietary operating system. It comes with iPhones and iPads. Even if you want to change your OS on iPhones or iPads you can't. It's possible, but it's very hard. If you are interested, check [this](https://fossbytes.com/linux-based-mobile-postmarketos-on-iphone-7/).

Installing another OS in an Android device isn't the easiest process. It's harder than installing Arch or Gentoo on a PC. If you have phones from some vendors like Huawei, you can't even unlock your bootloader. Ironicaly, Pixel, Xiaomi and OnePlus phones are the best for privacy, and not because their default OS is secure(it's entirely spyware), but because it's easy to unlock the bootloader.

# Map services 

- [Google Maps](https://www.google.com/maps) is the most known Maps service. It's kinda up-to-date and also lets users add locations. It is from Google, so you know.
- [Bing Maps](https://www.bing.com/maps) is from Microsoft. They are outdated and miss a lot of points.
- [OpenStreetMap](https://www.openstreetmap.org/) is the Wikipedia of maps. OpenStreetMap is a collaborative project available under an open source license. It can be used by anyone without any problems. OpenStreetMap is used by even some big companies like Facebook and Apple. Probably the best secure option. This might be the first software to beat a proprietary one.

Just use OpenStreetMap. They are a lot of applications that involve their API. You can download the maps for offline use.

# Office suits

- [Microsoft Office](https://www.office.com/) is Microsoft's very own office suit. It's the most used office suit. Microsoft implemented their proprietary extensions '.doc(x),.xls(x) etc.'. The other software suits needed to reverse engineer them because Microsoft didn't document them well, even if they are the most used extensions. Microsoft is selling a cloud based office service called Office 365. Not the best for privacy
- [Google Docs](https://docs.google.com/) is a word processor based on the internet. It is used for collaborative work inside the cloud. It's free for individuals, but it costs money for enterprises. It accepts almost every extension.
- [LibreOffice](https://www.libreoffice.org/) is the successor to [OpenOffice.org](OpenOffice.org). It's a FOSS project that has become de facto the office suite on Linux. It's sponsored by Collabora Office, which it's a cloud based office depending on LibreOffice. Some people remained with OpenOffice, even if it wasn't updated in a while, because the biggest sponsor of LibreOffice is Red Hat. LibreOffice also became very powerful in the last years, and it's a true competitor to Microsoft Office. It supports macros like it and also extensions.
- [OnlyOffice](https://www.onlyoffice.com/) is another open source suite. It's based on 3 servers, one for document server, one community, and for mails. OnlyOffice looks very similar to Microsoft Office. It offers also mobile applications for iOS and Android.

# Code hosting

- [GitHub](https://github.com/) is the biggest code hosting platform. It was bought by Microsoft, and includes trackers. Their API needs an account. It is fully proprietary, but somehow it's made for open source software. Microsoft turned it into a marketplace for enterprises.
- [GitLab](https://gitlab.com/) is also a big code hosting platform. It is open source, but it's not the most secure place. It's secure if you choose to self-host your product. Also needs an account to do almost anything. 
- [Gittea](https://gitea.io/en-us/) is another open source project. It is a community based project written in GO. However, you need an account for it. You can use your GitHub account if you have one.
- [SourceHut](https://sourcehut.org/) is a new open source project. Now, it's running through donations, but they say that it will require payment later. It doesn't need an account to open an issue, because these are sent through emails.

# Final words

These were my thoughts about software in general. I haven't treated only the privacy aspect, because in some cases the 'private' software is unstable. The fact is, you need at some point to use software that contains trackers. You can't do much about it, it happens. With this Covid-19 crises, every enterprise chose some proprietary garbage like Zoom, when they could just use Jitsi Meet. 

Anyway this is a huge markdown file, if you find some typing issues or some spelling mistakes start an issue, or make a pull request. I checked the typing through [LanguageTool](https://languagetool.org/), an open source project funded by the European Union, a very good competitor to Grammarly. 

If you want to find more software, you can check:
- [Opensource](https://opensource.com/) - I know it's funded by Red Hat, but sometimes the articles are good
- [r/privacytoolsIO](https://www.reddit.com/r/privacytoolsIO/) or [their website](https://www.privacytools.io/) 
- [r/degoogle](https://www.reddit.com/r/degoogle/)
- [r/privacy](https://www.reddit.com/r/privacy/)
- [r/technology](https://www.reddit.com/r/technology/)
- [/g/](https://boards.4channel.org/g/)
