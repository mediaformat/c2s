# c2s-pwa
A Progressive Web App (PWA) for the ActivityPub API (Client-to-Server API)

## Features
- [x] Login via OAuth ([RFC7591](https://datatracker.ietf.org/doc/html/rfc7591) & [RFC8414](https://datatracker.ietf.org/doc/html/rfc8414))
- [X] Fetch from Inbox
- [X] Fetch from SharedInbox
- [x] Post to Outbox
- [x] (Temporarily) Supports a custom proxy server for fetching remote Actors, Activities, Objects
- [ ] [CIMD](https://datatracker.ietf.org/doc/draft-ietf-oauth-client-id-metadata-document/)
- [ ] ...Stay tuned!

## Tested with
- [x] Pleroma
- [ ] FedBox (testing in progress)
- [ ] Streams (testing in progress)
- [ ] Epicyon (testing in progress)
- [ ] Onepage.pub 
- [ ] WordPress (support announced)

## Tracking Support
| Software    | RFC7591 | RFC8414 | CIMD | proxyURL |
| :---------- | :-----: | :-----: | :--: | :------: | 
| Pleroma     |  ☑      |  x      | -    | [1](https://git.pleroma.social/pleroma/pleroma/-/issues/3382)        |
| FedBox      |  -      |  -      | -    | -        |
| Epicyon     |  -      |  -      | -    | -        |
| Onepage.pub |  -      |  -      | -    | -        |
