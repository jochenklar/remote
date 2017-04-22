# remote

A remote control for spotify on the command line.

## Setup

Create ~/.remote-config with the credentials of *your* spotify application, i.e.:

```
{
  "client_id": "SUPERSECRET",
  "client_secret": "SUPERSECRET",
  "authorize_url": "https://accounts.spotify.com/authorize",
  "access_token_url": "https://accounts.spotify.com/api/token",
  "scope": "user-read-playback-state user-modify-playback-state"
}
```

Run `./remote init` and `./remote --help`. Enjoy.
