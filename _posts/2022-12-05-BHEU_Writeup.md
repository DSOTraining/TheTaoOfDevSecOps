---
title: Why Software Security Has Never Been More Important - my Review of Black Hat Europe 2022
date: 2022-12-13 12:00
categories: [conference,blackhat,BHEU,community]
tags: [conference,blackhat,BHEU,community]
---
A Veracoder attending Black Hat Europe 2022.

![BHEU 2022 the Journey Begins](/assets/BHEU_001.gif?raw=true)


Once again this year’s Black Hat Europe took place at Excel London, in the UK. In the past, travelling to Excel was a bit troublesome, but I used the new Elizabeth (tube) line and it was a breeze - less congestion and a lot quicker; at least coming in from King’s Cross train station.

![BHEU 2022 Tube](/assets/ExcelTube.png)

<img src="/assets/ExcelTube.png" alt=“BHEU_2022_Tube” width="300" height="200">

Black Hat was held at the far end of the conference centre so it was a bit of a walk from the station. The Registration area was sandwiched between the Business Hall (vendor stands situated on the lower ground floor) and the briefings (main talks) on the third floor. The sponsor (vendor-centric) talks and Arsenal (demonstration area of open source tools) were co-located in the Business Hall. This layout was very convenient.

Here are some of my colleagues looking after the Veracode stand at the event.
![BHEU 2022 V Stand](/assets/VC_Stand.jpg)

***
## Choosing What Sessions To Attend Was Tricky
As part of my preparation, I shortlisted the talks I wanted to potentially attend over the two days - some overlapped so I had to make tough choices. You can find my choice of **'The Top 5 Application Security Sessions to Attend'** in my other [blog](https://dsotraining.github.io/posts/Black-Hat-Europe-2022/).

The lineup on the first day attracted me more. One session was “Back-connect to the Connected Car. Search for Vulnerabilities in the VW Electric Car” delivered by Yuriy Serdyuk and Alexey Kondikov from the NavInfo Europe Cybersecurity Team. They presented a collection of weaknesses they discovered from various systems controlling the car. An example of one, which stood out for me, was the weakness relating to the software update process - it was a real OMG moment for me as this type of issue is not new in system design. Essentially, they discovered that it was possible to initiate a software system update via USB and the update scripts were executed under the context of root; both are potentially acceptable techniques however the critical point which underpinned this weakness was having no validation of the scripts and binary artefacts. This all leads back to the importance of securing your operational and maintenance workflows to be factored into your design and is an example of what is now coined Software Supply Chain Security.

![BHEU 2022 VW](/assets/VW_SW_Update.jpeg)

For those who are interested in standards relating to the car industry, there are two regulations from the United Nations Economic Commission for Europe (UNECE) for you to reference and digest:
- [UN Regulation No. 155 - Cyber security and cyber security management syste](https://unece.org/transport/documents/2021/03/standards/un-regulation-no-155-cyber-security-and-cyber-security)
- [UN Regulation No. 156 - Software update and software update management system](https://unece.org/transport/documents/2021/03/standards/un-regulation-no-156-software-update-and-software-update)

It’s been a while since I worked with a Security Operations Centre (SOC) and so the session titled “Confidence in Chaos: Strategies for World-Class Security Operations” by [Kathryn Knerle](https://www.linkedin.com/in/kathryn-knerler-b8b5b22/) and [Carson Zimmerman](https://www.linkedin.com/in/carson-zimmerman/) allowed me to play catch up with the world of Operational Security and how the SOC has evolved since I was last involved in this domain. The talk covered some of the changes and key areas contained in the freely published reference [11 Strategies of a World Class Cybersecurity Operations Center](https://www.mitre.org/sites/default/files/2022-04/11-strategies-of-a-world-class-cybersecurity-operations-center.pdf).
It is always wonderful for experts in their own field to collate and share their domain knowledge with the wider industry through the creation of an in-depth publication - sharing is caring.
***
## Key Highlights From the Event 
Both keynotes were the highlights for me as they reflected on the journey the security industry has taken and what we can do going forward.

[Daniel Cuthbert's](https://www.linkedin.com/in/daniel-cuthbert0x/) (@dcuthbert) keynote delivery was amazing. ChatGPT is all the rave and he used this to help generate his slide deck and talk.

He used the term “incentive” a number of times and this resonated with me a lot. It seems despite security professionals beating the drum to make things secure we were not really enabling this to happen. For example, we (tech in general) love to use fancy names which push people (outside the domain) away; another is stupefying the situation by fixing the problem as it is quicker to do this as opposed to showing/educating the person facing the challenge. I see this a lot and it is no wonder why for non-security individuals there is “no incentive to build secure products”. 

[Jen Ellis](https://www.linkedin.com/in/infosecjen/) (@Infosecjen) keynote and afternoon talk, with [Irfan Hemani](https://www.linkedin.com/in/irfan-hemani-493a4113/) (@irfanhemani), also resonated with me a lot as the topic was specific about what the UK Government are doing to improve cyber security for the country and the industry.

Daniel captured the essence of the talk very well in his live [tweet](https://twitter.com/dcuthbert/status/1600844299004149760?s=20&t=QXfriQJPZiXbE8HFvodkOw).

Here are some key slides from the talk. 
![BHEU 2022 JenEliss](/assets/Jen_Eliis_BHEU2002.png)

Interesting fact, in 2022 there were 16 ransomware incidents which invoked COBRA meetings indicating how serious the situation was for the UK government to have held these sessions.  Further details from the UK NCSC Annual Review 2022 can be found [here](https://www.ncsc.gov.uk/collection/annual-review-2022).

Jen stated that one of her key objectives for her talks was to inspire and provoke action to help shape the future of security in collaboration with your government (not exclusive to the UK). She has definitely piqued my interest to understand further what is happening in this space.

Here are a couple of areas which I will dig into more [AppSec and Privacy Code of Practice](https://www.gov.uk/government/consultations/app-security-and-privacy-interventions/app-security-and-privacy-interventions) and [Product Security and Telecommunications Infrastructure Bill](https://www.gov.uk/government/publications/product-security-and-telecommunications-infrastructure-bill-documents). Also to keep track of the forthcoming “Software Security” cyber policy.
***
## Final Thoughts 
Having attended different conferences over the last three weeks I noticed that the last day always seems to be very lightly attended. It is December 2022, so I guess we are still adapting to the new world we live in with people’s working practices and attending in-person events. 2023 will be another stage for us all. I hope I have the opportunity to continue to meet you wonderful folks in the new year and for us to share our experiences.

Reflecting upon the current techno landscape we work and live in, software security has never been more important. Defining the “right amount” of security for your business is challenging. Software Supply Chain Security (SSCS) continues to be a hot topic and it is excellent that the UK government is actively “improving this”. An element of SSCS is the Software Bill of Material (SBOM).  If you like to hear me discuss this with industry representatives then check out my [webinar](https://www.brighttalk.com/webcast/12807/503709) organised by [Veracode](www.veracode.com).

And finally, it is always a geeky moment to see Chris Wysopal (@WeldPond), as part of L0pht, being referenced in [talks](https://twitter.com/_MMAN888_/status/1600837525530034176?s=20&t=lXK9cvrc39iFW3_H8-oEsQ).
![BHEU 2022 L0PHT](/assets/L0PHT_Jen.png)