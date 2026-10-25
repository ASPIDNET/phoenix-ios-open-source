# Phoenix iOS engine — covered source and third-party notices

This repository provides the covered source used by Phoenix VPN’s iOS engine.
It contains no Phoenix account credentials, live VPN profiles, server configuration,
private app repository history, or app/IPA binaries.

## Version: ios-engine-go1.27.3-20261025

Engine device static-binary SHA-256:
`22f3fc6fefc50e62e165c9d29fe540cdb419ca0c9ba97f6058c8092390ae035f`.

The release archive contains the full prepared Xray-core source with the iOS
patches applied, pinned REALITY and juju/ratelimit source, the patch files, and
the iOS engine build script. The manifest records pins, source hashes and engine
outputs. It is a covered-source package, not the complete proprietary app or a
standalone build environment. Algorithm and handshake capabilities must be
assessed against the relevant runtime profiles, not inferred from this repository.

## Licences

Each component retains its original licence and notices; this repository does
not relicense those components. Xray-core and REALITY are MPL-2.0. The included
juju/ratelimit source is LGPLv3 with its upstream linking exception; the full
upstream licence/exception text is retained. Other component notices are in
`third-party-notices.json`; the linked-module inventory is `ios-go-licenses.tsv`.
Go runtime/standard-library BSD notice is included in that notice file.

Download the covered-source archive from the matching GitHub release. Preserve
the licence headers and notices when modifying or redistributing the sources.
Publication of this package does not certify App Store legal/export approval,
all-node connectivity, or negotiated cryptographic parameters.
