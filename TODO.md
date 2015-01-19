Porting Bitcoin 0.10 to Darkcoin
================================

Staging tree for Darkcoin-0.12.0.


COMPLETED:

- Updated strings in config, path and pid (~/.darkcoin)
- Renamed binaries (darkcoind, darkcoin-qt, etc.)
- Changed version numbers, protocol version, wallet version (compatible with DRK network)
- Updated Ports for communication and RPC (port=9999; rpcport=9998)
- Updated address versions (Public keys, Multisig keys, Coin Type)
- Added darkcoin seednodes
- Changed genesisblockhash and timestamp
- Reviewed and updated checkpoints


MANDATORY:
----------

- Adjust algorithm (X11)
- Update subsidity function (Block value)
- Adjust wallet keypool size to 1000 and add loading indicator on fresh wallet load
- Adjust difficulty and blockvalue (KGW, DGW based on blockheight)
- Define regression test genesis block
- Update wallet layout and branding
- Change Darkcoin units to DRK and add duffs
- Fix internal walletminer
- Adjust deploy scripts (mac, linux)


ADDITIONAL:
-----------

- Include trusted public key for message signing
- Masternodes, Enforcement, Darksend, InstantX, Atomic Transfers, ...
- Remove Bitcoin dead weight (SHA256, hardcoded keys, seednodes, ...)
- Update bootstrap.md
- Update strings
- Write tests
