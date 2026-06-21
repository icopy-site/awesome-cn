<div class="github-widget" data-repo="atblueprints/awesome-atproto"></div>
<div align="center">
<img src="https://raw.githubusercontent.com/atblueprints/awesome-atproto/main/assets/logo.png" width="300px">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

## Awesome ATProto 

> [AT Protocol](https://atproto.com/) is a federated protocol for building social applications on an open, decentralized network



## AT Protocol

### References

* [Glossary](https://atproto.com/guides/glossary) - Quick reference to AT Protocol terms.
* [Lexicons, Pinned Posts, and Interoperability](https://docs.bsky.app/blog/pinned-posts) - Post-mortem about the evolution of lexicons and lessons learned.
* [Quick start guide to building applications on AT Protocol](https://atproto.com/guides/applications) - Guide to create a basic ATProto application.

### Articles

* [First impressions of Bluesky's AT Protocol](https://educatedguesswork.org/posts/atproto-firstlook/) - In-depth analysis of Bluesky's ATProto, highlighting its aim to create a decentralized social media architecture.
* [Nostr and ATProto](https://shreyanjain.net/2024/07/05/nostr-and-atproto.html) - Comparison of Nostr and ATProto, two decentralized social media protocols, exploring their origins, similarities, and differences.
* [How decentralized is Bluesky really?](https://dustycloud.org/blog/how-decentralized-is-bluesky/) - Critical examination of Bluesky's decentralization claims and its architectural challenges compared to established protocols.
* [Reply on Bluesky and Decentralization](https://whtwnd.com/bnewbold.net/3lbvbtqrg5t2t) - Reply to Christine Lemmer-Webber's thoughtful (and widely read) "How decentralized is Bluesky really?" blog post.
* [What is atproto.com good for?](https://bnewbold.net/2022/atproto_thoughts/) - Technical exploration of ATProto's design principles, architectural challenges, and potential limitations as a decentralized social media protocol.
* [The AT Protocol Architecture](https://hackernoon.com/the-at-protocol-architecture) - Analysis of the ATProto's architecture.
* [Notes on Running a Full-Network atproto Relay (July 2024)](https://whtwnd.com/bnewbold.net/entries/Notes%20on%20Running%20a%20Full-Network%20atproto%20Relay%20(July%202024)) - Experience about running an ATProto relay.

## Browsers

* [PDSls](https://pdsls.dev/) - ATProto repositories browser.
* [ATProto Browser](https://atproto-browser.vercel.app/) - ATProto URIs browser.

## Platforms

* [Bluesky](https://bsky.social) - The beloved social network and main ATProto platform.
* [Blue Place](https://place.blue/) - Massive real-time collaborative canvas.
* [Bookhive](https://bookhive.buzz/) - Goodreads alternative.
* [Frontpage](https://frontpage.fyi/) - Federated link aggregator.
* [GrayHaze](https://grayhaze.live/about) - Live streaming service (alpha).
* [Linkat](https://linkat.blue/) - Link in bio for Bluesky.
* [Pastesphere](https://pastesphere.link/) - Pastebin alternative.
* [Picosky](https://psky.social/) - ATProto chatting appview.
* [PinkSea](https://pinksea.art/) - Oekaki BBS.
* [recipe.exchange](https://recipe.exchange/) - Cooking recipes sharing.
* [Skylights](https://skylights.my/) - Book reviews.
* [Smoke Signal](https://smokesignal.events/) - Event creation and managing.
* [Sparta Social](https://github.com/dblock/sparta-social) - Exercise activity tracker (wip).
* [TouchGrass](https://touchgrass.network) - An opinionated social network, ATProto- and ActivityPub-compatible, with a focus on real life, real friends, portability & interoperability.
* [Whitewind](https://whtwnd.com/) - Markdown blog service using ATProto with no registration required.

### Bluesky

* [ClearSky](https://clearsky.app/) - Tool to explore Bluesky accounts.
* [cleanfollow](https://cleanfollow-bsky.pages.dev/) - Select inactive or blocked accounts to unfollow.
* [Handles directory](https://blue.mackuba.eu/directory/) - Handles ranking by TLDs.
* [Labellers](https://blue.mackuba.eu/labellers/) - List of known labellers.
* [BluSki account history](https://mocku.me/nt/#%23+BluSki+account+history//%23%23+Whose+history%3F//Let's+pick+a+rando+hot+poster+from+Discovery+feed+--//%60%60%60JavaScript/%2F%2F+downloading+Discovery+feed+posts/let+discoveryFeedPosts+=+(await+fetch(/++'https:%2F%2Fapi.bsky.app%2Fxrpc%2Fapp.bsky.feed.getFeed%3Ffeed=at:%2F%2Fdid:plc:z72i7hdynmk6r22z27h6tvur%2Fapp.bsky.feed.generator%2Fwhats-hot%26limit=100',/++%7B+headers:+%7B+'accept-language':+'en'+%7D+%7D).then(x+=%3E+x.json())).feed;//%2F%2F+sort+by+likes/let+topTextPost+=+discoveryFeedPosts/++.filter(p+=%3E+p.post.record.text+%26%26+!p.post.record.embed)/++.sort((p1,+p2)+=%3E+p2.post.likeCount+-+p1.post.likeCount)%5B0%5D;//%2F%2F+let's+see+all+the+info+now/let+hotAuthor+=+%7B/++...topTextPost.post.author,/++post:+%7B+...topTextPost.post,+...topTextPost.post.record,+post:+undefined,+record:+undefined,+author:+undefined+%7D/%7D;/%60%60%60//If+you're+after+specifc+handle,+specify+it+now.//%60%60%60JavaScript/let+bskyHandle+=+%2F%2F+'oyin.bo';+++++++%2F%2F++%3C--+like+this/++hotAuthor.handle;+//let+resolvedAccount+=++await+fetch(/++'https:%2F%2Fpublic.api.bsky.app%2Fxrpc%2Fapp.bsky.actor.getProfile%3Factor='+%2B+bskyHandle).then(x=%3Ex.json())/%60%60%60//%23%23+Finding+PDS+for+that+account//PDS,+personal+data+server+physically+stores+account's+data.+Usually+it's+one+of+a+couple+dozens+BluSki+servers+in+the+cloud.//By+tradition+they+get+Latin+mushroom+names.//Accounts+sometimes+shift+from+one+mushroom+to+another,+so+we+find+the+latest+most+actual+PDS.//%60%60%60JavaScript/let+plcEntries+=+await+fetch(%60https:%2F%2Fplc.directory%2F$%7BresolvedAccount.did%7D%2Flog%2Faudit%60).then(x+=%3E+x.json());+%2F%2F+full+account+registry/let+lastKnownPds+=+plcEntries.slice().reverse().map(x=%3Ex.operation%3F.services%3F.atproto_pds%3F.endpoint).filter(Boolean)%5B0%5D;+%2F%2F+last+PDS+operation+record/%60%60%60//%23%23+Downloading+the+history+in+CAR%2FCBOR+format//Account+history+is+a+public+service,+because+it's+used+in+distributing+BluSki+data+across+the+network.+The+file+can+be+anything+between+1-50Mb+depending+on+shitposting+power.//The+binary+CAR%2FCBOR+format+saves+storage+and+bandwith,+and+has+extra+funky+cryptographic+signatures+(of+which+no+normal+person+cares).//%60%60%60JavaScript/let+binarySnapshot+=+await+fetch(lastKnownPds+%2B+'%2Fxrpc%2Fcom.atproto.sync.getRepo%3Fdid='+%2B+resolvedAccount.did).then(x+=%3E+x.arrayBuffer());/binarySnapshot.byteLength.toLocaleString()/%60%60%60//%23%23+Extracting+useful+data+from+CAR%2FCBOR//There+are+libraries+for+that+in+every+programming+language.+Just+invoke+and+it'll+come.//%60%60%60JavaScript/import+%7B+readCAR+%7D+from+'https:%2F%2Funpkg.com%2Fcoldsky';/let+parsedRecords+=+await+readCAR(resolvedAccount.did,+binarySnapshot,+%7B+sleep:+600+%7D)/%60%60%60//%23+Finally,+useful+info!//Having+this+rich+history+of+shitposts,+replies,+likes+and+more,+we+are+ready+to+look+at+actual+stats.//%23%23+What+kind+of+activity+dominates%3F//%60%60%60SQL/SELECT+%5B$type%5D,+COUNT(*)/FROM+$4+GROUP+BY+%5B$type%5D/ORDER+BY+COUNT(*)+DESC/%60%60%60//%23%23+5+days+of+heaviest+shitpost//%60%60%60SQL/SELECT+TOP+5+createdAt-%3Esplit('T')-%3E%5B0%5D+as+date,+COUNT(*)/FROM+$4/++WHERE+%5B$type%5D+=+%22app.bsky.feed.post%22/++GROUP+BY+createdAt-%3Esplit('T')-%3E%5B0%5D/ORDER+BY+COUNT(*)+DESC/%60%60%60//%23%23+5+days+of+love:+more+likes+gifted+to+others//%60%60%60SQL/SELECT+TOP+5+createdAt-%3Esplit('T')-%3E%5B0%5D+as+date,+COUNT(*)/FROM+$4/++WHERE+%5B$type%5D+=+%22app.bsky.feed.like%22/++GROUP+BY+createdAt-%3Esplit('T')-%3E%5B0%5D/ORDER+BY+COUNT(*)+DESC/%60%60%60//%23%23+10+favourite+accounts//%60%60%60SQL/SELECT+TOP+10+subject-%3Euri-%3Esplit('at:%2F%2F')-%3E%5B1%5D-%3Esplit('%2F')-%3E%5B0%5D+as+did,+COUNT(*)+AS+likes/FROM+$4/++WHERE+%5B$type%5D+=+%22app.bsky.feed.like%22/++GROUP+BY+subject-%3Euri-%3Esplit('at:%2F%2F')-%3E%5B1%5D-%3Esplit('%2F')-%3E%5B0%5D/ORDER+BY+COUNT(*)+DESC/%60%60%60//%23%23+Who+are+these+people%3F//Account+history+file+refers+to+other+accounts+with+hexadecimal+DID,+which+as+you+see+above+isn't+that+readable.//No+sweat,+BluSki+has+a+service+to+resolve+DID+to+account+name%2Fhandle%2Finfo.+Here+you+go.//%60%60%60JavaScript/Promise.all($8.map(async+entry+=%3E+%7B/++const+profile+=+await+fetch('https:%2F%2Fpublic.api.bsky.app%2Fxrpc%2Fapp.bsky.actor.getProfile%3Factor='+%2B+entry.did).then(x+=%3E+x.json());/++return+%7B/++++did:+profile.did,+handle:+profile.handle,+displayName:+profile.displayName,/++++likesCount:+entry.likes,/++++postsCount:+profile.postsCount,/++++...profile/++%7D;/%7D))/%60%60%60//%23%23+10+accounts+getting+most+reply+traffic//%60%60%60SQL/SELECT+TOP+10+reply-%3Eparent-%3Euri-%3Esplit('at:%2F%2F')-%3E%5B1%5D-%3Esplit('%2F')-%3E%5B0%5D+as+did,+COUNT(*)+AS+replies/FROM+$4/++WHERE+%5B$type%5D+=+%22app.bsky.feed.post%22+AND+reply+AND+reply-%3Eparent-%3Euri/++GROUP+BY+reply-%3Eparent-%3Euri-%3Esplit('at:%2F%2F')-%3E%5B1%5D-%3Esplit('%2F')-%3E%5B0%5D/ORDER+BY+COUNT(*)+DESC+/%60%60%60//And+again,+with+names+and+extra.//%60%60%60JavaScript/Promise.all($10.map(async+entry+=%3E+%7B/++const+profile+=+await+fetch('https:%2F%2Fpublic.api.bsky.app%2Fxrpc%2Fapp.bsky.actor.getProfile%3Factor='+%2B+entry.did).then(x+=%3E+x.json());/++return+%7B/++++did:+profile.did,+handle:+profile.handle,+displayName:+profile.displayName,/++++repliesCount:+entry.replies,/++++postsCount:+profile.postsCount,/++++...profile/++%7D;/%7D))/%60%60%60//) - Editable notebook to analyze a Bluesky account.
* [Starter Packs](https://www.starterpacks.net/) - Search Bluesky starter packs and profiles.
* [PDS self-hosting](https://atproto.com/guides/self-hosting) - Self-hosting a Bluesky PDS means running your own Personal Data Server that is capable of federating with the wider ATProto network.
* [Bluesky-powered comments for any website](https://github.com/czue/bluesky-comments) - Embed Bluesky comments on your website easily ([announcement](https://www.coryzue.com/writing/bluesky-comments/)).

For more Bluesky tools, check [Awesome Bluesky](https://github.com/notjuliet/awesome-bluesky), a more exhaustive list of tools and clients available for Bluesky.

## Tools

* [ATFile](https://github.com/ziodotsh/atfile) - Store and retrieve files on the ATmosphere.
* [ShopSavvy for Bluesky](https://github.com/shopsavvy/bluesky-shopsavvy) - AT Protocol suite: reactive mention bot for real-time price lookups, a custom deals feed generator, and a daily deal poster.

## Lexicons

Lexicon is a schema definition language used to describe atproto records, HTTP endpoints (XRPC), and event stream messages.

Find below each platform's lexicons:

* [ATFile](https://github.com/ziodotsh/lexicons/tree/main/blue/zio/atfile)
* [Bluemoji](https://github.com/aendra-rininsland/bluemoji/tree/main/schema/blue.moji)
* [Bluesky](https://github.com/bluesky-social/atproto/tree/main/lexicons/app/bsky)
* [Bookhive](https://github.com/nperez0111/bookhive/tree/main/lexicons)
* [Frontage](https://github.com/likeandscribe/frontpage/tree/main/lexicons/fyi/unravel/frontpage)
* [GrayHaze](https://github.com/hugeblank/grayhaze.live/tree/main/lexicons/live/grayhaze)
* [Linkat](https://github.com/mkizka/linkat/tree/main/lexicons/blue/linkat)
* [Pastesphere](https://github.com/echo8/pastesphere/tree/main/lexicons)
* [Picosky](https://github.com/psky-atp/appview/tree/main/lexicons/social/psky)
* [PinkSea](https://github.com/shinolabs/PinkSea/tree/master/PinkSea.Lexicons/com/shinolabs/pinksea)
* [place.blue](https://github.com/QuietImCoding/place.blue/tree/main/atproto/lexicons)
* [recipe.exchange](https://recipe.exchange/lexicons/)
* [Skylights](https://github.com/Gregoor/skylights/tree/main/web/lexicons)
* [Skymdb](https://github.com/safwanyp/skymdb/tree/main/domain/lexicons)
* [Smoke Signal](https://github.com/SmokeSignal-Events/lexicon)
* [Sparta Social](https://github.com/dblock/sparta-social/tree/main/lexicons)
* [Whitewind](https://github.com/whtwnd/whitewind-blog/tree/main/lexicons/com/whtwnd/blog) 

## Contributing

Contributions welcome! Read the [contribution guidelines](https://github.com/atblueprints/awesome-atproto/blob/master/contributing.md) first.
