_Technical Briefing_
# Creating a Distributed File Storage Ecosystem

### An Overview of Filecoin, a Blockchain-Based, Peer-to-Peer, Distributed Digital Storage System

## Summary
Commercial digital file storage services have seen relatively few changes for well over a decade. At their core, they allow customers to move their digital assets from localized, in-house, computers to servers that are distributed across the Internet. There is an Internet joke that goes, “There is no cloud. It’s just someone else’s computer.”<sup>[1]</sup> In the case of cloud storage in particular, this is very much the case. The key question, however, is whose computer?

The answer for the vast majority of all commercial digital file storage services is that it is a corporate one. As of 2024, Amazon subsidiary AWS holds 32 percent of the market, 67 percent of enterprise infrastructure is cloud-based, and corporations store 60 percent of their data in the cloud.<sup>[2]</sup> While this level of usage may be unsurprising and also have some advantages, it also has distinct disadvantages. 


## Details

For years, data storage has relied on centralized datacenters operated by large, for-profit corporations. These datacenters act as repositories for an incredibly diverse set of data, from personal files such as photographs or financial information to mission-critical business data. While centralized storage offers ease of use and scalability, it comes with major issues:


* **Security Vulnerabilities:** Centralized datacenters are prime targets for hackers and malicious actors. Most large corporations also use closed-source software that lacks the community-based security model, which is highly proactive in finding and closing possible attack vectors. 
* **Data Loss Risks:** Centralized systems are susceptible to data loss due to hardware failures, disasters, or outages, putting businesses and individuals at risk of losing critical information.
* **Lack of Transparency:** Users often have limited visibility into how their data is stored, managed, and shared. This opacity raises concerns about privacy and data ownership.
* **Data Sovereignty:** Centralized storage may be subject to government regulations and surveillance, undermining users’ control over their own data.

The last point is of particular concern for the purposes of this case study. Over the last 15 years, there has been a significant increase in democratic backslides worldwide, coupled with the strengthening of existing authoritarian regimes and new nationalist movements. Additionally, core, daily, common-use technological solutions have been centralized in the hands of large corporations — technological solutions such as cloud data storage.

Why is this important? While the causes are open to academic debate,<sup>[3]</sup> it is widely recognized that there has been more than a 15-year period of democratic recession, also known as democratic backsliding. When coupled with the strengthening of existing authoritarian regimes,<sup>[4]</sup> such as Russia, Belarus, and China, the ability of non-governmental organizations, educational institutions, pro-democracy advocacy groups, and everyday citizens to safely publish information becomes crucial. 

Journalist Bob Woodward popularized the phrase, “Democracy dies in the darkness,” but it reportedly originated from American Circuit Judge Damon Keith.<sup>[5] </sup> Woodward said that the slogan is “about the dangers of secrecy in government, which is what I worry about most.”<sup>[6]</sup> This is particularly relevant during democratic recessions. A government that once valued transparency can change course, removing already existing, crucial information while setting up barriers to the publishing of new data. It can do this not just within its own infrastructure, but also in the private sector, with either aid from corporations<sup>[7]</sup> or by applying pressure to them.<sup>[8]</sup>


## Solution
Filecoin is, at a glance, not dissimilar from other digital file storage solutions. It’s a cloud storage platform that allows individuals and organizations to store their files outside their own infrastructure. From there, Filecoin rapidly departs from the functional and even societal norms of the cloud storage market.

Instead of being a purely technical solution of networked servers owned by a single corporation or entity, Filecoin leverages a network that supplies data storage space for clients to use to store their data. The stated goal is to turn cloud storage into a commodity that can be supplied by many instead of a few. It is a cloud storage platform that allows for secure, reliable storage and access to data utilizing blockchain capabilities to record storage commitments. From there, Filecoin rapidly departs from established norms for both cloud storage and blockchain systems. 

In order to do so, Filecoin relies on an important piece of distributed web technology: the blockchain.<sup>[9]</sup> A blockchain is a shared, immutable ledger that facilitates the process of recording transactions and tracking assets in a business network. An asset can be tangible (a house, car, cash, land) or intangible, in this case digital files. Virtually anything of value can be tracked and traded on a blockchain network, reducing risk and increasing transparency for all involved.

By using blockchain as an integral part of its system, Filecoin achieves several major functional goals:<sup>[10]</sup>


* **Greater Transparency:** Blockchain’s greatest characteristic stems from the fact that its transaction ledger for public addresses is open to viewing. This adds an unprecedented layer of accountability, holding each sector of the business responsible to act with integrity towards the company’s growth, its community, and its customers.
* **Better Security:** Blockchain is far more secure than other recordkeeping systems because each new transaction is hashed and linked to the previous transaction. Blockchain, as the name suggests, is formed by a network of computers coming together to confirm a "block." This block is then added to a ledger, which forms a "chain." Blockchain is formed by a complicated string of mathematical numbers and is impossible to be altered once formed. This immutable and incorruptible nature of blockchain makes it safe from falsified information and hacks. Its decentralized nature also gives it a unique quality of being "trustless" — meaning that parties do not need trust to transact safely. 
* **Improved Traceability:** With the blockchain ledger, each time an exchange of goods is recorded on a blockchain, an audit trail is present to trace where the goods came from. This can not only help improve security and prevent fraud in exchange-related businesses, but it can also help verify the authenticity of stored assets. In industries such as medicine, it can be used to track the supply chain from manufacturer to distributor; in the art industry, it can provide an irrefutable proof of ownership.

There are many projects based on blockchains these days, but Filecoin’s unique contribution is that contributors to its blockchain consensus regularly submit mathematical proofs that they have, in fact, stored the data that customers requested they store. If they fail to do this, then they are penalized by the network. This means that there’s a strong built-in incentive for storage providers to preserve customer data, and customers can be confident that the data is stored for as long as these proofs are presented.

Additionally, Filecoin’s entire codebase is open-source. This gives it further benefits:<sup>[11]</sup>


* **Faster, More Transparent Development:** Closed-source software can often be a black box that neither developers nor business users (who aren’t programmers themselves) can meaningfully alter or enhance. As a result, companies often need to partner with vendor support agents or just wait until the vendor builds a solution to their problem. Open-source projects give full visibility into the codebase, which means it is possible to create solutions and directly document issues in community spaces. This can result in a variety of responses that provide as much or more context as would be received from a professional support team, as fast or faster.
* **Better, Community-Based Collaboration:** Developers work with an entire community of other developers, all using the same tools, who may have experienced similar issues and may already have solutions to share.
* **Community-Driven Security:** Open-source products often offer surprisingly robust security as teams tend to test extensively before releasing new versions.<sup>[12]</sup> Many successful open-source communities attract security experts who also make additions to the project.  
* **Community-Driven Reliability:** In the case of mature and popular projects in particular, open-source can offer surprisingly high reliability as many community members may have detected, and already improved upon, reliability issues.
* **Self-Generated Ecosystem:** By going open-source, Filecoin created its own user ecosystem around the open-source platform it created. Having a thriving community that understands the product and actively engages with it as both end users and builders opens up tremendous amounts of potential new business opportunities, product enhancements, and technical engagement that aren’t available in a traditional, closed-source product.

The combination of publishing a decentralized storage system as open-source software and coupling it to a blockchain-based distributed ledger allows the Filecoin ecosystem to harness the best aspects of technology and community. In doing so they created both a scalable, secure, enterprise cloud storage solution and a community-driven alternative to corporate technology that is resilient against government overreach. 

To learn more about Filecoin, go to [https://filecoin.io/](https://filecoin.io/)


## Credits

Erik Mathy, contractor, author

Ian Davis and Danny O’Brien, FFDW, technical reviewers

Editor, Stephen Jackson


## Notes


1. “[There is no cloud: it's just someone else's computer](https://www.redbubble.com/i/sticker/there-is-no-cloud-it-s-just-someone-else-s-computer-by-geekgoods/48737406.EJUG5),” (sticker), Redbubble.
2. “[34 Heavenly Cloud Computing Statistics for 2024](https://techjury.net/blog/cloud-computing-statistics/),” Aditya Rayaprolu, _TechJury_, January 2024.
3. “[Authoritarianism Has Been Reinvented for the Digital Age](https://www.cigionline.org/articles/authoritarianism-has-been-reinvented-for-the-digital-age/),” Marie Lamensch, _The Centre for International Governance Innovation_, July 9, 2021.
4. “[Digital Authoritarianism: How Digital Technologies Can Empower Authoritarianism and Weaken Democracy](https://www.gcsp.ch/publications/digital-authoritarianism-how-digital-technologies-can-empower-authoritarianism-and),” Federico Mantellassi, _Geneva Center for Security Policy_, February 16, 2023.
5. “[Democracy Dies in Darkness](https://en.wikipedia.org/wiki/Democracy_Dies_in_Darkness),” _Wikipedia_.
6. “[The Washington Post’s New Slogan Turns Out to Be an Old Saying](http://www.washingtonpost.com/lifestyle/style/the-washington-posts-new-slogan-turns-out-to-be-an-old-saying/2017/02/23/cb199cda-fa02-11e6-be05-1a3817ac21a5_story.html),” Paul Farhi, _The Washington Post_, February 24, 2017.
7. “[Corporate Control of Public Information](https://www.cjr.org/tow_center_reports/corporate-control-of-public-information.php),” Victoria Baranetsky, _TheTow Center for Digital Journalism, Columbia Journalism Review_, May 11, 2023.
8. “[Informal Government Coercion and the Problem of 'Jawboning](https://www.lawfaremedia.org/article/informal-government-coercion-and-problem-jawboning),'” Genevieve Lakier, _Lawfare_, July 26, 2021.
9. _“_[What Is Blockchain?](https://www.ibm.com/topics/blockchain)” _IBM._
10. “[The Benefits of Applying Blockchain Technology in Any Industry](https://www.forbes.com/sites/ilkerkoksal/2019/10/23/the-benefits-of-applying-blockchain-technology-in-any-industry/),” Ilker Koksal, _Forbes._
11. “[What to Know About Open-Source Software: Benefits and Advantages](https://www.heavybit.com/library/article/open-source-software-benefits-advantages),” Andrew Park, _Heavybit._
12. “[Linus’s Law](https://en.wikipedia.org/wiki/Linus%27s_law),” _Wikipedia._

_This technical briefing is supported by an award from the [Filecoin Foundation for the Decentralized Web](https://ffdweb.org/)._

_Public Good App House is a project of Caravan Studios, a division of TechSoup._
