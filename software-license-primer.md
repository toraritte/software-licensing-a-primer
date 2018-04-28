Free and open source software
---------------------------------

The usage of the word "free" is misleading because it both means "freedom" and "zero price". The problem is that English, unlike other languages, does not have a common adjective that unambiguously refers to freedom. French for example has "libre" for "freedom" and "gratuit" for "free of charge".[@https://www.gnu.org/philosophy/categories.en.html]

In this context, the intended meaning was "freedom", as in "freedom of users".

### 2.3.1 Brief history

#### 1970s

Computers are built from scratch by research organizations and custom software has to be written to operate them. "Software was not yet standardized and was not considered to be a monetizable product."[@roads-and-bridges]

#### 1981[@roads-and-bridges]

IBM introduces the "IBM PC" or "Personal Computer". Industry adoption is high, winnowing out the competition and capturing half of the market share by 1986.[@23inroadsandbridges]

Standardized hardware brought along the opportunity to standardize software. IBM hires Microsoft to write the operating system for their PC and they deliver MS-DOS in the same year. Other companies follow suit.

Turning software into business proves lucrative, resulting in commercial licenses promoting the creation of proprietary products, preventing users from copying, modifying or redistributing software.

#### 1983

Concern rises among computer scientists "_about the closed and proprietary direction that software was taking_".[@roads-and-bridges] As a response, Richard Stallman launches GNU, a free operating system, also inadvertently laying the foundation for the "free software movement".[@https://www.gnu.org/gnu/initial-announcement.html]

#### 1985

Stallman founds the Free Software Foundation to support the objectives of the "free software movement".[@https://www.gnu.org/gnu/manifesto.html]

#### 1992

The growth of the World Wide Web gains momentum and becomes more widely available.

#### 1996

The commercialization of the web begins with great success and huge gains.

#### 1998

In a move unprecented at the time from a software company, Netscape releases the source code of its high market-share web browser. This event becomes the catalyst to a group of technologists, who have been advocating a more pragmatic approach to the Free Software Foundation's principles, to create the Open Source Initiative. The new organization's focus is to promulgate "_the practical benefits of free software_"[@roads-and-bridges] without "_the ideological and confrontational connotations of the term_"[@https://en.wikipedia.org/wiki/Open-source_software_movement]

### 2.3.2 Open source versus free software

#### 2.3.2.1 Common ground

Both **free[^footnote-word_free] software** and **open source software** do roughly mean the same:

  * According to the Free Software Foundation's summary, it means that "_users have the freedom to run, copy, distribute, study, change and improve the software_"[@https://www.gnu.org/philosophy/free-sw.en.html].

  * The Open Source Initiative defines it as "_software that can be freely accessed, used, changed, and shared (in modified or unmodified form) by anyone. Open source software is made by many people, and distributed under licenses that comply with the [Open Source Definition](https://opensource.org/osd-annotated)._"[@https://opensource.org/faq#osd]

See [Glossary](#glossary) for their formal definitions.

#### 2.3.2.2 Differences

"_Open source is a development methodology; free software is a social movement._"[@https://www.gnu.org/philosophy/open-source-misses-the-point.en.html] Although often discussed together, they are politically distinct: "free software" being more closely associated with ethics ("_essential respect for the users' freedom"[@https://www.gnu.org/philosophy/open-source-misses-the-point.en.html]) and "open source" with pragmatism (i.e., a practical, business-case approach to free software[@https://opensource.org/history]).

The groups' relationship between free and proprietary software is one of the most defining difference:

  * Members of the open source community are willing to coexist with the makers of proprietary software[@https://en.wikipedia.org/wiki/Open-source_software_movement,@https://opensource.org/faq#permissive] and feel that the issue of whether software is open source is a matter of practicality[@https://opensource.org/history]. One example is [tivoization](https://en.wikipedia.org/wiki/Tivoization).

  * In contrast, members of the free software community maintain the vision that all software is a part of freedom of speech and that proprietary software is unethical and unjust[@https://www.gnu.org/philosophy/open-source-misses-the-point.en.html,@https://www.gnu.org/proprietary/proprietary.en.html,@https://www.gnu.org/proprietary/proprietary-surveillance.en.html,@https://www.gnu.org/proprietary/proprietary-back-doors.en.html].

This differentiation is best reflected by the software licenses used: the open source community allows the use of licenses that permit developing proprietary (i.e., closed sourced) software. This is unacceptable to proponents of free software.

Therefore, on the practical side, every existing free software would qualify as open source because the Open Source Initiative allows the more restrictive (or permissive, depending on the perspective) free software licenses but not vice versa.

### 2.3.3 Introduction to licenses

#### Why software licenses are necessary

"_Licenses are important tools for setting specific terms on which software may be used, modified, or distributed_" and they "_can be used to facilitate access to software as well as restrict it_".[@https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3406002/] Because the legal default for original works is exclusive copyright, potential users may become discouraged to use a specific piece of code without a license to avoid future litigations as they do not know which limitations owners may want to enforce.[@https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3406002/] 

Open collaboration also requires legal ground rules to be layed down because "_without a license, everybody who contributes to the project also becomes an exclusive copyright holder of their work. That means nobody can use, copy, distribute, or modify their contributions – and that “nobody” includes the author as well._"[@github.com/github/opensource.guide]

Copyright holders therefore set formal permissions in the form of licenses, especially if they expect their code to be reused.

#### 2.3.3.1 Copyright

Copyright grants the creator of an original work exclusive but limited rights[^footnote-copyright_limits] for its use and distribution[@https://en.wikipedia.org/wiki/Copyright;@http://www.etymonline.com/word/copyright;@https://opensource.com/resources/what-is-copyleft] by default under the Berne Convention[@https://en.wikipedia.org/wiki/Berne_Convention;@https://en.wikipedia.org/wiki/Berne_Convention_Implementation_Act_of_1988]. Authors therefore have complete authority and they have to provide explicitly permit any actions that would involve the use of their work.

[^footnote-copyright_limits]: "_Copyright law does not protect the titles of books or movies, nor does it protect short phrases such as, “Make my day.” Copyright protection also doesn’t cover facts, ideas, or theories. These things are free for all to use without authorization._"[@https://fairuse.stanford.edu/overview/public-domain/welcome/]

#### 2.3.3.0 Public domain software

Some developers reject the necessity of software licenses altogether and therefore do not use licenses[@https://en.wikipedia.org/wiki/License-free_software] or put their work explicitly in the public domain[@http://cr.yp.to/distributors.html].

License-free software are usually avoided because it is not explicitly in the public domain and the absence of a license makes the software fully copyright protected according to the Berne convention.

Dedicating software to the public domain is somewhat better received. Works in the public domain are creative material that are not protected by copyright, trademark or patent laws and can be modified, distributed, or sold even without any attribution by anyone.[@https://en.wikipedia.org/wiki/Public-domain_software;@https://en.wikipedia.org/wiki/Public_domain;@https://fairuse.stanford.edu/overview/public-domain/welcome/] Legal ambiguities still exist however, especially when it comes to software, such as:

  * What is the legally accepted way to place software in the public domain?

    There are four common ways for works to end up in the public domain: the copyright has expired, forfeited, waived or inapplicable.[@https://en.wikipedia.org/wiki/Public_domain;@https://fairuse.stanford.edu/overview/public-domain/welcome/]

    Abandoning the copyright is the most pertinent in this case and there is a debate about what methods are legally accepted[@https://lists.opensource.org/pipermail/license-review/2012-March/001679.html;@http://cr.yp.to/distributors.html] or whether it can be done at all[^footnote-abandon_copyright].

[^footnote-abandon_copyright]: There is legal precedent to it, at least by the US Ninth Circuit: "_Abandonment of such rights, however, must be manifested by some overt act indicative of a purpose to surrender the rights and allow the public to copy._"[@1960hampton]

  * How can public domain software be re-used in proprietary software?

    Modifications to a public domain work may be protected by copyright[@https://fairuse.stanford.edu/overview/public-domain/trouble-spots/] if the modification is non-trivial (i.e., meets the applicable laws' originality and creativity requirements)[@https://copyleft.org/guide/comprehensive-gpl-guidech2.html#x5-50001.1;@http://www.publicdomainsherpa.com/10-misconceptions-about-the-public-domain.html#five] and this could be interpreted that only the modification itself can copyrighted[@http://www.publicdomainsherpa.com/10-misconceptions-about-the-public-domain.html#five].

    The meaning of "public domain" also depends on jurisdiction[@https://www.quora.com/When-you-create-a-proprietary-software-after-using-quite-a-few-open-source-software-projects-as-a-starting-point-how-is-this-legal;@https://en.wikipedia.org/wiki/Public_domain] and licenses are necessary that emulate the public domain, such as CC0[@https://wiki.creativecommons.org/wiki/CC0], Unilicense[@http://unlicense.org/] or WTFPL[@http://www.wtfpl.net/].

#### 2.3.3.0 Copyleft

The most exhaustive resource on this topic is the continuously updated Copyleft and the GNU General Public License: A Comprehensive Tutorial and Guide[@https://copyleft.org/guide/] but the following sections try to give a quick summary.

##### 2.3.3.0.1 History and rationale

Since the emergence of computer science, developing and sharing programs was entirely in the public domain, mostly in academia and software was not copyrightable.

In 1974, the US Commission on New Technological Uses of Copyrighted Works (CONTU) decided that "_computer programs, to the extent that they embody an author's original creation, are proper subject matter of copyright_"[@http://www.digital-law-online.info/CONTU/].

The Copyright Act of 1976[@https://www.law.cornell.edu/uscode/text/17/117] (and following legal precedents, such as Apple v. Franklin[@https://openjurist.org/714/f2d/1240/apple-computer-inc-v-franklin-computer-corporation]) "_clarified that the Copyright Act gave computer programs the copyright status of literary works_"[@https://en.wikipedia.org/wiki/Public-domain_software].

The Berne Convention Implementation Act of 1988 puts any original creative works under copyright after creation by default.

The legislation gave rise to the development of proprietary software and helped it become a lucrative business opportunity from the early 1980s, causing the decline of the academic public domain software ecosystem[@https://en.wikipedia.org/wiki/History_of_Unix].

Richard Stallman, himself an academic and alarmed by the growing trend, founds the GNU Project, and with that, the free software movement. He writes the first version of GNU General Public License in 1989 as a response, to encode public domain rights on software, relying "_on the enforceability of the copyright to be effective_"[@https://en.wikipedia.org/wiki/Public-domain_software].

##### 2.3.3.0.2 What is copyleft?

Also referred to as *reciprocal* or *protective* licensing. The derogatory adjectives "viral" or "infectious" are also used[@https://en.wikipedia.org/wiki/Viral_license]. (See [Controversies]).

It is a form of licensing that retains the author's exclusive copyrights for works but gives permission to recipients of the work to reproduce, change or distribute it, with the accompanying requirement that any resulting copies or adaptations are also bound by the same licensing agreement. "_In essence, copyleft grants freedom, but forbids others to forbid that freedom to anyone else along the distribution and modification chains._"[@https://copyleft.org/guide].(Hence the term "reciprocal".)

Copyleft software intentionally shares properties with public domain software and by requiring the same copyleft license downstream is an attempt to close one of its loopholes: "_any nontrivial modification made to the [public domain] work is fully copyrightable_", ergo "_over time, some entities will choose to proprietarize their modified versions_" with little "_incentive to contribute back to the commons_", until "_almost no interesting work is left in the public domain, because nearly all new work is done by proprietarization._"[@https://copyleft.org/guide].

"_Copyleft uses functional parts of the copyright system to achieve an unusual result (legal protection for free sharing)_"[@https://copyleft.org/guide/]: it modifies copyright law, which is usually employed to strengthen the rights of authors or publishers by prohibiting "_recipients from reproducing, adapting, or distributing copies of their work_"[@https://en.wikipedia.org/wiki/Copyleft], to strengthen instead the rights of users. This reversal is reflected in its name as a wordplay on "copyright".

The stipulation that the "_information necessary for reproducing and modifying the work must be made available to recipients of the binaries_"[@https://en.wikipedia.org/wiki/Copyleft] (i.e., source code) is added to prevent the creation of proprietary products[@https://www.gnu.org/copyleft/copyleft.html] and it is probably the most notable difference to public domain software because "_an executable program can be in the public domain but the source code is not available_"[@https://www.gnu.org/philosophy/categories.en.html].

The idea of copyleft can be also applied to works that are not software. These licenses are usually called share-alike (see Creative Commons[@https://creativecommons.org/].

##### 2.3.3.0.3 Types

###### Strong and weak copyleft

"_“Strong vs. weak” copyleft is not a dichotomy, it’s a spectrum._"[@https://copyleft.org/guide/] "_The strength of the copyleft governing a work is an expression of the extent that the copyleft provisions can be efficiently imposed on all kinds of derived[sic] works._"[@https://en.wikipedia.org/wiki/Copyleft]

The stronger the license, the more it will seek to ensure that the same license will cover every version of derivative works, making them subject to its requirements.[@https://copyleft.org/guide/] Practically this means that the corresponding source code has to be made available to licensees. The ideological goal is to ensure the propagations of the software freedoms for each user.

Usually larger end user programs, which cannot be used further as a component, opt in using such licenses to prevent turning them into proprietary products.[^footnote-strong_copyleft_abuse] The versions of the GNU General Public License (GNU GPL) are the most commonly cited examples for strong copyleft.

[^footnote-strong_copyleft_abuse]: This is not a rule though and strong copyleft licenses are known to be abused by the industry. See [Controversies].

GNU GPL version 3 with its system library exception is cited (see 9.3.3 in [@https://copyleft.org/guide/]) as an example to prove that the strength of a license is indeed a spectrum.

As the "copyleft" gets weaker, the license starts to introduce "trade offs" such as allowing cases of derivative works that are permitted to use another license and/or keeping parts of the source closed in order to foster wider adoption but still try to hold on to most of copyleft's principles.[@https://en.wikipedia.org/wiki/Copyleft;@https://copyleft.org/guide/]

The most well-known example for this seemingly counter-intuitive rationale is the history of the GNU Lesser General Public License (GNU LGPL) and "glibc", the GNU project's implementation of the C standard library. It was created to provide a common alternative to the world of proliferating proprietary implementations that had limited functionality, sometimes specific only to certain vendors. If it had used a stronger license (such as the GPL), any software created with it would have to be shipped with the same license, thus providing their source code would have been necessary to avoid violation of the license's terms. "_The de-facto standard for the C library on GNU/Linux would likely be not glibc_"[@https://copyleft.org/guide/], a free software, but probably the most popular proprietary one that allows developers to create proprietary software.

There are multiple ways to purposely weaken copyleft restrictions:

  * "The LGPL distinguishes between two classes of works: “works based on the library,” and “works that use the library” and it is generally used for the creation of software libraries.[^footnote-lgpl_terms]

  * The Mozilla Public License version 2.0 (MPL v2.0) is using a "file-level" copyleft instead[@https://www.mozilla.org/en-US/MPL/2.0/FAQ/] that "_treats the source code file as the boundary between MPL-licensed and proprietary parts, meaning that all or none of the code in a given source file falls under the MPL._"[@https://en.wikipedia.org/wiki/Mozilla_Public_License] It also allows sublicensing[@https://softwareengineering.stackexchange.com/questions/189633/what-sublicense-actually-means][^footnote-mpl_extra]

[^footnote-lgpl_terms]: The quoted terms are specific to LGPLv2 and has been superseded by LGPLv3. See Chapters 10 and 11 in [@https://copyleft.org/guide/].

[^footnote-mpl_extra]: Extra resources on when choosing MPL v2.0 could be beneficial to a project are [@https://christoph-conrads.name/why-i-chose-the-mozilla-public-license-2-0/;@https://julien.ponge.org/blog/mozilla-public-license-v2-a-good-middleground/].

###### Full and partial copyleft

TODO links!
This classification is used by some sources but there is no authoritative source for their definitions by any of the well-established entities (for example, organization such as the Free Software Foundation, Open Source Initiative, Mozilla Foundation, or licensing websites such as choosealicense.com, TLDR-legal).
References
==========

