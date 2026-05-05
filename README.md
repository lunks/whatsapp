# mautrix-whatsapp (fork: keep deleted messages)
A Matrix-WhatsApp puppeting bridge based on [whatsmeow](https://github.com/tulir/whatsmeow).

This fork does not redact Matrix events when a message is deleted on WhatsApp.
Both "delete for everyone" (revoke) and "delete for me" leave the original
message intact and post a notice as a reply instead. Based on the approach in
[dvcrn/matrix-whatsapp-nodelete](https://github.com/dvcrn/matrix-whatsapp-nodelete).

## Documentation
All setup and usage instructions are located on [docs.mau.fi]. Some quick links:

[docs.mau.fi]: https://docs.mau.fi/bridges/go/whatsapp/index.html

* [Bridge setup](https://docs.mau.fi/bridges/go/setup.html?bridge=whatsapp)
  (or [with Docker](https://docs.mau.fi/bridges/general/docker-setup.html?bridge=whatsapp))
* Basic usage: [Authentication](https://docs.mau.fi/bridges/go/whatsapp/authentication.html)

### Features & Roadmap
[ROADMAP.md](ROADMAP.md) contains a general overview of what is supported by the bridge.

## Discussion
Matrix room: [#whatsapp:maunium.net](https://matrix.to/#/#whatsapp:maunium.net)
