# lumen-covenant

SQUIRL OS Lumen Covenant route — the append-only receipts ledger for the
XLM/XRP covenant ceremonies. Capability-separated from the satoshi/BTC route
(four-horsemen) by owner directive, 2026-10-20: each rail's covenant is a
distinct machine capability — Bitcoin carries the P2TR tweaked-key covenant
(commitment inside the output key), Stellar carries the persistent in-place
ManageData covenant (the account IS the vessel), XRP carries the persistent
in-place Domain field (AccountSet, consensus-accounted).

Ledger: LEDGER.md (append-only, forward-only, receipts-first). Preregistered
before broadcast; keyless byte-exact read-backs on every leg. No client data,
no PHI (POL-DISC-001). No LLM in any decision path.

> This software is a prototype and is provided for educational and research
> purposes only. It is not intended for production use, commercial deployment,
> or safety-critical environments. All systems are experimental and may contain
> defects on them.
