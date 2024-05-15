# Janastu: Enhancing Agency, Privacy, and Resiliency in Data Storage for Community Media
_A case study showcasing innovative applications and the real-world impact of creative technological interventions that harness DWeb technology for public benefit. _
![Image 1](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/14fa51f8-6138-4778-8b8d-533c598db091)

![Image 2](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/a0e35dea-8407-45f8-96db-4b8169bbb85f)

In the heart of Karnataka, India, lies a small village at the base of the Devarayanadurga Hills where — for the past decade — local community leaders, technologists, craftspeople, and other villagers have been working together to develop and implement various technology projects in service of their village. The group is called Janastu. They are an open-source software collective whose mission is “to enable community storytelling by the people, for the people.” 

For this report, we spoke with two of the leading facilitators of the Janastu Collective, Dinesh and Ram, to learn more about their approach to technology and capacity building among villagers — especially women. By creating safe and supportive community spaces, engaging local volunteers, co-designing user-friendly technology, and leveraging decentralized storage solutions, Janastu empowers villagers to capture and share important local knowledge and be the stewards of their own heritage.

This report dives into the work of the Janastu Collective. It was funded by an award from the Filecoin Foundation for the Decentralized Web.

## Project Overview

Since 2002, the members of Janastu have configured hardware devices, developed software applications, and grown the necessary underlying social networks and capacity to build and maintain all of their projects. This “socio-technical stack” has evolved over time, with each layer functioning to serve the goal of creating a community-owned media network.
![Image 3](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/68ce3627-db07-4f1f-a1d3-35838287c669)

These are the parts of the stack:

* A physical structure in their village called the Community Media Center, where they meet and engage local volunteers
* A community Wi-Fi network ([COW Mesh](https://open.janastu.org/projects/cowmesh)), which grants them internet access 
* Accessible UX interfaces for software applications 
* A local web radio to promote authentic storytelling
* A collection of recording devices they use to document audio and visual stories from their village

Janastu’s most recent project in the stack is called The Common Storage Layer. It is an API, or application programming interface, that connects to a range of data storage providers including local servers, decentralized peer-to-peer network providers (IPFS and Filecoin), and cloud services. This software gives community members more precise control over how and where their media is stored and shared. Using the API, users can share content between personal devices, publish it on the internet, or store it on decentralized networks in a more permanent community archive. 

By connecting to decentralized data storage networks, Janastu is able to capture the unique knowledge, stories, and insights from villagers in a way that promotes community control and agency, ensures privacy and security, and guarantees long-term accessibility and resiliency of the media.

![Image 4](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/eda7defa-7b29-4b49-9efe-2118f4b44ebc)
_Caption: The Anthill Hacks whiteboard placed by the communal kitchen provides a space for asynchronous syncing through messages and doodles throughout the week._

![Image 5](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/977018e0-1209-4ed3-ba64-b9fa25c6ce0f)


![Image 6](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/49165db9-e768-4a6a-9b0c-036a71f7ade4)
_Caption: Village and Anthill Hacks residents arrive to celebrate the raising of the bamboo mesh tower._

![Image 7](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/8b11f32e-184a-4438-9ab2-930df2608bc9)
_Caption: Mesh network hacking at the Red Cottage. Anthill Hacks is one the few intergenerational events in technology out there, blending discipline and age groups alike to create a true sense of community for the month._


## In Action

The technologies designed and developed by Janastu emerge directly from the needs of the village. For example, many people who live in the village are low-literate or illiterate, which makes using traditional text-based media technologies like smartphones, web browsing, and email very difficult or completely inaccessible. Janastu’s methods center around hands-on learning, and their projects focus on audio and video media as opposed to text.

At the hardware level, Janastu teaches youth and other local volunteers how to configure and deploy recording devices to document audio and visual stories from around the village — including timely and relevant community information, traditional songs sung by villagers, monuments with historical importance, and much more. They also use community-owned laptops with a Raspberry Pi core, which they’ve named the Aamne Saamne Pi (which translates as “Face to Face Pi”), to facilitate the creation and narration of community expressions.

For an example of how these technologies are used to capture community stories in practice, we can look to two villagers and members of Janastu, Aasha and Mangamma. (Note: their names have been changed to protect their privacy.)

Aasha is one of the volunteers at the Community Media Center, and Mangamma is an older woman who lives in the village. Over the years, the two have become close, and they meet up often to talk and share stories of their lives. Recently, Mangamma’s daughter married a man outside of her caste, which is extremely taboo in Indian culture. This resulted in her daughter being thrown out of the house and moving to the city of Bangalore. With help from Janastu’s technologies, Mangamma has been able to remain in contact with her daughter without her husband or other neighbors knowing.

Mangamma’s story is not unique. When Aasha and Mangamma meet, they record some of their conversations because they want other women who might be experiencing similar situations to know that they’re not alone and that it’s okay. 

Using the software component of the Janastu stack known as Sweets, [a platform for semantic annotations](https://sweets.janastu.org/), Aasha and Mangamma can later listen back to the recordings and add annotations — additional information that helps others interpret the stories, such as context, questions, comments, and even translations among the five local languages, to Hindi or English. The annotation platform is particularly important towards making information more accessible for low-literate communities and those that speak a different language from the one used on the original site. 

Other concerns Aasha and Mangammae have include the risk that these recordings could fall into the wrong hands, be traced back to Mangamma, or be lost completely. 

To this end, the annotations tool directly interfaces with the latest software addition to Janastu’s stack, the Common Storage Layer API. The API makes it easy for Aasha and Mangamma to transfer and store the recordings on different data storage providers depending on what information they want to make public versus keep private. 

For example, content with the most personal and sensitive information that Mangammma and Aasha share can be sent to storage only on local devices with fully secure encryption. Or, alternatively, they can decide to broadcast some segments onto the local web radio for other women or villagers more generally to hear. Finally, they can choose to publish content to the web or the decentralized web. Using the IPFS/Filecoin decentralized data storage network, they can create a resilient backup copy for safe and secure storage in a community-owned digital archive.

Using these technologies, especially the Common Storage Layer, Aasha and Mangamma have greater agency to control where their information is stored and can make more informed and empowered decisions based on their specific needs and circumstances.

![Image 8](https://github.com/CaravanStudios/PublicGoodAppHouse/assets/3868907/32f47ea0-3c91-4220-880e-fdd1d3733687)
_Caption: Viju (right), an architect and artist specializing in natural building materials, guides Max (left) on the process of building earth walls in the on-site housing prototype at Iruway._


## Dive Deep

The Janastu model of community-led technology development can be compared to its alternative: services like Facebook’s [Free Basics](https://advox.globalvoices.org/2017/07/27/can-facebook-connect-the-next-billion/), which currently operates in 63 countries around the world connecting people with limited internet access to “light” versions of Facebook and WhatsApp. However, these services only provide a relatively small amount of content relevant to local issues and needs, lack public service sites and independent news sources, and simultaneously collect all kinds of metadata about user activities. 

Dinesh and Ram are highly skeptical about these types of programs, not only because they believe they [violate the principles of net neutrality](https://www.theverge.com/2016/2/8/10939594/mark-zuckerberg-internet-org-india-court-defeat-zero-rating), but also because they do not actually serve the needs of their village.

“Media is not just global or national news,” Ram says. “We focus on what is newsworthy for the people of our village. Why isn’t there a way to have a conversation or share media between adjacent villages? For example, let’s say some crops are starting to fail and a farmer tries to understand why. That might not usually be newsworthy enough, but examples like these are what led to the Community Media Center.”

Every layer of Janastu’s socio-technical stack enables them to govern their own local media network — including the Common Storage Layer — which gives more agency back to the users to decide where data is stored and who can access it. Content can be shared as part of local news networks within and between villages (such as their [web radio](https://www.namdu1radio.com/)), published online for the public, or added to a community-governed archive for cultural preservation. The tool enables different content to be sent to different places depending on factors including file size, information sensitivity, longevity, and more. The tool also provides users with the ability to generate logical groupings of audio or video content and configure, at the group level, the content to sit in one provider or another.

Privacy is a significant concern when it comes to adequately serving the needs of community members within specific cultural and political contexts. An advantage of storing data on a decentralized network such as IPFS/Filecoin is that the content is automatically encrypted and broken down into pieces to be stored across a large, geographically distributed network as opposed to centralized cloud storage providers.

Another advantage of decentralized data storage is greater resiliency or immutability of data. A centralized cloud storage system has a single security system, which, if breached, can compromise the entire collection. This is known as a single point of failure. IPFS or Filecoin, on the other hand, breaks the data down into small pieces and replicates it over a large distributed network of volunteer nodes where it is stored — each protected by a distinct security system. This means that even if one node is attacked and breached, the data cannot be entirely ruined or lost.

This is particularly important to Janastu after a recent incident when they lost a large amount of data when an email from their data storage provider was accidentally sent to spam. They had exceeded the standard limit and had been charged a few extra euros, but after a month of no response and no payment from Janastu, the provider deleted the whole account, and the data was lost. Unfortunately, Janastu had also deleted their local backup copy. Not only is decentralized storage known to cost up to 95 percent less than traditional cloud services, but users also maintain ownership and control over their data, which means they are not subject to terms and conditions of any third-party providers who have power to censor or delete content according to their own terms.

While the Common Storage Layer affords greater agency for village members and decentralized data storage provides greater privacy and resiliency of data, the core rationale for implementing decentralized solutions comes out of the values, structures, and philosophies of the village itself.

“The social context has to drive how you build technology,” Ram says. “We cannot just throw whatever type of technology is available on the internet and say that it will solve your problem — that doesn’t work. That’s exactly why decentralized technology has to come in. Not because it’s cool tech or anything, but that’s just the nature of the village. And the technology is just a reflection of the nature of the village.”


## Colophon

Original publish date: May 15, 2024.

**Sources**

* Janastu Website: [https://janastu.org/](https://janastu.org/)
* Janastu Blog: [https://blog.janastu.org/](https://blog.janastu.org/)
* Thank you to Dinesh and Ram from Janastu for the interviews. 
* Thank you to Rithikha Rajamohan for the photographs.

**Credits**

* Author and researcher: [Val Elefante](https://www.linkedin.com/in/valerie-elefante/)
* Editor: Stephen Jackson, Director, Strategic Communications, TechSoup
* Project Managers: Billy Bicket, Head of Maker Labs; Elijah van der Giessen, Project Manager

**Images**

* Image 1: [Anthillhacks Gallery](https://anthillhacks.in/gallery/)
* Image 2: [Anthillhacks Galler](https://anthillhacks.in/gallery/)y
* Image 3: [Val Elefante](https://www.linkedin.com/in/valerie-elefante/)
* Image 4: [Rithikha Rajamohan](https://rithikha.com/)
* Image 5: [Anthillhacks Gallery](https://anthillhacks.in/gallery/)
* Image 6: [Rithikha Rajamohan](https://rithikha.com/)
* Image 7: [Rithikha Rajamohan](https://rithikha.com/)
* Image 8: [Rithikha Rajamohan](https://rithikha.com/)


_This report is supported by an award from the [Filecoin Foundation for the Decentralized Web](https://ffdweb.org/)._

_Public Good App House is a project of Caravan Studios, a division of TechSoup._
