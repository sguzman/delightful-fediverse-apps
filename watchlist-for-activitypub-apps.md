This is the list of projects that may be implementing ActivityPub, which began in issue https://gitlab.com/fediverse/fediverse.gitlab.io/issues/8

*Note*: none of these apps ought to be added to the official fediverse.party site until they have been tested with at least one (ideally 2-3) of the AP apps already listed, and can be confirmed to federate successfully. Once it is on the official site, it can be removed from this list, keeping it a list of apps to be watched/ tested.

*Note*: most of these projects include both a back-end and a web client, but this list also includes projects that are only a back-end. Projects that are only a web app, for use with an existing back-end, will go on the client list here:
https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/watchlist-for-client-apps

The [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hope will implement ActivityPub and links to Issues where it&#39;s discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). @Mayel from Social.coop is maintaining a [web spreadsheet of AP apps](https://ethercalc.org/fediverse-stacks) and their characteristics. More projects using AP are [profiled on We Distribute](https://medium.com/we-distribute) by Sean Tilley. From these and other sources (see links), it looks like all these apps are either considering, working on, or already rolling out AP support:

*Social network, Microblog Apps*

* [Aardwolf](https://github.com/Aardwolf-Social/aardwolf)

* [Indienet](https://source.ind.ie/project/heartbeat-cocoa/issues/194#note_10162)

* [Kroeg](https://github.com/puckipedia/Kroeg)

* [pump.io](https://github.com/pump-io/pump.io/issues/1241)

* [microblog.pub](https://github.com/tsileo/microblog.pub) - single-user microblog server

* [microstatus](https://github.com/Arkanosis/microstatus) - "Lightweight Mastodon- and GNU social-compatible ActivityPub and OStatus server implementation"

* [Osada](https://macgirvin.com/wiki/mike/Osada/Home) - an AP server that can also act as a bridge for smoother inter-operation between AP networks and Zot networks (Hubzilla)

* [Rustodon](https://github.com/rustodon/rustodon)

* [Smilodon/ Pylodon](https://blog.rowan.website/2017/12/23/pylodon/) - web front-end / back-end written in Python

* [PeerPx](https://github.com/peerpx) - social network for photographers ("alternative to 500px / Flickr")

*Blog and Publishing Apps*

* [Dokie.li](https://dokie.li/)

* [Ghost](https://forum.ghost.org/t/federate-over-activitypub/1989/15)

* [Known](https://github.com/idno/Known/issues/1701)

* [Plume](https://github.com/Plume-org/Plume)

* [Write Freely](https://writefreely.org)

* [Read.as](https://github.com/writeas/Read.as) - a reading app for long-form text shared over the fediverse

*Link-sharing Apps*

* [Anancus](https://gitlab.com/tuxether/anancus)

* [Prismo](https://gitlab.com/mbajur/prismo)

*Media-hosting Apps*

* [Anfora](https://github.com/anforaProject/anfora) (formerly Zinat) - image sharing

* [FunkWhale](https://medium.com/we-distribute/funkwhale-an-open-source-grooveshark-alternative-begins-activitypub-implementation-cbc10a412b20) - music streaming

* [MediaGoblin](https://issues.mediagoblin.org/ticket/5503) - streaming of any and all media files

* [PixelFed](https://pixelfed.org/) - image sharing

* [Quit.im](https://quit.im/) - this is a photo-sharing web client for a GNU social server, rather than a completely separate app, so it will become an AP implementation when the AP plug-in for GS is done.

* [snap.as](https://github.com/snapas) - photo sharing
 
*Events Apps*

* [Calendar-social](https://gitea.polonkai.eu/gergely/calendar-social/issues/122) - no specific mention of ActivityPub on the repo but rumour on the fediverse is that it will be an AP app. I will post a question on their issue tracker.

* [GetTogether](https://github.com/GetTogetherComm/GetTogether/issues/60)

*Files, Contacts, and Calendar Syncing Apps*

* [NextCloud](https://help.nextcloud.com/t/activitypub-the-new-standard-for-decentralized-networks/26381) - seem to be only using AP for internal federation?

* [ownCloud](https://github.com/owncloud/activity/issues/494) - seem to be only using AP for internal federation?

*Dev Tools*

* [BridgyFed](https://github.com/snarfed/bridgy-fed/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+activitypub)

* [Distbin](http://distbin.com/about)

* [ForgeFed](https://github.com/forgefed/forgefed/) (formerly GitPub) - a set of extensions to AP for federation between code forges (Git hosting sites like GitLab, Gogs, Gitea etc)

* [go-fed](https://github.com/go-fed/activity) - AP libraries written in Go

* [GitLab](https://gitlab.com/gitlab-org/gitlab-ce/issues/4013) (see also: https://gitlab.com/gitlab-org/gitlab-ce/issues/30991)

* [Places.pub](https://github.com/w3c/activitypub/issues/282) - AP implementation testing tool?

* [Pubstrate](https://gitlab.com/dustyweb/pubstrate) - experimental AP implementation written in GNU Guile

* [tags.pub](https://github.com/w3c/activitypub/issues/281) - AP implementation testing tool?

Proposed Projects

A place to list rumoured projects for further research, and vapourware, projects that have been planned but no usable code has been written yet.

* [CloutStream](https://pinafore.social/accounts/25168) - a federated replacement for LinkedIn

* [CommonsPub](https://gitlab.com/OpenCoop/CommonsPub) - a fork of Pleroma intended to provide a UX that supports economic transactions and coordination

* [Communecter](https://github.com/pixelhumain/communecter) - already supports ActivityStreams, plans to implement the rest of AP soon

* [Numa](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain but intends to federate with AP. No commits since early 2017. Dead project?

* [Spritely](https://gitlab.com/spritely/spritely) - a new federated media-streaming server in Ratchet, planned by Chris Webber of MediaGoblin fame