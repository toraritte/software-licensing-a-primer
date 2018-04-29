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

# opportunitites and potential use cases

Access news
* to teach literacy and languages (spelling, enunciation)
* ‎AD and voice over coaching as a service

SFTB as a hub for innovation and learning
Study groups for coding, project management, planning any skills of interest.
Sftb may not benefit from it directly but it will be in the center of innovation
Open for everyone
Freeform mentoring
Blind students!
No commitment s
Only rule is: do not disrupt

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
