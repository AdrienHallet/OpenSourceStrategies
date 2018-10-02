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

### Copyleft
It's a copyright that says that you can do whatever you want if you redistribute it with the same license.

### AGPL (Affero GPL)
Made for web applications. Needed because the webserver that runs the code is not possessed by the user. It says that every user that wants it can request the source code.

### MIT
No copyleft, do what you want as long as we are not responsible for what you do with the code

### BSD
A bit like MIT

### Mozilla Public License
Mozilla created their own license to customize their needs.

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

Trilicensing also exists

### GPL2 vs GPL3
The third version prevents the 'tivoisation' to force makers to let people do whatever they want on the code.


---
*Lecture 3*

## Business models
Business models need to be flexible, never stick to the initial idea. We need to change the business model to adapt the situation. There is always a customer. Even when the app is free (ads) or public (administration).

## The Metrix paradox
As soon as you realize a causation between a cause and effect, you'll have a tendency to maximize your profit (example of the cars, ...)

## Earn money with free softwares
* Integration and consultancing
* Consortium standardization
* Donation
* Proprietary features
* Services around the app (e.g.. odoo)
* Ads (sponsorship/...)
* Goodies
