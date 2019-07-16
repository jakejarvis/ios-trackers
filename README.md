# iOS Tracker Blocklist

My personal blocklist of iOS tracking, telemetry, and advertising domains.

Made for use with [Disconnect Pro for iOS](https://disconnect.me/) ([App Store](https://itunes.apple.com/us/app/disconnect-privacy-pro-entire/id1057771839?ls=1&mt=8)), which I highly recommend. It's worth noting that this particular app automatically blocks all subdomains under each domain, unlike a typical `hosts` file. If using another app, prepending wildcards may be required.

[Disconnect Pro](https://itunes.apple.com/us/app/disconnect-privacy-pro-entire/id1057771839?ls=1&mt=8) also comes preloaded with [Disconnect.me's great blocklist](https://github.com/disconnectme/disconnect-tracking-protection). The list in this repository is meant to supplement that list.


---

**Update as of July 2019:**

For my personal use I have switched to [AdGuard Pro](https://adguard.com/en/adguard-ios-pro/overview.html) on iOS, which allows for more flexibility and doesn't have a few of the bugs that Disconnect Pro has (which I've reached out to the developers about in the meantime). AdGuard Pro allows for custom "subscription lists" that can be pulled and updated automatically, so I've included `adguard.txt` which is compliant with its [syntax rules](https://kb.adguard.com/en/general/how-to-create-your-own-ad-filters). You can add the following raw text URL in AdGuard's settings under subscriptions:

https://raw.githubusercontent.com/jakejarvis/ios-trackers/master/adguard.txt

Other subscriptions I use:

https://raw.githubusercontent.com/jakejarvis/ios-trackers/master/adguard-disconnect-malvertising.txt

https://raw.githubusercontent.com/jakejarvis/ios-trackers/master/adguard-disconnect-ad.txt

https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers.txt

https://raw.githubusercontent.com/AdguardTeam/AdguardFilters/master/SpywareFilter/sections/tracking_servers_firstparty.txt

https://github.com/AdguardTeam/AdguardFilters/blob/master/MobileFilter/sections/spyware.txt

https://github.com/AdguardTeam/AdguardFilters/blob/master/MobileFilter/sections/adservers.txt
