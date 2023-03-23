# web-interface
A PRIVATE internet / web interface

# Base goals:
- [ ] locally host nextdns/adguard-dns for secure/private dns resolution
- [ ] 'Strict' protection and 'Relaxed' protection
  - Strict protections use local dns for dns sinkholing, preloading blocklists but giving user ability to add/remove, along with other softer implementations.
  - Relaxed protections uses dns blocklists as proxy patterns for local tor relay.
- [ ] deploy tor relay at launch
- [ ] build Yggdrasil compatibility+network for dns list exchange
- [ ] Implement Matrix's session id system for private, but personal identifiers for other clients and services.
