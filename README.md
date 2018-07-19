# Un guide pratique pour trouver des financements pour l'open source
*"Je travaille en open source, comment trouver un financement?"*


Ce document a pour objectif de fournir une liste exhaustive de toutes les façons dont les gens sont payés pour faire leurs travaux open source. Nous espérons que certains projets ou contributeurs trouveront la meilleure option pour eux dans ce document.

La liste ci-dessous est ordonnée par ordre d'ampleur. Chaque catégorie renvoie à plusieurs exemples réels (avec explication de leur choix quand cela est possible).

Les categories ne sont pas mutuellement exclusives. Par exemple, un projet peut être associé à une fondation mais peut aussi utiliser les levées de fond pour trouver de l'argent. On peut aussi faire du consulting et avoir un bouton de donation. Etc.

---

# Table des matières
1. [Bouton "donner"](#donation-button)
2. [Bounties](#bounties)
3. [Crowdfunding (one-time)](#crowdfunding-one-time)
4. [Crowdfunding (recurring)](#crowdfunding-recurring)
5. [Books and merchandise](#books-and-merchandise)
6. [Advertising & sponsorships](#advertising--sponsorships)
7. [Get hired by a company to work on project](#get-hired-by-a-company-to-work-on-project)
8. [Start a project while currently employed](#start-a-project-while-currently-employed)
9. [Grants](#grants)
10. [Consulting](#consulting)
11. [Paid support](#paid-support)
12. [SaaS](#saas)
13. [Dual license](#dual-license)
14. [Open core](#open-core)
15. [Foundations & consortiums](#foundations--consortiums)
16. [Venture capital](#venture-capital)
17. [Shared source](#shared-source)

APPENDIX: [Contributing to this guide](#contributing-to-this-guide) // [License & attribution](#license-and-attribution)  
TRANSLATIONS: [Traditional Chinese(繁體中文)](https://github.com/jserv/lemonade-stand) // [Simplified Chinese(簡體中文)](https://github.com/wizicer/FinancialSupportForOpenSource) // [Italian(italiano)](https://github.com/dakk/lemonade-stand) // [Japanese(日本語)](https://github.com/fumikito/lemonade-stand)

**"personal effort" notes when a funding effort was led by an individual, not a project*

## Bouton "donner"

*Ajoutez un bouton "donner" sur votre site. Vous pouvez utiliser Stripe ou PayPal, par exemple, pour accepter les donations*

#### Avantages

* Pas ou peu d'engagement
* Peu de travail pour la mise en place: "set it and forget it"

#### Inconvénients

* Génère peu d'argent sauf si vous déployez des efforts particuliers pour la levée de fonds;
* Besoin d'une plateforme intermédiaire pour recevoir l'argent. Les plateformes comme Stripe et PayPal prélèvent une taxe sur les transferts d'argent;
* Afin de faire une donation nette d'impôts, il faut que l'organisation qui reçoit les fonds soit reconnue d'utilité publique (aux états unis, c'est une 501(c)(3) organisation à but non lucratif);
* Parfois difficile d'identifier qui "mérite" l'argent dans un projet ou comment cet argent est distribué. Une organisation comme [OpenCollective](http://opencollective.com) peut aider.

#### Etude de cas

* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)
* [ChatSecure](https://chatsecure.org/blog/sustainable-open-source-starts-with-you/)

## Bounties

*Parfois, des projets ou des compagnies offrent des récompenses (bounties) pour des travaux open source (par exemple "corrigez ce problème contre 100€"). Il y a de nombreux sites web (listés ci-dessous) qui centralisent les offres et facilitent la récupération de la récompense*

#### Pros

* Ouvert à la participation de la communauté
* L'investissement est associé à un travail spécifique (plus comme un service payé que comme une donation)
* Particulièrement populaire en sécurité informatique

#### Cons

* Peut avoir des effets pervers (Pull Request faites à la va-vite, ...)
* Conflits pour savoir si un travail mérite une récompense ou pas
* Généralement peu d'argent pour chaque récompense
* Revenu irrégulier

#### Case Studies

* [Gitcoin](https://gitcoin.co/explorer)
* [Bountysource](http://bountysource.com)
* [Internet Bug Bounty](https://internetbugbounty.org/)
* [Google Patch Rewards](https://www.google.com/about/appsecurity/patch-rewards/)
* [GitHub Bug Bounty Program](https://bounty.github.com/)
* [Status Open Bounty](https://openbounty.status.im/)
* [Yes We Hack](https://yeswehack.com/en/index.html)

## Crowdfunding (one-time)

*If you have a specific idea you'd like to implement (rather than ongoing project work), a one-time crowdfunding campaign can help raise the funds you need. Both individuals and companies might be willing to donate to your campaign.*

#### Pros

* Few strings attached
* Can be easier for an individual to legally manage via, e.g. [Kickstarter](https://kickstarter.com/)

#### Cons

* Lots of work involved to market campaign
* Usually has to be tied to concrete outcome, perks
* Usually not that much money (~$50K for one time)
* Companies not always comfortable donating to campaigns

#### Case Studies

* [GDAL Coordinate System Barn Raising](https://gdalbarn.com/)
* [Dave Gandy + Font Awesome](https://www.kickstarter.com/projects/232193852/font-awesome-5)
* [Michal Papis + Rvm (personal effort)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (personal effort)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (personal effort)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://poststatus.com/kickstarter-open-source-project/)
* [Monero Forum Funding System (FFS)](https://getmonero.org/forum-funding-system/)
* [Dash Budget Proposal Tracker](https://dashvotetracker.com/)

## Crowdfunding (recurring)

*If you'd like to fund ongoing project work, you can set up a recurring crowdfunding campaign, with a monthly or annual financial commitment that renews indefinitely (or until the donor cancels). Those who use your project regularly (including both individuals and companies) might be willing to fund your work.*

#### Pros

* Few strings attached
* Can be easier for an individual to legally manage via, e.g. [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Liberapay](https://liberapay.com/), [OpenCollective](https://opencollective.com), [Flattr](https://flattr.com/)

#### Cons

* Harder to get commitments to recurring donations (often requires preexisting brand/reputation)
* Harder to explain concrete outcomes, perks that come with recurring donations
* Usually not that much money (~$1-4K monthly)
* Companies not always comfortable donating to campaigns

#### Case Studies

* [Evan You + Vue.js Patreon](https://www.patreon.com/evanyou)
* [Eran Hammer + hapi Patreon](https://www.patreon.com/eranhammer)
* [webpack](https://opencollective.com/webpack)
* [Babel](https://opencollective.com/babel)
* [GnuPG](https://www.gnupg.org/donate/index.html)
* [Tom Christie + Django REST framework (personal effort)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)
* [Clojurists Together](https://clojuriststogether.org)

## Books and merchandise

*If you are an expert in a domain that other people might find useful to learn about, you could write and sell a book or series of books. You can find a publisher (like O'Reilly) or self-publish. In addition to selling books, some projects sell merchandise (ex. shirts, hoodies) to support their work.*

#### Pros

* Outcome not tied to project work itself, so you retain creative freedom
* Can serve as marketing for the project itself
* Can be recurring source of revenue after initial development

#### Cons

* Often not a significant source of revenue
* Can distract from core development of project
* Merchandise can have upfront costs

#### Case Studies

* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (personal effort)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (personal effort)](http://www.poodr.com/)
* [Kyle Simpson + You Don't Know JS (personal effort)](https://github.com/getify/You-Dont-Know-JS)
* [CocoaPods (fundraising for charity)](https://cocoapods.org/socks)

## Advertising & sponsorships

*If your project has a large audience, you can sell sponsorships to advertisers who might want to reach them. You probably have a very targeted audience (ex. if you have a Python project, you can assume your audience is likely people who are technically familiar with Python), so use that to your advantage.*

#### Pros

* Business model aligned with something people are willing to pay for

#### Cons

* Need large enough audience to justify sponsorships
* Need to manage trust and transparency with user base (ex. no tracking)
* Can be a lot of work to find and manage clients
* Can involve ethical concerns about marketing
* Can introduce a conflict of interest; making controversial changes could result in losing sponsors/advertisers 

#### Case Studies

* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)
* [Code Sponsor](https://codesponsor.io)
* [GitFund](https://gitfund.io)

## Get hired by a company to work on project

*Companies sometimes hire individuals to do open source work. Find a company that uses the project you want to work on. Often this is a split arrangement (ex. 50% company work, 50% open source work). Alternatively, if you have an idea for a new project, find a company that would be interested in using what you produce. In these situations, having demonstrated experience you can point to will be very helpful.*

#### Pros

* Taps into those who have resources (i.e. companies)
* Can be well-aligned with company needs
* Steady income

#### Cons

* Usually involves “getting lucky”: no clear, repeatable path to finding this arrangement
* Project already needs to be well-known and used
* Person not contributing to company’s bottom line, which makes them expendable
* Governance issues, company could have undue influence over project
* Can affect project dynamics + balance

#### Case Studies

* [Donald Stufft + Hewlett-Packard and Python packaging (personal effort)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (personal effort)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (personal effort)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

## Start a project while currently employed

*Many open source projects started as employee side projects. The project might eventually outgrow the company, but starting it as a side project can be a great way to incubate the idea.*

*If you pursue this path, make sure you understand your company's policy on open source work. Some companies encourage employees to contribute to open source during working hours. Some might treat your open source work as a company project. Don't assume anything; ask someone at your company before starting.*

#### Pros

* Freedom to test new ideas without worrying about salary
* Can be well-aligned with company needs
* Suitable for newer, experimental ideas

#### Cons

* Need to do it as a side project or be approved to work on it during salaried time
* Risk of undue company influence
* Can lead to complicated governance later down the line

#### Case Studies

* [Mozilla and Rust](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Google and Go](https://golang.org/doc/faq#history)
* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)

## Grants

*Grants are effectively large donations that do not require repayment. Oftentimes the grantmaker receives other benefits from giving you the grant, such as access to you, demonstration of impact, a report of your work, or tax benefits.*

*Grants can come from many places, including companies, software foundations, philanthropic foundations, and the government. The technical and legal aspects of a grant vary greatly depending on where it comes from. For example, a company might give you a "grant" but legally treat it as a consulting invoice. A philanthropic foundation can only make grants to nonprofits, so you would need to be a nonprofit yourself, or (more commonly) find a nonprofit to sponsor you. If you're unfamiliar with grants, the best way to understand how grants work is to talk to someone who has received one before. Some examples of grant recipients are listed below.*

#### Pros

* Fewer strings attached
* Guaranteed money can help project focus for an unbroken period of time
* Gives project room to breathe and experiment

#### Cons

* There aren’t many software-related grantmakers (philanthropic, gov’t, corporate)
* Grants are finite. Still need to find sustainability beyond the life of a grant

#### Case Studies

* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Libraries.io grant applications](https://github.com/librariesio/supporters)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)
* [Segment Open Fellowship](https://segment.com/blog/segment-open-fellowship-2017/)

## Consulting

*Consulting can be a flexible way to fund open source work. You have more freedom to structure your time as you wish (for example, consulting 30 hrs of the week and spending 10 hrs of the week on open source work). Consultants can usually charge more for their time than salaried employees because the work is less steady, they don't receive benefits, etc. If you plan on doing this type of work regularly, you will probably want to set up an LLC (or equivalent outside of the US).*

*If your project is popular, you can also offer consulting & services around the project itself. For example, a client might pay you to implement the project for them, build something custom, or train them on how to use it.*

#### Pros

* Business model aligned with something people are willing to pay for

#### Cons

* Consulting requires human power, doesn’t scale well (except for rare outliers)
* Business needs can distract from writing code or other tasks related to the project itself
* Can be at odds with making software simple to use
* Project needs to be sufficiently popular that people are willing to pay for related services

#### Case Studies

* [Varnish Moral License](http://phk.freebsd.dk/VML/)
* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

## Paid support

*In this model, the code is freely available, but users need to pay to receive support from the project's maintainers. That might mean charging for access to the issue tracker, office hours, a community Slack, or an SLA (service-level agreement).*

#### Pros

* Business model aligned with something people are willing to pay for

#### Cons

* Can be at odds with making software simple to use
* Project needs to be sufficiently popular that people are willing to pay
* Maintainers don't necessarily want to offer professional support

#### Case Studies

* [Prism](https://www.patreon.com/prismlibrary) - supporting their Patreon gives you access to their community Slack channel for project support
* [Tidelift paid subscriptions](https://tidelift.com/subscription)
* [Red Hat](https://en.wikipedia.org/wiki/Red_Hat#Business_model)

## SaaS

*SaaS means [Software as a Service](https://en.wikipedia.org/wiki/Software_as_a_service). In this model, the codebase itself can remain open source, but you offer paid services such as charging for use of a main hosted site or for handling the hosting of dedicated instances for customers. Typically, paying customers also get priority support.*

#### Pros

* Can build community around open project and make money off of services for hosting
* Allows open source project to focus on users and as needs grow to help enterprises adopt the project
* Can scale by number of users

#### Cons

* Often means the hosting needs to be cheaper than hiring a dev to run the project for you.
* “Two tiers” of product support can make free users unhappy

#### Case Studies

* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [WordPress.com](http://wordpress.com/)
* [Discourse](https://www.discourse.org/)
* [Ghost](https://ghost.org/about/)
* [GitLab](https://gitlab.com) (also uses open core licensing)

## Dual License

*Companies prefer to include permissively licensed code (such as MIT or Apache 2.0) rather than copyleft licensed code (like the GPL) in their software, because the latter requires them to keep the same copyleft terms for their end products. So, some open source projects use a dual-license approach: the default project license is copyleft, but they sell either proprietary or permissive commercial licenses to companies who want to bypass the copyleft requirements.*

#### Pros

* Business model aligned with something people are willing to pay for
* Can scale well if successful

#### Cons

* Can be at odds with making software freely accessible
* Project needs to be big enough that customer need exists
* Only works for upstream software that's being used in downstream software
* There can be legal or monetary barriers to moving code from open to proprietary 

#### Case Studies

* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)
* [Metafizzy](https://metafizzy.co) (ex. [Isotope](https://isotope.metafizzy.co/license.html), [Flickity](https://flickity.metafizzy.co/license.html))
* [Qt](https://www1.qt.io/faq/#_Toc_3)

## Open core

*Under an [open core](https://en.wikipedia.org/wiki/Open_core) model, some aspects of the project are free, but other features are proprietary and available only to paid users. Usually this works when there is enterprise demand for the project.*

#### Pros

* Business model aligned with something people are willing to pay for
* Can scale well if successful

#### Cons
* Need to have something you can charge for (which means making certain features exclusive)
* Can be at odds with making software freely accessible
* “Two tiers” of product support can make free users unhappy
* May require a CLA (Contributor License Agreement) in order to accept code submissions from outside contributors while retaining the ability to relicense those submissions under the proprietary license

#### Case Studies

* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Phusion Passenger](https://www.phusionpassenger.com/); see also their talk, ["Bootstrapping a Business Around Open Source"](https://www.youtube.com/watch?v=uHaMpLyMOL0&feature=youtu.be) (video)
* [Sidekiq](http://sidekiq.org/)
* [Caddy](https://caddyserver.com/blog/accouncing-caddy-commercial-licenses); see also [retrospective](https://caddy.community/t/the-realities-of-being-a-foss-maintainer/2728/7)
* [GitLab](https://about.gitlab.com/)

## Foundations & consortiums

*A [foundation](https://en.wikipedia.org/wiki/Foundation_(nonprofit)) is a legal entity that can accept and/or disburse donations. Because their purpose is not to make profits, they can be a great choice to signal neutrality and steward a project. In the US, foundations are either 501(c)(3) (nonprofit) or 501(c)(6) (trade consortium). Many software foundations are 501(c)(6) because 501(c)(3) require demonstrating a charitable purpose, which can be more difficult in software.*

#### Pros

* Neutrality. Foundation protects the code and helps steward community
* Influence distributed across multiple donors
* Can legitimize project, companies might feel more comfortable giving to foundations than individuals

#### Cons

* Only really worth it for big projects
* Difficult to set up for IRS reasons (many do 501(c)(6) instead of 501(c)(3)), restrictions on what you can do
* Requires serious community effort and diverse skills (you still need to fundraise after setting up the entity!)

#### Case Studies

* [Linux Foundation](https://www.linuxfoundation.org/)
* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)
* [Signal Foundation](https://signal.org/blog/signal-foundation/)

## Venture capital

*Venture capital is a form of funding for high growth businesses. Unlike a bank loan or other forms of debt financing, venture capitalists take equity (a percent ownership in your business) in exchange for funding. Unlike taking out a loan, you don't have to repay your creditors if your business tanks. If you do succeed, however, you should expect to return capital to your investor at a multiple.*

*Venture capital is "high risk high reward": VCs are more risk tolerant than banks, but they also expect a large payoff if you are successful. If you plan on raising venture capital, you should set up a business entity structured as a C Corp, preferably in Delaware. If you're unfamiliar with the venture capital process, the best place to start is by reaching out to similar founders who have successfully raised venture.*

#### Pros

* Institutional support can be helpful for growing a business
* Large amounts of capital available

#### Cons

* Venture capital comes with expectations of an exit (i.e. returning the money to investors at a multiple). History suggests this is structurally difficult to achieve for open source businesses. Venture Capital isn't actually a business model but only investment capital for those who have some *other* business model for future revenue.
* Venture capital can change motivations and distract from priorities
* Unavailable to non-profits

#### Case Studies

* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)

## Shared source

*Shared source licenses (reminiscent of the older [shareware](https://en.wikipedia.org/wiki/Shareware) movement) are **not open source** because they do not meet all the [required freedoms](https://en.wikipedia.org/wiki/The_Open_Source_Definition) of an open source license. With shared source, the source code is available (either publicly or at least to customers who pay for a license), but they may limit the freedoms to redistribute and modify or to use the software commercially, and so on. Still, they are tangentially related to open source work.*

#### Pros

* Business model aligned with something people are willing to pay for
* Potential to scale well if successful

#### Cons

* Not actually open source (so may fail to achieve many or most of the benefits of open source)

#### Case Studies

* [Fair Source](https://fair.io/), used by [Sourcegraph](https://sourcegraph.com/)
* [BSL (Business Source License)](https://mariadb.com/bsl-faq-adopting), used by [MariaDB](https://mariadb.com/)
* [License Zero](https://medium.com/licensezero/the-license-zero-manifesto-fecb7aaf4c0a)
* [Ungit switched back from Faircode to MIT License](https://github.com/FredrikNoren/ungit/issues/997)


---

### Contributing to this guide

I wrote up this guide to aggregate my own knowledge. I recognize the pros/cons are somewhat subjective, but they reflect my views. If you submit changes, I may consider them but do not intend to cover everyone's viewpoints.

If something is factually incorrect (especially with a case study example), I welcome your edits. Also, if there's a category you know of that I missed, I would also welcome that addition.

### License and attribution

This guide is available under the Creative Commons CC0 1.0 License, meaning you are free to use it for any purpose, commercial or non-commercial, without any attribution back to me (public domain). If you do use it, I'd love to hear about it! (Find me here: [@nayafia](http://twitter.com/nayafia)) But you are in no way required to do so.
