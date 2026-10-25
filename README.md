# Conduit evidence archives

This repository stores checksummed historical evidence exported from the public [Conduit source repository](https://github.com/dancxjo/conduit). Binary payloads belong in immutable release assets, never in this repository's Git history.

Each shipment retains original bytes, original Git blob identities, SHA256 hashes and historical paths. Rehearsal commit/ref maps describe a proposed migration snapshot; they are not an origin cutover record. Historical evidence remains associated with its original source identities. A rewritten commit is not claimed to have produced that evidence.

Create shipments as drafts, upload without overwriting assets, verify a fresh download independently, then publish with immutable releases enabled. Retain an independent original Git backup and compact source-side retrieval manifests. Immutability does not replace backup against repository/account loss.

The first shipment contains 36 generated evidence blobs (598,444,017 payload bytes) and complete rehearsal mapping metadata. It does not contain personal Codex histories, credentials or unrelated machine data. Source history must not be rewritten until durable retrieval verification and a fresh live-ref migration audit succeed.
