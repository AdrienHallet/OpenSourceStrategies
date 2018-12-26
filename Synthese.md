# LINGI2401 : Open Source Strategy for Software Development
*Please note that the (ethical, political, ...) content of this summary does not reflect the views of the writers and are only based on the lecture.*

* **Lecturer** : Lionel Dricot (@uclouvain.be - lionel@ploum.net)

## Administrative talk
We will discuss :
* Licenses
* Business models
* Community
* Political aspects
* Security & Privacy
* Interoperability
* Decentralisation
* (if we have time) Bitcoin & Blockchain

Slides available on http://github.com/ploum/lingi2401 this course is an open source project. You are free to partake in its development.

Use Github ticket system to ask questions (or email if it's a private one). The goal of this course is also to prepare us to LINGI2402.

**References :** *Producing Open Source Software*, Karl Fogel

### The project
The goal is to **contribute to an open source project**. The contribution should make **sense** and be sent **2 weeks before the blocus** with a **report documenting the contribution and the process (markdown format, do whatever you want).**

1. Choose an open source project
2. Validate it with Lionel Dricot (merge on the \*.csv on Github. If merge accepted, we can have the project)
3. Complete the report day-to-day in our open source adventure

*Ideally, the contribution should be a small fix, feature, typo. We are encouraged to go outside our comfort zone.*

### The exam
* Laptop and internet allowed during the exam (no need to study)
* It's a situation-based exam

Contains :
* Face to face meeting
* Discuss about the contribution and the report
* Discuss concepts seen in the classroom
* The lecturer provides an evaluation grid and we fill it together

## What is a free software ?
It's a software that :
* You can **modify**
* Is protected by a **license** (automatic in Belgium)
* You can **redistribute**

At university, we are studying free softwares because no company can reinvent the wheel. Either they build their own (not good) or they base their new content on free, open content.

**Market University** : The university makes people fit the market (mainly in terms of skills)

## What is freedom ?
Freedom is :
* Lack of constraints
* Choices

*Example : A conference (see slides) where we have a constraint and we want to put the software's performances between those upper and lower bounds. Here, just by controlling the temperature of the engine, you can put the performances right in the right bounds.
James Liang is the engineer that managed to do that, but he's now in jail because he was the Volkswagen engineer that managed to lower the CO2 emissions levels during a testing environment.*

*His boss put the blame on him, and the CEO is obviously not in prison.*

*This example is only the beginning. They are many others (killing drones, AI populated kill lists, self-driving lists, ...). What code are we willing to do to keep our job ? What code are we ashamed about.*

This example is to show that we are not a cog in the machine. **Market univesity is (allegedly) bullshit.** We have nuances between that market-driven university and the **Humboldtian university** that aims to create better, more responsible people. The choice between the two is not binary. We can be a bit of both.

## History of free softwares

At first, every software was free (besides the expensive hardware). Then the commercial softwares came, there was still an exchange of those software around hackers (no internet yet).

In 1980, in the M.I.T., a new printer arrived (Xerox 9700). The queue for the whole building was quite long so a guy wrote a message-system to indicate to the user when the print job was finished. The company, on the other hand, copyrighted the source code and the new snippet was not allowed. The guy (Richard Stallman) then created the free software movement.

### The movement
* Free to use
* Free to study
* Free to modify
* Free to redistribute

*You are free to use your own definition of freedom.*

### GNU (GNU is Not Unix)
* Free operating system
* Lot of tools without any system
* GNU/GPL - 1989
* GNU/Hurd - 1990

The GPL license is a really important project where every using layer must have the GPL redistribution. It kind of "infects" the softwares using it with its license.

### Linux (GNU/Linux)
In 1991, Linus Torvalds wrote a mailing list where he asked for feedback on another OS because he was starting his own. Linux was born (amen) !
Only one year after, a first distribution was born (SLS), many other followed (Ubuntu was in 2004).

### Open source
Free software are a bit aggressive against copyrighted code. The Open Source movement aims to be less political. The philosophy is now about efficiency. Open Source code allows more people to collaborate, more fixes to happen, ... It's better for the software (and it also helps non-free software).

**FLOSS** : Free Libre Open Source Software

---
*Lecture 2*
# Licenses

### Context
>In economy, we talk about *rival goods and non-rival goods*. If you own a rival good, only you profits of its gain. An example of a non-rival good is a toll bridge. You cannot "steal" passage on the bridge.

The sixth century A.D. viewed **Sybaris Law**. It said that if you invent a receipe (non-rival good), you receive some money everytime a cook uses it for a year. It's the first occurence of a patent law.

Until the fifteenth century, people were mainly considering rival goods. The concept of authorship mainly was abstract, not financial. After that, the **printing press** was invented and information could be provided to a lot of customers.

The copyright was a censorship tool for the king to ensure that only allowed books were printed. It's not done to protect the author but instead to censor him. In opposition to the moral right ; the author has the right over its creation and cannot be sold. The copyright can be sold.

*Example given of the englishman who wed Hergé's widow and gained the copyrights for Tintin and now makes money over it.*

*Another example is the "Boléro de Ravel" which copyright went through quite the stir (massage->driver->whatever)*

Since code is also writing, creating it allows you to benefit from it as soon as you can prove you wrote it first.
### License ?
> A written agreement between two parties (the copyright holder and the user)

We standardize licenses to make things easier but we could have one license per software. A license is all that separates free from proprietary software.

#### How to license a software ?
The license should be in every source file, most use a license file in every repository

### Patents
> A **Patent** is the agreement that the patent office in your country has validated that you may have the rights to something that might not have been invented before and you may ask money in return for it ("may" is the keyword). In theory, you can only patent *physical* things.

The difference between classical patents and software patents is arbitrary since there is always a way to "express it physically" and patents can really be abused.

### Authorship in a company
* Every author claims his lines
* Economics rights usually are transferred to the employer
* Authors keep their moral rights
* Diffusion under a given license is an economic right

# Licenses
### GPL
You are forced to redistribute any modification with the same license.

It evolved from v2 to v3 because of a company named Tivo, which created an on-demand video machine based on a Linux kernel. They had it under GPL v2, which means they would sell it with a hard copy of the code. But they installed a chip on the device that would prevent it to run if anything was changed in the original code (this is called an *anti-feature$, a feature that is designed to block the user).

The community debated a long time about whether or not this should be allowed and, never agreeing, created GPL v3 that prevents such actions.

### Copyleft
It's a copyright that says that you can do whatever you want if you redistribute it with the same license.

### AGPL (Affero GPL)
Made for web applications. Needed because the webserver that runs the code is not possessed by the user of the website (they are not *technically* the owner) . It says that every user that wants it can request the source code.

### MIT
No copyleft, do what you want as long as we are not responsible for what you do with the code

### BSD
A bit like MIT, you are completely free to reuse or modify the software.

### Mozilla Public License
Mozilla created their own license to customize their needs, it is a middle ground between GPL and BSD.

### Apache
Same

### Creative Commons
The Creative Commons license has some clauses that allows for a fast and easy way to understand the license (Buy, Use, Transfer). The CC is quite unclear, for example about making money. There is four clauses to pick from (any combinaison) :
* Can use but need to specify who did it
* Non-commercial
* Can redistribute but not modify
* Can be reused but you have to transfer the right to modify to your user

In Europe, since it is not possible to put something in the public domain right away, we created *CC0*, which is the Creative Commons licence without any of the four clauses, which is equivalent to the public domain.

### Others
* WTFPL
* Beerware
* CeCILL
* OSI

### Dual Licensing
It allows to have two licenses in the same software. Example of StarOffice, a "better" (proprietary) version of OpenOffice.

Trilicensing also exists, or even relicensing (changing the licence), which is really hard to do but is achievable when fiddeling with the law (React did it).


---
*Lecture 3*
#Business models

The main metrics of our society is *money* (we consider someone to be successful/smart/good if he/she has money). But there is a paradox with every metrics (green and red cars image) :

>"Every system using a given metric as a measure of success will optimise itself to maximise that metric while becoming less and less efficient to solve the problem for which the system was initially conceived."

The following is a logic consequence :

>"Every organisation that needs money will have a strong tendancy to maximise money without consideration for anything else."

When creating a new company, there ofter is the problem of "raising money" (via seed funding,...). Those people giving money rarely are just angels, they excpect return on their investment; wich means that raising money is not a business model, you need to *sell* something, to have a product.

## Business models
Business models need to be flexible, never stick to the initial idea. We need to change the business model to adapt the situation. There is always a customer. Even when the app is free (ads) or public (administration).

## Earn money with free softwares
* Integration and consultancing
* Consortium standardization
* Donation
* Proprietary features
* Services around the app (e.g.. Odoo)
* Ads (sponsorship/...)
* Goodies

##Ads
Ads are not free ! At the very least, you pay with the time you spend to watch them. Always ask the question "If I'm not paying for it, who is paying?"

---
*Lecture 4*
# Community

There is a differences between **donation** and **charity** : charity is giving money out of pure generosity (or pity, or to feel better about something); when a donation is buying a service to the price you want.

In the free community, the **free price** is a PWYW (pay what you want) economic model.

Always ask yourself *if I'm not paying, who is paying for it ?*.

The most important thing in an Open source projet has not yet been discussed : the code. In such projetcs, there is one big question : "Should this modification be part of the code or not?" (like in the parliament, where they ask if the modification should be part of the law).

This requires code management. Here is a short history :
* First, contributors would send patches by (e-)mail, for the owner to merge. The good point is that the maintener decides
* Then, version control arrived, with RCS and SCCS; but they allowed to modify only one file at a time with locks
* Then, the second generation with CVS or SVN, where you had to merge before you commit.
* Then, finally, we had Mercurial/Bazaar/Git

But not everything in a project is code, we also need a way to communicate and to do project management. Those channels are :
* Mailing lists
* IRC
* Forums
* XMPP chatrooms
* Slack

We also use **bug tracker** to manage the project, it is a key to an healthy project : we need to have bug tracking conventions and **bug triagers** (people that classifies bug and report how to reproduce them).

We also need documentation or marketing using static websites or wiki (but wiki is bad, because no one maintains it).

It is important to take decisions about what to merge, what to develop (roadmap), the evolution of the project as a whole,...

Finally, there is the principle of **bicycle sheding** : when a group of people need to solve a difficult problem but some don't know how to go about it or feel not skilled enough, they end up talking about non-issues (like the color of a bicycle shed) for hours without making any progress in the real matter.

---
*Lecture 5*
#Why open source ?
When choosing a solution, there always is a few metrics :
* **Cost** : the *Total Cost of Ownership* (TCO) including hardware, salaries,... Very complex to calculate (nearly impossible in reality)
* **Meet the requirement**, meaning that we check the specifications. In reality, they can't cover everything, and most of the time not written by users.
* **Suport and maintainance**, where the real job begins, since it will take way longer than the devlopment. There is a really thin line between support and creating new features. Also, support needs to scale with the number of users.
* **Vision**, since software is now a continuous process, your customer needs the buy the vision of the future with your software (this might be the most important aspect of the sale)

This is the theoritical points. In reality, you deal with humains that will buy or not for unrationnal reasons (like the fact that you offered a pen).

What about Open Source ? What are the advantages ?
* The code source can be audited
* No licensing fee
* No vendor lock-in
* Allows you to take part in the community
* Transparent bug reporting and security update
* Open stadard or, at least, transparent implementation

Of course, it also has disadvantages :
* Sometimes hard to find professional support
* Usually harder to use
* Uncertainty about the future
* No clear responsability

Historically, open source software were not focused on UX. It is still frequent to have open source software with outdated UX or with tons of options in order to please everyone.

Also, the specifications may force Open Source, since you might one to be able to audit and modify the code.

---
Lecture 6
#Privacy and security

What is privacy ? Your position, phone number, messages, favorite sex fetish,... But it depends with whom you share it ! Most of us share our position with Google.

Why do we want to protect our privacy ? As soon as you *know* that someone is watching changes how you behave (you tend to follow more), you become a different person.

The **transitivity of privacy** means that once an information has been shared, you have to trust every informed person to protect your privacy. This means that any information transmitted to an untrustable party should be considered public.

*Streisand effect* trying to hide a public informations makes it more visible, attracting attention (from the picture of Baraba's Streisand house).

Also, why do people want to invade our privacies ? The first reason is to make you obey, either by coercion (surveillance) or by influencing you.

The impact of ads on your brain is worse than everyone ever thinked, it is purposedly designed to steal your attention.

Privacy is hard : there is no clear line, it depends on the context, on your trust,... Also, anonymisation is not privacy (military bases).

>Security is the set of actions that a community takes to ensure that its members respect the rules of the community.

It usually makes it harder to break the rule, but usually never impossible.

There is 3 pilars of security : moral (trough teaching and propaganda, you educate people so they don't break the rules), consequences, cost.

The feeling of security is different from true security, so it actually decrease the "real" security (military wearing war-tiers weapons that are not even loaded).

Should we make the world more secure ? It is actually really difficult, since we might want to be able to bend the rules from time to time. A solution might be the network of trust, we rely on trust in a carful way. The second solution is to rely on math, on cryptography (it is really hard, and should be done careful : *snake oil crypography*, "I ivented it and cannot break it, so it must be secure").

You need Open Source, because if not, you rely on security by obscurity.

Can we have both ? Decentralization with cryptography ? Yes, that's called Blockchain.

----
*Lecture 7*

### Is decentralisation a good thing ?
Yes, sometimes.

### Interoperability
Is good (duh). Writing is kind of an interoperability interface between human transcending time and space. It is good to be conservative in what you send, and open in what you receive. Interoperability sometimes occurs through reverse-engineering. It implies standardization, which is great, but usage is more important.

#### Standardization
There are multiple levels of standardization :
1. Active obfuscation
2. Closed source implementation (without obfuscation)
3. Documentation of the format
4. Documentation and open source reference implementation
5. A diverse group working to standardize the format
6. A recognized standard (e.g.: ISO)

There is *de-facto standards*, which are either non-standardised format or a bad implementation of an existing standard.

Also, we have to know that the best standrards does not always win, which mean we should not try to build the best possible one.

### Decentralization
A distributed system in which multiple authorities control multiples aspects of something, forming a system in which you don't have to trust a single authority to interact with the system. It's a permanently evolving consensus (which is called "protocol").

Why is it so hard ? Because you can't trust other members of the network, and you have to agree with them on the design.

You can break the decentralized network:
* Forking it (disagree)
* Pretend to agree but in fact disagree (bamboozled again)
* Respect the protocol but abuse the system (spam)

Benefits of decentralisation :
* Better resilience of the overal system (survivability)
* Privacy and security

Disadvantages of decentralization:
* Agreement on protocol changes
* Upgrading nodes of the network
* Spam
* Complexity (implementation)
* Complexity (UX)
* Social acceptance of problems
* Natural tendency to recentralise (everyone on the same instance)

Examples of decentrilised networks : Mail, XMPP, Mastodon, Diaspora

---
*Lecture 8*
# Open source in enterprise

## Use cases
1. Using open source software for non-product tasks
2. Using open source software in your product
3. Open sourcing an internal product
4. Open sourcing a released proprietary product
5. Developing an open source product

### Using for non-product tasks
When recommending an open source software, the first rule is that nobody will be fired for recommending Microsoft. Also, you have to know that you will be held responsible for the issues happening with your recommendation, and you're likely to become attached to it.

You have to ask youself two questions :
* Why should we use this tool ? -> Cost/benefit analysis, see the long term advantages, ask if ideology is important.

The consequences of choosing an open source product is the fear of contamination, the support and the adaptability. Change management will always be a big part of projects, and every change has a cost.

* How should I convince the others ? -> Be transparent with yourself and other about ideology or your own preferences, acknowledge whether the choice is rational or irrational.

To convince, pitch it to management, makes some experiments (sometimes hidding them) and recruit proponent. Follow the "don't ask for permission, ask for forgiveness", enlarging the project gradually when presenting it, making a point to say why it is interesting to take the risk to change.

### Using in your product
First, you have to clarify legal implications (contamination, publication). Then, you have to convince, like in the previous section. The convincing part should start with yourself, you have to be ready to hear new arguments and change your opinion.

Then, you have to choose between maintaining a private branch or contributing.

If you do a private branch, you'll have quick and dirty code, but you won't fear that it'll be stolen. You can try and link it with some proprietary code, but you'll have to be carful about the legality of that. Overall, it'll be a nightmare to mintain. Really.

If you choose to contribute, you'll have more upfront work, but virtually no maintenance. Also, you'll have good community karma, which is good to influence the project. But, if your use case is very specific, you *really* will have a lot upfront work.

The best case is to hire a contributor of the project, or to pay a employee to become an active contributor. It is also important to say thanks, either by making donation, becoming a sponsor, or hosting events for the project.

### Open sourcing an internal product
The advantages are that there is external contributions and potential collaboration, event with direct competitors, and again, good community karma.

The disadvantages are that maintaining a community is hard and time-consumming. Also, if you want to keep control, you should probably introduct dual-licensing (security by obscurity).

You should also think about the *bus factor* (the number of persons that could get hit by a bus before ruining your project). Most of the time, only a few people know the specifics of the project.

### Open sourcing a released proprietary product
This usually requires finding a new business model, because most open sourcing happen when there is no more money in the company.

Example : Netscape, StarOffice

### Developing an open source product
First thing : you don't have a good idea. You have to work on it, and then to execute it to have a business. Com up with a Minimum Viable Product, test it (even only on paper), try to sell it (even to yourself).

Build your pitch, your Business Model Canvas, and try.

---
*Lecture 9*
# Changing the world
TODO : read https://www.gnu.org/philosophy/right-to-read.html

Can open source change the world ? It has taught us governance, cooperation, freedom of knowledge, transparency, security, privacy and finally decentralisation.

It changes the businesses (imagine starting one without open source), changes our view on patents (see the Tesla policy).

We have created open science, and big companies like Google or Apple encourage open source (like Google summer of code). There is more care about privacy (mainly from Firefox).

It can change associations, change the political system. It could "save the internet" by re-decentralizing it (Tor, blockchain). Even create a new form of democracy (meritocracy, liquid democracy, where voters can always revoke or re-delegate).

---
*Lecture 10*
# Blockchain

Lemma 1 : merkle tree (tree with hashes of the two branches under, and text as the leaves).

Lemma 2 : intersubjective reality (religions, countries, money).

In fact, money (as our actual bills) has no "real" value, only the value we give it. Wich is why we could create virtual money (paypal or even bank accounts). Blockchain allows us to implement decentralized virtual money. [Note]: if it's not open source, it's not real blockchain because it can't be distributed.

Voluntary forks of those projects should be possible, but accidental ones should be avoided.

Byzantine generals problems (Reliable computer systems must handle malfunctioning components that give conflicting information to different parts of the system) and Sybil attacks (attack wherein a reputation system is subverted by forging identities in peer-to-peer networks).

We create the value with lemma 2, when people start to see value in a virtual currency, like with the bubbles of Bitcoin.

Note that cryptocurrency has its own blockchain (BTC, LTC, ETH,…) ERC20 is a standard smart-contract based on the Ethereum blockchain.

There is a vertical database problem : there is always a need for a human "translator". But blockchain is the first database to overcome that problem (becoming horizontal). It makes it transparent, accountable (private keys) and decentralized.

Examples : Namecoin, ZeroNet, Ethereum and smart contracts, supply chain, project management, identity, democracy,...

Bitcoin's blockchain is the bllions dolloars bounty, but a complex equilibrium of developers, nodes (users), miners and businesses.

We all know that mining consumes a lot of energy, so is this an ecological disaster ? Maybe not (currently an experiment), because most of the electricity comes from wasted sources, and it might change the dynamic of the power market.