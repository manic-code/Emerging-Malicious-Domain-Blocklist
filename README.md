![GitHub last commit](https://img.shields.io/github/last-commit/manic-code/Emerging-Malicious-Domain-Blocklist?style=for-the-badge) ![Github stars](https://img.shields.io/github/stars/manic-code/Emerging-Malicious-Domain-Blocklist?style=for-the-badge) ![Github filesize](https://img.shields.io/github/size/manic-code/Emerging-Malicious-Domain-Blocklist/hosts.txt?color=purple&style=for-the-badge) ![Github issues](https://img.shields.io/github/issues-raw/manic-code/Emerging-Malicious-Domain-Blocklist?color=maroon&style=for-the-badge)

# Info & Sources

> Here is the raw URL for the list, add this to your Pi-Hole or other DNS filtering tool. 
> https://raw.githubusercontent.com/manic-code/Emerging-Malicious-Domain-Blocklist/main/hosts.txt

This blocklist is intended to supplement existing/larger blocklist sources. The list provides the most coverage against free movie streaming site pop-ups, social media phishing links, newly registered domains intending to impersonate consumer brands, and various other untrustworthy domains. All additions to this blocklist are vetted to avoid including a false positive. While not intended to be used for anti-tracking purposes such domains may be included if they do not break any legitimate services when blocked.

All domains are sourced primarily from my personal blocklist. This is supplemented with various sources on Alienvault's OTX threat exchange site with a heavy emphasis on newly registered phising and malicious links. Sites actively spreading malware are my primary target.
> I make a strong effort to include phishing campaigns that are targeting users all over the world however as I'm limited by my sources this means currently coverage is limited to European & North American users. Hope to expand this soon. 


# Additional Notes
This list is one of many upstream sources for [Hagezi's Blocklist](https://github.com/hagezi/dns-blocklists), if you currently use the **PRO**, **PRO++**, or **Ultimate** version of Hagezi's list there's no additional benefit to adding this list as you are already protected by this source.

# Suggestions or Issues?
All submissions are welcome in the issues section, please ensure it does not break any legitimate services before submission. Newly registered domains that appear highly suspicious and have little history on VirusTotal.com are also eligible to be included in this list. 
> Please verify that new URL submissions do not already exist on [Hagezi's blocklist](https://github.com/hagezi/dns-blocklists). You can use [this website to search multiple blocklists for matches.](https://dnswarden.com/search.html) 
