---
title:  "Digital archives, a vision."
date:   2015-11-17 16:29:00
description: Technology Design
---

# Digital archives, a vision.

I was recently asked to write a vision piece on the future of archives. Yes, Creative Directors can know about technology too. We're not just good at colour and type. Some of us aren't at all good at colour and type. Anyway, this is the vision I came up with. It pissed off the archivists. I see this as a job well done.


**Introduction**.

Archives provide a foundation upon which our societies build.

A new idea, one created from nothing, is an illusion. The greatest discoveries our species have made, these celebrated moments, are theatre. Easy to understand dramas for all of us who don’t specialise in that specific subject.

The discovery of the Higgs Boson didn’t happen in an instant.

The realisation that hanging brick walls from a central metal structure would allow us to build higher was not found in a flash of inspiration.

Even mundane discoveries, PVC chairs, were built from discoveries, which built from discoveries, which built from discoveries…

The preservation and sharing of ideas and knowledge has allowed us to move from living on great plains to living in great cities. As we have changed our behaviour from paranoid, closed, and tightly controlled to willing, open, and loosely coupled our shared knowledge has pushed our collective achievements further than anyone could have imagined.

Without the discoveries of previous generations we have nothing to stand upon, and no place to start. Our archives, our libraries, our collective knowledge is our bedrock. The foundation of everything we do, every direction we take, and every success we have.

**Tribes**.

Preserving and passing on knowledge is a tribal behaviour, and each tribe has it’s own methods.

Songs, art, chants, dance, etc.

They are all ways to tell a story.

To preserve an essence.

Stories are powerful things. They have allowed us to keep safe the spirit of our cultures through hundreds of decades of rapid change. The original facts may be lost, but the essence carries on. Its impact is the same.

Unlike a physical object which carries a large amount of it’s meaning with it, digital data has none. The way it looks, feels, sounds, and reacts is all brought about not by the data itself but by whatever is representing it.

Data lives a vicarious life, experiencing the world through image viewers, audio players, text parsing applications, and a myriad of communication protocols. Without these layers the data is a useless string of zeros and ones. And so they too must be preserved, along with the links between them and their target files, and any additional dependencies they have.

Preservation is the outcome of a series of decisions you take starting from now. It is not an achievable goal in it’s own right.

The safer you want your content to be the more layers of preservation are required. As time and technologies pass, the number and complexity of layers grows, and the abstraction increases. An IFF file from 1991 is no longer supported on any available operating system. To access it you must emulate a hardware stack, upon which you can emulate an operating system, at which point you can access the image file. To preserve this file in it’s original state beyond the next decade will require you to either rewrite your hardware and software virtualisation tools, or add an additional layer of virtualisation on top.

The songs become more complicated, require more people to sing the additional parts, and introduce more potential for error.

**The digital archive**.

As far as I can tell, digital archives share only one thing in common with analogue archives. They exist to preserve, as best they can, the knowledge they contain and to share that knowledge as widely as possible.

Aside from this they are entirely different.

The content type the archive is preserving is different. The methods of access to that content are different. The capabilities to share that content is different. And the skills required to design, build, and operate a digital archive is different.

A digital archive cannot, in the strictest meaning of the word, 'preserve'. By it’s very nature the act of accessing or migrating digital data changes it. And as long as these changes are not malicious, this is acceptable.

A digital archive cannot live in one place. It can’t have a set of servers in a room to live on. It can’t be restricted to one database technology. It can’t be restricted to one operating system type. It must be able to live everywhere, as everywhere is where you’ll find useful and relevant data.

And finally a digital archive must be open. Open software, open protocols, open virtualisation, open normalisation algorithms, and with access open to all.


**A new approach to digital archives**.

If there is one lesson I have learned from my almost 20 years in digital is that things change fast. And the speed of that change is increasing exponentially. No matter how much we plan for the future we have to accept that it is only our current best guess, and given enough time it will be wrong.

My current best guess for the future of digital archives originates from looking at existing systems that already perform well in many of the areas any new platform must. Ironically the hackers and pirates of the digital world have provided us a great model to start the discussion - The Onion Router, Torrents, and Parity Files.

These systems work by spreading data across multiple places (including transmission protocols) with replicas of the data held in thousands of places. Each of these places, or repositories, is housed on an individual’s computer or smart phone. Different operating systems, different hardware, different storage methods, different network access capabilities, and yet they all communicate and share data seamlessly. Each repository is protected, each transmission is encrypted (with unique encryption keys per user), and the job of protecting the data from damage is given to the group, not to an individual system.

Whilst this approach will be unlikely to provide all the answers it provides a great starting point. Petabytes of data, housed across millions of secured repositories, curated by specialists with insight from the group, and protected from malicious damage by the very protocols that perform the transmission. It gives, at the very least, a new direction to consider.

Archives must be built adapt. To cope with the technical, social, legal, and economic changes that will happen during it’s lifetime.

Ownership of digital materials is a controversial and much debated subject. National and international laws have been, and continue to be, created in an attempt to protect access rights, and so technologies have to be invented to support these laws. The subject of whether DRM encryption should be included in an archived audio file is very interesting, but out of scope of this document. However a digital archive needs to be able to adapt to changes in law, encryption, and rights holder’s wishes.

<next page/>

Build in layers and modules, not in one large lump.

If you build an archive today, some part of that archive will need to be replaced (and archived?) within the next 5-10 years. If you build your new platform from layers and modules you’ll only have to replace a part, not the whole.

Building in modules allows you to add capability over time, to focus on each capability as you build it, and to scale your infrastructure gradually. Each part can be built on the most appropriate technology, by the best technology provider for that part. And as new technologies are created they can be incorporated into the system as a new module, rather than re-architecting everything.

<next page/>

Define a schema for your modules from the outset.

Modular systems can grow in complexity very quickly, and so it is essential to define the sets of schemas and protocols that will pass data between them before any development begins in earnest. Decide upon and document the relationships between, the capabilities of, and the dependencies of each module.

As it is likely that any new archiving platform will be adopted by a wide variety of organisations and institutions, who will each have specific and possibly complex requirements, the base set of capabilities and dependencies should be kept as simple as possible.

<new page/>

Build your system to be technology agnostic. It should be capable of running on any hardware, on any operating system. The more open you make it, the less chance of failure you have and the wider the adoption will be.

<new page/>

Accept that your new system will never be finished. Legal, social, and technological changes will require any new system to be capable of fast and sometimes radical change. The more open you build it, the more capable of change it is, the less likely it is to require a rebuild and migration in the near future.

<new page/>

Build in layers.

Modules allow the distinct capabilities of the system to live alone, with no dependencies upon each other. Layers allow the broader requirements of the system to be separated, creating a more flexible and easily modified stack.

Our assumption is that the four main layers of a digital archive are the repositories, a secure access layer, the catalogues, and the end user access layer.

**Repositories**.
The repositories are where you keep your stuff. They can be built in any type of database technology. They can be big or small. They can store anything, or specialise in specific formats. And they can be owned by you or third parties. They can be encrypted, or not, and can make use of any available additional security.

The open and flexible nature of the repository types described here is a requirement of any digital archive which is built to adapt to the future. We don’t know what’s coming, what will be deprecated, and what new technologies we’ll have to work with. And so we must design for a repository layer which is incredibly diverse.

Repositories are not linked directly, and do not know of each other’s existence. If one is removed nothing breaks, if another is added the same zero impact outcome is achieved. Repositories can be backed up entirely, or in chunks. Back ups can be static, dynamic, or even other repositories.

Some repositories will be owned and maintained by The National Archives, others by local government bodies, and yet others by public institutions. However with the model we would test repositories that contribute to the archive can be owned by anyone.

Each repository however will need to, either directly or via associated data, store a unique identifier with each discreet piece of data. Other than this no additional data need be stored, such as meta data, in the repository itself.

And finally the repository should be the least capable layer of the system, as it is the most likely layer to be attacked. Securing systems gets you only so far, but remove the ability for a system to destroy itself and an attack can only go so far.

**Secure Access Layer**

The Secure Access Layer, or SAL, provides a translation and brokerage service between the collections and the repositories. It is this layer that requests for repository access are made and managed through.

The SAL works by taking a requests, checking the authenticity of the request, and if that authenticity is correct returning the requested data to or from the repository. It also acts to translate the returned data from bits to a human readable format - audio files, image files, plain text etc. Where the returned result is a richer data set, say an executable file that requires virtualisation, the SAL will return the required stack as a package.

The SAL works as a barrier to unauthorised access to secured data. An example would be data which is archived but not available for public release for N years.

The SAL is the most capable layer in the stack.

**The Collections**.

A collection is simply a set of addresses for data within a repository, and the associated metadata, grouped by theme, subject, or other grouping. It is concerned not with data storage, but with information about the digital objects (be they photos, emails, movies, virtual machines, etc). The collection keeps metadata which describes these objects (what, who, when, where, why) and is the layer where access rights are governed - what can be accessed by whom, how it can be accessed, and for what purpose.

A collection is where judgement about the importance and relevance of a file happens.*

A collection can point to multiple SALs, and an SAL can be accessed by multiple collections. Collections can cache and store copies if given permission.**

The collection is where pre-ingest archival information packages and dissemination information packages are created, and is also the point of ingest. During ingest the collection will store key decisions about how the data is to be stored, how it will be normalised, emulated, migrated, etc.

*Judgement can happen at the individual level (the archivist responsible) or at the group level (through cluster analysis of the ontological links). It is therefore possible, and sensible, that collections can be automatically created and machine curated.

**Permissions and content governance is beyond the scope of this document, but we have spent many an evening having heated discussions about it with multiple digital archivists.

**End User Access Layer**.
The End User Access Layer, or EUAL, is where people access content. These can be secured websites, mobile apps, social media, broadcast radio or television, galleries. Anywhere, using any method, can be considered an EUAL.

The EUAL is authorised to access data from the collection, the collection is authorised access via the SAL.

<new page/>

Linked data and ontologies.

There is one potential additional layer which provides an overarching ontological understanding of the data held in every repository.

This layer, which sits above the SAL, uses the meta data from each collection along to build a dynamic taxonomy of terms used across the entire archive. These terms are not defined by any individual or predetermined group, but by every user of every collection who has the ability to enter meta data.

This layer would also collect the usage analytics from collections, and perform cluster analysis, to determine what end users believe are the most important and relevant relationships between various parts of data, across the entire archive.

By comparing the relationships defined by your users and the taxonomy defined by your collection editors, this layer builds a true ontological understanding of the data within the archive whilst simultaneously containing the context of each piece of data.

It is from these deep links between data that the richer essence is maintained. And as it is derived from social rules it is more relevant for the majority of users. It is opinionated, but open to change, and driven by the group not the individual archivist.

This additional layer provides one answer to the question “What should be keep?”. This layer suggests you keep everything, as one individual cannot say when any item will become relevant again. However the group can, and will, and this ontological layer will capture it.

<new page/>

The National Archives exist in part to promote best practice. To be the exemplars. To provide support. To show the way.

Digital preservation is a fascinating, tough, complex, wonderful mess of a problem. We hope we have shown that we understand the challenges, that we have experience in trying to answer some of the questions, and more importantly that the potential to play our small part in the future of this most exciting projects is one that excites us to a point we can’t express in words.






