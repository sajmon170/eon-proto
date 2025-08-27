# Design principles

The protocol described in this document is based on a set of well-defined design
principles. If a problem had multiple solutions the one that was chosen followed
those principles best.

- Whenever possible complicated behaviors aren't specified in the protocol
directly, but are an emergent property of other behaviors
- Keep It Simple, Stupid - the protocol should provide the bare minimum set of
primitives required to build other, more complicated behaviors by the
application. Every implemented primitive's usage is maximized
- Occam's Razor - every primitive should work in a straightforward manner.
Everything that's not necessary to understand or implement it needs to be cut.
- Local processing is preferred over sending remote requests (e.g. local garbage
collecting vs sending periodic network cleanup requests)
- The load needs to be balanced evenly between end users (e.g. no superpeers)
- Increasing anonymity can't come at the cost of network performance. Perfect
anonymity is useless if no one will use the service because it's too slow.
- Loss of anonymity is caused by the user's actions, not by the system.
- User authentication is based on public-key cryptography and there is no
centralized authority for creating new identities. Every connection is based on
a zero-trust model by default.
