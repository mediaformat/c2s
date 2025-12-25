# c2s-pwa
A Progressive Web App (PWA) for the ActivityPub API (Client-to-Server API)

## Features
- [x] Login via OAuth ([RFC7591](https://datatracker.ietf.org/doc/html/rfc7591), [RFC8414](https://datatracker.ietf.org/doc/html/rfc8414), Actor Endpoints)
- [X] Fetch from Inbox
- [X] Fetch from SharedInbox
- [x] Post to Outbox
- [x] (Temporarily) Supports a custom proxy server for fetching remote Actors, Activities, Objects
- [ ] [CIMD](https://datatracker.ietf.org/doc/draft-ietf-oauth-client-id-metadata-document/)
- [ ] ...Stay tuned!

## Tracking Support 
`☑` supported,
`x` unsupported,
`-` untested

| Software    | RFC7591 | RFC8414 | CIMD | Actor endpoints | proxyURL |
| :---------- | :-----: | :-----: | :--: | :-------------: | :------: | 
| [Pleroma](https://git.pleroma.social/pleroma/pleroma/)     |  ☑      |  x      | x    | ☑               | [x](https://git.pleroma.social/pleroma/pleroma/-/issues/3382)        |
| [FedBox](https://github.com/go-ap/fedbox)      |  -      |  -      | -    | -        | -        |
| [Bonfire](https://github.com/bonfire-networks/bonfire-app/issues/917)     |  -      |  -      | -    | ☑        | ☑        |
| [(streams)](https://codeberg.org/streams/streams)     |  ☑      |  ☑      | -    | ☑        | -        |
| [Onepage.pub](https://github.com/evanp/onepage.pub) |  -      |  -      | -    | -        | -        |

## Circlebuilder's Delightful extensive c2s support list
https://codeberg.org/fediverse/delightful-fediverse-experience/issues/130

## Implementation Report
Official, historic report (last updated 2021)
https://activitypub.rocks/implementation-report/
