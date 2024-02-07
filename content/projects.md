+++
date = 2024-02-05T13:50:45-05:00
draft = false
+++

# Here's What I've Been Working On...
- **Generative AI & Prompt Engineering** -- It is 2024, after all, and my parents have questions.
- **Kubernetes** -- While I have been successfully managing my own containers with a self-hosted instance of **Portainer**, I recognize the importance of a more robust managaement platform like K8s, especially for enterprise-level projects.
- [**Automation & Scripting, Python, Github Actions**](https://imgs.xkcd.com/comics/automation.png).
- **Linux** -- I've been regularly using Linux for a few years now but I quickly learned there is *always* so much more to learn. I'm currently working with the Ubuntu-based Mint 21.2 Xfce on my desktop and the Debian-based Raspberry Pi OS (fka Raspbian) on a headless Pi.
- **Free & Open Source Software**
- **Decentralizing the Internet, The ActivityPub Protocol**
- **Building a Personal Knowledge Base** -- My entire note-taking process has changed since I started using Obsidian, an endlessly extendable markdown-based notes app built on Electron. I've just begun work on developing my own plugins.
- **Networking** -- Because the WiFi is never perfect.
- **A freshwater planted aquarium** -- Because it can't all be tech.


## Home Server / Homelab
{{< figure src="/images/portainer.png" alt="Screenshot of my Portainer dashboard" width="auto" >}}

In late 2022 I started moving away from proprietary cloud software and relying more on my own infrastructure. Things started simply enough: a headless Raspberry Pi with an external harddrive connected to my router. I used Tasker to setup automation on my and my wife's phones so that every night all of the photos we had taken that day (having twin toddlers means there are a *lot* of photos) are backed up to the harddrive and made available to browse and view instantly via a media server we can access from any of our devices.

Since then the server has expanded as I have learned about **containerization** with **Docker**, **MariaDB** databases, **CalDAV** & **CardDAV** servers, **OPDS** protocol, **VPN tunnels**, **DNS record management**, **network monitoring**, and more.

I've been rethinking my backup strategy and I've outgrown the Raspberry Pi, so I'm currently in the process of building a compact DIY NAS based around an inexpensive Jasper Lake motherboard which will be operating TrueNAS Scale with RAID 5 parity. I'll then be converting the Raspberry Pi into a dedicated DNS server and ad-blocker with future plans of integrating a pfSense box into the setup.
## FOSSified Android
There's a stable alternative for *almost* everything, right? I've really gone down the rabbit hole and what started as flashing a custom ROM to try a new OS has turned into seeing if I can only use free & open source software without driving myself insane! It's a much more hands-on experience and I've been learning a lot about the architecture of Android. You can read more about this project at my [Dev.to page](https://dev.to/jsspen) where I have been blogging the journey and its various ups and downs.
## Local IoT
{{< figure src="/images/homeassistant-dash.png" alt="Screenshot of my HomeAssistant dashboard" width="auto" >}}
The Internet of Things is fun and exciting but there are obviously a lot of security concerns, so I've setup a dedicated Raspberry Pi running HomeAssistant OS to keep it all in-house. Using various helpers, scripts, and custom integrations I've been able to connect a variety of different devices, from cheapo WiFi bulbs to proprietary devices using Zigbee and Z-Wave radio signals, and control it all from a single local hub.

The next part of this project is a more thoughtful UI design and expanding my energy monitoring.

## (Art) Writing
- [Leomi Sadler's Tummy Bugs](https://solrad.co/im-very-inspired-by-the-bland-ambiance-of-generic-surrealism-leomi-sadlers-tummy-bugs) in *Solrad*, June 2021, Web
- [Son Ni’s The Well-Tempered Us](https://brooklynrail.org/2020/12/art_books/Son-Nis-The-Well-Tempered-Us) in *The Brooklyn Rail* Dec 20/Jan 21 Issue, Print/Web
- [Woman-About-Town: Newark's Own Ema Spencer](https://www.columbusmuseum.org/blog/2020/09/10/woman-about-town-newarks-own-ema-spencer/) in *No Mere Button-Pressers: Clarence H. White, Ema Spencer, and The Newark Camera Club*, September 2020, Print/Web (no relation)
- [Jim Hodges and the Holy Infinite](https://theseenjournal.org/jim-hodges-and-the-holy-infinite/) in *The Seen: Chicago's International Journal of Contemporary & Modern Art*, May 2020, Web

