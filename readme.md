# Wrawl, address a remote machine by it's public key.

## Goal

Wrawling for a public key yeilds a secure link to the owner of that key, regardless of network topology.

## Terms

### wisdom

A map from public key to address.

### publisher

An agent publishing its own public key.

### curator

An agent that accepts wisdom from publishers, and distributes it to conumers.

### consumer

An agent searching for a publisher with a specific public key.

## Subgoals

- curator stores a widom.
- curator accepts new wisdom.
- curator challenges publishers verifiy wisdom.
- curator passes wisdom to consumers on request.
- curator shares wisdom with other curators.
- publisher publishes its own public key to curators.
- publisher responds to challenges from curators and consumers.
- consumer looks up the address of a publisher.
- consumer establishes a secure link to a publisher.
- consumer punch through nat.
- publisher, curator, and consumer work together to punch NAT holes.
