# VCRED Stablecoin

**Debt‑Backed USD Peg on Hemi (chainID 43111)**

---

## Protocol Overview

VCRED is a **USD‑pegged, debt‑backed stablecoin** native to the Hemi L2 network. The VCRED treasury issues diversified DeFi debt, deploys proceeds into yield strategies, and uses cash‑flow surpluses to defend the peg and grow reserves.

> **Key Innovation:** Treasury debt generation *automatically scales sell‑side liquidity*, ensuring that new VCRED supply is matched by market depth.

---

## Peg Management

### Target Band & Triggers

* **Soft peg:** $1.00 ± 2%
* **Below $0.98:** Treasury injects reserves to buy back VCRED
* **Above $1.02:** Treasury sells VCRED to cap appreciation

### Operation Cadence

Peg actions are **executed manually each week** by the VCRED DAO multisig, allowing transparent review of reserves and market conditions.

---

## Treasury & Debt Engine

The DAO sources revenue through multiple debt instruments:

* Lending‑market notes (variable‑rate debt)
* Bonding programs (discounted VCRED for liquidity)
* Private structured deals with institutional partners

```
Net Yield = Σ (Debt Proceeds × Strategy APR) – Σ (Debt Cost)
```

Surplus yield is recycled into peg defense and long‑term reserve growth.

---

## Economic Model

**No redemption desk.** Holders freely *swap* VCRED for USDC.e, ETH, or other tokens on SushiSwap; zero protocol fees.

**Soft supply cap.** DAO mints additional VCRED only when market liquidity is thin.

---

## User Lifecycle

### Acquire

Buy VCRED from the **SushiSwap VCRED/USDC.e** pool on Hemi.

### Utilize

* Stable medium of exchange within Hemi DeFi
* Collateral in money markets
* Pair token for liquidity farming

### Exit

Swap VCRED back to other tokens anytime—no lockups, queues, or withdrawal limits.

> **Address:** `0x71881974e96152643C74A8e0214B877CfB2A0Aa1`

---

## Governance & Incentives

* **VCRED DAO:** Multisig controls treasury, peg ops, and supply
* **Liquidity Mining:** Weekly rewards boost AMM depth
* **Community Grants:** Funding for integrations and tooling

---

## Roadmap (Next 6 Months)

* Launch diversified debt‑market integrations
* Release bonding module for treasury growth
* Expand liquidity mining to additional DEXes

---

## Risk & Resilience

* **Demand Risk:** Low adoption slows revenue; mitigated with incentives and BD
* **Market Risk:** Treasury yield strategies diversify across L2 and L1
* **Operational Risk:** Weekly manual ops allow human oversight and rapid course correction

> **No Liquidations, No Redemption Runs:** Floating supply adjusts via market swaps, minimizing systemic shocks during stress events.

---

*VCRED Stablecoin • Decentralized Finance • Built on Hemi L2*
