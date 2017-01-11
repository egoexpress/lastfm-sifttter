# lastfm-sifttter
Fetch recent user tracks from last.fm and make them available to sifttter-redux-known

## Configuration

You need a configuration file in $HOME/.lastsiffter. It has to have the following entries:

```
---
lastfm:
  api_key: LASTFM_API_KEY
  api_secret: LASTFM_API_SECRET
  username: LASTFM_USERNAME
```

_LASTFM_API_KEY_ and _LASTFM_API_SECRET_ have to be obtained by creating and API account at the [last.fm site](http://www.last.fm/api/account/create).
_LASTFM_USERNAME_ is your usename (or any username you want to query actually).
