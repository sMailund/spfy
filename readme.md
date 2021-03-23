# spiffy

/ˈspɪfi/<br/>
*adjective*:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;smart in appearance.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;`"a spiffy new outfit"`

*noun*:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;a useful go-based Spotify CLI.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;`> spfy search -s "never gonna give you up"`

## setup
In the current version, environment variables `SPOTIFY_ID` and `SPOTIFY_SECRET` must be set, can be found in the spotify developer section.
Additionally, the project must be setup with `http://localhost:8080/callback` as a callback URL.

This is only a temporary measure until PKCE authentication is implemented, should probably use some safe credential storage 

## TODO
* proof-of-concept search and play flow
* PCKE authentication
