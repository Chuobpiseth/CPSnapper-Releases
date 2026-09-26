# CPSnapper Releases

Public, artifact-only update feed for CPSnapper Pro.

This repository contains signed update manifests, signed version indexes, the
public verification key, and compiled GitHub Release assets. The CPSnapper
source repository, activation records, browser data, private signing keys, and
provider credentials are not published here.

Channels:

- `stable/` — production clients
- `uat/` — user-acceptance builds
- `patch/` — patch candidates

Clients verify every manifest with the bundled Ed25519 public key and verify
the downloaded ZIP with its signed SHA-256 checksum before installation.
