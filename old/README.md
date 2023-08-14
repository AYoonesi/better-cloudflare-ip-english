# better-cloudflare-ip

Find the best choice for your current network environment Cloudflare Anycast IP

The old version will be out of service soon, and subsequent versions will not be updated if there are no obvious bugs!

This is final forked version and I fixed known bugs mostly in windows bat file after translation, I will no further update this fork version, if you find any issues you can always open an issue or make your own fork

## ToS

This project focuses on the study of the relationship between packet loss rate and network speed in anycast technology, for learning purposes only

This is an English fork of main code, most of English users do not need such thing but cesorship is global problem and English is our main way to conduct a basic communication, I translated readme file alonge side main code to English, following post are translated from main read me file.
Rules are respected however most of these terms may only apply to Chinese users, please read before proceed using this tool.

The prohibited scope guidelines are as follows

a) Relevant agencies warn that the web pages are threatening, and websites with illegal information prompts.

b )Hospital-type websites (hospitals for abortion, skin diseases, venereal diseases, etc.), websites that have not obtained the qualification of the Ministry of Health.

c) The main content of the website contains pornography (video dating, one-night stand dating), illegality (documentation of fake certificates, sale of imitation guns), feudal superstition, private game servers, game cheats, online earning, gender, beauty stickers and animation stickers (too large), gambling (Including the sale of gambling tools.), gambling and other content.

d) There are malicious rogue advertisements on the website (there are links to illegal content videos, illegal web content links).

e) The website has any acts of destroying or attempting to destroy network security, such as viruses, Trojan horses, malicious codes, phishing, etc., attempting to maliciously scan the website, network-related software and hardware, illegally intrude into the system, and obtain data illegally.

f) Websites whose content has copyright risks (video, novel, music, etc. websites).

g) The website contains sales of medicines and health care products, but has not obtained qualifications, or seriously exaggerates the facts of the efficacy of medicines.

h) The main business of the website is to provide illegal websites with services such as payment, trading platforms, guarantees, and acting as an agent for foreign financial management (stock trading, spot trading, and gold speculation).

i) There are a large number of websites with content that affects social harmony and stability (suspected of attacking the country, attacking leaders, attacking the people, websites with inflammatory speech).

j) The content of the website contains other content that is not permitted by relevant national laws and regulations.

k) The content of the website contains VPN, network proxy and other content.

l) Websites that interfere with the normal operation of all Cloudflare products through technical or non-technical means.

m) The content of the website is a website that publishes false and untrue news, or violates the legitimate rights and interests of others.

n) Obtaining the content of the website requires login and other methods, and it is impossible to directly view the website that causes the content to be unaudited.

o) Websites that provide download services for movies, software, and applications.


## User Data Security Statement

This version does not require users to upload any data to the server, the server only provides IP address pool maintenance and distribution!

## user defined data

Users can customize the IP address segment of ips-v4.txt and ips-v6.txt, if you try using data update, it will overwrite the local custom data

The content format of the custom ips-v4.txt is x.x.x.x or x.x.x.x/x CIDR notation, which is extracted by default. The first three digits

The content format of the custom ips-v6.txt is x:x:x:x:x:x:x:x or x:x:x:x:x:x:x:x/x, which is extracted by default : the first three digits

More custom gameplay is waiting for users to discover by themselves

## Windows batch version

Translated:
Please download the Release version to use, do not use Git Clone to download (garbled characters will appear)
Windows 7 users recommend using the ANSI encoded version
Users of Windows 8 and above versions are recommended to use the UTF-8 encoded version
Note: The ANSI encoding version can be used on all Windows platforms, and the BUG of some Windows systems will cause the console to output garbled characters

In this translated version these problems are gone, so there are no difference between UTF-8 and ANSI here.
Click to download [Windows version] (https://github.com/hoseinnikkhah/better-cloudflare-ip-english/releases/download/v1.0.0/Windows.zip)

## Linux version

Completely copy and paste the link below to the console and press Enter. For subsequent operations, just enter ./cf.sh and press Enter.

Currently tested Termux, OpenWrt, Ubuntu, Debian, CentOS, MacOS, Raspbian, Armbian, iSH

``` bash
curl https://raw.githubusercontent.com/hoseinnikkhah/better-cloudflare-ip-english/master/shell/cf.sh -o cf.sh && chmod +x cf.sh && ./cf.sh
```

## quote statement

For Cloudflare ASN https://bgp.he.net/AS13335 , Cloudflare IP Ranges from https://www.cloudflare.com/zh-cn/ips/
