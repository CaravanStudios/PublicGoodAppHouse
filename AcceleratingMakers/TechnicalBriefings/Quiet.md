_Technical Briefing_

# Secure Communications in the Age of Authoritarianism and Surveillance Capitalism

### An Overview of the Quiet Software Project, a Private and Distributed Peer-to-Peer Communication Application


## Summary

Over the last 15 years, we have seen a dramatic increase in democratic backslides worldwide, coupled with the strengthening of existing authoritarian regimes and new nationalist movements. Additionally, core, daily, common use technological solutions have been centralized in the hands of large corporations whose business model revolves around the harvesting and selling of their clients' data. 

These two seemingly unrelated, overarching global trends have combined to create two overwhelming problems:

* The loss of the ability to communicate privately
* The loss of the ability for individuals or small groups to organize themselves in the face of nationalist and authoritarian governments that are aided by their access to the massive troves of personal data collected by technology companies


## Details

In her essay “Surveillance Capitalism and the Challenge of Collective Action,”<sup>1</sup> Harvard Professor Emerita Shoshana Zuboff laid out a comprehensive narrative of the rise and breathtaking reach of corporate surveillance capitalism. Similarly, Marie Lamensch’s “Authoritarianism Has Been Reinvented for the Digital Age”<sup>2</sup> and Federico Mantellassi’s “Digital Authoritarianism: How Digital Technologies Can Empower Authoritarianism and Weaken Democracy,”<sup>3</sup> both detail how emerging technologies enable authoritarian practices in ways both subtle and unsubtle. The three articles lay out a highly compelling argument against both corporate and governmental control of technology.

While the causes are open to academic debate,<sup>4</sup> it is widely recognized that there has been a 15-plus-year period of democratic recession, also known as democratic backsliding. With the strengthening of existing authoritarian regimes,<sup>5</sup> such as Russia, Belarus, and China, the ability of pro-democracy advocacy groups and everyday citizens to safely communicate becomes crucial. Without it, even the most basic voicing of dissent becomes an easily discoverable and punishable event. In Russia, for example, a college student was given 10 days of jail time<sup>6</sup> for naming their router with a pro-Ukraine phrase. In China, the government’s pervasive control of technology and infrastructure allows it to surveil the Uyghur population to such an extent that it can detail who took part in religious fasting and who rode in whose car to religious ceremonies.<sup>7</sup> 

These issues are not limited to authoritarian regimes. In the United States, it is illegal for the government to collect citizen data wholesale. What happens instead is that the government pays for it, purchasing citizen data from private corporations,<sup>8</sup> many of which are completely unknown to anyone outside of law enforcement agencies. This practice is both highly invasive and pervasive. It has gone largely unchecked because of its high degree of secrecy. At the root, however, is that it would not be possible without the ubiquitous corporate adoption of surveillance capitalism.

In the face of that reality, the ability for populations to communicate free of government surveillance and corporate data collection becomes an absolute necessity.

For decades, there has been a wide variety of mass communication solutions available to the public. The twin inventions of the cellular phone and the internet, in particular, have been hugely impactful. Cellular phones have brought inexpensive call plans, text messaging, and mobile data. The internet has introduced populations to email, instant messaging, and video calls. Core to all of these capabilities is that they are all typically dependent on a central server or service. These central hubs are required for the storing of data, identifying who that data is intended for, and archiving it for future viewing. While there are many existing technologies available for private communications and small group communications, they all fall under this umbrella of central server reliance.

Below is a small sampling of the existing solutions available to general populations worldwide.


### X (Formerly Known as Twitter)

Historically, Twitter was known as a platform that enabled people to easily disseminate information to the wider public, communicate privately with others, and see information made public by others. It has had a sizable number of security issues over the years. Since its purchase by Elon Musk and transformation into X, Twitter has lost 80 percent of its staff, including 550 engineers, through firings or proactive departures. Twitter has also embraced some of Musk’s personal tendencies, reinstating Donald Trump and other right-wing individuals to the platform. It is not a distributed application and therefore relies on centralized servers. This centralization has made it difficult and in some cases impossible for journalists and independent observers to audit Twitter’s moderation decisions. 


### Meta (Facebook/Instagram/WhatsApp)

Starting in early 2020, Facebook started enabling end-to-end encryption (E2EE) on Messenger as an option users could select in their direct and group messages. On December 6, 2023, Facebook made E2EE the default communication method for Messenger, so that all messages sent through that platform are encrypted via a private key shared only by the devices taking part in the conversation. Facebook itself does not have access to this key and thus cannot decrypt the messages or comply with governmental agency requests to do so. Instagram, which is also owned by Meta, has E2EE available for it’s messaging but it is not enabled by default. WhatsApp, which was purchased by Meta in early 2014, has been fully E2EE since 2016. 


### Signal

Released in 2014 by Open Whisper Systems on iOS, Signal is an open-source project founded by Moxie Marlinspike. In its current iteration, Signal is an encrypted messaging service for instant messaging, voice, and video calls that uses a centralized server system. Signal uses E2EE for all message encryption with its own custom protocol, which has also been incorporated into WhatsApp, Facebook Messenger, and Skype. Messages sent via Signal are routed through, but not stored on, Signal servers. Additionally, all information regarding a user is also encrypted. This means that Signal itself does not store, or at any time have access to, an end user’s profile name, contact list, groups, or other data.

While Signal servers have been hardened against government surveillance or overreach, it could be argued that since Signal still relies on these servers for message routing and delivery, the Signal organization has the ability to see who is talking to whom, an inherent technical weakness that is easily addressed by a distributed web project such as Quiet.


### Cellular Phone Calls, Mobile Data, Phone Text Messages

Cellphone calls, data, and text messages are easily surveilled by governments and corporations (cellphone carriers) within carrier infrastructure. Governments and private individuals using cell site simulators, for example the Stingray system widely used by law enforcement,<sup>10</sup> can also initiate cellphone signal interception and collection. Cellphones are quite possibly the most insecure communications channel.


## Solution

Advancement into distributed web (DWeb) technologies has opened pathways to different approaches for technology architecture and design that do not rely on an individual or group of centralized services. Distributed systems have been in existence for some time, but their application to modern applications combined with new technologies<sup>11</sup> has given them a new outlet. Among the new use cases for DWeb applications is secure, peer-to-peer or group communication channels. One such application is Quiet.<sup>12</sup> 

Quiet is an open-source, distributed communications application that requires no central server at any point for any of its core functionality (except push notifications on iOS, due to nontechnical constraints imposed by Apple). Rather, it establishes direct connections between individual clients on a variety of devices, which makes it immune from the central source of vulnerability: a common server that is used to store credentials, identity information, messages, and more. 

Quiet’s current, prerelease functionality includes

* **Team Chat:** Create a "community" for your team or organization and invite members.
* **End-to-End Encryption**: All data is encrypted end-to-end between member devices.
* **Channels**: Organize chats in Slack-like channels.
* **Images**: Send and receive images, with copy/paste, drag-and-drop, and image previews.
* **Files**: Send and receive giant files without arbitrary limits.
* **Notifications**: Get desktop notifications for new messages, with optional sounds.
* **Invite Links**: Share invite links, just as in WhatsApp, Signal, or Discord.
* **Keyboard Controls**: Navigate channels without using the mouse.
* **Desktop Apps**: Desktop apps for Mac, Windows, and Linux.
* **Android App**: A fully peer-to-peer Android app with working notifications.
* **iOS App**: A fully peer-to-peer iOS app (TestFlight) without notifications.
* **The ability to use it without an email or phone number**: Unlike Slack, Discord, WhatsApp, Telegram, and Signal, no email or phone number is required to create or join a community.

From a technical perspective, Quiet leans heavily on the Tor project.<sup>13</sup> Tor began in the early 2000s as an open-source project by Roger Dingledine, Paul Syverson and Nick Mathewson. Tor stands for **T**he **O**nion **R**elay. It builds off earlier work done by Paul Syverson, David Goldschlag, and Mike Reed when they were working at the Naval Research Lab. Their creation of “onion routing” sends users internet requests through multiple relay servers, each with their own separate and distinct layer of encryption. This practice makes it difficult to track an individual’s internet usage.

By using Tor as the delivery backbone for its users' messages, Quiet adds a robust layer of security to the application itself. This does not mean that Quiet lacks its own base security implementations. From a technical standpoint, Quiet has implemented the following features:



* Community owners use standard public key infrastructure (PKI), with each community owner serving as the community's certificate authority.
* A preshared key (PSK) for the community is required to connect to peers and receive connections from peers.
* InterPlanetary File System (IPFS) and OrbitDB, an IPFS-based conflict-free replicated data type (CRDT), ensure that all data (messages, user data, etc.) syncs between peers with eventual consistency.
* A valid certificate from the community owner on account creation establishes a username, which the owner attests is unique.
* To invite new members, community owners provide (via some other secure channel) a PSK along with an onion address that points to a registration API, which accepts a certificate signing request, responds with a signed certificate, and provides sufficient peer information to connect to other peers.


## Weaknesses

Still, as with all communications applications, the inherent weakness of device security remains. If a Quiet end user’s laptop, phone, or tablet is compromised by malware, the message content, along with the rest of the phone, is fully or partially compromised. The other major threat vector is the physical security of the device being used for the Quiet application. If a bad actor gains physical access to the computer, tablet, or phone, it renders the serverless, Tor-based communications channel moot. Automatic message deletion is, however, on Quiet’s development roadmap.

Typically both of these attack vectors are carried out with social engineering methods or zero-click exploits. Software payloads are installed via links sent by email, compromised electronic documents, or website links or through exploiting insecurities found in software or operating systems. Physical access to a device is given when the owner hands their device to a bad actor who acquires it under false pretenses or by force. 

Lastly, Quiet is in a prerelease, beta status. This means that while certain features such as the use of the Tor network, E2EE, and not relying on central servers for message relay are implemented, the overall code base is not in an officially production-ready state. With that in mind, there may still be undiscovered bugs or security issues within Quiet itself.


## Conclusion

As democracies continue their worldwide recession, authoritarian governments expand power, nationalist groups grow, and corporations gain more access to the lives of everyday citizens, the ability to communicate outside of those spheres of influence becomes increasingly important. Existing solutions all share dependency on a centralized server infrastructure and, save for Whisper, fall under a variety of corporate umbrellas. This makes them inherently insecure. Quiet’s, peer-to-peer, open-source, distributed application removes those issues entirely. Built from the ground up with security in mind, it is a solution that is easy to install and use, although not without some issues of its own.

For nonprofit organizations and educational institutions that are in need of secure communications, Quiet offers an open-source, relatively easy to implement, decentralized means of communication with a focus on privacy and security. By moving to a peer-to-peer messaging system, it avoids both corporate surveillance capitalism and government access to data. For more information, the Quiet project can be found at: [https://tryquiet.org/](https://tryquiet.org/) .


## Notes

1. “[Surveillance Capitalism and the Challenge of Collective Action](https://journals.sagepub.com/doi/epub/10.1177/1095796018819461),” Shoshana Zuboff, _New Labor Forum, _Volume 28, Issue 1, January, 2019.
2. “[Authoritarianism Has Been Reinvented for the Digital Age](https://www.cigionline.org/articles/authoritarianism-has-been-reinvented-for-the-digital-age/),” Marie Lamensch, The Centre for International Governance Innovation, July 9, 2021.
3. “[Digital Authoritarianism: How Digital Technologies Can Empower Authoritarianism and Weaken Democracy](https://www.gcsp.ch/publications/digital-authoritarianism-how-digital-technologies-can-empower-authoritarianism-and),” Federico Mantellassi, Geneva Center for Security Policy, February 16, 2023.
4. [“Understanding and Responding to Global Democratic Backsliding](https://carnegieendowment.org/files/Carothers_Press_Democratic_Backsliding_v3_1.pdf)” (PDF), Thomas Carothers and Benjamin Press, Carnegie Endowment for International Peace, October, 2022.
5. “[The Global Expansion of Authoritarian Rule](https://freedomhouse.org/report/freedom-world/2022/global-expansion-authoritarian-rule),” Sarah Repucci and Amy Slipowitz, Freedom House, February, 202.
6. “[Russian Student Jailed for Pro-Ukraine Wi-Fi Name](https://www.bbc.com/news/world-europe-68526111),” Sofia Ferreira Santos, BBC News, March 9, 2024.
7. “[How China Made Xinjiang’s Ceremonies Illegal](https://foreignpolicy.com/2024/03/08/china-xinjiang-uyghur-muslims-weddings-human-rights/),” Darren Byler, _Foreign Policy_, March 8, 2024.
8. “[The Government Really Is Spying On You — And It’s Legal](https://www.politico.com/news/magazine/2024/02/28/government-buying-your-data-00143742),” Steven Overly, _Politico_, February 28, 2024.
9. “[Launching Default End-to-End Encryption on Messenger](https://about.fb.com/news/2023/12/default-end-to-end-encryption-on-messenger/),” Loredana Crisan, Meta Corporation, December 6, 2023.
10. “[How Cops Can Secretly Track Your Phone](https://theintercept.com/2020/07/31/protests-surveillance-stingrays-dirtboxes-phone-tracking/),” Kim Zetter, _The Intercept_, July 31, 2020.
11. “[Distributed Applications](https://www.techtarget.com/searchitoperations/definition/distributed-applications-distributed-apps),“ Ben Lutkevich, _TechTarget._
12. Quiet official website: [https://tryquiet.org/](https://tryquiet.org/) (website).
13. Tor official website: [https://www.torproject.org/](https://www.torproject.org/) (website).




_This technical briefing is supported by an award from the [Filecoin Foundation for the Decentralized Web](https://ffdweb.org/)._

_Public Good App House is a project of Caravan Studios, a division of TechSoup._
