![GitHub last commit](https://img.shields.io/github/last-commit/manic-code/Emerging-Malicious-Domain-Blocklist?style=for-the-badge) ![Github stars](https://img.shields.io/github/stars/manic-code/Emerging-Malicious-Domain-Blocklist?style=for-the-badge) ![Github filesize](https://img.shields.io/github/size/manic-code/Emerging-Malicious-Domain-Blocklist/hosts.txt?color=purple&style=for-the-badge) ![Github issues](https://img.shields.io/github/issues-raw/manic-code/Emerging-Malicious-Domain-Blocklist?color=maroon&style=for-the-badge)

# Info & Sources

> Here is the raw URL for the list, add this to your Pi-Hole or other DNS filtering tool. 
> https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt

This blocklist is intended to supplement existing/larger blocklist sources. The list provides the most coverage against free movie streaming site pop-ups, social media phishing links, newly registered domains intending to impersonate consumer brands, and various other untrustworthy websites. All additions to this blocklist are vetted to avoid including a false positive. While not intended to be used for anti-tracking purposes such domains may be included if they do not break any legitimate services when blocked.

All domains are sourced primarily from my personal blocklist. This is supplemented with various sources from Alienvault's open threat exchange site with a heavy emphasis on newly registered phishing and malicious links. Care is taken to select sources that are not being used in other blocklist projects. Sites actively spreading malware are a priority target and I make a strong effort to include phishing campaigns from all regions of the world so everyone is protected.
> The domain list is pruned of dead domains at times, all removed listings are maintained on a separate file and monitored for new signs of life so they can be re-added o the main blocklist. 

# Additional Notes
This list is one of many upstream sources for [Hagezi's Blocklist](https://github.com/hagezi/dns-blocklists), if you currently use any of the **"Multi"** lists which range from **Light** to **Ultimate** then there's no need to add this blocklist as you are already protected by this source.

# Suggestions or Issues?
All submissions are welcome in the issues section, please ensure it does not break any legitimate services before submission. Newly registered domains that appear highly suspicious and have little history on VirusTotal.com are also eligible to be included in this list. 
> Please verify that new URL submissions do not already exist on [Hagezi's blocklist](https://github.com/hagezi/dns-blocklists). You can use [this website to search multiple blocklists for matches.](https://dnswarden.com/search.html) 
