# Wrawl, address a remote machine by it's public key.

## Goal

Wrawling for a public key yeilds a secure link to the owner of that key, regardless of network topology.

## Subgoals

- Wrawl server stores a map from public key to ip.
- Wrawl server accepts publication of public keys.
- Wrawl server verifies publications with challenges.
- Wrawl server responds to ip lookup requests.
- Wrawl server assists in nat hole punching.
- Wrawl server becomes a decentralized pack of wrawl servers.
- Wrawl client may publish its own public key to a wrawl server.
- Wrawl client may lookup a public key from a wrawl server.
- Wrawl client may establish a secure link to another rawl client.
- Wrawl client may punch through nat.
