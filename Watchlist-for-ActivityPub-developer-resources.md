* :heavy_check_mark: == added to live website at [**fediverse.party**](https://fediverse.party)
* :black_nib: == newly added to this page (added, not altered. Only @light to remove please)

## Contents

- [Developer tools](#developer-tools)
  - [Libraries](#libraries)
  - [Plugins](#plugins)
  - [Bridges](#bridges)
  - [Utilities](#utilities)
  - [Testing](#testing)
- [Reference material](#reference-material)
  - [Protocol specifications](#protocol-specifications)
  - [API documentation](#api-documentation)
- [Tutorials](#tutorials)
  - [Getting started](#getting-started)
  - [ActivityPub server-to-server (S2S)](#activitypub-server-to-server-s2s)
  - [ActivityPub client-to-server (C2S)](#activitypub-server-to-server-s2s)
  - [WebFinger](#webfinger)
  - [Security](#security)
- [Research & Development](#research-development)
  - [Datashards](#datashards)
  - [Object capabilities](#object-capabilities)
  - [Federated authentication](#federated-authentication)
  - [Content addressing](#content-addressing)
  - [Peer-to-peer networking](peer-to-peer-networking)

## Developer tools

#### Libraries

* :heavy_check_mark: [**ActivityPhp**](https://github.com/landrok/activitypub) ([site](https://landrok.github.io/activitypub), [Fedi account](https://cybre.space/@landrok)): A PHP implementation of ActivityPub protocol based upon the ActivityStreams 2.0 data format. `MIT, PHP`

* :heavy_check_mark: [**ActivityPub-PHP**](https://github.com/pterotype-project/activitypub-php) ([Fedi account](https://mastodon.technology/@jdormit)): A PHP implementation of the ActivityPub protocol (used in Pterotype plugin).  `MIT, PHP`

* :heavy_check_mark: [**activityPub4j**](https://github.com/msummers/activityPub4j): W3C ActivityPub and ActivityStreams implementation in Java using Spring Boot. `?, Java` (no license, see: [issue](https://github.com/msummers/activityPub4j/issues/1))

* :heavy_check_mark: [**ActivityStreams**](https://github.com/OpenSocial/activitystreams): Full ActivityStreams 1.0 and 2.0 reference implementation in Java. `Apache-2.0, Java`

* :heavy_check_mark: [**CommonsPub**](https://gitlab.com/CommonsPub) ([site](http://commonspub.org)): Building blocks for creating multifunctional federated networks with ActivityPub. `AGPL-3.0, Elixir`

* :heavy_check_mark: [**Express ActivityPub**](https://github.com/dariusk/express-activitypub): A very simple reference implementation of an ActivityPub server using Express.js. `MIT, Javascript`

* :heavy_check_mark: [**astreams**](https://github.com/MatejLach/astreams) ([Fedi account](https://social.matej-lach.me/@MatejLach)): A hand-crafted implementation of the Activity Streams 2.0 specification in Go, especially suitable for projects implementing ActivityPub. `AGPL-3.0, Go`

* :heavy_check_mark: [**Golang ActivityPub**](https://github.com/go-ap) ([Fedi account](https://metalhead.club/@mariusor)): Libraries for using ActivityPub in the Go language. `MIT, Go`

* :heavy_check_mark: [**go-fed activity**](https://github.com/go-fed/activity) ([site](https://go-fed.org), [Fedi account](https://mastodon.technology/@cj)): Full ActivityStreams & ActivityPub implementation in Golang. Extensions can be easily added by design-time code generation from JSON-LD schema's (also supports [ForgeFed](https://forgefed.peers.community) this way, by default). `BSD-3-clause, Go`

* :heavy_check_mark: [**go-fed apcore**](https://github.com/go-fed/apcore) ([site](https://go-fed.org), [Fedi account](https://mastodon.technology/@cj)): A powerful single server ActivityPub framework for performant Fediverse applications. `AGPL-3.0, Go`

* :heavy_check_mark: [**Pubstrate**](https://gitlab.com/dustyweb/pubstrate): ActivityStreams and ActivityPub library implementation for GNU Guile. Includes a full ActivityStreams library and most of an ActivityPub implementation. `GPL-3.0, Guile`

* :heavy_check_mark: [**Federation**](https://federation.readthedocs.io): Library to abstract social web federation protocols like ActivityPub and diaspora `BSD-3-clause, Python`

* :heavy_check_mark: [**Little Boxes**](https://little-boxes.readthedocs.io): Tiny ActivityPub framework, both database and server agnostic `ISC, Python`

* :heavy_check_mark: [**Python ActivityPub**](https://github.com/dsblank/activitypub): A general ActivityPub library `MPL-2.0, Python`

* :heavy_check_mark: [**ActivityPub Express**](https://github.com/wmurphyrd/activitypub-express): Modular ActivityPub implementation as Express.js middleware to easily add decentralization and federation to Node apps `-, Javascript`

* :heavy_check_mark: [**Mastodon.py**](https://github.com/halcy/Mastodon.py): Python wrapper for the Mastodon API. `MIT, Python`

* :heavy_check_mark: [**atoot**](https://github.com/popura-network/atoot): Library providing an easy way to create Mastodon API applications `MIT, Python`

* :heavy_check_mark: [**Little Library**](https://github.com/Alamantus/little-library): A digital give-a-book, take-a-book library for ebooks `AGPL-3.0, Javascript`

#### Plugins

* :heavy_check_mark: [**ActivityPub for Drupal**](https://github.com/swentel/activitypub) ([Lead dev](https://github.com/swentel)): ActivityPub integration for Drupal 8 `GPL-2.0, PHP`

* :heavy_check_mark: [**XWiki Extension for ActivityPub**](https://github.com/xwiki-contrib/application-activitypub) ([site](https://extensions.xwiki.org/xwiki/bin/view/Extension/ActivityPub%20Application/), [Fedi account](https://social.weho.st/@XWiki)): An implementation of the ActivityPub protocol for XWiki (see [forum discussion](https://forum.xwiki.org/t/new-application-activitypub/6186)). `LGPL-2.1, Java`

* :heavy_check_mark: [**WordPress-ActivityPub**](https://github.com/pfefferle/wordpress-activitypub): ActivityPub for Wordpress `MIT, PHP`

* :heavy_check_mark: [**WordPress-OStatus**](hhttps://github.com/pfefferle/wordpress-ostatus): An OStatus plugin for WordPress `MIT, PHP`

* :heavy_check_mark: [**Pterotype**](https://github.com/pterotype-project/pterotype): WordPress plugin. Pterotype connects your blog to the Fediverse by giving it an ActivityPub feed `MIT, PHP`

#### Bridges

* :heavy_check_mark: [**BridgyFed**](https://github.com/snarfed/bridgy-fed) ([site](https://fed.brid.gy)): Bridges the IndieWeb to federated social networks: ActivityPub, OStatus, etc. `Public Domain, Python`

* :heavy_check_mark: [**feed2toot**](https://gitlab.com/chaica/feed2toot): Parses RSS feeds, identifies new posts and posts them on the Mastodon social network ([using the Mastodon API]((https://gitlab.com/chaica/feed2toot/issues/35#note_289027030))). `MIT, Python`

* :heavy_check_mark: [**RSS-to-ActivityPub Converter**](https://github.com/dariusk/rss-to-activitypub): Convert any RSS feed to an ActivityPub actor that can be followed by users on ActivityPub-compliant social networks like Mastodon. `MIT, Javascript`

* :heavy_check_mark: **[Nautilus](https://github.com/aaronpk/Nautilus)**: A standalone service to deliver posts from your own website to ActivityPub followers. `Apache-2.0, PHP`

#### Utilities

* [**tags-pub**](https://gitlab.com/evanp/tags-pub): Provides hashtag objects on the ActivityPub network. `Apache-2.0, Javascript`

* :heavy_check_mark: [**Pherephone**](https://github.com/writeas/pherephone): An ActivityPub server that reblogs all the statuses of certain actors. You set it up to follow a few accounts and it announces everything they post. `AGPL-3.0, Go`

#### Testing

* :heavy_check_mark: [**activitypub-mock**](https://gitlab.com/evanp/activitypub-mock): A mock ActivityPub server to use in testing code `Apache-2.0, Javascript`

* :black_nib: [**dfk-ap**](https://glitch.com/edit/#!/dfk-ap?path=README.md%3A1%3A0) ([site](https://tinysubversions.com/notes/activitypub-tool/)): A small ActivityPub debugging server on Glitch `MIT, Javascript`

* :heavy_check_mark: [**FedidB**](https://fedidb.org/about): A suite of tools for AP devs to help make it easier to test and validate your implementation with existing implementations like Mastodon, PeerTube, Pixelfed and Pleroma `-, -`

* :heavy_check_mark: [**Test Suite**](https://github.com/go-fed/testsuite): An unofficial partially-automated ActivityPub test suite `AGPL-3.0, Go`

## Reference material

#### Protocol specifications

* :heavy_check_mark: [**ForgeFed**](https://notabug.org/peers/forgefed), formerly GitPub ([site](https://forgefed.peers.community), [Fedi account](https://floss.social/@forgefed)): A set of extensions to ActivityPub for federation between code forges (i.e. git hosting sites like GitLab, Gogs, Gitea, etc. Reference implementation is [Vervis](https://dev.angeley.es/s/fr33domlover/p/vervis)). `CC0-1.0`

* :heavy_check_mark: [**LitePub**](https://github.com/litepub/litepub) ([site](https://litepub.social/litepub), [Fedi account](https://pleroma.site/users/kaniini)): A set of extensions to AP, being developed by devs from Pleroma and Mastodon (status: for the most part litepub group folded back into SocialCG, see: [issue](https://github.com/litepub/litepub/issues/6))

* :heavy_check_mark: [**NodeInfo2**](https://git.feneas.org/jaywink/nodeinfo2): An effort to create a standardized way of exposing metadata about a server. Helps expose ownership and organization details, usage statistics and protocol capabilities. `CC0-1.0`

#### API documentation

## Tutorials

#### Getting started

#### ActivityPub server-to-server (S2S)

#### ActivityPub client-to-server (C2S)

#### WebFinger

#### Security

#### NodeInfo

## Research & Development

#### Datashards

#### Object capabilities

#### Federated authentication

#### Content addressing

#### Peer-to-peer networking