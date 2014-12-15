Porting Bitcoin 0.10 to Darkcoin
================================

Staging tree for Darkcoin-0.12.0.


MANDATORY:
----------

- Update strings in config, path and pid (~/.darkcoin)
- Update Ports for communication and RPC (port=9999; rpcport=9998)
- Change version numbers, protocol version, wallet version (compatible with DRK network)
- Add darkcoin seednodes
- Update address versions (Public keys, Multisig keys)
- Change genesisblockhash and timestamp
- Review and update checkpoints
- Adjust algorithm (X11)
- Update subsidity function (Block value)
- Adjust wallet keypool size to 1000 and add loading indicator on fresh wallet load
- Adjust difficulty and blockvalue (KGW, DGW based on blockheight)
- Define regression test genesis block
- Update wallet layout and branding
- Reset testnet (v4) with new genesis and address version (start with x)
- BIP0032 addresses xpub and xpriv start with x (unchanged by design)
- Change Darkcoin units to DRK and add duffs
- Fixe internal walletminer
- Check rpcminer


ADDITIONAL:
-----------

- Include trusted public key for message signing
- Masternodes, Enforcement, Darksend, InstantX, Atomic Transfers, ...
- Remove Bitcoin dead weight (SHA256, hardcoded keys, seednodes, ...)
- Update strings
- Write tests
