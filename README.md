# lyra-crypto-operator

**Canonical home** for LYRA / Clawnch token launch utilities — **not** part of LYGO P0–P9 lattice verification.

| Skill (ClawHub slug) | Role |
|----------------------|------|
| `lyra-coin-launch-manager` | Clawnch receipts, Starcore family normalize/verify, bookmarks |

## Policy

Read `CRYPTO_LATTICE_SEPARATION.md`. Token metrics ≠ `lattice.ok`. Install only when you explicitly run launches.

## Maintainer

```bash
# From this repo root
npx clawhub@latest publish . --slug lyra-coin-launch-manager --name "LYRA Coin Launch Manager"
```

## Stack bridge

`lygo-protocol-stack` keeps a **publish stub** at `clawhub/mirrors/lyra-coin-launch-manager/` synced from here via:

```powershell
python tools/sync_from_lyra_crypto_operator.py   # run from lygo-protocol-stack
```

**Δ9Φ963 — crypto operator lane, sovereign stack lane.**