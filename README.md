# delightful fediverse apps  [![delightful](https://codeberg.org/teaserbot-labs/delightful/media/branch/main/assets/delightful-badge.png)](https://codeberg.org/teaserbot-labs/delightful)

A curated list of server applications with support for the ActivityPub protocol (Fediverse network) and related standards.

## Contents

- [Applications](#applications)
  - [Social networks, Microblog Apps](#social-networks-microblog-apps)
  - [Blog, Publishing, and Reading Apps](#blog-publishing-and-reading-apps)
  - [Link-sharing, Forum, and Group Apps](#link-sharing-forum-and-group-apps)
  - [Media-hosting Apps](#media-hosting-apps)
  - [Events and Meetups](#events-and-meetups)
  - [Files, Contacts, and Calendar Syncing Apps](#files-contacts-and-calendar-syncing-apps)
  - [Open data](#open-data)
  - [Reviewing](#reviewing)
  - [Games](#games)
  - [Software development](#software-development)
  - [Extensions](#extensions)
  - [Other](#other)
- [Maintainers](#maintainers)
- [Contributors](#contributors)
- [License](#license)

## Applications

Emoji's for each entry provide additional information on project status:

* :ghost: == inactive for over a year, or officially abandoned

#### Social networks, Microblog Apps

* [**Aardwolf**](https://github.com/Aardwolf-Social/aardwolf): Facebook-like social network connecting communities across the web `AGPL-3.0, Rust`

* [**Activity.next**](https://github.com/llun/activities.next): A single actor ActivityPub server implemented in NextJS. `MIT, Typescript`

* [**Akkoma**](https://akkoma.dev/AkkomaGang/akkoma) ([site](https://akkoma.social/), [Fedi account](https://ihatebeinga.live/users/akkoma)): A community-driven fork of Pleroma with new features such as support for Misskey-flavored Markdown. `AGPL-3.0, Elixir`

* [**Bonfire Social**](https://github.com/bonfire-networks) ([site](https://bonfirenetworks.org/), [Fedi account](https://indieweb.social/@bonfire)): Your plug & play federated social network. Tend to your digital life in community. `AGPL-3.0, Elixir`

* [**Bugle**](https://github.com/rknightuk/bugle): ([site](https://bugle.lol/), [Fedi account](@bugle@bugle.lol)) A minimal ActivityPub server built with Laravel. `Unknown, PHP` 

* [**Convene**](https://github.com/zinc-collective/convene) ([site](https://convene.zinc.coop/), [Fedi account](https://social.coop/@Zee)): Secure, affordable, private digital spaces for work and play. `PPL-3.0, Ruby`

* [**Decodon**](https://github.com/jesseplusplus/decodon): A fork of Mastodon focusing on followers-only posting of media. Configurable circles to post to. `AGPL-3.0, Ruby`

* [**Ecko**](https://github.com/magicstone-dev/ecko) ([Fedi account](https://c4.social/@weex)): A fork of Mastodon to optimize toward community, that is making it as easy as possible to contribute. `AGPL-3.0, Ruby`

* [**Emissary**](https://github.com/EmissarySocial/emissary) ([site](https://emissary.social/), [Fedi account](https://mastodon.social/@benpate)): A customizable, private space in the Fediverse where people can create, share, and collaborate. `AGPL-3.0, Go`

* [**Enigmatick**](https://gitlab.com/enigmatick) ([Fedi account](https://ser.endipito.us/@justin)): Social networking platform (under development). `-, Rust`

* [**Epicyon**](https://gitlab.com/bashrc2/epicyon) ([site](https://libreserver.org/epicyon)): ActivityPub server implementing S2S and C2S protocols, suitable for single board computers. Includes features such as moderation tools, post expiry, content warnings, and image descriptions `AGPL-3.0, Python`

* [**Firefish**](https://git.joinfirefish.org/firefish/firefish) ([site](https://joinfirefish.org/), [Fedi account](https://fedi.software/@firefish)): An actively developed, community-driven fork of Misskey with many quality of life improvements for users and admins alike `AGPL-3.0, TypeScript`

* [**FlockingBird**](https://github.com/flockingbird/roost) ([site](https://search.flockingbird.social), [Fedi account](https://fosstodon.org/@flockingbird)): social network for professionals (WIP)

* [**FoundKey**](https://akkoma.dev/FoundKeyGang/FoundKey): A fork of Misskey with various bugfixes and improvements. `AGPL-3.0, TypeScript`

* [**Friendica**](https://github.com/friendica/friendica) ([site](https://friendi.ca)): Personal network that helps to keep in contact with friends. Interface and functionality include common features of a mainstream social network `AGPL-3.0, PHP`

* [**GNU social**](https://notabug.org/diogo/gnu-social) ([site](https://gnusocial.network)): Microblogging server with multiple plugins `AGPL-3.0, PHP`

* [**Goldfish Social**](https://github.com/Goldfish-Social/Goldfish) ([Fedi account](https://mstdn.social/@stux)): Alternative for Vine / TikTok (alpha). ActivityPub will come later! `AGPL-3.0, PHP`

* [**groundpolis**](https://github.com/xeltica/groundpolis): A microblogging service forked from Misskey `AGPL-3.0, TypeScript`

* [**Glitch-soc**](https://github.com/glitch-soc/mastodon) ([site](https://glitch-soc.github.io/docs), [Fedi account](https://friend.camp/@darius)): A friendly fork of Mastodon, with the aim of providing additional features at the risk of potentially less stable software `AGPL-3.0, Ruby`

* [**GoToSocial**](https://github.com/gotosocial/gotosocial) ([Fedi account](https://ondergrond.org/@dumpsterqueer)): A headless Mastodon-compatible Fediverse server project, written in Golang. `AGPL-3.0, Go`

* [**Hometown**](https://github.com/hometown-fork/hometown) ([Fedi account](https://friend.camp/@darius)): A fork of Mastodon that provides local posting and a wider range of content types `AGPL-3.0, Ruby` 

* [**Honk**](https://humungus.tedunangst.com/r/honk) ([Fedi account](https://honk.tedunangst.com/u/tedu)): ActivityPub server with minimal setup and support costs `ISC, Go`

* [**Iceshrimp**](https://iceshrimp.dev/iceshrimp/iceshrimp): A Misskey fork with a focus on community needs, bugfixes, QoL and performance `AGPL-3.0, TypeScript`

* [**im@stodon**](https://github.com/imas/mastodon) ([site](https://imastodon.net), [Fedi account](https://imastodon.net/@fusagiko)): A fork of Mastodon. Unlisted posts with tags are published on tags, a list of fav tags, image size restrictions and transcoding `AGPL-3.0, Ruby`

* [**Kanzaki**](https://github.com/KnzkDev/kanzaki): A Mastodon-compatible, ActivityPub-speaking server in OCaml `AGPL-3.0, OCaml`

* [**Kepi**](https://gitlab.com/marnanel/chapeau) ([Fedi account](https://queer.party/@marnanel)): A Django-based microblogging server, written in Python, which supports the Mastodon protocol. `GPL-2.0, Python`

* [**Kibou**](https://codeberg.org/charlag/kibou): Lightweight social networking server that implements Mastodon's REST API. `AGPL-3.0, Rust`

* [**Kitsune**](https://github.com/valerauko/kitsune): An ActivityPub-speaking microblogging service. `AGPL-3.0, Clojure`

* [**Kitsune**](https://github.com/kitsune-soc/kitsune): ActivityPub-federated microblogging. `MIT, Rust`

* [**kmyblue**](https://github.com/kmycode/mastodon) ([site](https://kmy.blue), [Fedi account](https://kmy.blue/@official)): A fork of Mastodon for creators: emoji reactions, localposting, groups, misskey-like antennas, post self-destruction and more moderation options `AGPL-3.0, Ruby`

* [**Ktistec**](https://github.com/toddsundsted/ktistec) ([Fedi account](https://mastodon.social/@toddsundsted), [site](https://epiktistes.com/@toddsundsted/)): A single-user ActivityPub server with minimal dependencies, using SQLite, [server](https://epiktistes.com) `AGPL-3.0, Crystal`

* [**Kroeg**](https://puckipedia.com/kroeg) ([site](https://puckipedia.com/kroeg)): Generic ActivityPub server, with a focus on microblogging style activities `Unknown , Rust` 

* [**lectrn**](https://github.com/lectrn/lectrn) ([site](https://lectrn.com/)): A social network for humans that is free, decentralized, open, and easy to use. `AGPL-3.0, JavaScript`

* [**Letterbook**](https://github.com/Letterbook/Letterbook) ([Fedi account](https://hachyderm.io/@jenniferplusplus)): A Mastodon-compatible microblogging server, optimized to reduce administrative costs and burdens. `AGPL-3.0, C#`

* [**Little Forest**](https://github.com/mashirozx/mastodon) ([site](https://hello.2heng.xin/about/more), [Fedi account](https://hello.2heng.xin/@mashiro)): A fork of Mastodon with full Markdown, Quote and Local-Only Toots, Gitlab/hub sign-in, Google Translate, deeper support of Chinese and more theming. `AGPL-3.0, Ruby`

* [**mammoth**](https://gitlab.koehn.com/mammoth) ([Fedi account](https://mammoth.home.koehn.com/api/actor/bkoehn)): A federated social media platform implementing the ActivityPub specification for client/server and server/server communications. `AGPL-3.0, TypeScript`

* [**Mastodon**](https://github.com/tootsuite/mastodon) ([site](https://joinmastodon.org)): Epic microblogging network with many features and multiple interface layouts to choose from `AGPL-3.0, Ruby`

* [**Mathtodon**](https://github.com/Nyoho/mathtodon) ([site](https://mathtod.online/), [Fedi account](https://mathtod.online/@Nyoho)): A fork of Mastodon where you can post toots with beautiful mathematical formulae in TeX/LaTeX style `AGPL-3.0, Ruby`

* [**microblog.pub**](https://git.sr.ht/~tsileo/microblog.pub) ([site](http://docs.microblog.pub)): Self-hosted, single-user, ActivityPub powered microblog. `AGPL-3.0, Python`

* [**MatticNote**](https://github.com/MatticNote/MatticNote): ActivityPub compatible SNS that aims to be easy for everyone to use. `AGPL-3.0, Go`

* [**microstatus**](https://github.com/Arkanosis/microstatus): Lightweight Mastodon and GNU Social-compatible server implementation `ISC, Rust`

* [**Misskey**](https://github.com/misskey-dev/misskey) ([site](https://misskey-hub.net/en/)): Interplanetary microblogging platform. Provides many additional features like calendar, emoji reactions, polls, games, and many other widgets `AGPL-3.0, JavaScript`

* [**netop**](https://github.com/what-cheer/netop):  An ActivityPub Server in Scala. `MIT, Scala`

* [**OCamlot**](https://github.com/Gopiandcode/ocamlot): An ActivityPub server written in OCaml. `AGPL-3.0, OCaml`

* [**Personal Reader for Drupal**](https://git.drupalcode.org/project/reader) ([Fedi account](https://realize.be/user/1), [site](https://www.drupal.org/project/reader)): A personal reader on your website which is installable as a PWA on your phone or tablet. `GPL-2.0, PHP`

* [**Pinetta**](https://codeberg.org/pinetta/pinetta) ([Fedi account](https://fedi.software/@pinetta)) - A decentralized, federated social pinboard in the style of Pinterest. (In development, see [prototype](https://codeberg.org/pinetta/proto-pinetta) `AGPL-3.0, Python`

* [**Pleroma**](https://git.pleroma.social/pleroma) ([site](https://pleroma.social)): Microblogging platform `AGPL-3.0, Elixir`

* [**Pothole**](https://gt.tilambda.zone/o/pothole/server.git/about/): A lightweight federated microblogging server, designed to be simple & fast. `AGPL-3.0-or-later, Nim`

* [**pub**](https://github.com/davecheney/pub) ([Fedi account](https://cheney.net/@dfc)): A tiny ActivityPub host intended for a single actor, that implements Mastodon API for use with various clients. `BSD3-Clause, Go`

* [**Pubblr**](https://github.com/brandonsides/pubblr): A federated blogging platform built on the ActivityPub protocol. `MIT, Go`

* [**pubgate**](https://github.com/autogestion/pubgate):  Lightweight ActivityPub CMS. Implements both client-to-server (C2S) and server-to-server(S2S) APIs. Compatible with Mastodon, Pixelfed, Pleroma and microblog.pub. `BSD-3-clause, Python`

* [**pump.io**](https://github.com/pump-io/pump.io/issues/1241): Still considers adding ActivityPub.

* [**Rebased**](https://gitlab.com/soapbox-pub/rebased): Fediverse backend written in Elixir (fork of [Pleroma](https://pleroma.social/)).  Compatible with the Mastodon API.  The recommended backend for [Soapbox](https://soapbox.pub), also supports [Pleroma-FE](https://docs-fe.akkoma.dev/stable/) as a frontend.

* [**Ruffy**](https://github.com/Taullo/Ruffy) ([Fedi account](https://aethy.com/@Ruffy)): A fork of Glitchsoc, with a changed layout and focus on readability and rich content `AGPL-3.0, Ruby`

* [**Rustodon**](https://github.com/rustodon/rustodon): Mastodon-compatible server `AGPL-3.0, Rust`

* [**Scuttlebutt**](https://github.com/DanielMowitz/ssb_ap_bridge): currently working on a bridge between SSB and AP networks.

* [**Seppo**](https://codeberg.org/seppo/seppo) ([site](https://seppo.social), [Fedi account](https://digitalcourage.social/@mro)): A server-side, single-user, Fediverse-integrated microblog engine. Creating static assets published by webserver. `GPL-3.0, OCaml`

* [**Shuttlecraft**](https://github.com/benbrown/shuttlecraft) ([site](https://shuttlecraft.net/), [Fedi account](https://hackers.town/@benbrown)): A single user ActivityPub server to interact with the Fediverse and other indie web protocols like RSS. `MIT, Javascript`

* [**Smalltown**](https://github.com/chandrn7/smalltown): A fork of Mastodon designed for civic communities looking to run their own social networks. `AGPL-3.0, Ruby`

* [**Smithereen**](https://github.com/grishka/Smithereen): VKontakte-like social network, with friends, walls, photo albums and groups `Unlicense, Java`

* [**snac**](https://codeberg.org/grunfink/snac2) ([Fedi account](https://comam.es/snac/grunfink)): A simple, minimalistic ActivityPub instance with minimal dependencies, multiuser, no database nor cookies needed, totally JavaScript-free `MIT, C`

* [**Socialhome**](https://gitlab.com/jaywink/socialhome) ([site](https://socialhome.network)): Personal webpage with social networking functionality `AGPL-3.0, Python`

* [**Spritely**](https://gitlab.com/spritely) ([site](https://spritely.institute), [Fedi account](https://octodon.social/@spritelyproject)): Research space for a next-gen distributed social network written in Racket and consisting of multiple projects, by AP specification co-author Christine Lemmer Webber. `Apache-2.0, Racket`

* [**Streams**](https://codeberg.org/streams/streams) ([Fedi account](https://macgirvin.com/channel/mike)): Public domain federated communications server. Provides a feature rich ActivityPub and Nomad communication node. `Public domain and others, PHP`

* [**Swanye**](https://codeberg.org/WammKD/Swanye) ([Fedi account](https://fosstodon.org/@Swanye)): A tumblelog in the style of Tumblr. `AGPL-3.0, Elixir`

* [**Takahē**](https://github.com/andrewgodwin/takahe) ([site](https://jointakahe.org), [Fedi account](https://jointakahe.takahe.social/@takahe)): An experimental Fediverse server for microblogging `BSD-3-clause, Python`

* [**Tapir**](https://github.com/ar-nelson/tapir) ([Fedi account](https://tapir.social/@tapir), [site](https://tapir.social)): A small, efficient Mastodon-compatible Fediverse server for single-user instances. Based on Deno. (Note: [license discussion](https://socialhub.activitypub.rocks/t/hi-everyone/3165/8)) `Blue Oak, Typescript`

* [**Tavern**](https://gitlab.com/ngerakines/tavern/-/tree/release-amber-ale) ([Fedi account](https://mastodon.social/@ngerakines)): A minimalistic Activity Pub server. Think Mastodon, but smaller and with fewer features `MIT, Go`

* [**Tootik**](https://github.com/dimkr/tootik): A federated nanoblogging service with a Gemini frontend. `Apache-2.0, Go`

* [**Vagabond**](https://github.com/CameronWhiteCS/Vagabond) ([site](https://stable.teamvagabond.com/)): A federated social network built with security and privacy in mind. `GPL-3.0, Python`

* [**Wafrn**](https://github.com/gabboman/wafrn): Small Tumbl-inspired social network. `Apache-2.0, Typescript` 

* [**Yarn**](https://git.mills.io/yarnsocial/yarn) ([site](https://yarn.social/)): A decentralised self-hosted microblogging platform that has a privacy-first focus. `AGPL-3.0, Go`

* :ghost: [**Dolphin**](https://github.com/syuilo/dolphin): Lightweight ActivityPub Server optimized for single-user. A fork and sister project of Misskey `AGPL-3.0, JavaScript`

* :ghost: [**fed**](https://github.com/kissen/fed): Trying to be a basic twitter-like service that works with ActivityPub. Based on [Go-Fed](https://go-fed.org) `GPL-3.0, Go`

* :ghost: [**GangGo**](https://github.com/ganggo/ganggo/tree/develop)  - Developer has suspended development for the foreseeable future

* :ghost: [**Jejune**](https://github.com/kaniini/jejune) - A work-in-progress ActivityPub server designed to use constructions which provide functional security and resilience `ISC license, Python`

* :ghost: [**Lumen-ap-server**](https://notabug.org/tinyrabbit/lumen-ap-server) ([Fedi account](https://floss.social/@tinyrabbit)): ActivityPub server using Lumen framework `MIT, PHP`

* :ghost: [**Mistpark 2020**](https://codeberg.org/zot-archive/misty) aka 'misty' - A webserver app that supports AP and Zot protocols, fork of Zap. (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**MrBotchi**](https://github.com/mrbotchi-team/mrbotchi) ([Fedi account](https://norimono.moe/@silverscat_3)): A federated microblogging platform for single-user - not updated since June 2020 `AGPL-3.0, Go`

* :ghost: [**Osada**](https://codeberg.org/zot-archive/osada) - A full featured social network application. (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**Pylodon**](https://github.com/rowanlupton/pylodon) - Flask-based (Python) ActivityPub server , [source code also on GitLab](https://gitlab.com/rowanlupton/pylodon), no updates on either repo for about a year, nor on their [Smilodon client app](https://github.com/rowanlupton/smilodon)

* :ghost: [**Redmatrix 2020**](https://codeberg.org/zot-archive/redmatrix): A fediverse server. (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP` 

* :ghost: [**Roadhouse**](https://codeberg.org/zot-archive/roadhouse): Next gen Fediverse server. (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**ShaarliGo**](https://code.mro.name/mro/ShaarliGo): Self-reliantly posting on the #Fediverse with painless hosting and security in mind. `GPL-3.0, Go`

* :ghost: [**Smilodon**](https://gitlab.com/tuxcrafting/smilodon) (server by Tuxcraft) - abandoned by developer "I'm now [working on Sminos](https://gitlab.com/tuxcrafting/sminos/issues/1) and so this will probably be 100% abandoned. There's not much to salvage, its code is cancer." Sminos appears to have never got beyond the initial commits

* :ghost: [**Technopolis**](https://github.com/technopolis-microblog) ([site](https://technopolis.app/), [Fedi account](https://norimono.moe/@silverscat_3)): A globally interconnected micro-blogging platform inspired by Misskey - not updated since December 2020 `AGPL-3.0, Rust`

* :ghost: [**tranquility**](https://github.com/aumetra/tranquility): Small ActivityPub server written in Rust. (Archived, see [issue](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/32)) `MIT, Rust`

* :ghost: [**un chapeau**](https://gitlab.com/marnanel/un_chapeau/-/issues/17): Server for the Mastodon protocol, implemented in Django. Latest commit - May 2019. `AGPL-3.0, Python`

* :ghost: [**Zap**](https://codeberg.org/zot-archive/zap): A webserver app that supports AP and Zot protocols (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

#### Blog, Publishing, and Reading Apps

* [**Dinolog**](https://github.com/bauripalash/dinolog) ([Fedi account](https://fosstodon.org/@bauripalash)): Utterly simplified and lightweight blogging protocol. (AP support planned. See [toot](https://fosstodon.org/@bauripalash/108440377225675211)) `Unknown, Go`

* [**Dokie.li**](https://github.com/linkeddata/dokieli) ([site](https://dokie.li)): Article authoring and formating `Apache-2.0, JavaScript`

* [**GoBlog**](https://git.jlel.se/jlelse/GoBlog) ([site](https://goblog.app/), [Fedi account](https://fosstodon.org/@jle)): Simple blogging system written in Go `MIT, Go`

* [**Hubzilla**](https://framagit.org/hubzilla) ([site](https://hubzilla.org)): CMS with a range of groupware tools available as plug-ins `MIT, PHP` 

* [**Known**](https://github.com/idno/known) ([site](https://withknown.com/), [Fedi account](https://mastodon.social/@benwerd)): A collaborative social publishing engine (Working on AP support, see [this issue](https://github.com/idno/known/issues/2615)). `Apache-2.0, PHP`

* [**Little Library**](https://github.com/Alamantus/little-library): A digital give-a-book, take-a-book library for ebooks. `AGPL-3.0, JavaScript`

* [**Plume**](https://github.com/Plume-org/Plume) ([site](https://joinplu.me)): Blogging application `AGPL-3.0, Rust`

* [**Read.as**](https://github.com/writeas/Read.as) ([site](https://read.as)): Reading app by the devs of WriteFreely `AGPL-3.0, Go`

* [**site**](https://github.com/Lonor/site): Minimalist blog that implements ActivityPub endpoints. `MIT, Javascript`

* [**WordPress**](https://codeberg.org/fediverse/fediparty/wiki/Wordpress-integration-with-Fediverse) - [listed as a project on the-federation.info](https://the-federation.info/wordpress). [AP plug-in](https://wordpress.org/plugins/activitypub) by @pfefferle@mastodon.social, that allows users on AP apps to follow WP blogs, and comment on them, from an AP app

* [**WriteFreely**](https://github.com/writefreely) ([site](https://writefreely.org), [Fedi account](https://writing.exchange/@writefreely)): Blog software `AGPL-3.0, Go`

* [**Yuforium**](https://github.com/yuforium) ([Fedi account](https://mastodon.social/@cpmoser)): A federated community platform that focuses on federated communities so they are no longer constrained to a single entity. `GPL-3.0, TypeScript`

* :ghost: [**FediBlog**](https://framagit.org/DavidLibeau/FediBlog) ([site](https://fedi.blog)): Fully customisable blog engine `GPL-3.0, PHP`

* :ghost: [**Lamia**](https://github.com/Scarly-Crow/lamia): Distributed blogging, polls, and status updates powered by activitypub, python, the gay agenda, and snake women. `AGPL-3.0, Python`

* :ghost: [**NoteIn**](https://github.com/notein/NoteIn): No commits since October 2018

* :ghost: [**Redaktor**](https://redaktor.me): AP-powered CMS; website suspended, no actual code repo

#### Link-sharing, Forum, and Group Apps

* [**brutalinks**](https://github.com/mariusor/go-littr) ([Fedi account](https://metalhead.club/@mariusor)): Link aggregator inspired by Reddit `MIT, Go`

* [**ENiGMA½**](https://github.com/NuSkooler/enigma-bbs): A modern BBS software with a nostalgic flair. (see: [issue](https://github.com/NuSkooler/enigma-bbs/issues/459)) `BSD-2-Clause, Javascript`

* [**Flarum**](https://github.com/squeevee/flarum-ext-feddle): Experimental plugin for [Flarum](https://flarum.org/) forum software by [@squeevee](https://yiff.life/@squeevee/102496777538790361)

* [**Kbin**](https://codeberg.org/Kbin/kbin-core) ([site](https://kbin.pub)) - Link aggregator and microblogging platform for Fediverse `AGPL-3.0, PHP`

* [**Lemmy**](https://github.com/dessalines/lemmy): Link aggregator, by [@LemmyDev](https://mastodon.social/@LemmyDev/102106696961226378) `AGPL-3.0, Rust`

* [**Lobste.rs**](https://github.com/lobsters/lobsters/issues/499): Existing Reddit replacement adding AP support, AP issue still open

* [**lotide**](https://git.sr.ht/~vpzom/lotide): A federated forum / link aggregator. `AGPL-3.0, Rust`

* [**MoonTree**](https://github.com/Faleidel/moontreeproject): Link aggregator, a work in progress `MIT, Typescript`

* [**Postmarks**](https://github.com/ckolderup/postmarks) ([site](https://postmarks.glitch.me/)): a single-user bookmarking website designed to live on the Fediverse `MIT, Javascript`

* [**Smilodon**](https://source.puri.sm/liberty/host/smilodon): the server by Purism used in LibreOne, not the abandoned Tuxcraft server or Pylodon client; a complementary fork of Mastodon, focusing on opt-in public spaces `AGPL-3.0, Ruby`

* [**Vicinitude**](https://gitlab.com/RyanMcCoskrie/vicinitude): A social media platform for Local Communities. `MIT, Ruby`

* [**vxwClub**](https://github.com/wxwmoe/wxwClub): Simple social groups compatible with ActivityPub. `MIT, PHP`

* :ghost: [**Anancus**](https://gitlab.com/tuxether/anancus): By [@tuxether](https://floss.social/@tuxether), Link aggregator, [discontinued](https://gitlab.com/tuxether/anancus/issues/2)?

* :ghost: [**Prismo**](https://gitlab.com/prismosuite/prismo) ([Fedi account](https://mastodon.social/@prismo)): Link aggregator. Latest update - May 2019. `AGPL-3.0, Ruby`

#### Media-hosting Apps

* [**Anfora**](https://github.com/anforaProject/anfora) ([site](https://anfora.app)): (formerly Zinat) Image sharing `AGPL-3.0, Python`

* [**CastoPod Host**](https://code.podlibre.org/podlibre/castopod) ([site](https://podlibre.org/), [Fedi account](https://podlibre.social/@castopod)): An open-source hosting platform made for podcasters who want engage and interact with their audience. `AGPL-3.0, PHP`

* [**Catcast D**](https://github.com/mrcatman/catcast-d) ([Fedi account](https://mastodon.social/@mrcatmann)): A federated video live streaming platform `Unknown, TypeScript`

* [**FChannel**](https://github.com/FChannel0/FChannel-Server): A libre, self-hostable, federated, imageboard platform that utilizes ActivityPub. `AGPL-3.0, Go`

* [**FunkWhale**](https://dev.funkwhale.audio/funkwhale/funkwhale) ([site](https://funkwhale.audio)): Music streaming `AGPL-3.0, Python`

* [**Librecast LIVE**](https://codeberg.org/librecast/librecast-live) ([Fedi account](https://chaos.social/@onepict), [site](https://librecast.net/live.html)): Live Streaming Video Platform with Multicast `GPL-2.0-only OR GPL-3.0-only, JavaScript`

* [**Minipub**](https://github.com/skymethod/minipub) ([site](https://minipub.dev)): Minimal ActivityPub server for posting federated podcast comments `MIT, TypeScript`

* [**Owncast**](https://github.com/owncast/owncast) ([site](https://owncast.online), [Fedi account](@gabek@mastodon.social)): Owncast is a self-hosted live video and web chat server for use with existing popular broadcasting software. `MIT, Go`

* [**PeerTube**](https://github.com/Chocobozzz/PeerTube) ([Fedi account](https://framapiaf.org/@peertube), [site](http://joinpeertube.org)): Video-hosting site using WebTorrent `AGPL-3.0, TypeScript`

* [**PixelFed**](https://github.com/dansup/pixelfed) ([site](https://pixelfed.org), [Fedi account](https://mastodon.social/@pixelfed)): Photo Sharing. For Everyone. A free and ethical photo sharing platform. `AGPL-3.0, PHP`

* [**Podverse**](https://github.com/podverse/podverse-web) ([Fedi account](https://podcastindex.social/web/@podverse), [site](https://podverse.fm)): Web app for the Podverse podcast clip sharing system. `AGPL-3.0, TypeScript`

* [**snap.as**](https://github.com/snapas) ([Fedi account](https://m.abunchtell.com/@snap_as), [site](https://snap.as)): Snap.as is a minimalist tool for publishing and sharing your photos on the web. (Not really started yet)

* [**Vidzy**](https://codeberg.org/vidzy/vidzy) ([site](https://vidzy.codeberg.page/)): The federated alternative to TikTok. `AGPL-3.0, Python`

* :ghost: [**Acorde**](https://github.com/polymerwitch/Acorde) - federated social music platform. Almost a year has passed since the initial commit

* :ghost: [**Audon**](https://codeberg.org/namekuji/audon): Audio chat space for Mastodon, Akkoma, GoToSocial, and Firefish, `AGPL-3.0-or-later, Go`

* :ghost: [**Fontina**](https://github.com/beta-phenylethylamine/fontina) - proposed as a photo-sharing social media network. GH repo has gone read-only, and now says "dead project"

* :ghost: [**Marmota**](https://gitlab.com/Nefix/marmota/issues?label_name=ActivityPub): Streaming service like Spotify. No commits -  since March 2019 

* :ghost: [**Pubcast**](https://github.com/pubcast/pubcast) ([site](https://pubcast.pub)): Podcasting platform that allows people to listen to podcasts in a new way. Latest commit - March 2019. `MPL-2.0, Go`

* :ghost: [**PeerPx**](https://github.com/peerpx): Social network for photographers (alternative to 500px / Flickr); Latest commit - October 2018

* :ghost: [**reel2bits**](https://github.com/rhaamo/reel2bits) ([site](https://reel2bits.org)): Music and podcast hosting, `AGPL-3.0, Python`

* :ghost: [**Soundstorm**](https://github.com/weathermen/soundstorm): The Federated Social Audio Platform. (Currently inactive, see [issue](https://github.com/weathermen/soundstorm/issues/21#issuecomment-882626364)) `GPL-3.0, Python`

 
#### Events and Meetups

* [**Gancio**](https://framagit.org/les/gancio) ([site](https://gancio.org)): Shared agenda for local communities; demo [site](https://demo.gancio.org) `AGPL-3.0, JavaScript`

* [**Gath**](https://github.com/lowercasename/gathio): Public events with no registration required, an instance connected with the friend.camp Mastodon instance is up at: http://events.friend.camp `GPL-3.0, JavaScript`

* [**GetTogether**](https://github.com/GetTogetherComm/GetTogether/issues/60) - Still considering adding AP support

* [**Mobilizon**](https://framagit.org/framasoft/mobilizon) ([site](https://joinmobilizon.org/en), [Fedi account](https://framapiaf.org/@mobilizon)): Aims to be more than a Meetup clone `AGPL-3.0, Elixir`

* [**The Occasion Octopus**](https://github.com/theoccasionoctopus/theoccasionoctopus-server) ([site](https://www.theoccasionoctopus.net/), [Fedi account](https://fosstodon.org/@theoccasionoctopus)): A federated network ofOpen Data for discovering interesting events `AGPL-3.0, PHP`

* **Friendica** (see above) has an [events engine that federates events over AP](https://socialhub.activitypub.rocks/t/activitypub-at-36c3-the-decentral-assembly-and-fediverse-party/402/5) and is looking to test interop with other AP events apps. [NextCloud federated events](https://github.com/nextcloud/calendar/pull/878) are in the works but this [may or may not be AP-compatible](https://github.com/nextcloud/server/issues/1440).

* :ghost: [**FedEvent**](https://github.com/shiburizu/fedevent): A prototype for federating event information

#### Files, Contacts, and Calendar Syncing Apps

* [**Artist Hub**](https://github.com/creative-passport/artist-hub) ([site](https://www.creativepassport.net/)): Part of Creative Passport NGI0-funded project for providing a verified digital ID for Music Makers (very early stage of development) `AGPL-3.0, TypeScript`

* [**NextCloud-Social**](https://github.com/nextcloud/social) ([site](https://apps.nextcloud.com/apps/social)): Social networking app for NextCloud `AGPL-3.0, PHP`

* [**MoodleNet**](https://gitlab.com/moodlenet): [Social client for Moodle](https://moodle.com/moodlenet) LMS (Learning Management System) aimed at helping teachers collaboratively collate and curate sets of OER (Open Educational Resources)

* :ghost: [**Calendar-social**](https://gitea.polonkai.eu/gergely/calendar-social/) - was definitely planning to [implement AP](https://gitea.polonkai.eu/gergely/calendar-social/issues/122). Missing, [presumed discontinued](https://gitea.polonkai.eu/gergely/calendar-social/issues/123)

#### Open data

* [**bopwiki**](https://codeberg.org/Valenoern/bopwiki) ([Fedi account](https://floss.social/@Valenoern)): An experimental 'microwiki implementation' / 'mini CMS' with ActivityPub support. `GPL-3.0, Common Lisp`

* [**Chatter Net**](https://github.com/chatternet/chatternet-server-http): Chatter Net is a modern decentralized semantic web built atop self-sovereign identity. `MIT, Rust`

* [**CPub**](https://gitlab.com/openengiadina/cpub): a semantic web server, implements a Linked Data Platform (LDP), uses RDF Turtle as serialization format, part of the [openEngiadina](https://openengiadina.net) project `AGPL-3.0, Elixir`

* [**Inventaire**](https://github.com/inventaire/inventaire) ([site](https://inventaire.io/welcome), [Fedi account](https://mamot.fr/@inventaire)): A libre collaborative resource mapper powered by open-knowledge, starting with books. (Considers AP integration, see [Github issue](https://github.com/inventaire/inventaire/issues/187)) `AGPL-3.0, JavaScript`

* [**OLKi**](https://framagit.org/synalp/olki/olki/-/wikis/ActivityPub-dialect-documentation) ([site](https://olki.loria.fr/platform), [Fedi account](https://mastodon.etalab.gouv.fr/@scifed)): A self-hosted linguistic corpora exchange platform that aims to be a simple gateway to the Fediverse for scientific interaction `AGPL-3.0, Python`

* [**Openki**](https://gitlab.com/Openki/Openki) ([site](https://openki.net/)): An interactive p2p web-platform to provide barrier-free access to education for everyone. (not federated yet, see [AP feature request](https://gitlab.com/Openki/Openki/-/issues/1263)) `AGPL-3.0, JavaScript`

* [**SemApps**](http://www.virtual-assembly.org/semapps-2/) ([site](http://semapps.org/?PagePrincipale&lang=en)): A collaborative, generic knowledge management system. Aims to ease data storage and filtering. `Apache-2.0, JavaScript`

* [**SkoHub**](https://github.com/hbz/skohub-pubsub) ([site](https://skohub.io)): Creates a publication / subscription infrastructure for Open Educational Resources. It allows to follow specific subjects and to be notified when new content about that subject is published. `Apache-2.0, JavaScript`

* [**XWiki**](https://github.com/xwiki) ([site](http://www.xwiki.org/), [Fedi account](https://social.weho.st/@XWiki)): An advanced open source Enterprise Wiki (via the [ActivityPub Extension](https://extensions.xwiki.org/xwiki/bin/view/Extension/ActivityPub%20Application/)). `LGPL 2.1, Java`

#### Reviewing

* [**Bookwyrm**](https://github.com/mouse-reeve/bookwyrm) ([site](https://joinbookwyrm.com), [Fedi account](https://tech.lgbt/@bookwyrm)): A federated alternative to Goodreads (non-OSS license) `ANTI-CAPITALIST SOFTWARE LICENSE v1.4, Python`

* [**FediMovies**](https://code.caric.io/FediMovies/fedimovies): Lively federated movies reviews platform. `AGPL-3.0, Rust`

* :ghost: [**exlibris**](https://github.com/exlibris-fed/exlibris): A social network dedicated to tracking and discussing what you're reading, based on [go-fed](https://go-fed.org) (development stalled, see [this toot](https://mastodon.social/web/statuses/105567590537815892)). Latest commit - October 2020 `MIT, Go`

* :ghost: [**Readlebee**](https://gitlab.com/Alamantus/Readlebee) ( [Fedi account](https://floss.social/@Readlebee)): An attempt to create a viable Goodreads alternative, book reading progress, lists, reviews, comments (Project looking for new Maintainers) `AGPL-3.0, JavaScript`

#### Games

* [**Dharma**](https://github.com/cjslep/dharma): A federated community-building platform for Eve Online corporations. `AGPL-3.0, Go`

* [**Guild Website**](https://git.lubar.me/ben/guild-website): Federating guild website using GuildWars2 API `MIT, Go`

* [**castling.club**](https://github.com/stephank/castling.club) ([site](https://castling.club/), [Fedi account](https://mastodon.social/@kosinus)): Challenge someone to a game of chess using toots. An ActivityPub server with a single hardcoded King service actor that acts as a chess arbiter. `MIT, TypeScript`

* [**Wolfgame**](https://gitlab.com/stemid/wolfgame) ([Fedi account](https://mastodon.se/@stemid)): Wolfgame is a lot like Mafia. Once started the game simulates day/night cycle and allows players to vote for who might be a werewolf during the day. `MIT, Python`

* :ghost: [**FediQuest**](https://shapegoal.org/matejlach/fediQ-server) ([site](https://shapegoal.org)): A federated alternative to traditionally centralized question & answer platforms, such as Quora/StackOverflow. `GPL-3.0, Go`

#### Software development

* [**ForgeFlux**](https://github.com/forgeflux-org/interface) ([site](https://forgeflux.org/), [Fedi account](https://gts.batsense.net/@forgeflux)): API-space software forge federation. Will implement ForgeFed external to the forges, using the forge's HTTP APIs. `AGPL-3.0, Python`

* [**ForgeFriends**](https://lab.forgefriends.org/forgefriends/forgefriends) ([site](https://forgefriends.org), [Fedi account](https://mastodon.online/@forgefriends)): An online service to federate forges. `MIT, Go`

* [**Gitea**](https://github.com/go-gitea/gitea) ([site](https://gitea.io/en-us/)): A community managed lightweight code hosting solution. (In progress. For status, see: [go-gitea/#18240](https://github.com/go-gitea/gitea/issues/18240), [gitea/#3](https://gitea.com/Ta180m/gitea/issues/3)) `MIT, Go`

* [**Gitlab**](https://gitlab.com): Starting with 'Social following' Gitlab is working along a roadmap to adding ActivityPub support. See top-level [Epic](https://gitlab.com/groups/gitlab-org/-/epics/11247). `MIT, Ruby`

* [**Git Social**](https://git.vp.mk/ui/git-social.git/master/about): A federated self-hosted git repository management tool `GPL-3.0, Rust`

* [**Ruisseau**](https://github.com/oknozor/ruisseau): Federated Git platform (still in early stages of development). `-, Rust`

* [**Vervis**](https://vervis.peers.community/repos/WvWbo/source) ([Fedi account](https://todon.nl/@fr33domlover)): Eventually-decentralized project hosting and management platform. Reference implementation for [ForgeFed](https://forgefed.org) protocol extension. `AGPL-3.0, Haskell`

* :ghost: [**Distbin**](https://github.com/gobengo/distbin) ([site](https://distbin.com)): Post bin. Latest commit - September 2019. `Apache-2.0, TypeScript`

#### Extensions

* [**apevents**](https://github.com/ngerakines/apevents) ([Fedi account](https://thegem.city/@nick)) - Event management system that allows event creation and coordination across Fediverse `MIT, Rust`

* [**AP-Groups**](https://github.com/michaelcpuckett/ap-groups) ([site](https://chirp.social/), [Fedi account](https://a11y.social/@mpuckett)): Group actors as bot/relay. `MIT, TypeScript`

* [**Fediplan**](https://framagit.org/tom79/fediplan) ([site](https://fedilab.app/page/fediplan/), [Fedi account](https://toot.fedilab.app/@apps)): A way to safely schedule messages with Mastodon and Pleroma. `GPL-3.0, PHP`

* [**Group actor**](https://git.ondrovo.com/MightyPork/group-actor) ([Fedi account](https://piggo.space/users/piggo)): Groups work with any software that implements Mastodon client API; has moderation, admin announcements, [test server](https://piggo.space/hob) `MIT, Rust`

* [**Guppe**](https://github.com/wmurphyrd/guppe) ([site](https://a.gup.pe)): By [@datatitian](https://social.coop/@datatitian/102837577105371476), adds "groups" support as group-type actors `GPL-3.0, JavaScript`

* [**Mastodon Bot Autoresponder**](https://github.com/drequivalent/mastodon-bot-autoresponder) ([Fedi account](https://mastodon.ml/@drq)): a bot that implements group functionality in Mastodon. `MIT, Python`

* [**tootgroup.py**](https://github.com/oe4dns/tootgroup.py): Emulate group accounts on Mastodon. `GPL-3.0, Python`

#### Other

* [**activitypub-core**](https://github.com/michaelcpuckett/activitypub-core): An attempt to build a spec-compliant ActivityPub server in Node.js. `MIT, TypeScript`

* [**Alovoa**](https://github.com/Alovoa/alovoa) ([site](https://alovoa.com/)): Free and open-source dating platform that respects your privacy (considering AP support, see [issue](https://github.com/Alovoa/alovoa/issues/13)) `AGPL-3.0, Java`

* [**bovine_herd**](https://codeberg.org/bovine/bovine/src/branch/main/bovine_herd): A bovine powered ActivityPub server, which interoperates with the rest of the FediVerse. `MIT, Python`

* [**Communecter**](https://github.com/pixelhumain/communecter) ([site](https://www.communecter.org/)): Manage cities as a connected citizen, produce openCityData, manage organizations, projects, events openly, an open societal approach (intends to add AP support, see [this issue](https://github.com/pixelhumain/communecter/issues/1395)) `Apache-2.0, PHP`

* [**Corteza**](https://github.com/cortezaproject/corteza-server) ([site](https://cortezaproject.org)): "Digital Work Platform for Humanity" an open-source, low-code federated platform for building cloud-based business apps with CRM capabilities `Apache-2.0, Go`

* [**ENiGMA½ BBS**](https://github.com/NuSkooler/enigma-bbs) ([site](https://nuskooler.github.io/enigma-bbs/)): A modern BBS software with a nostalgic flair! (In progress, see [PR](https://github.com/NuSkooler/enigma-bbs/pull/460)) `BSD-2-Clause, Javascript`

* [**FairSync**](https://git.fairkom.net/fairsync) ([site](https://fairmove.it/fairsync/)): Develops and collects best practices to synchronize maps and events and to federate messengers and identities. (Funded with NGI0, implementing ActivityStreams, but AP support not clear, currently unlicensed) `Unknown, Java`

* [**FitTrackee**](https://github.com/SamR1/FitTrackee) ([Fedi account](https://mastodon.social/@SamR1)): A simple self-hosted workout / activity tracker. (Still considering AP support, see [issue](https://github.com/SamR1/FitTrackee/issues/16)) `AGPL-3.0, Python`

* [**flohmarkt**](https://codeberg.org/grindhold/flohmarkt): A decentralised federated small trade platform. `AGPL-3.0, Python`

* [**fossilphant**](https://github.com/swaldman/fossilphant) ([Fedi account](https://zirk.us/@interfluidity)): a static-site generator for Mastodon archives. `AGPL-3.0, Scala`

* [**hvxahv-platform**](https://github.com/disism/hvxahv) ([site](https://dev.halfmemories.com): A multifunctional decentralized social network implementation. `MIT, Go`

* [**Immers Space**](https://github.com/immers-space/immers) ([Fedi account](https://gup.pe/u/immersspace)): The decent(ralized) metaverse. `AGPL-3.0, JavaScript`

* [**Inbox**](https://github.com/WhyINeedToFillUsername/inbox) ([site](https://whyineedtofillusername.github.io/inbox/about)): An application built for a diploma thesis to showcase work with Linked Data Notifications, Activity Streams and ActivityPub, using Solid pod as data provider. (See also [Solid forum discussion](https://forum.solidproject.org/t/inbox-new-messaging-application/4093). No license, see [issue](https://github.com/WhyINeedToFillUsername/inbox/issues/2)) `Unknown, TypeScript`

* [**Life Server**](https://github.com/interop-alliance/life-server) ([site](https://permanent.cloud/apps/life-server)): A decentralized personal data framework inspired by MIT's Solid Project (AP support planned, see [Roadmap](https://github.com/interop-alliance/life-server/blob/main/README.md#roadmap)), `MIT, JavaScript`

* [**Ocelot Social**](https://github.com/Ocelot-Social-Community/Ocelot-Social): Free and open-source social network for active citizenship. `MIT, JavaScript`

* [**retrospring**](https://github.com/Retrospring/retrospring) ([site](https://retrospring.net/), [Fedi account](https://floss.social/@retrospring)): Q&A based social network. Ask questions, give answers and learn more about your friends. (AP support planned. See: [Github issue](https://github.com/Retrospring/retrospring/issues/395)) `AGPL-3.0, Ruby`

* [**Smartlike**](https://github.com/smartlike-org/smartlike) ([site](https://smartlike.org/), [Fedi account](https://mastodon.social/@vadim_frolov)): A free non-profit decentralized donation processor with a focus on freedom, privacy and efficiency. `AGPL-3.0, Rust`

* [**Transit Fedilerts**](https://github.com/kona314/transit-fedilerts) ([site])(https://transit.alerts.social/)): ActivityPub-compliant server for distributing transit service alerts. `ISC, Typescript`

* [**Vocata**](https://codeberg.org/Vocata/vocata): A vocabulary-agnostic ActivityPub server. Vocata does not limit what types of content can be handled by it, and how it is presented to users. `LGPL-3.0-or-later, Python`

* :ghost: [**Agora**](https://github.com/scenaristeur/agora): [Home page](https://scenaristeur.github.io/agora),  POC to use ActivityPub on top of the Solid Platform. - developed by [@spoggy@mstdn.fr](https://mstdn.fr/@spoggy). Latest commit - June 2020 

* :ghost: [**Indienet**](https://source.ind.ie/indienet) - [homepage](https://web.archive.org/web/20190507034117/https://indienet.info/) - abandoned in favour of [Tincan development](https://small-tech.org/research-and-development)

* :ghost: [**Numa**](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain but intended to federate with AP. No commits since April 2018. No reply on issue about AP compatibility testing from May 8. Homepage now a spam site

* :ghost: [**Pantheon**](https://github.com/TGNThump/Pantheon): Platform for building communities. No commits -  since September 2019

## Sources

Aside from project homepages and issue trackers, and comments made on the fediverse, the [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hoped would implement ActivityPub and links to issues where it's discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). @Mayel from Social.coop created a [web spreadsheet of AP apps](https://ethercalc.org/fediverse-stacks) and their characteristics. More projects using AP are [profiled on We Distribute](http://wedistribute.org/) by Sean Tilley and his team. There are boards for discussing a range of [AP implementations on the SocialHub forum](https://socialhub.activitypub.rocks/c/software/14). [Alternative.to](https://alternativeto.net/list/5696/activitypub) has a list of AP servers and client apps. The [ActivityPub tag on GH](https://github.com/topics/activitypub) is also a way to discover projects experimenting with AP.

## Maintainers

If you have questions or feedback regarding this list, then please create an [Issue](https://codeberg.org/fediverse/delightful-fediverse-apps/issues) in our tracker, and optionally `@mention` one or more of our maintainers:

- [`@circlebuilder`](https://codeberg.org/circlebuilder)
- [`@lostinlight`](https://codeberg.org/lostinlight)

## Contributors

With delight we present you some of our [delightful contributors](delightful-contributors.md) (please [add yourself](https://codeberg.org/teaserbot-labs/delightful/src/branch/main/delight-us.md#attribution-of-contributors) if you are missing).

## License

[![CC0 Public domain. This work is free of known copyright restrictions.](https://i.creativecommons.org/p/mark/1.0/88x31.png)](LICENSE)
