<div id="disclaimer">
**Disclaimer**: The materials available at this web site are for informational purposes only and not for the purpose of providing legal advice. You should contact your attorney to obtain advice with respect to any particular issue or problem.
</div>

<div id="rationale">
### Rationale for yet another write-up

There are many good resources, but most assume some basic familiarity with the topic and/or legal terms. I started out with reading the [Understanding Open Source and Free Software Licensing](http://www.oreilly.com/openbook/osfreesoft/) by Andrew M. St. Laurent (which is freely available by courtesy of O'Reilly's [Open Books Project](http://www.oreilly.com/openbook/)), and ended up with, at one point, ca. 120 open browser tabs. 

If you find any inaccuracies or typos, feel that parts are opinionated, biased even, or have suggestions for improvement, please feel free to [contact me](https://github.com/toraritte), [add an issue](https://github.com/toraritte/software-licensing-primer/issues/new) or create a pull request.

Please also feel free to browse the [issues](https://github.com/toraritte/software-licensing-primer/issues) and submit a pull request, but make sure that you agree with putting your contribution(s) in the public domain (see license below) by adding your name to the list of authors.

### Authors

[Attila Gulyas](https://github.com/toraritte), 

### License

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://toraritte.github.io/software-licensing-a-primer#authors">
    <span property="dct:title">authors</span></a>
  have waived all copyright and related or neighboring rights to
  <span property="dct:title"> Software Licensing - A Primer</span>.
</p>
</div>

## 1 Types of legal relationships between software authors and their works

<div class="footnote">
###### Intellectual property

The initial title has been "Approaches to intellectual property", but as it turns out, "_the term "intellectual property" is widely accepted and used by lawyers, the term also has a fascinating and controversial history_"[@eff-ip]. As Richard M. Stallman puts it, "_it has become fashionable to toss copyright, patents, and trademarks — three separate and different entities involving three separate and different sets of laws — plus a dozen other laws into one pot and call it “intellectual property”._"[@fsf-ip]

Interestingly, the [United States Copyright Office](https://www.copyright.gov) barely mentions the term, even in their [circulars](https://www.copyright.gov/circs/).
</div>

### 1.1 Why software licenses are necessary

"_Licenses are important tools for setting specific terms on which software may be used, modified, or distributed_", and they "_can be used to facilitate access to software as well as restrict it_".[@sci-programmer] Because the legal default for original works is exclusive copyright, potential users may become discouraged to use a specific piece of code without a license to avoid future litigations as they do not know which limitations owners may want to enforce.[@sci-programmer] 

Open collaboration also requires legal ground rules to be layed down because "_without a license, everybody who contributes to the project also becomes an exclusive copyright holder of their work. That means nobody can use, copy, distribute, or modify their contributions – and that “nobody” includes the author as well._"[@osg]

Copyright holders therefore set formal permissions in the form of licenses, especially if they expect their code to be reused.

### 1.2 Copyright

Copyright grants the creator of an original work exclusive, but limited rights for its use and distribution[@wiki-copyright;@oed-copyright;@cotton-copyleft] by default under the Berne Convention[@wiki-berne;@wiki-berne1886]. Authors therefore have complete authority and they have to explicitly permit any actions that would involve the use of their work.

The United States Copyright Office defines copyright as "_a form of protection provided by the laws of the United Statesto the authors of “original works of authorship” that are fixed in a tangible form of expression. An original work of authorship is a work that is independently created by a human author and possesses at least some minimal degree of creativity. A work is “fixed” when it is captured (either by or under the authority of an author) in a sufficiently permanent medium such that the work can be perceived, reproduced, or communicated for more than a short time.  Copyright protection in the United States exists automatically from the moment the original work of authorship is fixed._"[@usco-copyright] They quickly add in their [Copyright Basics](https://www.copyright.gov/circs/circ01.pdf) circular that "_the authoritative
source for U.S. copyright law is the Copyright Act, codified in Title 17 of the United States Code_"[@usco-copyright], available to download [from their website](https://www.copyright.gov/title17/).

As noted above, the rights provided by copyright are limited as it "_does not protect the titles of books or movies, nor does it protect short phrases such as, “Make my day.” Copyright protection also doesn’t cover facts, ideas, or theories. These things are free for all to use without authorization._"[@public-domain-stim] See the United States Copyright Office's [Works Not Protected by Copyright](https://www.copyright.gov/circs/circ33.pdf) for a full treatment on the topic.[@usco-copyright;@usco-limits]

### 1.3 License-free software

Some developers reject the necessity of software licenses altogether and therefore do not use licenses[@license-free] (or they explicitly put their works in the public domain[@put-public]).

License-free software is usually avoided because it is not explicitly in the public domain and the absence of a license makes the software fully copyright-protected according to the Berne Convention.

### 1.4 Public domain software

Works in the public domain are creative material that are not protected by copyright, trademark or patent laws and can be modified, distributed, or sold even without any attribution by anyone.[@wiki-pub-domain-sw;@wiki-pub-domain;@public-domain-stim] Legal ambiguities still exist however, especially when it comes to software, such as:

  * **What is the legally accepted way to place software in the public domain?**

    There are four common ways for works to end up in the public domain: the copyright has expired, forfeited, waived or inapplicable.[@wiki-pub-domain;@public-domain-stim]

    Abandoning the copyright is the most pertinent in this case and there is a debate about what methods are legally accepted[@put-public] or whether it can be done at all[@@cc0-rosen]. A notable legal precedent exists however, but the US Ninth Circuit states in their ruling that "_abandonment of such rights, however, must be manifested by some overt act indicative of a purpose to surrender the rights and allow the public to copy._"[@1960hampton]

  * **How can public domain software be re-used in proprietary software?**

    Modifications to a public domain work may be protected by copyright[@public-domain-stim] if the modification is non-trivial (i.e., meets the applicable laws' originality and creativity requirements) and this could be interpreted that only the modification itself can be copyrighted.[[@copyleft-guide] - [1.2.1 Public Domain Software](https://copyleft.org/guide/comprehensive-gpl-guidech2.html#x5-110001.2.1)][[@pd-sherpa] - [Item 5](http://www.publicdomainsherpa.com/10-misconceptions-about-the-public-domain.html#five)]

    The meaning of "public domain" also depends on jurisdiction[@quora-os-legal;@wiki-pub-domain] and licenses are necessary that emulate the public domain, such as CC0[@cc0], Unlicense[@unlicense] or WTFPL[@wtfpl].

### 1.5 Copyleft

The most exhaustive resource on this topic is the continuously updated _Copyleft and the GNU General Public License: A Comprehensive Tutorial and Guide_[@copyleft-guide], but I found that knowing the historical background helps understanding the rationale behind it.

#### 1.5.1 Historical background

Since the emergence of computer science, developing and sharing programs was entirely in the public domain, mostly in academia and software was not copyrightable.

In the 1970s, computers have been built from scratch by research organizations and custom software had to be written to operate them. "_Software was not yet standardized and was not considered to be a monetizable product._"[@roads-and-bridges]

In 1974, the US Commission on New Technological Uses of Copyrighted Works (CONTU) decided that "_computer programs, to the extent that they embody an author's original creation, are proper subject matter of copyright_"[@contu].

The Copyright Act of 1976[@copyright1976] (and following legal precedents, such as Apple v. Franklin[@apple-franklin]) "_clarified that the Copyright Act gave computer programs the copyright status of literary works_"[@wiki-pub-domain-sw].

In 1981, IBM introduced the "IBM PC" or "Personal Computer". Industry adoption was high, winnowing out the competition and capturing half of the market share by 1986.[@from-altair-to-ipad] Standardized hardware brought along the opportunity to standardize software. IBM hired Microsoft to write the operating system for their PC and they deliver MS-DOS in the same year. Other companies follow suit to create their own versions.

The legislation gave rise to the development of proprietary software, helping it to become a lucrative business opportunity. It resulted in commercial licenses promoting the creation of proprietary products, preventing users from copying, modifying or redistributing software, causing the decline of the academic public domain software ecosystem.[@unix-history;@roads-and-bridges]

By 1983, concern started rising among computer scientists "_about the closed and proprietary direction that software was taking_"[@roads-and-bridges]. As a response, Richard Stallman, himself an academic and alarmed by the growing trend, launched the GNU Project, a free operating system, also inadvertently laying the foundation for the "free software movement".[@gnu-initial]

In 1985, Stallman founded the Free Software Foundation to support the objectives of the "free software movement".[@gnu-initial]

The Berne Convention Implementation Act of 1988[@wiki-berne;@wiki-berne1886] puts any original creative works under copyright after creation by default.

As a response, Richard Stallman wrote the first version of GNU General Public License (the first and most widely known copyleft license) in 1989, to encode public domain rights on software, relying "_on the enforceability of the copyright to be effective_"[@wiki-pub-domain-sw].

#### 1.5.2 What is copyleft?

Also referred to as _reciprocal_ or _protective_ licensing. The derogatory adjectives "viral" or "infectious" are also used[@viral-licensing]. (See [Controversies]).

It is a form of licensing that retains the author's exclusive copyrights for works, but gives permission to recipients of the work to reproduce, change or distribute it, with the accompanying requirement that any resulting copies or adaptations are also bound by the same licensing agreement. "_In essence, copyleft grants freedom, but forbids others to forbid that freedom to anyone else along the distribution and modification chains._"[@copyleft-guide].(Hence the term "reciprocal".)

Copyleft software intentionally shares properties with public domain software and by requiring the same copyleft license downstream is an attempt to close one of its loopholes: "_any nontrivial modification made to the [public domain] work is fully copyrightable_", ergo "_over time, some entities will choose to proprietarize their modified versions_" with little "_incentive to contribute back to the commons_", until "_almost no interesting work is left in the public domain, because nearly all new work is done by proprietarization._"[@copyleft-guide].

"_Copyleft uses functional parts of the copyright system to achieve an unusual result (legal protection for free sharing)_"[@copyleft-guide]. It modifies copyright law, which is usually employed to strengthen the rights of authors or publishers by prohibiting "_recipients from reproducing, adapting, or distributing copies of their work_"[@wiki-copyleft], to strengthen instead the rights of users. This reversal is reflected in its name as a wordplay on "copyright".

The stipulation that the "_information necessary for reproducing and modifying the work must be made available to recipients of the binaries_"[@wiki-copyleft] (i.e., source code) is added to prevent the creation of proprietary products[@gnu-copyleft] and it is probably the most notable difference to public domain software because "_an executable program can be in the public domain but the source code is not available_"[@gnu-philosophy-category].

The idea of copyleft can also be applied to works that are not software. These licenses are usually called share-alike, such as the [Creative Commons](https://creativecommons.org) licenses.

#### 1.5.3 Types

##### 1.5.3.1 Strong and weak copyleft

"_“Strong vs. weak” copyleft is not a dichotomy, it’s a spectrum._"[@copyleft-guide] "_The strength of the copyleft governing a work is an expression of the extent that the copyleft provisions can be efficiently imposed on all kinds of derived works._"[@wiki-copyleft]

**GNU General Public License (GPL) version 3**, one of the most commonly cited examples of strong copyleft, proves that the strength of a license is indeed a spectrum: its System Library Exception "_is designed to allow copylefted software to link with these_ [proprietary] _libraries when prohibition of that linking would hurt software freedom more than it would hurt proprietary software._"[[@copyleft-guide] - [9.3.3](https://copyleft.org/guide/comprehensive-gpl-guidech10.html#x13-730009.3.3)]

The stronger the license, the more it will seek to ensure that the same license will cover every version of derivative works, making them subject to its requirements.[@copyleft-guide] Practically this means that the corresponding source code has to be made available to licensees. The ideological goal is to ensure the propagations of the software freedoms for each user.

Usually larger end user programs, which cannot be used further as a component, opt in using such strong licenses to prevent turning them into proprietary products<sup>FOOTNOTE</sup>.

<div class="footnote">
[FOOTNOTE] This is not a rule though and strong copyleft licenses are known to be abused by the industry. See [Controversies].
</div>

As the "copyleft" gets weaker, the license starts to introduce "trade offs" such as allowing cases of derivative works that are permitted to use another license and/or keeping parts of the source closed in order to foster wider adoption, but still try to hold on to most of copyleft's principles.[@wiki-copyleft;@copyleft-guide]

The most well-known example for this seemingly counter-intuitive rationale is the history of the **GNU Lesser General Public License (GNU LGPL)** and "glibc", the GNU project's implementation of the C standard library. It was created to provide a common alternative to the world of proliferating proprietary implementations that had limited functionality, sometimes specific only to certain vendors. If it had used a stronger license (such as the GPL), any software created with it would have to be shipped with the same license, thus providing their source code would have been necessary to avoid violation of the license's terms. "_The de-facto standard for the C library on GNU/Linux would likely be not glibc_"[@copyleft-guide], a free software, but probably the most popular proprietary one that allows developers to create proprietary software.

There are multiple ways to purposely weaken copyleft restrictions:

  * "The LGPL distinguishes between two classes of works: “_works based on the library,_” and “_works that use the library_” and it is generally used for the creation of software libraries.<sup>FOOTNOTE</sup>

      <div class="footnote">
      [FOOTNOTE] The quoted terms are specific to LGPL version 2 and has been superseded by LGPL version 3.[[@copyleft-guide] - [Chapter 10](https://copyleft.org/guide/comprehensive-gpl-guidech11.html#x14-9600010) and [Chapter 11](https://copyleft.org/guide/comprehensive-gpl-guidech12.html#x15-10600011)]
      </div>

  * The **Mozilla Public License version 2.0 (MPL v2.0)** is using a "file-level" copyleft instead[[@mpl2] - [MPL 2.0 FAQ](https://www.mozilla.org/en-US/MPL/2.0/FAQ/)] that "_treats the source code file as the boundary between MPL-licensed and proprietary parts, meaning that all or none of the code in a given source file falls under the MPL._"[@wiki-mpl] It also allows [sublicensing](https://softwareengineering.stackexchange.com/questions/189633/what-sublicense-actually-means).<sup>FOOTNOTE</sup>


    <div class="footnote">
    [FOOTNOTE] A couple good resources to help decide whether you need MPL v2.0 or not:

      * [The Mozilla Public License Version 2.0: A Good Middle Ground?](https://julien.ponge.org/blog/mozilla-public-license-v2-a-good-middleground/)

      * [Why I Chose the Mozilla Public License 2.0](https://christoph-conrads.name/why-i-chose-the-mozilla-public-license-2-0/)
    </div>

##### 1.5.3.2 Full and partial copyleft

This classification is used by some sources, but there is no authoritative source for their definitions by any of the well-established entities (for example, organizations such as the [Free Software Foundation](https://www.fsf.org/), [Open Source Initiative](https://opensource.org/), [Mozilla Foundation](https://www.mozilla.org/en-US/foundation/), or licensing websites such as [choosealicense.com](https://choosealicense.com/), [TLDR-legal](https://tldrlegal.com/)).

Most of the definitions can be found in many places, but they are

  1. vague without examples, and using exact or minimally modified copies of each other (cf. [@wiki-copyleft], [[@free-world] - [page 34](https://books.google.com/books?id=WRAFJNMrSdkC&pg=PA34&lpg=PA34&dq=full+partial+copyleft&source=bl&ots=lg50hOJ0oe&sig=h8i3mjiEPmbazN7mV63v2z2tKs8&hl=en&sa=X&ved=0ahUKEwjWsLWf2ZHXAhVJ2GMKHVvCBK8Q6AEIfzAQ#v=onepage&q=full%20partial%20copyleft&f=false)], [[@marxwiki-copyleft] - [Full and partial copyleft](http://machines.plannedobsolescence.net/marxwiki/index.php?title=Copyleft#Full_and_partial_copyleft)], [@yourdict-copyleft], [@wikivis-copyleft], [@freedict-copyleft], [@pcmag-copyleft]),

  2. indistinguishable in meaning from or bear close resemblance to weak/strong copyleft (cf. [@fullmetal-copyleft] and other citations above),

  3. describing the difference between conventional and "file-level"[[@mpl2] - [MPL 2.0 FAQ](https://www.mozilla.org/en-US/MPL/2.0/FAQ/)] (or "per-file"[@gnu-license-list]) copyleft[@gaz-copyleft].
  <br>
  <br>
  This category sounds the most plausible, but none of the cited sources bring [_Common Development and Distribution License (CDDL)_](https://opensource.org/licenses/CDDL-1.0) or [_Mozilla Public License_](https://www.mozilla.org/en-US/MPL/2.0/) as an example, even though they fit the bill perfectly. The Software Freedom Law Center's report[@sflc-cddl] comes closest in supporting this theory as it uses both ["strong" and "partial" to describe CDDL's copyleft properties](https://www.softwarefreedom.org/resources/2016/linux-kernel-cddl.html#cddl).

The adjective "full" is never used by any of the aforementioned entities to describe copyleft licenses<sup>FOOTNOTE</sup> and "partial" is used as a synonym to "weak" copyleft (with the exception of the Software Freedom Law Center's report[@sflc-cddl]). Cf. [@oss-licensing;@docracy;@openoffice-move], [[@intro-to-tech-computing] - [page 276](https://books.google.com/books?id=isTBDAAAQBAJ&pg=PA276&lpg=PA276&dq=gnu+partial+copyleft&source=bl&ots=w4PESycpiK&sig=Hsb4A5DAlUVGMOyFoCJIA-8rmxk&hl=en&sa=X&ved=0ahUKEwjd_eWL5JHXAhUP-GMKHW6CCOEQ6AEIgwEwEA#v=onepage&q=gnu%20partial%20copyleft&f=false)].

<div class="footnote">
FOOTNOTE The Open Source Initiative goes further because it does not even use "weak" or "strong" to categorize copyleft licenses.
</div>

Interestingly, the Free Software Foundation has both "copyleft-weak" and "copyleft-partial" as explicit categories in its [license description templates](https://directory.fsf.org/wiki/User:Jgay/license-categorization), but only the latter is used actively to categorize licenses traditionally referred to as "weak" copyleft licenses.

## 2 Approaches to software licensing

### 2.1 Proprietary software licenses

Proprietary programs use copyright licenses exclusively. "_The primary purpose of a proprietary software license is to limit the use of software according to the rights owner's business strategy_"[@sci-programmer], generally distributed in binary form. They are typically very restrictive for end users as they disallow any action that is not specifically layed out in the license.

Examples of limitations:

  * Deployment

      * How many times can a software be installed?
      * How many devices can it be installed?
      * Are simultaneous installations allowed?

  * Use

      * What are the exact purposes that the software can be used for?
      * Are other users allowed to use a specific installation?
      * How can the functionality of the software be extended?

  * Distribution

      * What counts as (re-)distribution?
      * Is it allowed at all?

  * Derivative works

      * What is a derivative work according to the copyright owner?
      * Is it allowed to use parts or the entire software in derivative works?

### 2.2 Free software licenses

The usage of the word "free" in "free software" may be misleading because it both means "freedom" and "zero price". The problem is that English, unlike other languages, does not have a common adjective that unambiguously refers to freedom. French for example has "libre" for "freedom" and "gratuit" for "free of charge".[@gnu-philosophy-category]

In this context, the intended meaning was "freedom", as in "freedom of users".

#### 2.2.1 History

As mentioned in section [1.5.1 Historical background], Richard Stallman eventually founded the Free Software Foundation in 1985, as a response to the rising concern among academic circles "_about the closed and proprietary direction that software was taking_"[@roads-and-bridges]. In 1989, the GNU General Public License, the first free software license, is published.

#### 2.2.2 Description

Free software licenses are the ones that comply with the [definition of free software](https://www.gnu.org/philosophy/free-sw.html)[@gnu-what-is-free-software]:

>A program is free software if the program's users have the four essential freedoms: [[1](https://www.gnu.org/philosophy/free-sw.html#f1)]
>
>  * The freedom to run the program as you wish, for any purpose (**freedom 0**).
>
>  * The freedom to study how the program works, and change it so it does your computing as you wish (**freedom 1**). Access to the source code is a precondition for this.
>
>  * The freedom to redistribute copies so you can help others (**freedom 2**).
>
>  * The freedom to distribute copies of your modified versions to others (**freedom 3**). By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.


Free software tend to be copyleft licenses to keep propagating the same freedoms down the line, but it is a misconception to think that all copyleft licenses are also automatically qualify as free software licenses (e.g., [Sybase Open Watcom Public License version 1.0](https://www.gnu.org/licenses/license-list.en.html#Watcom)) or that copyright ones won't (one exception is the [Standard ML of New Jersey Copyright License](https://www.gnu.org/licenses/license-list.en.html#StandardMLofNJ)).

The Free Software Foundation's Licensing and Compliance Lab maintains an annotated and categorized list of licenses that can be found at <https://www.gnu.org/licenses/license-list.en.html>. It also lists the license's compatibility to versions of the GNU General Public Licenses, that are the progressive, legal embodiment of the free software movement's governing philosophies.

To date, the latest version is the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). An [extensive legal analysis is also available by the Software Freedom Law Center](https://www.softwarefreedom.org/resources/2014/SFLC-Guide_to_GPL_Compliance_2d_ed.html)[@sflc-gpl2] or see the de facto [copyleft guide](https://copyleft.org/guide/)[@copyleft-guide].

### 2.3 Open source licenses

#### 2.3.1 History

To recapitulate the last mentioned events of our historical timeline, the Free Software Foundation (FSF) is founded and their license (GNU GPL) is published in 1989. By the time the World Wide Web gains momentum and become more widely available around 1992, FSF has already publishes the second version of the GNU GPL. The race to commercialize the web begins with huge gains.[@roads-and-bridges]

In 1998, in a move unprecented at the time from a software company, Netscape releases the source code of its high market-share web browser. This event becomes the catalyst to a group of technologists, who have been advocating a more pragmatic approach to the Free Software Foundation's principles, to create the **Open Source Initiative**. The new organization's focus is to promulgate "_the practical benefits of free software_"[@roads-and-bridges] without "_the ideological and confrontational connotations of the term_"[@open-source-movement-wiki].

#### 2.3.2 Description

Open source licenses are licenses that comply with the [Open Source Definition](https://opensource.org/osd)[@osi-osd], [including non-copyleft licenses that allow proprietary derivative works](https://opensource.org/faq#permissive). (A reason why they are also called "permissive" licenses).

As the defintion of open source software is an extension of [the four essential freedoms of the Free Software Definition](https://www.gnu.org/philosophy/free-sw.html), all copyleft licenses are also open source licenses.

The list of approved licenses is maintained by the Open Source Initiative that can be found at <https://opensource.org/licenses>.

### 2.4 Open source versus free software

#### 2.4.1 Common ground

Both **free software** and **open source software** do roughly mean the same:

  * According to the [Free Software Foundation](https://www.fsf.org/)'s summary, "_users have the freedom to run, copy, distribute, study, change and improve the software_"[@gnu-what-is-free-software].

  * The Open Source Initiative defines it as "_software that can be freely accessed, used, changed, and shared (in modified or unmodified form) by anyone. Open source software is made by many people, and distributed under licenses that comply with the Open Source Definition[@osi-osd]._"[[@osi-faq] - [What is "Open Source" software?](https://opensource.org/faq#osd)]

#### 2.4.2 Differences

"_Open source is a development methodology; free software is a social movement._"[@gnu-os-misses] Although often discussed together, they are politically distinct: "free software" being more closely associated with ethics ("_essential respect for the users' freedom_"[@gnu-os-misses]) and "open source" with pragmatism (i.e., a practical, business-case approach to free software)[@osi-history].

The groups' relationship towards proprietary software is one of the most defining difference:

  * Members of the open source community are willing to coexist with the makers of proprietary software[@open-source-movement-wiki],[[@osi-faq] - [What is a "permissive" Open Source license?](https://opensource.org/faq#permissive)] and feel that the issue of whether software is open source is a matter of practicality[@osi-history]. One example is [tivoization](https://en.wikipedia.org/wiki/Tivoization).

  * In contrast, the free software community maintains the vision that all software is a part of freedom of speech and that proprietary software is unethical and unjust, or even downright dangerous at times[@gnu-os-misses;@gnu-proprietary;@gnu-surveillence;@gnu-backdoor].

The philosophical differences are also reflected in software licensing approaches: the open source community allows the use of licenses that permit developing proprietary (i.e., closed sourced) software. This is unacceptable to proponents of free software.

Therefore, on the practical side, every existing free software would qualify as open source because the Open Source Initiative allows the more restrictive (or permissive, depending on the perspective) free software licenses, but not vice versa.

## (Somewhat finished sections)

    ###### Controversial licensing practices
    ##### Compliance
    ###### compatibility
    ###### ?
    ##### 2.3.3.4 Choosing a license

    Choosing a license depends on many factors, such as use cases (e.g., end user product, software module), adopting entities (e.g., company, group of hobby developers), project goals (e.g., commercial product, free or for fee services).[@https://blog.p2pfoundation.net/why-apache-defeated-the-gpl-license-developer-freedom-vs-user-freedom/2013/01/21,@https://softwareengineering.stackexchange.com/questions/107883/agpl-what-you-can-do-and-what-you-cant,@https://news.ycombinator.com/item?id=1273231,@roads-and-bridges]

    #### 2.5.4 Factors to consider before adoption

      * **Cost**

        Proprietary software is always more expensive because a company has to pay for development, distribution, support, legal fees etc.

        On the contrary, open source code can be obtained free of charge but all sources agree that there are hidden costs (if not about their extent).[@https://www.americanexpress.com/us/small-business/openforum/articles/the-open-source-conundrum-3-benefits-and-drawbacks-to-consider/;@https://jaxenter.com/think-open-source-software-free-think-131436.html;@https://crowdsourcedtesting.com/resources/pros-cons-open-source-software/;@http://thevarguy.com/open-source-application-software-companies/reasons-organizations-opt-not-use-open-source-software;@https://www.americanexpress.com/us/small-business/openforum/articles/the-open-source-conundrum-3-benefits-and-drawbacks-to-consider/;@http://entrepreneurhandbook.co.uk/open-source-software/;@https://crowdsourcedtesting.com/resources/pros-cons-open-source-software/;@roads-and-bridges,@osmovement] and the next items expand on the nature of these. Their categorization into pros and cons is not straightforward because it depends on the scope of the adopting organization and the parties involved making their case.

      * **Risk of abandonment of dependent projects.**

        The argument stems from the fear of the decentralized open source workflow and that project governance is unclear in many cases.

        On the other hand this fear is also valid regarding proprietary software: companies phase out older products or functionality (sometimes without any notice) regardless of users relying on them (e.g., subsequent iterations of Microsoft products routinely defy assumptions based on previous versions) and even profiting from offering additional transitional support.

      * **Support and ongoing maintenance**

        Commercial proprietary products are traditionally shipped with guaranteed support whereas open source is perceived to lack this level of care[@http://thevarguy.com/open-source-application-software-companies/reasons-organizations-opt-not-use-open-source-software]. This may be due to the fact that it is not stated explicitly in every project but is an intrinsic part of open source culture:

        * documentation is kept up to date

        * communities around a project have mailing lists, chat rooms, meet-ups set up (even regular office hours specified![@https://make.wordpress.org/community/handbook/wordcamp-organizer/planning-details/gpl-primer/]

        * sites dedicated to answering questions of almost any nature, such as Stackoverflow or Quora

        * issues and feature requests can be directly opened on the project's source code repository (e.g., on Github)

        * as a last resort, the source code is always available

        Open source companies also offer commercial support as part of their business model.

      Commercial support for proprietary software on the other hand can be so poor that another company needs to be hired for deployment and for ongoing operations. The worst case scenario is that local staff takes up the mantle even though they had no role in development and have little ability to do anything else other than coming up with workarounds by trial and error as the implementation details are not known.[@osmovement]

        This brings up the issue of control:

      * **Control**

        Proprietary vendors have iron grip over the software's functionality and future evolution. Monopolies eliminate any upstart innovators, effectively locking the organizations into a platform with the ability to demand any price.

        Open source's alluring promise is to return control.
        over the tools one would like to use and how one would like to use them.

        Examples to the former are alternatives to proprietary software such as
        Control over the choice of tools one would like to use:

          * OpenOffice instead of Microsoft Office

          * Linux, BSD or other open source operating systems instead of Microsoft Windows or Apple Mac OS X[^footnote-macosx_open]

          * FreeSWITCH instead of Avaya IP Office

        Control over how one would like to use these tools:

          * Restrictions of proprietary software licenses are able to limit any aspect of a program (such as JAWS, Raiser's Edge, EyeCare, Microsoft Office): the number of times a software can be installed, the number of computers it can be present simultaneously, the number of database records, the date until it can be used and so on.

            Alternatives, such as NVDA, CiviCRM, OpenERM, OpenOffice etc. do not have these restrictions.

          * Avaya IP Office phone system only allows certain functionality in combination with specific hardware (and even then it is not guaranteed).

            FreeSWITCH may be compiled on any commodity hardware and can be extended programmatically or by community modules.

        Control over one's own data because by the lack of regulations, users' have little authority over what should happen to their voluntarily supplied information to large corporations[@https://www.economist.com/news/leaders/21721656-data-economy-demands-new-approach-antitrust-rules-worlds-most-valuable-resource]. Open Stack is one solution to create a private or public cloud on any available hardware.

    [^footnote-macosx_open]: Even though Apple recently open sourced the kernel of Mac OS X but it is only responsible for booting up the computer - all the useful programs are still proprietary and are not included[@https://www.techrepublic.com/article/why-apple-open-sourcing-mac-os-x-isnt-terribly-exciting/]

      * **Standards and tools**

        Ever since the business opportunity of selling software has been recognized, companies have been creating programs to solve a specific problem (networking, data management, etc.) with the intent of successful commercial distribution. Many times the problem domains have been complex enough to develop a proprietary standard solution and patent it, leading the way to reinvent the wheel over and over. Overall secrecy made it difficult to prove the superiority of one product over the other and typically the corporation with the most resources and/or better marketing campaign prevailed.

        Adopting organizations still require long periods of deliberation before purchasing any proprietary software suite because:

        * The rigidness of the tools would require adjusting organizational processes and workflows (i.e., serving the tool instead of the other way around)

        * It would lock them in in the long haul. Reasons include:

            * information is stored in a proprietary format

            * no interoperation with other vendor's products

            * accumulated experience would not translate to other similar solutions requiring re-training and/or new hires

        With the emergence of the free and the open source movement large-scale collaboration on *open standards* became the norm. Proprietary software could still be built upon them but many went down the open source path. Of course this led to the proliferation of tools but now one had a choice even if in the end a proprietary product ended up being use. Open standards also incentivized corporations to get involved as more and more customers started to trust the new process of laying down the foundations of a new technology in the open.

      * **Qualified labor**

        Proprietary software usually has one setup for each use case (because many times they are tied to a specific proprietary hardware) that makes life easier but this ease comes with the aforementioned costs. Vendors usually sell trainings and certifications for individuals and/or they provide support services to help operations. Such specialization comes with high prices and limits the mobility of the workforce (i.e., seek opportunitites only at companies with the same equipment or setup).

        The learning curve of open source is steeper but becoming versed in its ways may yield many advantages:

          * Individuals get a reusable set of skills and a more holistic view of how principles from multiple fields can be tied together.

            Specialization to proprietary systems is easier using this path because companies use their own obfuscated terminology based on marketing buzzwords whereas the underlying principles have their standard terminology rooted in (academic) research. Open standards used the latter as clarity is crucial in wide-spread adoption.

          * Organizations lay down a foundation for future flexibility and continuous improvement.

            Open source has a vibrant community based around popular and well documented programming languages and frameworks with their own support support networks sharing the same infrastructure (e.g., Github, Stackoverflow, Slack). Switches between *technology stacks* are common and seamless because the underlying tools are the same and/or based on similar principles.

            Adopted tools can also be further specialized/improved and these modifications can be contributed back to the larger community.

          * Wide-spread availability promotes easy entry for anyone interested

          * Most people working on open source projects are characterized mostly by enthusiasm[@https://ocw.mit.edu/courses/sloan-school-of-management/15-352-managing-innovation-emerging-trends-spring-2005/readings/lakhaniwolf.pdf]

      * **Security**

        Proponents of open source believe in [Linus' Law](https://en.wikipedia.org/wiki/Linus%27s_Law)[@bazaar]: open source project are more widely available to the publicand more eyes mean higher chances to discover a (security) bug.

      Although this statement has not been proved by any major research and it relies on questionable assumptions.[@http://www.zdnet.com/article/six-open-source-security-myths-debunked-and-eight-real-challenges-to-consider/] The most widely publicized open source vulnerability was the OpenSSL Heartbleed bug[@http://heartbleed.com/] but the causes leading up to it are more complex than a simple oversight.[^footnote-heartbleed]. Security issues tend to be disclosed almost as soon as they are discovered though, as opposed to proprietary bugs.

    [^footnote-heartbleed]: The report titled "Roads and Bridges: The Unseen Labor Behind Our Digital Infrastructure"[@roads-and-bridges] written by Nadia Eghbal for the [Ford Foundation](http://www.fordfoundation.org)[^footnote-cc_license] gives an extensive treatment of the issue and open source infrastructure in general. (See chapters "Introduction" and "The hidden costs of ignoring infrastructure".)

        Opponents argue that "proprietary programs whose code is closed cannot be as easily inspected by malicious hackers who are looking for security holes to exploit"[@http://thevarguy.com/open-source-application-software-companies/reasons-organizations-opt-not-use-open-source-software].

        Proprietary software is most often tied to business interests and therefore withhold disclosure for certain period of time or entirely until revealed by a leak. Examples include the Equifax breach[@https://www.wired.com/story/equifax-breach-no-excuse/], Yahoo breach[@https://techcrunch.com/2017/10/03/yahoo-says-all-3b-accounts-were-impacted-by-2013-breach-not-1b-as-thought/] or a Microsoft breach that remained undisclosed since 2013[@https://ca.reuters.com/article/technologyNews/idCAKBN1CM0D0-OCATC]. The exploits could have been easily prevented because the open source projects, that the proprietary solutions were building upon, had their security holes already fixed but these patches haven't been applied due to neglect.[@https://jaxenter.com/think-open-source-software-free-think-131436.html] Aside from business misconducts, the "United States National Institute of Standards and Technology (NIST) specifically recommends against using closed source as a way to secure the software (i.e. “security through obscurity”)"[@https://www.efrontlearning.com/blog/2012/04/open-source-and-the-security-through-obscurity-fallacy.html], and they state, “system security should not depend on the secrecy of the implementation or its components” [@https://csrc.nist.gov/publications/detail/sp/800-123/final].

        A recent (10/16/2017) flaw in the WPA2 protocol[@https://www.krackattacks.com/] (a protocol that secures all modern protected Wi-Fi networks) proves that security bugs sometimes stem from accepted industry standards therefore any correct implementation would be affected, regardless of being an open source or a proprietary product.

      * **Compliance requirements**

        Software compliance means to keep track of all the copyright notices and licenses, and oblige to their requirements. Compliance tracking is also important to document the software supply chain (e.g. to be able to produce a Bill of Materials on request) and to respond quickly to a newly disclosed security vulnerability (i.e., to know which parts are affected, if any).

        From a software development standpoint, large corporations have advantage as they usually own all of the source code. Even if they incorporate open source projects in their closed source product(s), they have the legal apparatus to tip the scale to their favour should it come to a legal dispute over license ambiguities. Therefore in the case of proprietary software, the burden of compliance falls to the users, especially if the products are going to be used in a commercial setting.

        With open source software the users are the clear winners because they have complete freedom on how to use the products and they only have to satisfy license obligations if they are planning on commercial re-distribution of the (modified) works or if they would like to create a proprietary product from open source projects.[^footnote-proprietary_opensource]

    [^footnote-proprietary_opensource]: Although if they steer clear of strong copylefted code than their situation becomes magnitudes easier.

        Building on open source code on the other becomes more complex as each included project may have different (or even multiple) licenses. Fortunately, this requirement has become more and more a standardized and automated process with the lead of large open source non-profits such as the Linux Foundation or the Open Source Initiative.[@https://www.linuxfoundation.org/blog/why-companies-that-use-open-source-need-a-compliance-program/] One example is the Software Composition Analysis methodology[@https://blog.blackducksoftware.com/software-composition-analysis-compatible-agile-devops].

    #### 2.3.5 Commercial applicability
    ##### controversies

    ##### 2.3.5.1 Commercial versus proprietary software

    It is worth emphasizing:

    >“Commercial” and “proprietary” are not the same! Commercial software is software developed by a business as part of its business. Most commercial software is proprietary, but there is commercial free software, and there is noncommercial nonfree software.
    >
    >For example, GNU Ada[^footnote-ada_link] is developed by a company. It is always distributed under the terms of the GNU GPL, and every copy is free software; but its developers sell support contracts. When their salesmen speak to prospective customers, sometimes the customers say, “We would feel safer with a commercial compiler.” The salesmen reply, “GNU Ada is a commercial compiler; it happens to be free software.”[@GNU's "Categories of free and nonfree software"  https://www.gnu.org/philosophy/categories.en.html#commercialSoftware]

    [^footnote-ada_link]: https://en.wikipedia.org/wiki/GNAT

    ##### 2.3.5.2 Free/open source software versus commercial software

    Commercial software is not the antonym of free and open source software, proprietary software is. Misunderstandings stem from conflicting uses of the adjectives *commercial* and *proprietary*.[@http://peerproduction.net/issues/issue-1/peer-reviewed-papers/why-free-software-is-not-the-antonym-of-commercial-software/]

    Software licensed under an open source (or even under a more strict free software) license can be sold for a price or licensed for a fee just like any other product.[@https://blog.codecentric.de/en/2012/05/using-gpl-licensed-components-in-proprietary-projects/,@https://www.gnu.org/licenses/gpl-faq#DoesTheGPLAllowMoney,]

    ##### 2.3.5.3 Business models for open source software

    ##### 2.3.5.2.3 Controversies

    It can be especially hard if one would like to choose an open source license for a commercial project as some of them are historically abused for unethical business practices[@http://www.dr-chuck.com/csev-blog/2014/09/how-to-achieve-vendor-lock-in-with-a-legit-open-source-license-affero-gpl/;@http://www.davewentzel.com/content/open-source-licensing] and some have pejorative connotations associated with them by negative campaigns at the time when open source practices where perceived as a threat by corporations (e.g., adjectives "viral" and "infectious" used for copyleft licenses[@https://en.wikipedia.org/wiki/Viral_license]).


## (Notes without any structure)

    commercial vs open source / free
    ================================

    http://peerproduction.net/issues/issue-1/peer-reviewed-papers/why-free-software-is-not-the-antonym-of-commercial-software/
    NOTE: free and open source software is not an antonym of commercial software (proprietary is)

    In other words, for this developer all the software covered by the GPL should be considered as a specific form of commercial software, to the extent that developers are entitled by the license to distribute copies of the software asking for a payment. This definition (FLOSS as commercial software), states the developer, is also supported by concrete examples such as the GNU/Linux commercial distributions.

    NOTE: so you can sell it but you have to provide the source code and the buyer (or licensee) can further distribute the product with the same license (and its restrictions). The next quote further emphasizes that free/open source is not against commercial use:

    Open Design Alliance members have created the following free utilities, based on the OpenDWG Libraries, for your unrestricted, non-commercial use. Please note that inclusion of any utility in a commercial product does require commercial licensing [14]
    This post clarifies to GRASS developers that it is not possible for them to use the OpenDWG Library together with GRASS, due to the clear commercial nature of GRASS granted by the terms of the GPL (for instance by the term 1 ). Indeed, the OpenDWG source code can be freely used, as it is clearly stated above, but only for non-commercial purposes. Therefore we have an opposition between FLOSS and non-commercial software and not between FLOSS and commercial software.


    Lessons for creating good open source software[edit]
    ====================================================

    @bazaar
    Raymond points to 19 "lessons" learned from various software development efforts, each describing attributes associated with good practice in open source software development:[3]
    Every good work of software starts by scratching a developer's personal itch.
    Good programmers know what to write. Great ones know what to rewrite (and reuse).
    Plan to throw one [version] away; you will, anyhow. (Copied from Frederick Brooks' The Mythical Man-Month)
    If you have the right attitude, interesting problems will find you.
    When you lose interest in a program, your last duty to it is to hand it off to a competent successor.
    Treating your users as co-developers is your least-hassle route to rapid code improvement and effective debugging.
    Release early. Release often. And listen to your customers.
    Given a large enough beta-tester and co-developer base, almost every problem will be characterized quickly and the fix obvious to someone.
    Smart data structures and dumb code works a lot better than the other way around.
    If you treat your beta-testers as if they're your most valuable resource, they will respond by becoming your most valuable resource.
    The next best thing to having good ideas is recognizing good ideas from your users. Sometimes the latter is better.
    Often, the most striking and innovative solutions come from realizing that your concept of the problem was wrong.
    Perfection (in design) is achieved not when there is nothing more to add, but rather when there is nothing more to take away. (Attributed to Antoine de Saint-Exupéry)
    Any tool should be useful in the expected way, but a truly great tool lends itself to uses you never expected.
    When writing gateway software of any kind, take pains to disturb the data stream as little as possible—and never throw away information unless the recipient forces you to!
    When your language is nowhere near Turing-complete, syntactic sugar can be your friend.
    A security system is only as secure as its secret. Beware of pseudo-secrets.
    To solve an interesting problem, start by finding a problem that is interesting to you.
    Provided the development coordinator has a communications medium at least as good as the Internet, and knows how to lead without coercion, many heads are inevitably better than one.


    # controversies, copyleft shakedowns, bait and switch etc

    ## https://www.infoworld.com/article/2616665/open-source-software/what-s-next-after-gpl-and-apache-.amp.html

    The software that resulted worked really well, but when it came time to move to production, most companies asked for legal advice. As always happens when you ask your lawyer for business advice (instead of making business decisions and asking your lawyer to help you achieve them legally), they were told to play safe and buy a proprietary license to MySQL and Red Hat Enterprise Linux. Despite open source licenses offering everyone the freedom to use the software for any purpose, many companies were concerned that the GPL might force them to open up all their internal workings to the world.

    A number of software entrepreneurs chose to base their business models on this fear. They selected the GPL for their software projects, not to promote some vision of digital liberty, but rather to exploit the fears of corporate legal advisers about the GPL. Called the dual-license model (referring to the software being available under both an open source license and a proprietary license), it depends on the software developer owning all the copyrights so that they can provide different license terms for paying and nonpaying users, and on the use of the most scary open source license possible in the eyes of inexperienced legal advisers. Today this means use of the AGPL, a variant of the GPL that is also triggered by Web deployment, unlike the GPL itself.

    Open core as a business model
    As the scare value of the GPL declined, some business ventures switched to another approach. They tended to retain the GPL for the core project, hoping still to scare up a little revenue. However, more and more of them added proprietary layers on top, becoming little better than the proprietary vendors they claimed to replace. By making the features essential to enterprise deployment proprietary, they hoped to force adopters into their revenue funnel.
    Moreover, since the proprietary software couldn't be used by the community, they faced no direct competition from community members offering better value points to their customers. The combination of enterprise compulsion and lock-in was very attractive, and many projects in the late years of the decade moved to this "open core" approach.

    For the customer, the problem is that instead of delivering and cultivating software freedom, the open-core business model induces dependency on closed software and lock-in to a vendor. Open-core businesses hope you'll be willing to trade your freedom for tangible short-term benefits or even just for "shiny."

    They stand to benefit massively from having you locked in; they want to trade your freedom for their profit. While open-core businesses truthfully say they are sustaining open source core software, their actual business has nothing to do with open source. It’s a bait-and-switch, wrapping the same old lock-in under the flag of open source and hoping you won't notice.

    ## http://wso2.com/blogs/thesource/2011/04/what-we-mean-by-no-gimmicks-open-source-licensing/

    Dual License

    Because GPL’s copyleft provisions can be scary, many GPL-based open source companies have evolved a profitable workaround.  In many cases you can acquire GPL software under a separate commercial license.  That alternative license removes the viral copyleft feature, and replaces it with normal commercial restrictions – including license fees.

    For many enterprises, this negates the advantages of open source software in the first place – avoiding lock-in to a specific vendor, having no control over pricing, and so forth.  What originally appeared as a free open source license has become in effect a paid proprietary license.  We classify that bait-and-switch as a gimmick.

    It annoys us even more that many companies offer some products as open source (the “community edition”) and then reserve the real product (the “enterprise edition”) completely under a commercial license.  For serious users that’s not free software – just a free taste.  Often turning your proof of concept into a production deployment involves installing new software instead of flipping a switch – what a drag!

    No Gimmicks

    So when WSO2 claims we have a “no gimmicks” approach here’s the commitment we make:

    Our software line is available completely under the Apache license.

    There are no “community”, “light”, or “demo” versions – every edition is enterprise ready from day one.  Even our WSO2 Stratos cloud platform is Apache-licensed – the obvious high-value candidate for a dual-licensed model.

    We welcome you to join the community, ask questions on our forum, even become a committer.  If you don’t want or need a commercial support relationship with WSO2, we are still happy you are using our technology.  Just please tell your friends!

    We have to work consistently for your business, not lock you in.  Our success and business model is based entirely on providing the highest quality support services and doing everything we can to ensure your project is successful.

    Our support includes creation of patches for your deployed version of the product – so you don’t have to upgrade to the latest version to get a critical fix.  While these patches are created specifically for you under the terms of our Production Support agreement and are not redistributable, you are free to continue to keep them installed should you discontinue Production Support services.

    ## https://www.infoworld.com/article/2627153/software-licensing/profiting-from-open-source----without-selling-out.html

    Yet for all of this wealth, there's a feeling that these businesses succeeded by being hybrids. They use the open source vision to attract users, but their business success comes by pushing proprietary options. Thus, the dark secret is that their open source version are merely a form of marketing.

    Calling this a bait-and-switch may be too cynical, but all users can feel the commercial tilt. Many companies, for example, find it is cheaper to buy a full commercial license for MySQL than to hire a lawyer to see if they are in compliance with the open source license. Red Hat makes a big distinction between the free version, distributed under the name Fedora, and its enterprise products sold under the name Red Hat. Lest there be any expectation that their software is truly free, both MySQL and Red Hat offer 30-day trials, a phrase that's not usually associated with the ideals of open source. Remember Oracle CEO Larry Ellison's famous interview with the Financial Times where he said, "If an open source product gets good enough, we'll simply take it."

    exchange of work and software: "Free software and open source exist in a market (or ecosystem) where each of the participants needs to give and receive value. To understand what business models work around open source, we need to understand what each participant in the market stands to gain, what exchange they are making and what the effect is on the market."

    While this approach sounds like it was drafted by an accountant, Greant points out that the gains and the exchanges may not be obvious. A freeloader who complains vociferously may be annoying, but such demands are also a stream of free bug reports. The challenge for businesses is to find viable mechanisms for aligning the interests of the users and the programmers -- a complex task of social engineering.

    about?

    Open source business model 1: Work with friends
    Open source business model 2: Work with colleagues

    Open source business model 3: Sell documentation
    This model may become very limited as paper documentation is replaced by digital instructions. For example, the iText package, 
    The books are still available, but version 5.0 of the software was released under the Affero General Public License (AGPL): People who wanted to upgrade needed to either release the source code to their entire application or buy a commercial license.

    Open source business model 4: Sell support
    Bob Bickel, an advisor to and board member of several software companies, says there are no good examples of support companies that offer both profitability and growth. The names that first come to mind, such as Red Hat and Swing, rely heavily on proprietary enhancements such as the Red Hat Network and tcServer to entice customers to pay for the enhanced version, he says -- "it's not the support."

    Support is a difficult sell because the costs seem outrageously high: $200 for a phone call sounds steep until you realize that a basic engineer needs to field two to three per day to cover the costs of salary and overhead.

    Then there's the problem of competition. Red Hat's stock plunged in 2008 after Oracle started offering support at half the price. Companies may hate this competition, but customers love it. And at the end of the day, it's better to be in a competitive field where there are customers than to have a lock on an expensive product without any customers.

    Knowing the poor economic history of support-funded open source, Monty Widenius' new company MariaDB won't handle support at all, instead concentrating on what he calls "custom engineering." This is a form of support with lots of extra code writing mixed in -- in other words, big-ticket contracts to enterprises that want specially tuned versions.

    But others point out that support is a perfectly viable small, sustainable business. It may never offer explosive growth, but it can still pay the rent. "Support and professional services can be great businesses," says Luke Kanies, CEO of Puppet Labs. "They're just difficult businesses to get funding for, which means they're slower to build and harder to exit."

    Open source business model 5: Sell hardware
    Open source business model 6: Don't sell software
    Open source business model 7: Sell FUD
    Open source business model 8: Cripple your product

    Open source business model 8: Cripple your product
    The word "cripple" sounds negative, so no one uses that word. It's better to "enhance" the enterprise version and give away the community version -- crippling without the nasty name.

    Of course, this model gets pretty close to the "open source as marketing ploy" approach that is so bothersome to open source believers. James Phillips, one of the co-founders of NorthScale, says, "There are companies that require a supplier relationship and will pay for open source software. Holding back feature sets, in my opinion, just confuses the customer."

    Puppet Labs' Kanies rebuts these purists: "You absolutely have to have something to sell -- no one will pay you just because they use their awesome software." He adds, "If you happen to make usable, simple software that just gets out of their way, you won't even know the users exist." So, he suggests, rather than remove features from the free version, you might get the same push to paid by making the free version onerous to use.

    ## http://www.tritsch.org/2008/11/11/open-core-licensing-moving-from-bait.html

    Open Core Licensing - moving from "bait-and-switch" to "suggest-and-complement"

    Nov 11, 2008

    The Open Core Licensing discussion is really refreshing! Lots of good ideas and lots of good energy. Obviously the "earlier" versions of the model were more oriented towards a "bait-and-switch" approach (get a good stack for free, but then if you want to do real/serious enterprise computing, you have to to buy the real thing :)). Right now the models have evolved into more mature "suggest-and-complement" models (aka. Open Core Licensing). And I am using the word "mature", because talking about it (the desire the make money with open source) like this, should be the norm and not the exception.

    ## https://blogs.the451group.com/opensource/2008/10/13/open-source-is-not-a-business-model/

    Last month I noted that Matt Asay, one of the highest profile proponents of open source software, had changed his position on the use of proprietary extensions as a means of attracting paying customers to software based on open source code.

    “How do vendors generate revenue from open source software?”.

    The report also busted some other open source-related myths, such as the idea that open source vendors are reliant on ad hoc support services, and that open source eliminates the need for direct sales. We found that:

    Ad hoc support services are used by nearly 70% of the vendors assessed, but represent the primary revenue stream for fewer than 8% of open-source-related vendors.

    Most vendors generating revenue from open source software are reliant on direct sales staff to bring in the largest proportion of revenue.

    As for the overall conclusion. I have already hinted at the findings in acouple of posts, noting that:

    “Open source is a business tactic, not a business model. Open source is not a market in and of itself, nor is it a vertical segment of the market. Open source is a software development and/or distribution model that is enabled by a licensing tactic.”

    “The cat is already out of the bag when it comes to open source related business models and there is no way it is going back in.”

    “There is very little money being made out of open source software that doesn’t involve proprietary software and services.”

    The line between proprietary software and open source software is becoming increasingly blurred as open source software is embedded in broader proprietary hardware and software products and proprietary extensions are used to attract more customers.

    ## http://www.davewentzel.com/content/open-source-licensing

    I have personal reservations about Intellectual Property (IP) rights.  But even though I don't like IP, I have to respect it in my daily dealings.  Open source licensing, in general, disgusts me because if you are a bit lax, even accidentally, your OSS vendor can swoop in and claim large portions of your profits as its own, legally.  In many regards these licenses are far more punitive and Draconian than anything I've ever seen from a closed-source vendor like M$ or Oracle.  Why is this?

    OSS vendors have to Make Money.  Choice-of-license is how they do it

    Some people believe that OSS vendors chose the open source model because of some kind of altruism.  "We provide our software for free to make the world a better place."  Bullshit!  Every company has to make money.  How a vendor chooses to license their product is how they make it.  There are open source licenses that foster "building a community" prior to building sustaining revenue (example, Apache licensing) and there are licenses meant to generate revenue first, often sneakily (example, GPL).  

    GPL vs Apache
    Let's take two examples.  Company A develops some software and decides the best way it can make money with it is to build a community of avid users of the software.  "Build it and they will come", if you will.  The Apache License best meets that goal.  As a business-owner and independent consultant for ISVs I look first for software with Apache licensing (or BSD, MIT, or similar).  These licenses are business-friendly.  I'm not an attorney and I bear no responsibility for any misinformation given in this post, but essentially an Apache License gives the licensee full control to do with the software anything it wants to do with it, as long as the copyright notice is preserved.  It's about as close to free as it gets.  No royalties necessary.  In this case Company A believes the Apache License affords it the best method of gaining market momentum.  So, how does Company A make money if its software is "free"?  There are many ways, but in-app advertising and paid services (support) are the two most common.  This example is straightforward and is what most people think of with OSS.  You really have to do something stupid to get in trouble using this variety of OSS.  

    GPL, "Copyleft", and Derivatives

    ￼Company B would rather sustain its business with licensing revenue (just like Oracle or M$) but it still wants to call itself OSS.  Just my opinion, but this is sneaky and bordering on dishonest.  Here's how it works.  Company B chooses a "copyleft" licensing scheme like GPL or AGPL.  Again, I'm not a lawyer but copyleft works by saying the license is just like an Apache license except that derived works must also be released as open-sourced, copyleft works.  Said differently, the license must be moved forward.  

    Huh?  Company C is an ISV that would like to use some open source software to augment its closed source software.  If Company C uses an Apache-licensed piece of software then they may continue to keep their software closed-sourced without paying royalties.  But if they decide to use a GPL license then Company C *must* open source its software or it will be in violation of the GPL.  That means the GPL "moves forward".  

    So, how does Company C use GPL'd software in its closed-source product?  Carefully.  All "copyleft" ISVs like Company B will offer both a GPL version of its product and then another version with a non-open-source license that the licensee can then use in its closed-source product without having to open source everything or violate the GPL. The GPL'd version is still "free", the alternatively-licensed version can have whatever royalties and terms that it desires, just like a closed source product.  By "version" I don't mean a separate set of binaries (like Windows Standard vs Enterprise), rather a different "version" of the license. 

    A True Horror Story

    An ISV I worked for loved using OSS whenever it could.  The OSS always used Apache licensing (or equivalent) whenever we redistributed our code.  If it was software used in-house for administration or development only then nobody really cared about the licensing covenants.  There was a secret push to begin using a NoSQL alternative to SQL Server for some aspects of data persistence for a skunkworks project.  Cost was the reason.  SQL Server was deemed too expensive.  I was not involved in the evaluation or recommendation of the OSS product but a company-that-shall-remain-nameless gave a demo of their "free" distributed document store software to the skunkworks team.  I was not invited.  The product worked well and our developers coded a bunch of stuff against it that was not yet released.  

    There are industry horror stories with this particular OSS vendor.  This vendor is known for touting its free OSS and then strong-arming ISVs into huge licensing fees at a later time once your software was coded and released.  You either paid this vendor for the closed-source license, or you open sourced your ENTIRE application.  Even if only a small corner of your application used the vendor's product they threatened that your WHOLE APPLICATION needed to be open sourced.  Most ISVs get scared and do not want to open source their product and rely solely on services revenue.  This would be a dramatic change for most ISV business models.  So these ISVs usually relent and pay the equivalent of shakedown money for a non-free, non-GPL license for the product.  It is either that, or rip out the GPL'd product and start over.  That would be equally unappealing.  

    Soon the secret was out that there was a group developing against a new data persistence engine.  This is when I found out.  I knew this OSS package was GPL and its use could radically alter our business model.  The vendor would not give me a straight answer as to exactly how much of our product would need to be open-sourced if we took on their product.  At this point I could've gotten our legal department involved but that tends to be slow.  Much better to have the vendor speak to our management team directly.  

    I organized another presentation with the NoSQL vendor and they started out touting the free, open source nature of their product, case studies of its success, etc.  This time the audience was the senior architects and the management team.  About 10 minutes into it I raised my hand and asked very pointedly, "How much will your product cost us in licensing if we choose NOT to open source our product under the terms of the GPL?"  The vendor attempted to deflect but I kept pushing.  Eventually the vendor opened a different Prezi that discussed alternative closed source licensing arrangements.  Clearly they had different presentations based on where the customer was in its implementation of their product.  The vendor did not realize that I did my homework and knew this was going to happen.  Neither did our management.  Or our architects.  "Deer in the headlights" does not do justice to the looks on everyone's faces.  

    The alternative licensing was MORE EXPENSIVE per node than SQL Server, not to mention it was a distributed document store which would have meant LOTS of small, little licenses for small, little nodes.  It was eye-opening for management.  There would be no cost savings.  We quickly had our developers pick a document store that was Apache licensed and we delayed our release for a few months until we could rewrite.  

    From then on there were policies on which OSS licenses we could use and rules regarding what could be redistributed.  Our Legal Department was now required to sign off on ANY third party tool where the code was checked in and integrated with our source code.  This event scared management so much that they brought in Black Duck Software to make sure our exisitng software portfolio wasn't hiding any other potential OSS timebombs.  (It was).  

    Since then customers of our software have also performed the equivalent of Black Duck audits on our software to make sure we were being thorough and honest.  This is mission-critical software.  With GPL software it isn't just the licensee that can get caught up in a licensing battle, it is the "licensee or assigns", which means anyone who purchases our software.  The ramifications of this is really scary.  You could purchase a piece of software and through no fault of your own find yourself on the receiving end of a lawsuit because your vendor was improperly using GPL'd software.  This is another reason why IP rights are so dangerous.  

    All hail Apache?
    Apache licensing has problems too, IMHO, that you should be aware of.  The business model for Apache licensed software brings its sustainability into question, always.  An example is OpenSSL.  It is Apache licensed and is supported by the equivalent of a handful of full-time developers.  It has almost ZERO revenue to sustain the software.  Something like Heartbleed was bound to happen under this situation.  OpenSSL has a large, avid following.  Cisco and M$ use it...heck, it's embedded in EVERYTHING.  And very few users have given ANY money to the project to sustain it because it is Apache licensed (IMHO) and therefore viewed as totally free (without cost).  "Let someone else pay for it".  The very backbone of security on the internet is in the hands of a few OpenSSL developers because no one wants to contribute money.  It is an 800 lb gorilla.  In this case maybe GPL software is a bit better.  If the price isn't too steep.  And since Heartbleed there are some new GPL'd alternatives to OpenSSL that may be safer and more sustainable simply because the revenue-generation model is better.  Only time will tell of course.  Others have pointed out that something as critical as OpenSSL should be closed source anyway.  Again, time will tell.  Perhaps the best answer is a consortium of vendors that can take over OpenSSL and give it the care and feeding it needs, without resorting to GPL.  I'm certainly no expert in any of this.  But it is fascinating.  

    Why is this so gd complicated?  Another story

    Now you see why I think IP rights cause more grief than they solve and why EVERYTHING I do on this website is public domain with ZERO licensing, not even Apache licensing.  (I always appreciate an attribution, but I'm not going to sue you if you don't).  It's just not worth it to me to deal with all of this licensing.  I don't even have a copyright notice on this site, although I probably should.  

    ￼I do some side work as a Drupal consultant.  Drupal is GPL.  Yet there is a lot of Drupal code out there that is available only for a fee.  Especially themes.  People often wonder how that arrangement is possible.  If GPL forces derivational products to also be GPL'd, then how can a themer charge for a Drupal theme?  Very easily.  The themer must provide the source code for any theme and therefore the customer can do anything with it thereafter, including give it away for free.  

    Sounds goofy doesn't it?  

    I once bought a theme for $50 because it had everything my customer wanted...cool graphics, the ability to skin minutae, it was "responsive" (the ability to resize dynamically to the new form-factor devices coming to market daily), and had lots of other features not available elsewhere.  After I got the code for the theme I realized I was sold a lemon.  The theme did nothing advertised and had ZERO documentation.  I politely asked for my money back and was denied by the vendor, who spoke little English.  I then threatened to simply follow the terms of the GPL license and modify a few bits and re-release the new theme as my own and give it away for free.  

    I had his attention now.  He told that was not legal that his theme was his, not mine.  "Nope, sorry, you supplied me with a Drupal theme.  Drupal is GPL therefore your theme is GPL too.  I can modify it however I choose and re-release it to the world.  I can't wait to give your hard work away under my name."  Needless to say my $50 was promptly refunded.  

    ## https://blog.p2pfoundation.net/why-apache-defeated-the-gpl-license-developer-freedom-vs-user-freedom/2013/01/21

    the early open source business model, which used the GPL to essentially build a proprietary software business from free software licensing. That is, with the GPL, an open source vendor could give away its software under a license that many viewed as radioactive, to the extent that it was completely open… and effectively proprietary. Given that the GPL requires any derivative works to also be licensed under the GPL, including third-party software that links to GPL software, depending on how the developer links the software, the GPL puts fear into the heart of legal counsel of would-be users and commercial developers of GPL software. It is free to use, but the possibility of “tainting” one’s code is a risk many simply refuse to take. As such, it is open but closed to such companies, that is, impossible for them to accept using without purchasing a proprietary license to use the GPL software.

    # open source business models

    ## https://medium.com/@stephenrwalli/there-is-no-open-source-business-model-cdc4cc20238

    Well run open source software communities are interesting buckets of technology. If they evolve to a particular size they become ecosystems of products, services (support, consulting, training), books and other related-content. To use an organic model, open source is trees, out of which people create lumber, out of which they build a myriad of other products.

    Soon after Fedora was delivered such that a Red Hat focused developer community would have an active place to collaborate while Red Hat maintained stability for enterprise customers on RHEL.

    Harvard economist Theodore Levitt once observed that a customer didn’t want a quarter inch drill, what they wanted was a quarter inch hole. 

    comment
    Applause from Stephen Walli (author)
    ￼
    balaji bal
    Jan 6
    An article of its time, and one I wished had been written earlier. Have been speaking to a number of OSS companies in the past 3 months (especially smaller breakthrough projects) and found most of them struggling with the ‘OSS as business model’ question — rather than IMHO viewing Open Sourcing as a ‘production methodology’. The de facto ‘enhancement and services based’ model is increasingly being challenged with the entrance of institutional investors into the OSS space. The root cause of which seems to be the institutional investors dislike of ‘transactional models’ vs ‘subscription based models’. The net result is a large number of companies building SaaS products (at least in the Cloud Space) instead of Standalone (self-hosted) software. My observation based on speaking to the companies behind OSS (some 20–30) of them is that the next 2–3 years will be a defining period in the further development of “OSS Business Models”.

    ## https://techcrunch.com/2016/02/09/the-money-in-open-source-software/

    ### Think about a business model from day one

    This seems obvious, but you’d be surprised how often open-source entrepreneurs think of their business model only after their free-software downloads are off the charts. In contrast, our experience suggests that some of the best open-source companies had a clear idea of how they were going to make money from their early days.

    Companies often do this by selling enterprise versions of open-source projects with extra security and management features. These are designed to appeal to the large enterprises that are big IT spenders. Another option is to offer a premium SaaS service, essentially a pay-as-you-go model. While delivering a reliable service can be difficult — namely, packaging many open-source components together into one compelling, cloud-based offering — SaaS can be another route to revenue.

    So while Red Hat maintained a vibrant open-source community around Fedora, updating it with new features and releases every six months, the company marketed enterprise-grade security and optimization on standard Intel hardware to people using the paid enterprise product. This allowed Red Hat to build a recurring revenue stream of more than $1 billion from enterprise customers; it also, more broadly, helped Linux become the most widely adopted server operating system.

    ### Pick a licensing model aligned with your monetization strategy

    Keep in mind that even open-source software is always owned by someone, usually either a for-profit company or a non-profit foundation (kumbaya only goes so far). Licenses range from permissive (Apache) to restrictive (General Public License, or GPL, variants, with Affero GPL the most restrictive), and everything in between.

    ### Ancillary services and “hand holding” may be necessary, but don’t get hooked on them for revenue

    Open-source software has disrupted some of the most important technologies in enterprise infrastructure: think MongoDB and Cassandra taking on legacy Oracle databases, OpenStack and Docker threatening virtualization giant VMware and Linux displacing Solaris and Windows Server software. What helped these open-source underdogs grow was real-world successes — not, as some entrepreneurs think, pricey consulting services to augment deployments.

    In the early days of open-source adoption, of course, some professional services and “hand holding” may be necessary to get open-source systems off the ground, especially when customers are dealing with integrating legacy software. Indeed, some of the earliest Hadoop, OpenStack and Cloud Foundry deployments needed consulting services to make key customers successful.

    But don’t try to build your business on services revenue. It carries a lower gross profit margin than other revenue streams — perhaps 20-30 percent, as opposed to 90 percent for product-related revenue — and it’s not generally repeatable. Ultimately, if you’re successful, you’ll have millions of users, but you’ll only be able to tap perhaps a few hundred of them for services revenue.

    Plus, if you chase services revenue too aggressively you could wind up competing with services partners (e.g., Accenture, IBM) that could help bring you new users. Our advice: Focus on building your recurring revenue from subscriptions, which should be your high-margin core product. Build your services organization to support customer success and partner success, not to drive revenue. What’s more, we would even support aggressively cannibalizing your services business by making your product easier to use and your partners more capable, so that they can take over running it themselves in the longer term.

    ### Ongoing customer satisfaction trumps upfront sales

    Sales cycles in open source are very different from those in traditional, enterprise software. With regular, enterprise software, it’s often hard to convince customers to use the technology; on top of that, they have to pay for it. In open source, that decision process is often bifurcated, happening in two separate steps. Convincing people to use your software is often much easier, because the product may be initially free. But then you face a separate task, later, to convince them to pay.

    This shift can be disorienting for those who are used to traditional enterprise-software sales and marketing. Reps can spend lots of time trying to convince someone to use your software — and succeeding — but then not wind up with any revenue for their effort. In the early days of your company, that might be okay, because you’re also trying to build your user base, which could turn into revenue later.

    But even after you grow, and start racking up sales, you need to become very disciplined about getting your sales team to focus on ongoing customer satisfaction, because happy customers buy more, and buy products with higher ASPs (average selling prices). This, in turn, helps subsidize your ongoing R&D. Overall, this is quite different than most enterprise-sales models, which focus on making the sale and moving on to the next prospect.

    Salespeople need to be measured on the subscription revenue they are bringing in, while a separate team focused on community should nurture adoption growth. This may mean hiring a different type of salesperson — someone who may not be from the high-pressure Oracle mold, for instance, though those folks can still succeed with the right type of training.

    At MongoDB, we had a very successful salesperson who had previously started a sports-uniform business and another business to clean roof gutters. He may not have had a lot of software experience, but he was fanatical about customer satisfaction.

    ## https://opensource.com/business/16/4/refactoring-open-source-business-models
    we switched to a higher touch "customer success" model that involves encouraging customers to ask questions, regardless of whether they would be traditionally triaged as support questions. For instance, in our old, traditional support model, we might only handle requests related to stack traces and production issues, but not business/developer issues, such as how best to improve the quality of results or how to incorporate machine learning into an application. Today, we routinely answer all types of questions, as they help the customer be successful. For those cases in which the answer is more involved or the client wants detailed help, we offer consulting. In many cases, the customer just needed a point in the right direction when implementing a feature. This may seem obvious, but most support centers at most companies are geared toward call deflection, not engagement. Our approach has yielded a significant improvement in renewal rates for us on the pure support side of our business. Care must be taken to make sure support expenses don't spiral out of control, however, and that these touchpoints don't turn into hours of free consulting.

    Open core or commercial extensions

    Many companies go this route hoping they can get people to pay for value-add capabilities, such as better administration tools. The challenge for companies in this space usually falls under the category of fear of vendor lock-in (never mind that any choice locks you in). Or the community builds similar features, which you're also forced to support and differentiate against. If you find a sweet spot, you can maintain margins while still being good stewards of the community, but it takes a keen eye for product development, and is often grown into after doing a fair bit of consulting and support to better understand what users actually need. For example, in our first iteration of our product (Lucidworks Search), it was developed mainly by looking at features of the previous generation of search products on the market, and it was tightly coupled to Solr, which prevented users from taking advantage of Solr's full feature set.

    Although the product wasn't completely designed in a vacuum, feedback often focused on how we were hiding too much of Solr or that their plugins didn't work with it. Internally, even our own developers often felt conflicted working on it because it was competing too much with the open source project itself instead of complementing it. With our new architecture and product (Lucidworks Fusion), we can connect and work with a number of different versions of the main project (Solr) we support, and we also integrate other key open source projects, like Apache Spark. We look at it as an extension of, not a replacement for the open source. We also look for more ways to capture and use more data intelligently, as opposed to writing smarter, proprietary algorithms.

    https://opensource.stackexchange.com/questions/6234/is-there-a-generally-accepted-anti-copyleft-clause-or-license
