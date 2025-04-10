# delightful fediverse apps  [![delightful](https://codeberg.org/teaserbot-labs/delightful/media/branch/main/assets/delightful-badge.png)](https://codeberg.org/teaserbot-labs/delightful)

A curated list of server applications with support for the ActivityPub protocol (known as the fediverse) and related standards.

## Contents

- [Applications](#applications)
  - [Microblogging](#microblogging)
  - [Blogging, Publishing, and Reading](#blogging-publishing-and-reading)
  - [Link-sharing, Forums, and Groups](#link-sharing-forums-and-groups)
  - [Media Hosting](#media-hosting)
  - [Events and Meetups](#events-and-meetups)
  - [Files, Contacts, and Calendar Syncing](#files-contacts-and-calendar-syncing)
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

* :ghost: means inactive for over a year, or officially abandoned

#### Microblogging

* [**Aardwolf**](https://github.com/Aardwolf-Social/aardwolf): Facebook-like social network connecting communities across the web `AGPL-3.0, Rust`

* [**Activity.next**](https://github.com/llun/activities.next): A single actor ActivityPub server implemented in NextJS. `MIT, TypeScript`

* [**Areionskey**](https://github.com/sakura-tel/areionskey) ([site](https://uma.milkey.homes/), [Fedi account](@areionskey@uma.milkey.homes)): a federated/distributed microblogging platform based on Meisskey v11 `AGPL-3.0, TypeScript`

* [**Ayuskey**](https://github.com/TeamBlackCrystal/ayuskey): A fork of Misskey with more widgets and other design improvements. `AGPL-3.0, TypeScript`

* [**Akkoma**](https://akkoma.dev/AkkomaGang/akkoma) ([site](https://akkoma.social/), [Fedi account](https://ihatebeinga.live/users/akkoma)): A community-driven fork of Pleroma with new features such as support for Misskey-flavored Markdown. `AGPL-3.0, Elixir`

* [**Bonfire Social**](https://github.com/bonfire-networks) ([site](https://bonfirenetworks.org/), [Fedi account](https://indieweb.social/@bonfire)): Your plug & play federated social network. Tend to your digital life in community. `AGPL-3.0, Elixir`

* [**Bugle**](https://github.com/rknightuk/bugle) ([site](https://bugle.lol/), [Fedi account](@bugle@bugle.lol)): A minimal ActivityPub server built with Laravel. `Unknown, PHP`

* [**Catodon**](https://codeberg.org/catodon/catodon) ([site](https://catodon.social), [Fedi account](@panos@catodon.social)): A platform to build your federated community on. Fork of Firefish `AGPL-3.0, TypeScript`

* [**CherryPick**](https://github.com/kokonect-link/cherrypick) ([site](https://kokonect.link/), [Fedi account](@noridev@kokonect.link)): A Korean fork of Misskey `AGPL-3.0, TypeScript`

* [**Convene**](https://github.com/zinc-collective/convene) ([site](https://convene.zinc.coop/), [Fedi account](https://social.coop/@Zee)): Secure, affordable, private digital spaces for work and play. `PPL-3.0, Ruby`

* [**Decodon**](https://github.com/jesseplusplus/decodon): A fork of Mastodon focusing on followers-only posting of media. Configurable circles to post to. `AGPL-3.0, Ruby`

* [**Ebisskey**](https://github.com/shrimpia/misskey) ([site](https://mk.shrimpia.network), [Fedi account](@Lutica@mk.shrimpia.network)): A fork of Misskey that lets you nickname other users and steal posts. `AGPL-3.0, TypeScript`

* [**Ecko**](https://github.com/magicstone-dev/ecko) ([Fedi account](https://c4.social/@weex)): A fork of Mastodon to optimize toward community, that is making it as easy as possible to contribute. `AGPL-3.0, Ruby`

* [**Emissary**](https://github.com/EmissarySocial/emissary) ([site](https://emissary.social/), [Fedi account](https://mastodon.social/@benpate)): A customizable, private space in the Fediverse where people can create, share, and collaborate. `AGPL-3.0, Go`

* [**Enigmatick**](https://gitlab.com/enigmatick) ([Fedi account](https://ser.endipito.us/@justin)): Social networking platform (under development). `GPL-3.0, Rust`

* [**Epicyon**](https://gitlab.com/bashrc2/epicyon) ([site](https://libreserver.org/epicyon)): ActivityPub server implementing S2S and C2S protocols, suitable for single board computers. Includes features such as moderation tools, post expiry, content warnings, and image descriptions `AGPL-3.0, Python`

* [**Firefish**](https://git.joinfirefish.org/firefish/firefish) ([site](https://joinfirefish.org/), [Fedi account](https://info.firefish.dev/@firefish)): An actively developed, community-driven fork of Misskey with many quality of life improvements for users and admins alike `AGPL-3.0, TypeScript`

* [**FlockingBird**](https://github.com/flockingbird/roost) ([site](https://search.flockingbird.social), [Fedi account](https://fosstodon.org/@flockingbird)): social network for professionals (WIP) `MIT, Ruby`

* [**FoundKey**](https://akkoma.dev/FoundKeyGang/FoundKey): A fork of Misskey with various bugfixes and improvements. `AGPL-3.0, TypeScript`

* [**Friendica**](https://github.com/friendica/friendica) ([site](https://friendi.ca)): Personal network that helps to keep in contact with friends. Interface and functionality include common features of a mainstream social network `AGPL-3.0, PHP`

* [**GNU social**](https://notabug.org/diogo/gnu-social) ([site](https://gnusocial.network)): Microblogging server with multiple plugins `AGPL-3.0, PHP`

* [**Goldfish Social**](https://github.com/Goldfish-Social/Goldfish) ([Fedi account](https://mstdn.social/@stux)): Alternative for Vine / TikTok (alpha). ActivityPub will come later! `AGPL-3.0, PHP`

* [**Glitch-soc**](https://github.com/glitch-soc/mastodon) ([site](https://glitch-soc.github.io/docs), [Fedi account](https://friend.camp/@darius)): A friendly fork of Mastodon, with the aim of providing additional features at the risk of potentially less stable software `AGPL-3.0, Ruby`

* [**GoToSocial**](https://github.com/gotosocial/gotosocial) ([Fedi account](https://ondergrond.org/@dumpsterqueer)): A headless Mastodon-compatible Fediverse server project, written in Golang. `AGPL-3.0, Go`

* [**Hollo**](https://github.com/dahlia/hollo) ([Fedi account](https://hollo.social/@hollo)):- A federated single-user microblogging software powered by Fedify `AGPL-3.0, TypeScript`

* [**Hometown**](https://github.com/hometown-fork/hometown) ([Fedi account](https://friend.camp/@darius)): A fork of Mastodon that provides local posting and a wider range of content types `AGPL-3.0, Ruby`

* [**Honk**](https://humungus.tedunangst.com/r/honk) ([Fedi account](https://honk.tedunangst.com/u/tedu)): ActivityPub server with minimal setup and support costs `ISC, Go`

* [**Iceshrimp**](https://iceshrimp.dev/iceshrimp/iceshrimp): A Misskey fork with a focus on community needs, bugfixes, QoL and performance `AGPL-3.0, TypeScript`

* [**Iceshrimp.NET**](https://iceshrimp.dev/iceshrimp/Iceshrimp.NET) - New code base for Iceshrimp with a focus on performance, stability and maintainability `EUPL-1.2, C#`

* [**illuminant**](https://koldfront.dk/git/illuminant/tree/README.md): An ActivityPub server with an NNTP interface. `GPL-2.0, Haskell`

* [**im@stodon**](https://github.com/imas/mastodon) ([site](https://imastodon.net), [Fedi account](https://imastodon.net/@fusagiko)): A fork of Mastodon. Unlisted posts with tags are published on tags, a list of fav tags, image size restrictions and transcoding `AGPL-3.0, Ruby`

* [**Kakurega**](https://github.com/hideki0403/misskey.yukineko.me/): A fork of Misskey with a distraction free Zen Mode, hideable global timeline, and other QoL improvements `AGPL-3.0, TypeScript`

* [**Kanzaki**](https://github.com/KnzkDev/kanzaki): A Mastodon-compatible, ActivityPub-speaking server in OCaml `AGPL-3.0, OCaml`

* [**Kepi**](https://gitlab.com/marnanel/chapeau) ([Fedi account](https://queer.party/@marnanel)): A Django-based microblogging server, written in Python, which supports the Mastodon protocol. `GPL-2.0, Python`

* [**Kibou**](https://codeberg.org/charlag/kibou): Lightweight social networking server that implements Mastodon's REST API. `AGPL-3.0, Rust`

* [**Kitsune**](https://github.com/kitsune-soc/kitsune): ActivityPub-federated microblogging. `MIT, Rust`

* [**kmyblue**](https://github.com/kmycode/mastodon) ([site](https://kmy.blue), [Fedi account](https://kmy.blue/@official)): A fork of Mastodon for creators: emoji reactions, localposting, groups, misskey-like antennas, post self-destruction and more moderation options `AGPL-3.0, Ruby`

* [**Ktistec**](https://github.com/toddsundsted/ktistec) ([Fedi account](https://mastodon.social/@toddsundsted), [site](https://epiktistes.com/@toddsundsted/)): A single-user ActivityPub server with minimal dependencies, using SQLite, [server](https://epiktistes.com) `AGPL-3.0, Crystal`

* [**Kroeg**](https://web.archive.org/web/20220715210708/https://puck.moe/git/) ([site](https://puckipedia.com/kroeg)): Generic ActivityPub server, with a focus on microblogging style activities `Unknown, Rust`

* [**lectrn**](https://github.com/lectrn/lectrn) ([site](https://lectrn.com/)): A social network for humans that is free, decentralized, open, and easy to use. `AGPL-3.0, JavaScript`

* [**Leisskey**](https://github.com/Leies-202/misskey) ([site](https://mk.lei202.com), [Fedi account](@ia@mk.lei202.com)): A fork of Meisskey with an extra Sugar theme and no instance tickers. `AGPL-3.0, TypeScript`

* [**Letterbook**](https://github.com/Letterbook/Letterbook) ([Fedi account](https://hachyderm.io/@jenniferplusplus)): A Mastodon-compatible microblogging server, optimized to reduce administrative costs and burdens. `AGPL-3.0, C#`

* [**Little Forest**](https://github.com/mashirozx/mastodon) ([site](https://hello.2heng.xin/about/more), [Fedi account](https://hello.2heng.xin/@mashiro)): A fork of Mastodon with full Markdown, Quote and Local-Only Toots, Gitlab/hub sign-in, Google Translate, deeper support of Chinese and more theming. `AGPL-3.0, Ruby`

* [**Magnetar**](https://git.astolfo.cool/natty/magnetar): A social networking server anyone can self-host. `AGPL-3.0, Rust`

* [**mammoth**](https://gitlab.koehn.com/mammoth) ([Fedi account](https://mammoth.home.koehn.com/api/actor/bkoehn)): A federated social media platform implementing the ActivityPub specification for client/server and server/server communications. `AGPL-3.0, TypeScript`

* [**Mastodon**](https://github.com/tootsuite/mastodon) ([site](https://joinmastodon.org)): Epic microblogging network with many features and multiple interface layouts to choose from `AGPL-3.0, Ruby`

* [**Mathtodon**](https://github.com/Nyoho/mathtodon) ([site](https://mathtod.online/), [Fedi account](https://mathtod.online/@Nyoho)): A fork of Mastodon where you can post toots with beautiful mathematical formulae in TeX/LaTeX style `AGPL-3.0, Ruby`

* [**MatticNote**](https://github.com/MatticNote/MatticNote): ActivityPub compatible SNS that aims to be easy for everyone to use. `AGPL-3.0, Go`

* [**Mbin**](https://github.com/MbinOrg/mbin): A federated content aggregator, voting, discussion and microblogging platform. Fork of Kbin. `AGPL-3.0, PHP`

* [**microblog.pub**](https://git.sr.ht/~tsileo/microblog.pub) ([site](http://docs.microblog.pub)): Self-hosted, single-user, ActivityPub powered microblog. `AGPL-3.0, Python`

* [**microstatus**](https://github.com/Arkanosis/microstatus): Lightweight Mastodon and GNU Social-compatible server implementation `ISC, Rust`

* [**Milkey**](https://github.com/sakura-tel/milkey) ([site](https://milkey.homes), [Fedi account](https://milkey.homes/@Milkey221B)): A beta edition and continuation of Groundpolis `AGPL-3.0, TypeScript`

* [**Misskey**](https://github.com/misskey-dev/misskey) ([site](https://misskey-hub.net/en/)): Interplanetary microblogging platform. Provides many additional features like calendar, emoji reactions, polls, games, and many other widgets `AGPL-3.0, JavaScript`

* [**Misskey.art**](https://github.com/Misskey-art/misskey) ([site](https://misskey.art/)): Fork of Misskey by Misskey.art `AGPL-3.0, TypeScript`

* [**Mitra**](https://codeberg.org/silverpill/mitra) ([Fedi account](https://mitra.social/@mitra)): Built on ActivityPub protocol, self-hosted, lightweight `AGPL-3.0, Rust`

* [**Nekomiya-net**](https://github.com/nekomiyanet/misskey-v12) ([site](https://nekomiya.net/): A fork of Misskey focusing on maintainability and behaviour. Has a Cat timeline, fox ears, and Meisskey-like self-destructing notes. `AGPL-3.0, TypeScript`

* [**nexkey**](https://github.com/nexryai/nexkey): A fork of Misskey 12 optimized for small-to-medium servers. `AGPL-3.0, TypeScript`

* [**Nijimiss.moe**](https://github.com/TeamNijimiss/misskey) ([site](https://nijimiss.moe/), [Fedi account](@TeamNijimiss@nijimiss.moe)): A media-focused fork of Misskey, with refinable tag searches `AGPL-3.0, TypeScript`

* [**netop**](https://github.com/what-cheer/netop):  An ActivityPub Server in Scala. `MIT, Scala`

* [**OCamlot**](https://github.com/Gopiandcode/ocamlot): An ActivityPub server written in OCaml. `AGPL-3.0, OCaml`

* [**Personal Reader for Drupal**](https://git.drupalcode.org/project/reader) ([Fedi account](https://realize.be/user/1), [site](https://www.drupal.org/project/reader)): A personal reader on your website which is installable as a PWA on your phone or tablet. `GPL-2.0, PHP`

* [**Pinetta**](https://codeberg.org/pinetta/pinetta) ([Fedi account](https://fedi.software/@pinetta)): A decentralized, federated social pinboard in the style of Pinterest. (In development, see [prototype](https://codeberg.org/pinetta/proto-pinetta) `AGPL-3.0, Python`

* [**Pleroma**](https://git.pleroma.social/pleroma) ([site](https://pleroma.social)): Microblogging platform `AGPL-3.0, Elixir`

* [**Pothole**](https://github.com/penguinite/pothole): A lightweight federated microblogging server, designed to be simple & fast. `AGPL-3.0, Nim`

* [**pub**](https://github.com/davecheney/pub) ([Fedi account](https://cheney.net/@dfc)): A tiny ActivityPub host intended for a single actor, that implements Mastodon API for use with various clients. `BSD-3-Clause, Go`

* [**Pubblr**](https://github.com/brandonsides/pubblr): A federated blogging platform built on the ActivityPub protocol. `MIT, Go`

* [**pubgate**](https://github.com/autogestion/pubgate): Lightweight ActivityPub CMS. Implements both client-to-server (C2S) and server-to-server(S2S) APIs. Compatible with Mastodon, Pixelfed, Pleroma and microblog.pub. `BSD-3-Clause, Python`

* [**pump.io**](https://github.com/pump-io/pump.io/issues/1241): Still considers adding ActivityPub. `Apache-2.0, JavaScript`

* [**Rebased**](https://gitlab.com/soapbox-pub/rebased): Fediverse backend written in Elixir (fork of [Pleroma](https://pleroma.social/)). Compatible with the Mastodon API.  The recommended backend for [Soapbox](https://soapbox.pub), also supports [Pleroma-FE](https://docs-fe.akkoma.dev/stable/) as a frontend. `AGPL-3.0, Elixir`

* [**Ruffy**](https://github.com/Taullo/Ruffy) ([Fedi account](https://aethy.com/@Ruffy)): A fork of Glitchsoc, with a changed layout and focus on readability and rich content `AGPL-3.0, Ruby`

* [**Rustodon**](https://github.com/rustodon/rustodon): Mastodon-compatible server `AGPL-3.0, Rust`

* [**Seppo**](https://codeberg.org/seppo/seppo) ([site](https://seppo.social), [Fedi account](https://digitalcourage.social/@mro)): A server-side, single-user, Fediverse-integrated microblog engine. Creating static assets published by webserver. `GPL-3.0, OCaml`

* [**Sharkey**](https://git.joinsharkey.org/Sharkey/Sharkey) ([site](https://joinsharkey.org/), [Fedi account](https://transfem.social/@Amelia)): A Sharkish microblogging platform. `AGPL-3.0, TypeScript`

* [**Shuttlecraft**](https://github.com/benbrown/shuttlecraft) ([site](https://shuttlecraft.net/), [Fedi account](https://hackers.town/@benbrown)): A single user ActivityPub server to interact with the Fediverse and other indie web protocols like RSS. `MIT, JavaScript`

* [**Smalltown**](https://github.com/chandrn7/smalltown): A fork of Mastodon designed for civic communities looking to run their own social networks. `AGPL-3.0, Ruby`

* [**Smithereen**](https://github.com/grishka/Smithereen): VKontakte-like social network, with friends, walls, photo albums and groups `Unlicense, Java`

* [**snac**](https://codeberg.org/grunfink/snac2) ([Fedi account](https://comam.es/snac/grunfink)): A simple, minimalistic ActivityPub instance with minimal dependencies, multiuser, no database nor cookies needed, totally JavaScript-free `MIT, C`

* [**Soapbox**](https://gitlab.com/soapbox-pub/soapbox) ([site](https://soapbox.pub/), [Fedi account](https://gleasonator.com/users/soapbox)): Social media with a focus on custom branding and ease of use. `AGPL-3.0, Unknown`

* [**Socialhome**](https://codeberg.org/socialhome/socialhome) ([site](https://socialhome.network)): Personal webpage with social networking functionality `AGPL-3.0, Python`

* [**Spritely**](https://gitlab.com/spritely) ([site](https://spritely.institute), [Fedi account](https://octodon.social/@spritelyproject)): Research space for a next-gen distributed social network written in Racket and consisting of multiple projects, by AP specification co-author Christine Lemmer Webber. `Apache-2.0, Racket`

* [**Steskey**](https://github.com/Steve-0628/misskey): A fork of Misskey with deeper theming and some [reverts](https://github.com/Steve-0628/misskey/blob/steskey/DIFFERENCE.md) `AGPL-3.0, TypeScript`

* [**Streams**](https://codeberg.org/streams/streams) ([Fedi account](https://fediversity.site/channel/streams)): Public domain federated communications server. Provides a feature rich ActivityPub and Nomad communication node. `Public Domain, PHP`

* [**Swanye**](https://codeberg.org/WammKD/Swanye) ([Fedi account](https://fosstodon.org/@Swanye)): A tumblelog in the style of Tumblr. `AGPL-3.0, Elixir`

* [**Takahē**](https://github.com/andrewgodwin/takahe) ([site](https://jointakahe.org), [Fedi account](https://jointakahe.takahe.social/@takahe)): An experimental Fediverse server for microblogging `BSD-3-Clause, Python`

* [**Tanukey**](https://github.com/tanukey-dev/tanukey): A fork of Misskey for managed environments `AGPL-3.0, TypeScript`

* [**Tapir**](https://github.com/ar-nelson/tapir) ([Fedi account](https://tapir.social/@tapir), [site](https://tapir.social)): A small, efficient Mastodon-compatible Fediverse server for single-user instances. Based on Deno. (Note: [license discussion](https://socialhub.activitypub.rocks/t/hi-everyone/3165/8)) `Blue Oak, TypeScript`

* [**Tavern**](https://gitlab.com/ngerakines/tavern/-/tree/release-amber-ale) ([Fedi account](https://mastodon.social/@ngerakines)): A minimalistic Activity Pub server. Think Mastodon, but smaller and with fewer features `MIT, Go`

* [**Toki**](https://github.com/purifetchi/Toki)  ([Fedi account](https://sh.itjust.works/u/prefetcher)) Will support the Mastodon API. `AGPL-3.0, C#`

* [**Tootik**](https://github.com/dimkr/tootik): A federated nanoblogging service with a Gemini frontend. `Apache-2.0, Go`

* [**Type-9ine**](https://github.com/9ineverse-dev/Type-9ine) ([site](9ineverse.com)): A fork of Misskey with some features expanded for 9ineverse.com community needs. `AGPL-3.0, TypeScript`

* [**Vagabond**](https://github.com/CameronWhiteCS/Vagabond) ([site](https://stable.teamvagabond.com/)): A federated social network built with security and privacy in mind. `GPL-3.0, Python`

* [**Wafrn**](https://github.com/gabboman/wafrn): Small Tumbl-inspired social network. `Apache-2.0, TypeScript`

* [**Yarn**](https://git.mills.io/yarnsocial/yarn) ([site](https://yarn.social/)): A decentralised self-hosted microblogging platform that has a privacy-first focus. `AGPL-3.0, Go`

* [**Yoiyami**](https://github.com/rca-fedi/yoiyami): A fork of Misskey which tries to make features opt-out. For example, you can hide custom emoji reactions. `AGPL-3.0, TypeScript`

* :ghost: [**Dolphin**](https://github.com/syuilo/dolphin): Lightweight ActivityPub Server optimized for single-user. A fork and sister project of Misskey `AGPL-3.0, JavaScript`

* :ghost: [**fed**](https://github.com/kissen/fed): Trying to be a basic twitter-like service that works with ActivityPub. Based on [Go-Fed](https://go-fed.org) `GPL-3.0, Go`

* :ghost: [**GangGo**](https://github.com/ganggo/ganggo/tree/develop)  - Developer has suspended development for the foreseeable future. `Unknown, Unknown`

* :ghost: [**groundpolis**](https://github.com/xeltica/groundpolis): A microblogging service forked from Misskey `AGPL-3.0, TypeScript`

* :ghost: [**Jejune**](https://github.com/kaniini/jejune) - A work-in-progress ActivityPub server designed to use constructions which provide functional security and resilience `ISC license, Python`

* :ghost: [**Kitsune**](https://github.com/valerauko/kitsune): An ActivityPub-speaking microblogging service. No updates since 2022. `AGPL-3.0, Clojure`

* :ghost: [**Lumen-ap-server**](https://notabug.org/tinyrabbit/lumen-ap-server) ([Fedi account](https://floss.social/@tinyrabbit)): ActivityPub server using Lumen framework `MIT, PHP`

* :ghost: [**Mistpark 2020**](https://codeberg.org/zot-archive/misty) aka 'misty' - A webserver app that supports AP and Zot protocols, fork of Zap. (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**MrBotchi**](https://github.com/mrbotchi-team/mrbotchi) ([Fedi account](https://norimono.moe/@silverscat_3)): A federated microblogging platform for single-user - not updated since June 2020 `AGPL-3.0, Go`

* :ghost: [**Osada**](https://codeberg.org/zot-archive/osada) - A full featured social network application. (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**Pylodon**](https://github.com/rowanlupton/pylodon) - Flask-based ActivityPub server, [source code also on GitLab](https://gitlab.com/rowanlupton/pylodon), no updates on either repo for about a year, nor on their [Smilodon client app](https://github.com/rowanlupton/smilodon). `Unknown, Python`

* :ghost: [**Redmatrix 2020**](https://codeberg.org/zot-archive/redmatrix): A fediverse server. (replaced by streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**Roadhouse**](https://codeberg.org/zot-archive/roadhouse): Next gen Fediverse server. (replaced by streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

* :ghost: [**ShaarliGo**](https://code.mro.name/mro/ShaarliGo): Self-reliantly posting on the #Fediverse with painless hosting and security in mind. `GPL-3.0, Go`

* :ghost: [**Smilodon**](https://gitlab.com/tuxcrafting/smilodon) (server by Tuxcraft) - abandoned by developer "I'm now [working on Sminos](https://gitlab.com/tuxcrafting/sminos/issues/1) and so this will probably be 100% abandoned. There's not much to salvage, its code is cancer." Sminos appears to have never got beyond the initial commits `0BSD, Unknown`

* :ghost: [**ssb ap bridge**](https://github.com/DanielMowitz/ssb_ap_bridge): currently working on a bridge between SSB and AP networks. No updates since 2019 `Unknown, JavaScript`

* :ghost: [**Technopolis**](https://github.com/technopolis-microblog) ([site](https://technopolis.app/), [Fedi account](https://norimono.moe/@silverscat_3)): A globally interconnected micro-blogging platform inspired by Misskey - not updated since December 2020 `AGPL-3.0, Rust`

* :ghost: [**tranquility**](https://github.com/aumetra/tranquility): Small ActivityPub server written in Rust. (Archived, see [issue](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/32)) `MIT, Rust`

* :ghost: [**un chapeau**](https://gitlab.com/marnanel/un_chapeau/-/issues/17): Server for the Mastodon protocol, implemented in Django. Latest commit - May 2019. `AGPL-3.0, Python`

* :ghost: [**Zap**](https://codeberg.org/zot-archive/zap): A webserver app that supports AP and Zot protocols (EOL, replaced by Streams. See [#20](https://codeberg.org/fediverse/delightful-fediverse-apps/issues/20#issuecomment-749876)) `CC0-like, PHP`

#### Blogging, Publishing, and Reading

* [**Dokie.li**](https://github.com/linkeddata/dokieli) ([site](https://dokie.li)): Article authoring and formating `Apache-2.0, JavaScript`

* [**Ghost**](https://github.com/tryghost/ghost) ([site](https://activitypub.ghost.org)): Independent technology for modern publishing, memberships, subscriptions and newsletters. `MIT, JavaScript`

* [**Gimli**](https://codeberg.org/Laxystem/Gimli/): Federated end-to-end-encrypted guild-based messaging app & blogging platform. `MPL-2.0, Kotlin`

* [**GoBlog**](https://git.jlel.se/jlelse/GoBlog) ([site](https://goblog.app), [Fedi account](https://fosstodon.org/@jle)): Simple blogging system written in Go `MIT, Go`

* [**Hubzilla**](https://framagit.org/hubzilla) ([site](https://hubzilla.org)): CMS with a range of groupware tools available as plug-ins `MIT, PHP`

* [**Known**](https://github.com/idno/known) ([site](https://withknown.com), [Fedi account](https://mastodon.social/@benwerd)): A collaborative social publishing engine (Working on AP support, see [this issue](https://github.com/idno/known/issues/2615)). `Apache-2.0, PHP`

* [**Little Library**](https://github.com/Alamantus/little-library): A digital give-a-book, take-a-book library for ebooks. `AGPL-3.0, JavaScript`

* [**Plume**](https://github.com/Plume-org/Plume) ([site](https://joinplu.me)): Blogging application `AGPL-3.0, Rust`

* [**Read.as**](https://github.com/writeas/Read.as) ([site](https://read.as)): Reading app by the devs of WriteFreely `AGPL-3.0, Go`

* [**site**](https://github.com/Lonor/site): Minimalist blog that implements ActivityPub endpoints. `MIT, JavaScript`

* [**social.distributed.press**](https://github.com/hyphacoop/social.distributed.press): A Social Inbox for Decentralized Publishing and ActivityPub. `AGPL-3.0, TypeScript`

* [**Wordforge**](https://codeberg.org/grafcube/wordforge): Federated creative writing server. Write novels using markdown. `AGPL-3.0, Rust`

* [**WordPress**](https://github.com/automattic/wordpress-activitypub): Official Automattic plugin that federates WordPress blogs into the fediverse. `MIT, PHP`

* [**WriteFreely**](https://github.com/writefreely) ([site](https://writefreely.org), [Fedi account](https://writing.exchange/@writefreely)): Blog software `AGPL-3.0, Go`

* [**Yuforium**](https://github.com/yuforium) ([Fedi account](https://mastodon.social/@cpmoser)): A federated community platform that focuses on federated communities so they are no longer constrained to a single entity. `GPL-3.0, TypeScript`

* :ghost: [**FediBlog**](https://framagit.org/DavidLibeau/FediBlog) ([site](https://fedi.blog)): Fully customisable blog engine `GPL-3.0, PHP`

* :ghost: [**Lamia**](https://github.com/Scarly-Crow/lamia): Distributed blogging, polls, and status updates powered by activitypub, python, the gay agenda, and snake women. `AGPL-3.0, Python`

* :ghost: [**NoteIn**](https://github.com/notein/NoteIn): No commits since October 2018. `Unknown, Unknown`

* :ghost: [**Redaktor**](https://redaktor.me): AP-powered CMS; website suspended, no actual code repo. `Unknown, Unknown`

#### Link-sharing, Forums, and Groups

* [**Azorius**](https://humungus.tedunangst.com/r/azorius): A link aggregator and comment site. `ISC, Go`

* [**Betula**](https://git.sr.ht/~bouncepaw/betula/tree) ([site](https://betula.mycorrhiza.wiki/)): Self-hosted personal link collection manager. `AGPL-3.0, Go`

* [**brutalinks**](https://github.com/mariusor/go-littr) ([Fedi account](https://metalhead.club/@mariusor)): Link aggregator inspired by Reddit `MIT, Go`

* [**ENiGMA½**](https://github.com/NuSkooler/enigma-bbs): A modern BBS software with a nostalgic flair. (see: [issue](https://github.com/NuSkooler/enigma-bbs/issues/459)) `BSD-2-Clause, JavaScript`

* [**Flarum**](https://github.com/squeevee/flarum-ext-feddle): Experimental plugin for [Flarum](https://flarum.org/) forum software by [@squeevee](https://yiff.life/@squeevee/102496777538790361). `MIT, PHP`

* [**Kbin**](https://codeberg.org/Kbin/kbin-core) ([site](https://kbin.pub)): Link aggregator and microblogging platform for Fediverse `AGPL-3.0, PHP`

* [**Lemmy**](https://github.com/dessalines/lemmy): Link aggregator, by [@LemmyDev](https://mastodon.social/@LemmyDev/102106696961226378) `AGPL-3.0, Rust`

* [**Lobste.rs**](https://github.com/lobsters/lobsters/issues/499): Existing Reddit replacement adding AP support, AP issue still open. `Unknown, Ruby`

* [**lotide**](https://git.sr.ht/~vpzom/lotide): A federated forum / link aggregator. `AGPL-3.0, Rust`

* [**MoonTree**](https://github.com/Faleidel/moontreeproject): Link aggregator, a work in progress `MIT, TypeScript`

* [**PieFed**](https://codeberg.org/rimu/pyfedi) ([site](https://join.piefed.social/), [Fedi account](https://mastodon.nzoss.nz/@rimu)): A federated forum / link aggregator. `AGPL-3.0, Python`

* [**Postmarks**](https://github.com/ckolderup/postmarks) ([site](https://postmarks.glitch.me/)): A single-user bookmarking website designed to live on the Fediverse `MIT, JavaScript`

* [**Smilodon**](https://source.puri.sm/liberty/host/smilodon): the server by Purism used in LibreOne, not the abandoned Tuxcraft server or Pylodon client; a complementary fork of Mastodon, focusing on opt-in public spaces `AGPL-3.0, Ruby`

* [**Vicinitude**](https://gitlab.com/RyanMcCoskrie/vicinitude): A social media platform for Local Communities. `MIT, Ruby`

* [**vxwClub**](https://github.com/wxwmoe/wxwClub): Simple social groups compatible with ActivityPub. `MIT, PHP`

* :ghost: [**Anancus**](https://gitlab.com/tuxether/anancus): By [@tuxether](https://floss.social/@tuxether), Link aggregator, [discontinued](https://gitlab.com/tuxether/anancus/issues/2)? `Unknown, Unknown`

* :ghost: [**Prismo**](https://gitlab.com/prismosuite/prismo) ([Fedi account](https://mastodon.social/@prismo)): Link aggregator. Latest update - May 2019. `AGPL-3.0, Ruby`

#### Media Hosting

* [**Anfora**](https://github.com/anforaProject/anfora) ([site](https://anfora.app)): (formerly Zinat) Image sharing `AGPL-3.0, Python`

* [**CastoPod Host**](https://code.podlibre.org/podlibre/castopod) ([site](https://podlibre.org/), [Fedi account](https://podlibre.social/@castopod)): An open-source hosting platform made for podcasters who want engage and interact with their audience. `AGPL-3.0, PHP`

* [**Catcast D**](https://github.com/mrcatman/catcast-d) ([Fedi account](https://mastodon.social/@mrcatmann)): A federated video live streaming platform `Unknown, TypeScript`

* [**FChannel**](https://github.com/FChannel0/FChannel-Server): A libre, self-hostable, federated, imageboard platform that utilizes ActivityPub. `AGPL-3.0, Go`

* [**FunkWhale**](https://dev.funkwhale.audio/funkwhale/funkwhale) ([site](https://funkwhale.audio)): Music streaming `AGPL-3.0, Python`

* [**Librecast LIVE**](https://codeberg.org/librecast/librecast-live) ([Fedi account](https://chaos.social/@onepict), [site](https://librecast.net/live.html)): Live Streaming Video Platform with Multicast `GPL-2.0, JavaScript`

* [**Minipub**](https://github.com/skymethod/minipub) ([site](https://minipub.dev)): Minimal ActivityPub server for posting federated podcast comments `MIT, TypeScript`

* [**Owncast**](https://github.com/owncast/owncast) ([site](https://owncast.online), [Fedi account](@gabek@mastodon.social)): Owncast is a self-hosted live video and web chat server for use with existing popular broadcasting software. `MIT, Go`

* [**PeerTube**](https://github.com/Chocobozzz/PeerTube) ([Fedi account](https://framapiaf.org/@peertube), [site](http://joinpeertube.org)): Video-hosting site using WebTorrent `AGPL-3.0, TypeScript`

* [**PixelFed**](https://github.com/dansup/pixelfed) ([site](https://pixelfed.org), [Fedi account](https://mastodon.social/@pixelfed)): Photo Sharing. For Everyone. A free and ethical photo sharing platform. `AGPL-3.0, PHP`

* [**Podverse**](https://github.com/podverse/podverse-web) ([Fedi account](https://podcastindex.social/web/@podverse), [site](https://podverse.fm)): Web app for the Podverse podcast clip sharing system. `AGPL-3.0, TypeScript`

* [**snap.as**](https://github.com/snapas) ([Fedi account](https://m.abunchtell.com/@snap_as), [site](https://snap.as)): Snap.as is a minimalist tool for publishing and sharing your photos on the web. `MIT, Go`

* [**Vidzy**](https://codeberg.org/vidzy/vidzy) ([site](https://vidzy.codeberg.page/)): The federated alternative to TikTok. `AGPL-3.0, Python`

* :ghost: [**Acorde**](https://github.com/polymerwitch/Acorde) - federated social music platform. Almost a year has passed since the initial commit. `Unknown, Unknown`

* :ghost: [**Audon**](https://codeberg.org/namekuji/audon): Audio chat space for Mastodon, Akkoma, GoToSocial, and Firefish. `AGPL-3.0-or-later, Go`

* :ghost: [**Fontina**](https://github.com/beta-phenylethylamine/fontina) - proposed as a photo-sharing social media network. GH repo has gone read-only, and now says "dead project" `Unknown, Unknown`

* :ghost: [**Marmota**](https://gitlab.com/Nefix/marmota/issues?label_name=ActivityPub): Streaming service like Spotify. No commits -  since March 2019. `Unknown, Unknown`

* :ghost: [**Pubcast**](https://github.com/pubcast/pubcast) ([site](https://pubcast.pub)): Podcasting platform that allows people to listen to podcasts in a new way. Latest commit - March 2019. `MPL-2.0, Go`

* :ghost: [**PeerPx**](https://github.com/peerpx): Social network for photographers (alternative to 500px / Flickr); Latest commit - October 2018. `Unknown, Unknown`

* :ghost: [**reel2bits**](https://github.com/rhaamo/reel2bits) ([site](https://reel2bits.org)): Music and podcast hosting, `AGPL-3.0, Python`

* :ghost: [**Soundstorm**](https://github.com/weathermen/soundstorm): The Federated Social Audio Platform. (Currently inactive, see [issue](https://github.com/weathermen/soundstorm/issues/21#issuecomment-882626364)) `GPL-3.0, Python`

#### Events and Meetups

* [**Gancio**](https://framagit.org/les/gancio) ([site](https://gancio.org)): Shared agenda for local communities; demo [site](https://demo.gancio.org) `AGPL-3.0, JavaScript`

* [**Gathio**](https://github.com/lowercasename/gathio) ([site](https://gath.io/)): Public events with no registration required `GPL-3.0, JavaScript`

* [**GetTogether**](https://github.com/GetTogetherComm/GetTogether/issues/60): Still considering adding AP support. `Python, BSD-2-Clause`

* [**Mobilizon**](https://framagit.org/framasoft/mobilizon) ([site](https://joinmobilizon.org/en), [Fedi account](https://framapiaf.org/@mobilizon), [Current owners](https://www.kaihuri.org/)): Federated Event planner. `AGPL-3.0, Elixir`

* **Friendica** (see above) has an [events engine that federates events over AP](https://socialhub.activitypub.rocks/t/activitypub-at-36c3-the-decentral-assembly-and-fediverse-party/402/5) and is looking to test interop with other AP events apps. [NextCloud federated events](https://github.com/nextcloud/calendar/pull/878) are in the works but this [may or may not be AP-compatible](https://github.com/nextcloud/server/issues/1440). `AGPL-3.0, PHP`

* :ghost: [**The Occasion Octopus**](https://github.com/theoccasionoctopus/theoccasionoctopus-server) ([site](https://www.theoccasionoctopus.net/), [Fedi account](https://fosstodon.org/@theoccasionoctopus)): A federated network of Open Data for discovering interesting events; no updates since 2021 `AGPL-3.0, PHP`

* :ghost: [**FedEvent**](https://github.com/shiburizu/fedevent): A prototype for federating event information. `Unknown, Unknown`

#### Files, Contacts, and Calendar Syncing

* [**Artist Hub**](https://github.com/creative-passport/artist-hub) ([site](https://www.creativepassport.net/)): Part of Creative Passport NGI0-funded project for providing a verified digital ID for Music Makers (very early stage of development) `AGPL-3.0, TypeScript`

* [**NextCloud-Social**](https://github.com/nextcloud/social) ([site](https://apps.nextcloud.com/apps/social)): Social networking app for NextCloud `AGPL-3.0, PHP`

* [**MoodleNet**](https://gitlab.com/moodlenet): [Social client for Moodle](https://moodle.com/moodlenet) LMS (Learning Management System) aimed at helping teachers collaboratively collate and curate sets of OER (Open Educational Resources). `AGPL-3.0, Unknown`

* :ghost: [**Calendar-social**](https://gitea.polonkai.eu/gergely/calendar-social/) - was definitely planning to [implement AP](https://gitea.polonkai.eu/gergely/calendar-social/issues/122). Missing, [presumed discontinued](https://gitea.polonkai.eu/gergely/calendar-social/issues/123) `Unknown, Unknown`

#### Open data

* [**bopwiki**](https://codeberg.org/Valenoern/bopwiki) ([Fedi account](https://floss.social/@Valenoern)): An experimental 'microwiki implementation' / 'mini CMS' with ActivityPub support. `GPL-3.0, Common Lisp`

* [**Chatter Net**](https://github.com/chatternet/chatternet-server-http): Chatter Net is a modern decentralized semantic web built atop self-sovereign identity. `MIT, Rust`

* [**CPub**](https://gitlab.com/openengiadina/cpub): A semantic web server, implements a Linked Data Platform (LDP), uses RDF Turtle as serialization format, part of the [openEngiadina](https://openengiadina.net) project `AGPL-3.0, Elixir`

* [**Inventaire**](https://github.com/inventaire/inventaire) ([site](https://inventaire.io/welcome), [Fedi account](https://mamot.fr/@inventaire)): A libre collaborative resource mapper powered by open-knowledge, starting with books. (Considers AP integration, see [Github issue](https://github.com/inventaire/inventaire/issues/187)) `AGPL-3.0, JavaScript`

* [**OLKi**](https://framagit.org/synalp/olki/olki/-/wikis/ActivityPub-dialect-documentation) ([site](https://olki.loria.fr/platform), [Fedi account](https://mastodon.etalab.gouv.fr/@scifed)): A self-hosted linguistic corpora exchange platform that aims to be a simple gateway to the Fediverse for scientific interaction `AGPL-3.0, Python`

* [**Openki**](https://gitlab.com/Openki/Openki) ([site](https://openki.net/)): An interactive p2p web-platform to provide barrier-free access to education for everyone. (not federated yet, see [AP feature request](https://gitlab.com/Openki/Openki/-/issues/1263)) `AGPL-3.0, JavaScript`

* [**SemApps**](http://www.virtual-assembly.org/semapps-2/) ([site](http://semapps.org/?PagePrincipale&lang=en)): A collaborative, generic knowledge management system. Aims to ease data storage and filtering. `Apache-2.0, JavaScript`

* [**SkoHub**](https://github.com/hbz/skohub-pubsub) ([site](https://skohub.io)): Creates a publication / subscription infrastructure for Open Educational Resources. It allows to follow specific subjects and to be notified when new content about that subject is published. `Apache-2.0, JavaScript`

* [**XWiki**](https://github.com/xwiki) ([site](http://www.xwiki.org/), [Fedi account](https://social.weho.st/@XWiki)): An advanced open source Enterprise Wiki (via the [ActivityPub Extension](https://extensions.xwiki.org/xwiki/bin/view/Extension/ActivityPub%20Application/)). `LGPL 2.1, Java`

#### Reviewing

* [**Bookwyrm**](https://github.com/mouse-reeve/bookwyrm) ([site](https://joinbookwyrm.com), [Fedi account](https://tech.lgbt/@bookwyrm)): A federated alternative to Goodreads (non-OSS license) `ANTI-CAPITALIST SOFTWARE LICENSE v1.4, Python`

* [**FediMovies**](https://code.caric.io/FediMovies/fedimovies): Lively federated movies reviews platform. `AGPL-3.0, Rust`

* [**LibRate**](https://codeberg.org/mjh/LibRate): Libre media rating website. `AGPL-3.0, Go`

* [**NeoDB**](https://github.com/neodb-social/neodb) ([site](https://neodb.net), [Fedi account](https://mastodon.social/@neodb)): Self-hosted server that helps users manage, share and discover collections, reviews and ratings for books, movies, music, podcasts, games and performances in Fediverse. `AGPL-3.0, Python`

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

* [**Gill**](https://github.com/oknozor/gill): a free and open-source git-service based on ActivityPub and ForgeFed. Previously called Ruisseau. `MIT, Rust`

* [**Vervis**](https://vervis.peers.community/repos/WvWbo/source) ([Fedi account](https://todon.nl/@fr33domlover)): Eventually-decentralized project hosting and management platform. Reference implementation for [ForgeFed](https://forgefed.org) protocol extension. `AGPL-3.0, Haskell`

* :ghost: [**Distbin**](https://github.com/gobengo/distbin) ([site](https://distbin.com)): Post bin. Latest commit - September 2019. `Apache-2.0, TypeScript`

#### Extensions

* [**apevents**](https://github.com/ngerakines/apevents) ([Fedi account](https://thegem.city/@nick)): Event management system that allows event creation and coordination across Fediverse `MIT, Rust`

* [**AP-Groups**](https://github.com/michaelcpuckett/ap-groups) ([site](https://chirp.social/), [Fedi account](https://a11y.social/@mpuckett)): Group actors as bot/relay. `MIT, TypeScript`

* [**Fediplan**](https://framagit.org/tom79/fediplan) ([site](https://fedilab.app/page/fediplan/), [Fedi account](https://toot.fedilab.app/@apps)): A way to safely schedule messages with Mastodon and Pleroma. `GPL-3.0, PHP`

* [**Group actor**](https://git.ondrovo.com/MightyPork/group-actor) ([Fedi account](https://piggo.space/users/piggo)): Groups work with any software that implements Mastodon client API; has moderation, admin announcements, [test server](https://piggo.space/hob) `MIT, Rust`

* [**Guppe**](https://github.com/wmurphyrd/guppe) ([site](https://a.gup.pe)): By [@datatitian](https://social.coop/@datatitian/102837577105371476), adds "groups" support as group-type actors `GPL-3.0, JavaScript`

* [**Mastodon Bot Autoresponder**](https://github.com/drequivalent/mastodon-bot-autoresponder) ([Fedi account](https://mastodon.ml/@drq)): A bot that implements group functionality in Mastodon. `MIT, Python`

* [**tootgroup.py**](https://github.com/oe4dns/tootgroup.py): Emulate group accounts on Mastodon. `GPL-3.0, Python`

#### Other

* [**activitypub-core**](https://github.com/michaelcpuckett/activitypub-core): An attempt to build a spec-compliant ActivityPub server in Node.js. `MIT, TypeScript`

* [**Alovoa**](https://github.com/Alovoa/alovoa) ([site](https://alovoa.com/)): Free and open-source dating platform that respects your privacy (considering AP support, see [issue](https://github.com/Alovoa/alovoa/issues/13)) `AGPL-3.0, Java`

* [**bovine_herd**](https://codeberg.org/bovine/bovine/src/branch/main/bovine_herd): A bovine powered ActivityPub server, which interoperates with the rest of the FediVerse. `MIT, Python`

* [**Communecter**](https://github.com/pixelhumain/communecter) ([site](https://www.communecter.org/)): Manage cities as a connected citizen, produce openCityData, manage organizations, projects, events openly, an open societal approach (intends to add AP support, see [this issue](https://github.com/pixelhumain/communecter/issues/1395)) `Apache-2.0, PHP`

* [**Corteza**](https://github.com/cortezaproject/corteza-server) ([site](https://cortezaproject.org)): "Digital Work Platform for Humanity" an open-source, low-code federated platform for building cloud-based business apps with CRM capabilities `Apache-2.0, Go`

* [**DiveDB**](https://github.com/cetra3/divedb): Web application that allows Scuba Divers to catalogue and record their dives, dive sites, sealife and photos. ([site](https://divedb.net/)): `AGPL-3.0, Rust`

* [**ENiGMA½ BBS**](https://github.com/NuSkooler/enigma-bbs) ([site](https://nuskooler.github.io/enigma-bbs/)): A modern BBS software with a nostalgic flair! (In progress, see [PR](https://github.com/NuSkooler/enigma-bbs/pull/460)) `BSD-2-Clause, JavaScript`

* [**FairSync**](https://git.fairkom.net/fairsync) ([site](https://fairmove.it/fairsync/)): Develops and collects best practices to synchronize maps and events and to federate messengers and identities. (Funded with NGI0, implementing ActivityStreams, but AP support not clear, currently unlicensed) `CC0-like, Java`

* [**FitTrackee**](https://github.com/SamR1/FitTrackee) ([Fedi account](https://mastodon.social/@SamR1)): A simple self-hosted workout / activity tracker. (Still considering AP support, see [issue](https://github.com/SamR1/FitTrackee/issues/16)) `AGPL-3.0, Python`

* [**flohmarkt**](https://codeberg.org/grindhold/flohmarkt): A decentralised federated small trade platform. `AGPL-3.0, Python`

* [**fossilphant**](https://github.com/swaldman/fossilphant) ([Fedi account](https://zirk.us/@interfluidity)): A static-site generator for Mastodon archives. `AGPL-3.0, Scala`

* [**hvxahv-platform**](https://github.com/disism/hvxahv) ([site](https://dev.halfmemories.com): A multifunctional decentralized social network implementation. `MIT, Go`

* [**Immers Space**](https://github.com/immers-space/immers) ([Fedi account](https://gup.pe/u/immersspace)): The decent(ralized) metaverse. `AGPL-3.0, JavaScript`

* [**Inbox**](https://github.com/WhyINeedToFillUsername/inbox) ([site](https://whyineedtofillusername.github.io/inbox/about)): An application built for a diploma thesis to showcase work with Linked Data Notifications, Activity Streams and ActivityPub, using Solid pod as data provider. (See also [Solid forum discussion](https://forum.solidproject.org/t/inbox-new-messaging-application/4093). No license, see [issue](https://github.com/WhyINeedToFillUsername/inbox/issues/2)) `Unknown, TypeScript`

* [**Life Server**](https://github.com/interop-alliance/life-server) ([site](https://permanent.cloud/apps/life-server)): A decentralized personal data framework inspired by MIT's Solid Project (AP support planned, see [Roadmap](https://github.com/interop-alliance/life-server/blob/main/README.md#roadmap)), `MIT, JavaScript`

* [**Ocelot Social**](https://github.com/Ocelot-Social-Community/Ocelot-Social): Free and open-source social network for active citizenship. `MIT, JavaScript`

* [**retrospring**](https://github.com/Retrospring/retrospring) ([site](https://retrospring.net/), [Fedi account](https://floss.social/@retrospring)): Q&A based social network. Ask questions, give answers and learn more about your friends. (AP support planned. See: [Github issue](https://github.com/Retrospring/retrospring/issues/395)) `AGPL-3.0, Ruby`

* [**Smartlike**](https://github.com/smartlike-org/smartlike) ([site](https://smartlike.org/), [Fedi account](https://mastodon.social/@vadim_frolov)): A free non-profit decentralized donation processor with a focus on freedom, privacy and efficiency. `AGPL-3.0, Rust`

* [**Transit Fedilerts**](https://github.com/kona314/transit-fedilerts) ([site](https://transit.alerts.social/)): ActivityPub-compliant server for distributing transit service alerts. `ISC, TypeScript`

* [**Vocata**](https://codeberg.org/Vocata/vocata): A vocabulary-agnostic ActivityPub server. Vocata does not limit what types of content can be handled by it, and how it is presented to users. `LGPL-3.0-or-later, Python`

* :ghost: [**Agora**](https://github.com/scenaristeur/agora): [site](https://scenaristeur.github.io/agora),  POC to use ActivityPub on top of the Solid Platform. - developed by [@spoggy@mstdn.fr](https://mstdn.fr/@spoggy). Latest commit - June 2020 `Unknown, Unknown`

* :ghost: [**Indienet**](https://source.ind.ie/indienet) - [archive](https://web.archive.org/web/20190507034117/https://indienet.info/) - abandoned in favour of [Tincan development](https://small-tech.org/research-and-development) `Unknown, Unknown`

* :ghost: [**Numa**](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain, was federating with AP. No commits since April 2018. `MIT, Ruby`

* :ghost: [**Pantheon**](https://github.com/TGNThump/Pantheon): Platform for building communities. No commits since September 2019. `Unknown, Unknown`

## Sources

Aside from project pages and issue trackers, comments made on the fediverse, the [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hoped would implement ActivityPub and links to issues where it's discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). There are many projects using AP [profiled on We Distribute](http://wedistribute.org/). There are boards for discussing a range of [implementations on the SocialHub forum](https://socialhub.activitypub.rocks/c/software/14). [Alternative.to](https://alternativeto.net/list/5696/activitypub) has a list of servers and client apps. The [ActivityPub tag on Github](https://github.com/topics/activitypub) is also a good way to discover projects experimenting with an implementation.

## Maintainers

If you have questions or feedback regarding this list, then please create an [Issue](https://codeberg.org/fediverse/delightful-fediverse-apps/issues) in our tracker, and optionally `@mention` one or more of our maintainers:

- [`@circlebuilder`](https://codeberg.org/circlebuilder)
- [`@lostinlight`](https://codeberg.org/lostinlight)
- [`@wakest`](https://codeberg.org/wakest)
- [`@wisdomchicken`](https://codeberg.org/wisdomchicken)

## Contributors

With delight we present you some of our [delightful contributors](delightful-contributors.md) (please [add yourself](https://codeberg.org/fediverse/delightful-fediverse-apps/src/branch/main/delightful-contributors.md) if you are missing).

## License

[![CC0 Public domain. This work is free of known copyright restrictions.](https://i.creativecommons.org/p/mark/1.0/88x31.png)](LICENSE)
