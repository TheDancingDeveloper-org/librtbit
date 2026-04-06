# librtbit

Core BitTorrent client library for the rtbit torrent client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |

### Depends On

- **librtbit-bencode** (git, v0.1.0) — bencode serialization
- **librtbit-tracker-comms** (git, v0.1.0) — HTTP/UDP tracker communication
- **librtbit-buffers** (git, v0.1.0) — byte buffer utilities
- **librtbit-core** (git, v0.1.0) — core types (info hashes, magnets, metainfo)
- **librtbit-lsd** (git, v0.1.0) — Local Service Discovery (BEP 14)
- **librtbit-clone-to-owned** (git, v0.1.0) — owned/borrowed type conversion
- **librtbit-peer-protocol** (git, v0.1.0) — peer wire protocol
- **librtbit-sha1-wrapper** (git, v0.1.0) — SHA1/SHA256 hashing
- **librtbit-dht** (git, v0.1.0) — Kademlia DHT
- **librtbit-upnp** (git, v0.1.0) — UPnP port forwarding
- **librtbit-upnp-serve** (git, v0.1.0, optional) — UPnP MediaServer

## Features

- `default-tls` (default) — OpenSSL-backed TLS and SHA1
- `rust-tls` — rustls + aws-lc-rs alternative
- `http-api` — Axum HTTP REST API server
- `http-api-client` — API client library
- `webui` — React web UI (embedded)
- `upnp-serve-adapter` — UPnP MediaServer integration
- `prometheus` — Metrics export
- `postgres` — PostgreSQL persistence backend
- `swagger` — OpenAPI/Swagger UI
- `watch` — File system monitoring
- `tokio-console` — Tokio console debugging
