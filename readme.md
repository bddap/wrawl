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
