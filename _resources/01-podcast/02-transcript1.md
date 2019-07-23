---
permalink: /resources/podcast-episode-1-transcript/
title: "Episode n. 1 transcript"
excerpt: "Transcript of first episode"
author_profile: false
last_modified_at: 2019-07-22T12+02:00
sidebar:
  nav: "resources"

---

### Introduction

HTC aims to be the reference point - gathering people and partners worldwide - for creative awareness campaigns about the harms of addictive and invasive technologies. HTC proposes to guide people to systemic and technological solutions, starting with a humane purpose and design. We evaluate technology for what it brings into our lives - how it supports our long-term needs and aspirations. Hello, everyone. My name is Pat and I am a member of HTC.

In this first podcast, our guest is Gokulakrishna Sudharsan, a FLOSS developer in India.

### Interview

**Pat:** OK, could you please explain, in layperson's terms, what free, libre, open-source software is?

**Gokul:** So there are two types of software in general. One is the type of software that respects your freedom, and then the other type is the kind of software which we call as proprietary.

So when we say free and libre and open-source software, there are some licenses under which one can release a software which will bring it into the umbrella of free and libre and open-source software. So a free software provides some rights to the users. In fact, it provides the most rights to the users - unlike proprietary software, in which all rights are reserved at the hands of the developer or the owner or initial creator of the application. One pre-condition to have free software - when I say *free,* I don't mean cost; I mean free as in *freedom*. So for a free-as-in-freedom software, the pre-condition is that the source code in human-readable form should be made available. So that it enables the community and everybody who is interested to inspect it, audit it, find any defects in it and provide, contribute fixes and upgrades and also features to the software.

A free software is a collaborative effort across the whole globe, unlike proprietary software, where only a few people will have the chance to ever look at the source code and try to build anything that is useful. As you can imagine, when something is a proprietary software, it puts too much power at the hands of the developer or developers behind it. So most of the problems that we, in humane tech community, want to solve can easily be solved if all the software in the world - or at least all the softwares which we personally use - are free as in freedom software.

**Pat:** Thank you, that's a great explanation. Can you talk about the things that you've created, the three addons for Firefox. Also describe the vetting process that they had to go through.

**Gokul:** I have created three addons so far, and two of which, two of the three can run in Chrome, Firefox and all browsers based on Chrome, which include Brave, Opera, Vivaldi and others. And all three of which can run in Android devices as well as in mobile Android Firefox. The first one, which is closest to my heart, is my addon called Wayback Everywhere.

One of the most important projects that we have is the nonprofit organization - their project called Internet Archive and the Wayback Machine. The average age or the up time of any given page on the web is usually measured to be around a hundred days. So let’s say I write a research paper and then I refer to an article, or let's say there is a court proceeding and then they enter a page URL in the legal documents, and after a hundred days, after two hundred days, that page may not be there at all. This creates what we call as the broken web, where links just disappear from everywhere. The Wayback Machine project archives about billions of pages, in fact hundreds of billions of pages across time. I think it started around the late 1990s. The addon which I developed provides the feature to automatically redirect all the pages that we’ve opened to their archived snapshots in the Wayback Machine and also automatically save the page if the page is not yet archived at the time of opening.

Obviously, there are some sites which we'll need to exclude from this redirection, so that we can log in and maybe watch a video on those sites. So to enable the user, the addon comes with more than six hundred to seven hundred sites as a default exclude to provide a starting point. Because since it is a *free* software--where we talk about freedom - the user is completely *free* to add or remove from these excludes and use the addon however she wishes. The main motivation behind this is that whichever article that we read, whichever page that we browse, it will be very useful for future reference if the page is archived for posterity.

So let’s imagine how we browse the world wide web in general. There may be a select, a small number of sites where we log in and where we maintain a session. That is, most of the websites that we browse online are all public pages that don’t require a login, that’s not about watching a video. So those pages are very well supported, the public pages are supported by the Internet Archive's Wayback Machine.

**Pat:** I see. So it becomes a huge repository.

**Gokul:** Yes, Pat. So the Internet Archive's Wayback Machine and their volunteers, they run what we call as crawlers and they will automatically crawl and add more sites, add more pages to the Wayback Machine snapshots, but then that is not personalized. I use my Twitter account and then there is some interesting article which I open, and if I just open it in the live version, it may not be caught by those crawlers, because maybe it's a regional website and the crawlers may be on another continent. And say six months from now, I want to refer the same article, it may not be there, so this will ensure that a copy of what we read is always there in the Wayback Machine.

**Pat:** Can you talk about your Cloud Firewall addon also?

**Gokul:** So there was a research conducted by Kashmir Hill. She was a journalist with Gizmodo tech site. She tried to spend six weeks where she blocked a big cloud service vendor per week - say, Google, Amazon, and others [Facebook, Microsoft, Apple]. And on the sixth week, she spent her whole time blocking Google, Amazon, Facebook [and Microsoft, Apple]. Yeah, she spent her sixth week blocking all these five major big tech companies and their clouds. She documented it in a very detailed way about her experiences.

Her research is excellent, and we need to reproduce it so that we can confirm that everybody is able to see a similar experience that she has had during her research. It was a good opportunity for me to create a tool which enables anybody to recreate and reproduce her data and her results by using this addon over time.

The way she did was that she used a local VPN, a custom VPN with blocking rules, and that may not be easy for a normal user, particularly if you are mostly spending your time on a mobile device. With this addon, you can install it in your Firefox or any Firefox variant in desktop or in your Android phone. And then you can try to reproduce her experiment by selectively choosing to block a particular big tech company and see how your web-browsing experience changes.

**Pat:** Your addons were included in HTC's Awesome HumaneTech List - that is, a list of open-source software that HTC recommends for use by members.

**Gokul:** Yes, before we move on to that, let me mention about my third addon as well. It's a smaller one compared to the other two. The third one which I created is called Warn Common Password addon, which works entirely offline - unlike the other solutions, which will hash, encrypt your password, and send your password to a remote server and then they get some data back and then do some sort of local comparison. Sure, it happens, but in a corporate network or in a school network or in a university network, the network admin or system admin may not prefer that password in any form - even in encrypted or hashed form - leave the network other than to the first-party site. So in those cases, this addon will help by securing the user from making the mistake of using a very common password like *password1*, *letmein*, *logmein*, and all such very simple passwords.

There was a research conducted by another researcher - he goes by the nickname [Berserk0](https://github.com/berzerk0/Probable-Wordlists) - and he had published more than a billion commonly used passwords. From his research, I picked the top 500,000 most commonly used passwords and bundled that within this addon. So whenever there is a password field or security answer field where you see the dots [•••••] instead of plain text, in those fields if you enter something as simple as, say, *ferrari*, *rainbow*, *password1*, or any such very simple common password from the top 500,000, it will show a warning notification saying you are using a very simple common password, try to make it more complex so that your account is more secure that way.

The main goal of this addon is that the user should still be secure even if some remote server which is providing this password verification service goes down - because it [the addon] is entirely offline. This will be highly useful for universities and corporate networks.

**Pat:** Wow, that's impressive. So, how long does it take you to create these addons?

**Gokul:** Yeah, so there is a project called openhub. This openhub project is about doing code analytics based on lines of code, lines of non-blank, non-comment code and type of language, and it tries to measure the total estimated effort spent on developing the application and the estimated cost of developing the application since it is open-source software. And as you can see, like my projects, many of these projects are done on personal time like my three addon projects. And there are some corporate-funded open-source projects like Google's Chromium browser, upon which Chrome, Brave, and other browsers are based on.

There's this site called *openhub.net*, and there I have listed my addons and to have the tool analyze my projects. So in this tool, you can exclude some files which are not your own code. For example, you may be including a library or set of libraries which are built by somebody else, and those are also obviously released under a freedom-respecting, user-respecting license.

We have something called license compatibility. Within my libre-licensed project, any library which I use will also be a libre-licensed project. So from end-to-end, it will be always be about users' rights, and freedom-respecting expectations are always met. So in the case of my Cloud Firewall addon, the tool estimates that the code base size is around 4,400 lines and estimated cost is around 50,000 U.S. dollars. It estimates that around 1 person year as the estimated effort. It's a very good tool, and check that out at *openhub.net*.

Your question on how the selection process happens for Humane Tech Awesome list: I invite the listeners and the community to review our humane tech awesome list which is available in GitHub pages, which you will find the link for below the wiki post. So we have what we call the pyramids of humane technology listed on top of the page. So any listing which you will find here, of course we have not done a thorough code review, but these are all community-recommended, community-supported free, as in freedom, software. Since the goal of HTC is to improve well-being, freedom and then society itself, the only way to become that, the only way to be humane, to be ethical, is to release your software, services, and applications under a freedom-respecting license. In our humane tech awesome list, it is categorized under different sections, starting from ethics and privacy and well-being, and others. One common criterion for selection of any of these entries is that, obviously, the software or service should be a libre-licensed, open-source software.

**Pat:** So is there some kind of organization that verifies that software is indeed free and libre? Or is it a matter of trust?

**Gokul:** Yes, Pat, so when it comes to IT software field, there are two types of trust - ideally, there should only be one type - so in case of proprietary software, the developer says: "Trust us because you can trust us." And then in case of freedom-respecting free software, the trust is not because somebody says so. For example, we have the license of the application which is provided with the application itself. Say for my addons, it will be GPL license, the General Public  License. And apart from this, the source code of the application is also available. So it is always possible to review, if somebody's not from software field, they can always hire someone to review or they could ask a friend to review it. Or if somebody is a teacher or professor at a school or university, they can assign students homework or any project assignment to review the existing open-source software so it will be a good educational learning experience - to learn from experts on the field. This will not be possible if it is a proprietary software, because proprietary software only wants people to be users and consumers. Proprietary software does not want us to be creators. Proprietary does not easily let people to imagine and create the future that they want. So free software, software freedom is essential for education purpose.

**Pat:** You had shared an article with me by Dion Moult. He was writing on what he calls ethical software. He said: *"As a result, software should be created by the community. That is, not only open-source, but the core developers should be welcoming to all contributors and unafraid of forks."* Can you explain to us what forks are and why users should be able to create them?

**Gokul:** Yes, Pat. Whenever we are hosting software source code in a source repository like GitLab, when we say forks, there are two types. One is when you see my application and you review my code and you find a bug or you want to add a feature or contribute to the software. You can do something called forking and you can locally work on the changes that you want to do, and then you can ask the original developer to merge your changes and then make a new release with a new feature or bug fix which you contributed. So that is one kind of fork.

And the other fork is when there is a specific feature that you want, but the original developer of the software thinks that it is not suitable for his target audience. Let's say you want that feature to be made available to your company or for your personal use or at your own school - which may not be applicable for rest of the users. So the original developer may not want to merge your changes with his code base. So in that case, you can release your own version as a fork. That's also called a fork.

**Pat:** I see, thank you. OK, our last question: for those users who *don't* have tech backgrounds, what principles of software use and internet behavior do you recommend?

**Gokul:** We should always encourage users to do things which are easy but also freedom defending and security enhancing and privacy enhancing. So in that case, I would recommend people to switch to Firefox, which is developed by Mozilla. They are very trusted. And apart from that, there is a fantastic browser add-on which is developed by Raymond Hill and other contributors, which is uBlock Origin. So if a person does not want to do anything else other than taking one action to defend their browsing experience and enhance it, they should get Firefox and get the uBlock Origin addon.

Apart from this, as I said, the whole free-software movement is an educational movement. It's never late to learn something new, so anybody, everybody is welcome to the community. Everybody will encourage you to learn more and do the harder stuff also.

**Pat:** Yes, I think the community that is formed around free and libre software is very impressive and probably a model of community building for other groups. I think that was my last question. Is there anything else you want to say or add?

**Gokul:** No, Pat, that's all I have today.

**Pat:** Thank you so much for your time, Gokul, really appreciate it.

**Gokul:** You're welcome.
