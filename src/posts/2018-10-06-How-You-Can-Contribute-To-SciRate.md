---
title: How You Can Contribute to SciRate
author: Noon van der Silk
---

Since 2017, I've been managing and funding SciRate on my own. But SciRate
hasn't survived, since it's inception
[2007](https://dabacon.org/pontiff/?p=1418), through entirely the time and
money of one person. Any community needs involvement from community members to
thrive. It's actually quite a great example of an open-source projcet that has
changed hands several times over the years.

I'd now like to invite participation from you, the community, and outline a
few ways in which you can become involved.


## 1. Milestone Feature Development

The biggest feature on the roadmap is: integrating other services.

Here is my order of preference:

- [ECC (scirate/github issue 205)](https://github.com/scirate/scirate/issues/205)
- [ChemRxiv (scirate/github issue 346)](https://github.com/scirate/scirate/issues/346)
- [Cryptology ePrint Archive (scirate/issue 206)](https://github.com/scirate/scirate/issues/206)
- [bioRxiv (scirate/issue 206)](https://github.com/scirate/scirate/issues/206)
- [PeerJ (scirate/issue 206)](https://github.com/scirate/scirate/issues/206)

Presently, SciRate acts _only_ as a front for the arXiv; but the dream was
always to add more back-end services. The more such services that are added,
the more useful SciRate will be as a service for paper discovery.

Luckily, the team that developed the present version of SciRate (mostly
[Jaiden Mispy](https://mispy.me/)) did an excellent job, and the database
structure is essentially in place for this kind of integration to be done. The
main task in any integration is working out how to bring in their paper feed
into our database. The best place to look is
[here](https://github.com/scirate/scirate/blob/3225f14960024816f514fa3236738c644c92124f/lib/tasks/arxiv_paper_sync.rake)
and [here](https://github.com/mispy/arxivsync).

I'd estimate about ~2 weeks of full-time work, for someone moderately
experienced with Ruby to pull this off. If you're keen to work on this, then
get in touch with me and I can help guide you through it, but putting some
more details in the relevant issues.


## 2. Bug Fixing, Issue Reporting, Feature Requests

There's a bunch of minor things that can be worked on by people familiar with
Ruby: [scirate issues on GitHub](https://github.com/scirate/scirate/issues).

I've been very-slowly attempting to highlight the easier tasks with the "help
wanted" tag on GitHub: [github/scirate issues - "help
wanted"](https://github.com/scirate/scirate/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22).

Contributing to fixing minor bugs in SciRate is actually how I first started
my involvement in the site, way back when [Bill
Rosgen](http://intractable.ca/bill/) was managing it.

We're also very happy to receive pull requests adding new features!


## 3. Community Leadership

SciRate has a small group of moderators, and I'm open to more people joining.
If you're interested, get in touch via the [mailing
list](https://groups.google.com/forum/#!forum/scirate).

I'm also open to other community engagements, such as a slack channel, for
more free-flowing conversations. If you have an interest in this, then get in
touch.

Please also have a careful read of the (new!) [Code of Conduct](https://scirate.com/conduct).


## 4. Funding and Sponsorship

As I mentioned, presently SciRate is funded entirely by me, with no academic
or corporate backing. If you're an institution or organisation and you'd like
to:

- Reach a large community of researchers (5000+, and growing by hundreds each month), 
- Support our open-science mission and Improve the way science is done,

Then please [email me](mailto:noonsilk@gmail.com); it'd be amazing to have your support!


